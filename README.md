# WeebzSlayer_Scene ⚔️

![Status](https://img.shields.io/badge/Status-Live-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-black?style=flat-square)
![Category](https://img.shields.io/badge/Category-Modding-blueviolet?style=flat-square)

**WeebzSlayer_Scene** is an AI-powered background removal tool designed specifically for **technical artists** and **modders** 🎨. Unlike standard background removers that tightly crop subjects, this tool performs **Intelligent Scene Extraction**. Preserving the character and the physical surface they are standing on while erasing sky, horizons, and background clutter.

Specially designed to create stencils for **login screen backgrounds in Woltk** ❄️.

<img width="1423" height="685" alt="WS_Scene preview" src="https://github.com/user-attachments/assets/bc112cb5-63fb-456f-af9e-2ddcb0cca308" />

## ⚡ Key Features

- **📍 Spatial Consistency**: Extracted subjects remain in their **exact original relative coordinates**. No automatic centering or scaling shifts.
- **🏜️ Scene-Aware Extraction**: Automatically identifies and retains the "ground" or "surface" context (sand dunes, floors, platforms).
- **🔒 Hard-Locked 1K Output**: All renders are strictly normalized to **1024x1024 pixels** 📐, optimized for texture mapping and asset engines.
- **🖥️ Ultra-Minimalist UI**: A distraction-free, terminal-inspired interface using a strict **grey-on-black aesthetic** 🌑.
- **🚀 High-Performance AI**: Powered by the **Gemini 2.5 Flash-Image core** for near-instant results. *(Note: This may be updated in future releases as new free models for image editing become available)*.

## 🛠 Tech Stack

- **Frontend**: React 19 ⚛️ + Tailwind CSS 🌬️ + TypeScript 📘
- **AI Core**: Google Gemini 2.5 API (Flash Image) 🧠 I'm trying to implement Gemini 3 at the moment, without reaching the credit limit too early. 
- **Native Version**: C# .NET 8.0 (Windows Forms) #️⃣

## 📖 Usage Instructions

1. **📂 LOAD**: Click the `[ LOAD_ASSET_MODULE ]` zone to import a `.png`, `.jpg`, or `.jpeg`.
2. **👁️ REVIEW**: View your source image in the `BUFFER_INPUT_01` pane.
3. **⚔️ SLAY**: Press `_EXECUTE_SCENE_SLAYER`. The AI will compute the mask, remove the background, and normalize the scene to **1024x1024**.
4. **💾 EXPORT**: Use `OUT_JPEG` for compressed previews or `OUT_PNG` for **high-quality lossless assets**.

## 📝 Specifications

- **📄 Input Formats**: PNG, JPG, JPEG
- **📺 Output Resolution**: 1024x1024 (1:1 Ratio)
- **⬜ Background**: Solid White (#FFFFFF)
- **⚓ Spatial Logic**: Subject Anchor Retention (No shifting)

## 👾 Credits

- **[WeebzSlayer](https://github.com/WeebzSlayer)**  

---

*Slay those weebz!* 🗡️
