# ✈️ ScrollTrigger 3D Plane Animation

This project demonstrates a **3D interactive scroll-based animation** using **Three.js** and **GSAP (GreenSock)** with the **ScrollTrigger** and **DrawSVG** plugins.  
It loads a 3D plane model (`.obj`), sets up a Three.js scene, and animates the plane along with SVG blueprint lines as the user scrolls.

---

## 🚀 Features
- 3D model rendering with **Three.js**
- Smooth animations with **GSAP**
- **Scroll-triggered effects** (plane rotation, movement, and scene transitions)
- **SVG line drawing animations** (length, wingspan, and phalange indicators)
- Responsive rendering with window resize handling
- Layered rendering using multiple cameras

---

## 📂 Project Structure
.
├── script.js # Main script handling scene setup, model loading, and animations
├── index.html # Example HTML file (include Three.js, GSAP, and plugins here)
├── style.css # Optional styling for layout and scroll sections

php-template
Copy
Edit

---

## 🛠️ Dependencies
Make sure you include the following libraries in your HTML file:

- [Three.js](https://threejs.org/)  
- [GSAP](https://greensock.com/gsap/)  
- [GSAP ScrollTrigger Plugin](https://greensock.com/scrolltrigger/)  
- [GSAP DrawSVG Plugin](https://greensock.com/drawsvg/)  
- [OBJLoader](https://threejs.org/docs/#examples/en/loaders/OBJLoader)

Example (CDN links in your `index.html`):

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/ScrollTrigger.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/DrawSVGPlugin.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/three@0.128.0/examples/js/loaders/OBJLoader.js"></script>
▶️ Usage
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/scrolltrigger-3d-plane.git
Open index.html in your browser.

Scroll down the page to see the 3D plane animation and SVG line effects.

🎥 Demo
When you scroll:

The plane smoothly rotates and moves in 3D space.

SVG blueprint lines animate (drawSVG) to highlight different parts of the plane.

Ground and cloud layers shift for parallax-like effects.

📸 Preview
<img width="1851" height="872" alt="Screenshot 2025-08-22 212951" src="https://github.com/user-attachments/assets/a4c498cb-8955-4a69-946c-2112117964fa" />


🧑‍💻 Author
Developed by Pavankalyan ✨

📜 License
This project is licensed under the MIT License – feel free to use and modify it.

Copy
Edit
