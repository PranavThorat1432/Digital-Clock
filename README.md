# ⏰ Digital Clock

A sleek, stylish **Digital Clock** built using **HTML, CSS, and JavaScript**. The clock displays the current time dynamically with smooth updates every second, featuring a **modern glassmorphic UI**.

---

## 📌 Features

✔️ **Real-Time Updates** – Automatically updates every second.  
✔️ **Beautiful UI** – Designed with a glassmorphic effect and soft gradient background.  
✔️ **Fully Responsive** – Works seamlessly on desktops, tablets, and mobile devices.  
✔️ **Lightweight & Fast** – Uses minimal resources for smooth performance.  

## 🎥 Demo Preview

🔗 **[Live Demo](https://digital-clock01.vercel.app/)** – Click here to see it in action!  

---

## 🛠️ Technologies Used  

- **HTML** – Structure of the clock.  
- **CSS** – Stylish gradient background and glassmorphic effects.  
- **JavaScript** – Fetches and updates time dynamically.  

---

## 📂 Project Structure  

```
Digital-Clock/
│── index.html       # Main HTML file
│── style.css        # CSS for styling
│── script.js        # JavaScript for clock functionality
└── README.md        # Project documentation
```

---

## 🚀 Installation & Usage  

1️⃣ **Clone the repository**  
```sh
git clone https://github.com/yourusername/digital-clock.git
```

2️⃣ **Open `index.html` in your browser**  
```sh
cd digital-clock
start index.html
```

---

## ⚙️ How It Works  

🔹 Fetches the current time using `new Date()`.  
🔹 Updates the clock every **1000ms (1 second)** using `setInterval()`.  
🔹 Ensures **double-digit formatting** (e.g., `09:05:02` instead of `9:5:2`).  

```js
function updateClock() {
    let currTime = new Date();
    
    hrs.innerHTML = String(currTime.getHours()).padStart(2, '0');
    min.innerHTML = String(currTime.getMinutes()).padStart(2, '0');
    sec.innerHTML = String(currTime.getSeconds()).padStart(2, '0');
}

setInterval(updateClock, 1000);
updateClock();
```

---


## 🎯 Future Enhancements  

✅ **Add AM/PM format option**  
✅ **Enable Dark/Light mode toggle**  
✅ **Customize font and colors dynamically**  

---

## 💡 Contributing  

🔹 **Fork the repository**  
🔹 **Create a new branch** (`feature-newFeature`)  
🔹 **Commit changes** (`git commit -m "Added a new feature"`)  
🔹 **Push to GitHub** and open a **Pull Request**  

---

## 📜 License  

📄 This project is **MIT Licensed** – Free to use and modify.  

---

## ⭐ Show Your Support  

Give a ⭐ **if you like this project!** 😊  

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/PranavThorat1432)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://linkedin.com/in/curiouspranavthorat)

