
# 🎄 Grand Luxury Tree

[![Contributors](https://img.shields.io/github/contributors/electronicminer/gesture-Christmas_tree-3d_with_photo?color=dark-green)](https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors)

Hello! This is a small project created to celebrate Christmas. ✨

Originally, I just wanted to draw a regular 3D Christmas tree, but I thought it wasn't cool enough, so I added **gesture recognition** and **particle effects**. Now you can control this tree "remotely" through your camera and hang your favorite photos on it.

Although it's only a few hundred lines of code, the visual effects are maxed out (especially on large screens).

Click the link below to access it directly:
https://electronicminer.github.io/gesture-Christmas_tree-3d_with_photo/christmas_tree_touch&gesture.html

<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf" />


## 🤔 What is this? (Intro)

This is not one of those static webpage greeting cards. This is a dynamic tree composed of **thousands of particles**.
I integrated Google's MediaPipe, so it can understand your gestures.

* **Particle Effects**: The tree breathes, rotates, and can explode into a sky full of stars.
* **Remote Control**: No mouse needed, just wave your hand at the camera to control it (feels like Doctor Strange).
* **Hang Memories**: Click the button in the upper right corner to upload photos, and they'll turn into gold-framed Polaroids floating around the tree.
* **Minimalist Aesthetic**: Only black and gold colors, no flashy decorations, focusing on a "premium feel".
<img width="2557" height="1291" alt="image" src="https://github.com/user-attachments/assets/d7d31b4c-bf4d-49b2-b922-79813bbddba5" />

<img width="2559" height="1294" alt="image" src="https://github.com/user-attachments/assets/d7e4e982-3042-449d-8898-105048aeac1d" />


## 🛠️ What's Used? (Tech)

Pure frontend magic, no complex frameworks:
* **Three.js** - Handles 3D rendering and particle systems.
* **MediaPipe** - Handles gesture recognition (this thing is so powerful).
* **Vanilla JS (ES Modules)** - Hand-coded core logic.

## 🎮 How to Play? (Controls)

For first-time players, it's recommended to turn on your speakers (although there's no background music yet, you can play Jingle Bells yourself 🎵).

### 🖐️ Gesture Mode (Key Feature!)
Make sure your browser allows camera access, then:
1.  **Open Palm (🖐️)**: This is "explosion mode"! The tree will scatter into a nebula, and you can rotate the view.
2.  **Closed Fist (✊)**: Contract! The particles will reassemble into a Christmas tree.
3.  **Pinch Fingers (🤏)**: Like pinching something, it will randomly grab a photo and zoom in for you.

### 🖱️ Mouse Users
* Left-click drag to rotate, scroll wheel to zoom.
* **H Key**: Press to hide all UI, great for screenshots or recording wallpapers.

## 🚀 How to Run

⚠️ **Warning:** Because ES Modules and camera permissions are used, **DO NOT open `index.html` by double-clicking**, the browser will report an error (CORS policy restrictions). You need to start a local server.

**If you have VS Code (Recommended):**
Install the `Live Server` plugin, right-click `index.html` -> "Open with Live Server". Done.

**If you're a Python expert:**
Open terminal in the directory:
```bash
python -m http.server 8000
````

Then visit `localhost:8000` in your browser.

**If you're used to Node.js:**

```bash
npx http-server .
```



**Merry Christmas\! 🎅**
If you think this project is interesting, feel free to Star it, or Fork it and change it to your favorite colors!

Added mobile web support
## Contributors ✨

Thanks to all the developers who contributed to this project:

<a href="https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=electronicminer/gesture-Christmas_tree-3d_with_photo" />
</a>

## 📊 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=electronicminer/gesture-Christmas_tree-3d_with_photo&type=Date)](https://star-history.com/#electronicminer/gesture-Christmas_tree-3d_with_photo&Date)
