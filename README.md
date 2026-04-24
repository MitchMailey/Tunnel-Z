# Tunnel-Z (v14.16)

A procedural 3D tunnel runner. It is built on pure logic, without textures or audio files. This game uses mathematics, real-time synthesis, and aims for the "flow state."

It is inspired by classic Atari aesthetics and SpeedX 3D.

## 🚀 Key Features

-   **Zero Asset Design**: The entire game is generated via code in real-time. The visual world consists of 24 dynamic stripes and procedural geometry.
-   **Procedural Audio Synthesis**: Features a multi-layered dynamic soundtrack (ambient-trance) built with the Web Audio API. The music's tempo (BPM) scales directly with flight speed.
-   **Precision Input**: Optimized touch controls for mobile devices. Steer with left/right taps and fire with a dual-finger press without losing trajectory.
-   **Retro-Hardcore Gameplay**: Dodge mines, navigate narrow gaps between red obstacles, and manage ammo (shells) while the speed constantly increases.
-   **Local Records**: Tracks the personal best score and average speed.

## 🕹 How to Play

### Mobile (Android/Browser)

-   **Tap Left/Right**: Steer the tunnel.
-   **Dual Tap (Both sides)**: Fire a projectile.
-   **Objective**: Reach maximum distance and speed without hitting red obstacles. Green objects slow the player down (safely), yellow provides ammo, and purple mines cause turbulence.

### PC (Browser)

-   **Arrow Keys**: Steer.
-   **Spacebar**: Fire.

## 🛠 Tech Stack

-   **Engine**: [Three.js](https://threejs.org) (Vanilla JavaScript).
-   **Audio**: Custom synth engine using Web Audio API.
-   **Platform**: Cross-platform HTML5. Built for Android using [Capitator](https://capacitorjs.com).

## 💎 Credits

This project is a unique artifact of human-AI collaboration:

-   **Concept & Direction**: lek vob
-   **Code & Audio Synthesis**: AI on Google Search (powered by the Gemini family of models)

## 📜 License

This project is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

-   **Attribution**: Credit must be given to the authors.
-   **Non-Commercial**: This material may not be used for commercial purposes.
-   **Share-Alike**: If the material is remixed, transformed, or built upon, contributions must be distributed under the same license as the original.
-   **Forks**: All derivative works must remain free, open-source, and strictly ad-free.
