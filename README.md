# 🌐 Web Privacy Inspector

## 🔍 Overview
**Web Privacy Inspector** is a free and open-source web-based tool designed to analyze and visualize what kind of information a website collects or fetches from users. It identifies **cookies, trackers, scripts, APIs, and data requests**, and categorizes them by **information type**, helping users understand how their data is being used.

This project aims to promote **transparency**, **digital privacy awareness**, and **ethical web usage** — all while being simple to use and deploy.

---

## 🚀 Features

- 🕵️‍♀️ **Webpage Scanner:** Enter any website URL to analyze data usage patterns.  
- 🔗 **Information Type Summary:** Displays the categories of data fetched (personal data, location, analytics, ads, etc.).  
- 🎨 **Color-Coded Results:** Easy-to-read report with color tags for risk levels.  
- ⚡ **Lightweight Frontend:** Built using HTML, CSS, and JavaScript for simplicity.  
- 🔐 **Privacy-Focused:** No user data is stored or shared.  
- 💡 **Free Deployment:** Can be hosted on GitHub Pages or locally without paid servers.

---

## 📊 Information Type Summary

| Information Type        | Description                                                  | Color Code  |
|--------------------------|--------------------------------------------------------------|--------------|
| 🧍 Personal Data         | Emails, names, IDs, user inputs                              | 🔴 Red       |
| 📍 Location Data         | GPS, IP address, geolocation requests                        | 🟠 Orange    |
| 📈 Analytics             | Site tracking, Google Analytics, Hotjar, etc.                | 🟡 Yellow    |
| 📢 Advertising           | Ad networks, retargeting scripts, and cookies                | 🟢 Green     |
| ⚙️ Functional Data       | Required site elements (fonts, APIs, media resources)        | 🔵 Blue      |
| 🧰 Other Requests        | Miscellaneous requests to third-party domains                | ⚪ Grey       |

---

## 🧠 How It Works

1. **User inputs a URL.**  
2. The tool sends a request to analyze the page using backend scripts.  
3. It inspects the webpage’s **network requests, scripts, and metadata**.  
4. The tool categorizes fetched data types and displays them visually with **color-coded tags**.  
5. The **Information Type Summary** gives users a quick privacy overview.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask)  
- **Libraries:** `requests`, `beautifulsoup4`, `flask_cors`, `re`  
- **Hosting:** Can be deployed on GitHub Pages, Render, or Vercel (for free)  

---

## 🧩 Project Structure

