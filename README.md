# ♟️ EchoBoard: Sensory-Augmented Gaming for the Blind
**A Multimodal Interface for Inclusive Social Play**

Designed as part of the Master of Design (MDes) program at UC Berkeley.  
*Core Concepts: Calm Computing, Sensory Substitution, and Social Interaction.*

---

## 🌟 The Vision
Traditional board games are often inaccessible to visually impaired players due to their reliance on visual patterns. **EchoBoard** transforms the user's finger into a "digital probe," using computer vision and spatial audio to bridge the gap between physical touch and mental mapping.

Instead of a chatty AI narrator, EchoBoard provides a **"Sensory Bridge"**—delivering minimalist audio and haptic feedback as the player explores the board with their hands.

## 🎨 Key Features (Interaction Palette)
- **Finger-as-a-Cursor:** Uses the mobile camera to detect the color/state of the game piece exactly where the user is pointing.
- **Minimalist Audio Feedback:** Converts color data into short, distinct vocal cues (e.g., "Red", "Yellow") or pitched earcons to reduce cognitive load.
- **Haptic Confirmation:** Short vibration pulses when a piece is detected, providing a tactile "click" in the digital space.
- **Perspective Mirroring:** Automatically adjusts coordinates so "Top-Left" for the camera means "Top-Left" for the player sitting across the board.
- **Social-First Design:** Engineered to be quiet and unobtrusive, allowing players to focus on their social connection rather than the technology.

## 🛠 Tech Stack
- **Framework:** React + Vite
- **Styling:** Tailwind CSS
- **AI/Vision:** OpenAI GPT-4o (Codex) / Web Camera API
- **Feedback:** Web Speech API (Audio) & Web Vibrations API (Haptic)
