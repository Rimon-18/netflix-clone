# 🎬 Netflix Clone

A fully responsive Netflix UI clone built using HTML, CSS, and JavaScript.

## 🌐 Live Demo
👉[Click here to visit the live site]( https://rimon-movie-ui.netlify.app/)

## 🚀 Features
- Responsive design
- Netflix-style UI
- Smooth hover effects

## 📸 Screenshots
<img width="1882" height="1035" alt="image" src="https://github.com/user-attachments/assets/ac1fcdbc-fa7f-4fc4-883a-7586ca72d0ca" />



## 🛠️ Tech Stack
- HTML5
- CSS3

## 🧠 Challenges I Faced & How I Fixed Them

| # | Challenge | How I Fixed It |
|---|-----------|----------------|
| 1 | **Making the navbar transparent** that becomes solid on scroll | Used CSS `position: fixed` with `background: transparent` and added a scroll event listener in JavaScript to toggle a `.scrolled` class |
| 2 | **Hero section not filling full screen** on all devices | Used `height: 100vh` with `min-height` fallback and tested across screen sizes using Chrome DevTools |
| 3 | **Movie cards overflowing** outside the container on small screens | Fixed using `overflow-x: hidden` on parent and `flexbox` with `flex-wrap: wrap` for the card grid |
| 4 | **Images not maintaining aspect ratio** when resizing | Used `object-fit: cover` with fixed height containers to keep images consistent |
| 5 | **Hover effects not smooth** on movie cards | Replaced abrupt transitions with `transition: transform 0.3s ease` for a smooth scale effect |

> 💡 Each challenge taught me something new about responsive design and CSS behaviour across different screen sizes.

## 👨‍💻 Author
**Rimon**
- GitHub: [@Rimon-18](https://github.com/Rimon-18)
