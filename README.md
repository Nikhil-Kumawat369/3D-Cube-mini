# 🎲 3D Rotating Cube (HTML & CSS)

A simple **3D rotating cube animation** built using pure **HTML and CSS**.  
This project demonstrates CSS 3D transforms, perspective, and keyframe animations — no JavaScript required.

---

## 🌐 Live Demo

🔗 **Deployed here:**  
https://nikhil-kumawat369.github.io/3D-Cube-mini/

---

## 🚀 Features

- Fully 3D cube rendered using CSS
- Smooth continuous rotation animation
- Six uniquely colored faces
- No JavaScript or external libraries
- Lightweight and beginner-friendly

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
  - `transform-style: preserve-3d`
  - `perspective`
  - `translateZ`
  - `rotateX` / `rotateY`
  - `@keyframes` animations

---

## 📁 Project Structure

    ├── index.html
    ├── style.css

---

## ⚙️ How It Works

- The `#container` element sets the 3D perspective.
- The `#cube` element preserves the 3D space for its children.
- Each face is positioned using CSS transforms to form a cube.
- A keyframe animation rotates the cube on both X and Y axes for a smooth 3D effect.

---

## ▶️ How to Run Locally

1. Clone or download this repository
2. Ensure `index.html` and `style.css` are in the same directory
3. Open `index.html` in your browser

No setup or dependencies required 🎉

---

## 🎨 Customization

- **Change cube size**  
  Update the width and height of `#container` and adjust `translateZ`.

- **Change rotation speed**  
  Modify the animation duration:
  ```css
  animation: spin 15s ease-in-out infinite;

- **Change colors**
  
  Edit background colors for each face (#front, #back, etc.).

## 🎯 Learning Purpose

This project is great for learning:

- CSS 3D transforms

- Perspective and depth handling

- Keyframe animations

- Structuring small visual projects

## 📜 License


>This project is open for learning and experimentation.
>You may modify, distribute, or expand it freely.


## 👤 Author


Developed by: Nikhil Kumawat
<br>
Language: HTML | CSS 
<br>
Project: Move Of Faith


>“Not so simple , Not so mini.”
