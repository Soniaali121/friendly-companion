# 🌱 Safe Zone - AI-Driven Companion Web Application

A responsive frontend web application integrated with generative AI, engineered to provide a supportive, empathetic conversational interface for individuals navigating loneliness or personal hardship.

## 🚀 Core Features & Product Capabilities
* **Dynamic Multi-Turn Memory:** Implements a state-managed array pipeline to preserve full conversation context across interactions, mirroring professional chat interface logic.
* **Responsive Slide-out Drawer Architecture:** Features a smooth, accessible hamburger menu toggle that structures, abbreviates, and lists historical chat logs.
* **Context-Preserved Session Switching:** Allows users to archive active dialogues gracefully and initiate fresh instances via a clear session lifecycle handler.
* **Empathetic Prompt Engineering:** Enforces a precise backend context injection wrapper to transition the LLM outputs from rigid, technical configurations into gentle, human-centric peer responses.

## 🛠️ Technical Architecture & Stack
* **Frontend Framework:** React.js (built with Vite for highly optimized asset bundling and hot module reloading)
* **AI Orchestration Engine:** Google Gemini Developer SDK (`gemini-2.5-flash`)
* **State Management:** React Reactivity Hooks (`useState`, spread syntax mutations)
* **Styling Paradigm:** Component-scoped declarative JavaScript style objects for zero-dependency stylesheet loading

## 💻 Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd safe-zone-ai-companion
   ```

2. **Install node dependencies:**
   ```bash
   npm install
   ```

3. **Establish Environment Variable Credentials:**
   Open `src/App.jsx` and configure your API profile key variable context securely:
   ```javascript
   const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY_HERE";
   ```

4. **Launch the local development environment server:**
   ```bash
   npm run dev
   ```

## 📈 Future Iterations & Extensions
* Transitioning frontend browser client credentials to an isolated Node.js/Express server framework to mask keys seamlessly.
* Integrating a persistent client-side data mechanism (via `localStorage` or IndexedDB API) to prevent session data from clearing upon hard browser reloads.
