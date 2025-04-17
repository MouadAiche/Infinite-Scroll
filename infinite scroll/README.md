# ♾️ Infinite Scroll Animation

A smooth and continuous scrolling animation built with **HTML** and **CSS**, perfect for sliders, showcases, or animated banners.

---

## 📺 Live Demo

🔗 [Live Demo](https://mouadaiche.github.io/Infinite-Scroll/infinite%20scroll/)

---

## 🛠️ Features

- 🔄 Seamless infinite horizontal scrolling  
- 🧱 Two wrapper rows for synchronized motion  
- 🧩 Pure CSS animations using `@keyframes`  
- 🧮 Custom delay calculation for each item to maintain spacing  
- 🌈 Fully responsive and visually centered layout  

---

## 📁 Project Structure

```
📦 Infinite Scroll Animation
├── index.html
├── style.css
└── README.md
```

---

## 🧠 How It Works

- `.Item` elements are absolutely positioned and animated from right to left  
- Each item has a unique `animation-delay` for perfect spacing and loop sync  
- `wrapper-1` and `wrapper-2` repeat the same items for continuous movement  
- `left: max(calc(200px * 8), 100%)` ensures smooth start outside the container  
- All logic handled with CSS — no JavaScript needed  

---

## 🧰 Tech Stack

- **HTML5**
- **CSS3**

---

## 📜 License

This project is open-source and free to use.
