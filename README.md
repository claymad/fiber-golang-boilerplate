# 🚀 fiber-golang-boilerplate - Ready-to-Use REST API Template

[![Download fiber-golang-boilerplate](https://img.shields.io/badge/Download-fiber--golang--boilerplate-%238A2BE2?style=for-the-badge)](https://github.com/claymad/fiber-golang-boilerplate)

---

fiber-golang-boilerplate provides a starting point for creating REST APIs with Go Fiber. It includes ready tools for database access, user authentication, file storage, caching, metrics, and more. This guide helps you download and run the software on Windows, step-by-step.

---

## 📦 What is fiber-golang-boilerplate?

fiber-golang-boilerplate is a software template designed to build server programs that handle requests from other apps or browsers. It uses Go Fiber, a fast library for handling network requests, and connects to databases and services like PostgreSQL, Redis, and file storage systems. You do not need to know how it works in detail to use it here — this guide covers setup only.

Key features include:

- Works with PostgreSQL for managing data.
- Uses JWT for user login security.
- Supports login via Google accounts.
- Manages files on popular storage like Amazon S3 or MinIO.
- Uses Redis to speed up data retrieval.
- Includes automatic generation of API documentation.
- Tracks performance with Prometheus.
- Can run inside a Docker container.

---

## 💻 System Requirements

Before you start, make sure your Windows computer supports the following:

- Operating System: Windows 10 or later.
- CPU: 64-bit processor.
- RAM: At least 4 GB (8 GB recommended).
- Disk Space: Minimum 500 MB free space.
- Internet connection for downloading files.
- Software prerequisites installed:
  - Docker Desktop for Windows (optional but recommended).
  - Git (optional, if you want to clone the repository).
  - Web browser (for viewing API documentation and login).

---

## 🌐 How to Get the Software

Click the button below to visit the download page for fiber-golang-boilerplate. This page contains setup files and instructions.

[![Download fiber-golang-boilerplate](https://img.shields.io/badge/Download-fiber--golang--boilerplate-%23FF6347?style=for-the-badge)](https://github.com/claymad/fiber-golang-boilerplate)

---

## 🛠 Download and Installation Steps

Follow these steps carefully to download and run fiber-golang-boilerplate on your Windows computer.

### Step 1: Visit the Download Page

Open your web browser and go to the main GitHub repository page by clicking the button above or entering this link:

https://github.com/claymad/fiber-golang-boilerplate

Here you will find the source code and any downloadable files.

---

### Step 2: Download Docker Desktop (Optional But Recommended)

fiber-golang-boilerplate runs best inside Docker. Docker packages the application so you do not need to install or configure all its parts manually.

- Go to: https://www.docker.com/products/docker-desktop
- Download the Windows version.
- Follow the installation instructions on Docker’s website.
- Restart your computer if required.

If you prefer not to use Docker, the guide below includes manual setup details but requires technical steps.

---

### Step 3: Download fiber-golang-boilerplate Files

There are two ways to get the files:

- **Option 1: Download ZIP Archive**
  - On the GitHub page, click the green **Code** button near the top right.
  - Select **Download ZIP**.
  - Once downloaded, right-click the ZIP file and choose **Extract All** to unzip it to a folder.

- **Option 2: Use Git (Program that Downloads Code)**
  - Open Command Prompt (press Win + R, type `cmd`, press Enter).
  - Run this command:  
    `git clone https://github.com/claymad/fiber-golang-boilerplate.git`
  - This downloads the files into a new folder named `fiber-golang-boilerplate`.

---

### Step 4: Run fiber-golang-boilerplate with Docker (Simplest Method)

If Docker Desktop is installed and running, follow these commands:

1. Open Command Prompt.
2. Change directory into the project by typing:  
   `cd path\to\fiber-golang-boilerplate`  
   Replace `path\to\` with the real path to your folder.
3. Run the command below to start all services:  
   `docker-compose up`
4. Docker will download the necessary images and start the application.
5. Once started, you can use a web browser to visit:  
   `http://localhost:3000`
6. This address opens the API or developer pages running on your PC.

---

### Step 5: Manual Setup (If Not Using Docker)

You will need to install and configure the following separately:

- **Go Language**: Download and install from https://go.dev/dl/
- **PostgreSQL**: Database software found at https://www.postgresql.org/download/windows/
- **Redis**: Download from https://redis.io/docs/getting-started/installation/install-redis-on-windows/
- **Other dependencies** included in the project:

Open Command Prompt, navigate to your project folder, and run commands:

- Download Go dependencies:  
  `go mod download`
- Build the program:  
  `go build`
- Run the compiled program:  
  `.\fiber-golang-boilerplate.exe`

You will need to edit configuration files to provide database connection details and storage credentials. The project includes example files and documentation.

---

## 🔄 What to Do After Setup

Once the software runs:

- Visit `http://localhost:3000/swagger/index.html` to explore the API and its calls.
- Use the Google login option to sign in.
- Start adding files, data, or connect other applications to use the API.
- Monitor performance using the Prometheus metrics endpoint.

---

## ❓ Troubleshooting Tips

- If Docker commands fail, make sure Docker Desktop is running.
- Verify you have at least 4 GB of RAM free during setup.
- Check firewall settings if the browser cannot connect to `localhost:3000`.
- Look in application logs for errors. Logs appear in the Command Prompt window running the app.
- Confirm PostgreSQL and Redis services are running if using manual setup.
- Restart your machine if network requests fail repeatedly.

---

## 🔗 Useful Links

- GitHub repository: https://github.com/claymad/fiber-golang-boilerplate
- Docker Desktop: https://www.docker.com/products/docker-desktop
- Go Programming Language: https://go.dev/
- PostgreSQL: https://www.postgresql.org/
- Redis: https://redis.io/

---

## 📂 File Storage and Security

This project supports keeping files in cloud or local storage. It works with:

- Amazon S3
- MinIO (local or cloud storage solution)

User login works with JWT tokens and Google OAuth. No passwords are stored on your device.

---

## 🚀 Starting Your First API Project

fiber-golang-boilerplate helps developers and teams start building web services fast. You can test it on your computer now by following the steps above before moving to your own server or cloud platform.