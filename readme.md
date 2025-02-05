# 🚀 Harsh E-Commerce Project

Welcome to the **Harsh E-Commerce Project**! This project is a full-stack e-commerce platform designed to provide seamless shopping experiences. Follow the steps below to set up the project and get it running on your local machine. 🖥️💻

---

## 📥 Installation & Setup

### 📌 Prerequisites
Before proceeding with the installation, make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/en/download/) (Latest LTS version recommended) 🟢
- [MongoDB](https://www.mongodb.com/try/download/community) (For database management) 🗄️
- [MongoDB Compass](https://www.mongodb.com/products/compass) (GUI for MongoDB) 📊
- [Visual Studio Code](https://code.visualstudio.com/download) (Recommended IDE) 💡

### 🔹 Step 1: Download the Project
1. Click on this link: [Harsh_E_Commerce_Project](https://github.com/harshy-00/Harsh_E_Commerce_Project) 🌐
2. Click on the **Code** button ⬇️
3. Select **Download ZIP** 📂
4. Extract the ZIP file to a suitable location on your computer.

### 🔹 Step 2: Open in VS Code
- Open **Visual Studio Code**.
- Click **File > Open Folder** and select the extracted project folder.

### 🔹 Step 3: Open Terminal
- Open the terminal in **VS Code** by pressing `Ctrl + ~` (tilde) or navigating to **Terminal > New Terminal**.

### 🔹 Step 4: Setup Backend 🛠️
Navigate to the `backend` folder and install dependencies:
```sh
cd backend
npm install
```
Fix any vulnerabilities:
```sh
npm audit fix
npm audit fix  # Run this command again for extra security
```
Start the backend server:
```sh
npm start
```
- The backend should now be running at **http://localhost:5000/**.
- Ensure that **MongoDB** is running before proceeding.

### 🔹 Step 5: Install MongoDB 🗄️
1. Download MongoDB from [here](https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-8.0.4-signed.msi) 🛜
2. Install it and follow the setup instructions (This may take up to **10 minutes** ⏳).

### 🔹 Step 6: Install MongoDB Compass 📊
1. Download MongoDB Compass from [here](https://downloads.mongodb.com/compass/mongodb-compass-1.45.2-win32-x64.exe)
2. Install and open it.

### 🔹 Step 7: Setup Database 📂
1. Open **MongoDB Compass**.
2. Click the green button **"Add new connection"**.
3. Enter your database name in this format: `yourname_db` 🏦 (e.g., `harsh_db`)
4. Click **Save and Connect**.

### 🔹 Step 8: Setup Frontend 🎨
Navigate to the `webapp` folder and install dependencies:
```sh
cd webapp
npm install
```
Fix any vulnerabilities:
```sh
npm audit fix
npm audit fix  # Run this command again for extra security
```
Start the frontend server:
```sh
npm start
```
- The frontend should now be running at **http://localhost:4200/**.

### 🔹 Step 9: Angular Setup ⚡
During setup, you may be prompted with the following message:
```sh
Would you like to share pseudonymous usage data about this project with the Angular Team at Google under Google's Privacy Policy at https://policies.google.com/privacy.
```
- Enter **y** ✅ to proceed.

### 🔹 Step 10: Open the Project 🌐
- Open **[http://localhost:4200/](http://localhost:4200/)** in your browser.

### 🔹 Step 11: Login 🔐
Use the following credentials to log in as an admin:
- **Email:** `admin@test.com` 📧
- **Password:** `12345` 🔑

---

## 📌 Features
✅ Full-Stack E-Commerce Platform
✅ User Authentication & Authorization 🔐
✅ Secure Database with MongoDB 🛢️
✅ Interactive UI with Angular 🎨
✅ Backend powered by Node.js & Express ⚙️
✅ Admin Dashboard for Managing Products & Orders 📊
✅ RESTful API Integration 🌐

---

## 🎯 Enjoy Your E-Commerce Project! 🛒✨
If you have any issues or questions, feel free to reach out. Happy coding! 🚀
