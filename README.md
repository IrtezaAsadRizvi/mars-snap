# Mars Snap — Random Landscape Generator 🔴🏜️

<p align="center">
  <img src="https://i.ibb.co.com/rRhVQcKY/mars-snap-git-cover.jpg" width="900" alt="Mars Cover">
</p>

Generate cinematic, Mars‑like desert landscapes directly in the browser using WebGL, GLSL, and a multi‑pass renderer. This project creates **random Martian terrains** with atmosphere, fog, shadows, and filmic lighting — all procedural and reproducible, and is **primarily designed for wallpaper generation**.

> A shader‑driven Mars landscape generator for dramatic, dusty, red‑planet vistas.

---

## 📸 Preview

<table>
  <tr>
    <td><img src="https://i.ibb.co/Qjbs4cJm/mars-snap-git-gallery-1.jpg" width="260" alt="Mars Preview 1"></td>
    <td><img src="https://i.ibb.co/JF5RCvmq/mars-snap-git-gallery-2.jpg" width="260" alt="Mars Preview 2"></td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/XZ9q4yhj/mars-snap-git-gallery-3.jpg" width="260" alt="Mars Preview 3"></td>
    <td><img src="https://i.ibb.co/W4yWnJV5/mars-snap-git-gallery-4.jpg" width="260" alt="Mars Preview 4"></td>
  </tr>
</table>

---

## ✨ Highlights

- **Random Mars terrain generation** (heightmaps + noise)
- **Atmospheric sky + fog** for dusty red‑planet mood
- **Multi‑pass shader pipeline** (AO, lighting, composition)
- **Smooth viewport pan** for interactive viewing
- **One‑click PNG export**
- **Free to use** (see license, MIT)

---

## 🧭 Quick Start

```bash
npm install
npm run start
```

Open the local server URL printed by budo. Click **Next** to generate a new Mars scene, move the mouse to pan, and click **Download** to save.

---

## 🧱 How It Works (Mars Render Pipeline)

1. **Noise + Heightmap** → Martian terrain elevation
2. **Chunked geometry pass** → world positions
3. **Sky cubemap** → atmospheric scattering
4. **Shadow volume** → low‑angle sun shadows
5. **Normals + AO** → crater/detail depth
6. **Diffuse + Direct light** → dusty surface color
7. **Composition** → final Mars look

---

## 🎛️ Controls

- **Next** ▶️: generate a brand‑new Mars landscape
- **Mouse Move** 🖱️: smooth pan around the scene
- **Download** ⬇️: export PNG

---

## 📁 Project Structure

- `src/index.js` — app entry + UI + render orchestration
- `src/render.js` — multi‑pass rendering pipeline
- `src/commands.js` — regl draw commands
- `src/glsl/` — shader stages (height, sky, AO, compose, etc.)
- `public/index.html` — app shell

---

## ⚙️ Tech Stack

- **JavaScript** + **regl** + **GLSL**
- **gl-matrix** for camera math
- **budo / browserify** for dev bundling

---

## 🧪 Customization Ideas

- Push red/orange tones for **deeper Mars dust**
- Increase fog density for **stormy haze**
- Render at higher resolution for **poster‑quality Mars art**

---

## 🪪 License

This project is **free in every way**. You can use it commercially or personally, with or without attribution. Enjoy! 😄

---

## 🔎 Keywords (SEO)

Mars landscape generator, random Mars terrain, WebGL Mars scene, GLSL Mars shader, dune landscape renderer, procedural red planet, atmospheric scattering, desert terrain generator, regl WebGL.
