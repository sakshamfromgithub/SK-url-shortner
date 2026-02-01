# 🔗 SK URL Shortner

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-green)

**SK URL Shortner** is a lightweight, fast, and privacy-focused **URL shortening web app** built using pure **HTML, CSS, and JavaScript**.  
It converts long URLs into short, shareable links and redirects users instantly.

> 🚀 No backend required  
> 🌐 Perfect for Netlify & GitHub Pages  
> 🔐 No login, no tracking, no data selling  

---

## 🌍 Live Demo
After deployment, short links work like this:


Opening the link will automatically redirect to the original URL.

---

## ✨ Features
- 🔹 Shorten long URLs instantly  
- 🔹 Custom short code support  
- 🔹 Auto redirect using `?c=CODE`  
- 🔹 One-click copy button  
- 🔹 Open links in new tab  
- 🔹 Delete individual links  
- 🔹 Export links as JSON  
- 🔹 Reset all stored links  
- 🔹 Fully responsive UI  

---

## 🧠 How It Works
1. User enters a long URL.
2. App generates a unique short code.
3. Mapping is saved in browser **localStorage**.
4. When `?c=CODE` is opened, the app redirects to the original URL.

⚠️ Links are stored **locally per browser**, not globally.

---

## 📁 Project Structure
sk-url-shortner/
│
└── index.html


Only **one file** is required to run the project.

---

![Home Page]

🛠️ Run Locally

Clone the repository:

git clone https://github.com/your-username/SK-url-shortner.git
