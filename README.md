# ⚡ VIBE | Select Your Frequency

VIBE is a premium, minimalist, and ultra-responsive web hub for party games designed to break the ice, bypass superficial small talk, and inject raw, dynamic energy into any gathering. Built completely on a native web stack without heavy frameworks, it merges zero-dependency frontend design with interactive physics-based backgrounds, smooth spatial accessibility features, and strict data persistence.

The core design centers around an immersive, premium user experience featuring subtle fluid backdrop elements, beautiful theme overrides for individual game states, and absolute customization control.

---

## 🎨 Core Architectural & Aesthetic Design

VIBE is built to adapt beautifully to your environment and hardware setup. It utilizes a highly tailored front-end pipeline featuring:

*   **Dynamic Theme Engines:** The interface dynamically morphs its CSS variable variables based on the active game module, moving fluidly from a unified menu gradient to highly specialized colors (Emerald for Never Have I Ever, Crimson for Do or Drink, and Blue/Sky for Would You Rather).
*   **Aesthetic Invariance (Dark/Light Modes):** The application respects your system settings natively, utilizing strict CSS media queries (`prefers-color-scheme`) to switch into a clean, minimalist Dark Mode setup. This reduces screen glare during night sessions while preserving rich element scaling.
*   **Interactive Particle Canvas Layer:** Built using custom hardware-accelerated HTML5 Canvas operations, the background features an advanced spatial matrix grid that calculates mouse/touch vectors in real time, drawing individual nodes closer to user click or drag movements with smooth mechanical dampening physics.
*   **TV & D-Pad Spatial Navigation:** Featuring a custom keybound traversal algorithm, the site fully maps spatial directional strokes (`ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`) to let users traverse standard grid components with ease. Perfect for setting up onto a central living room monitor, smart TV browser, or gamepad emulator mapping environment.
*   **True Randomness via Fisher-Yates Shuffling:** To avoid the repetitive prompt traps common in basic digital card apps, VIBE processes card selections using an unbiased Fisher-Yates array-mutation algorithm. Decks are perfectly randomized upon initialization, and a question is completely removed from execution visibility until the absolute exhaustion of the deck array.

---

## 🕹️ The Game Modules & Frequencies

VIBE splits its content catalog into four distinctly balanced frequencies, each curated to drive varying degrees of interaction.

### 🟣 1. BYPASS
*   **The Vibe:** Deep, revealing, and chaotic truths.
*   **Description:** Skip the standard introductory chatter and go straight into core motivations. Bypass consists of 100 heavily curated, high-impact confession questions designed to uncover hidden perspectives, hilarious past situations, and unfiltered opinions. 
*   **Sample Questions:**
    *   *What is a secret you know about someone else that could ruin their life?*
    *   *If you were arrested tomorrow, what would your friends assume you did?*

### 🟠 2. Do or Drink (Casual Forfeits)
*   **The Vibe:** Brutal dares and chaotic structural physical actions.
*   **Description:** A massive collection of high-energy active dares ranging from dramatic pop-culture impersonations to social-roulette text messaging assignments. It includes an integrated safety disclaimer system that can be paired seamlessly with any party format.
*   **Sample Dares:**
    *   *Prank call a friend and ask “Did you take my mango?”*
    *   *Text your crush “Guess what?” and don’t reply for 5 minutes.*

### 🟢 3. Never Have I Ever
*   **The Vibe:** The ultimate crowd-source confession game.
*   **Description:** The classic rulebook, modernized for immediate group engagement. Ideal for checking past shared experiences, wild coincidences, or unbelievable accidents. Players reveal secrets together based on historical actions.
*   **Sample Statements:**
    *   *Never have I ever skipped school while at school.*
    *   *Never have I ever practiced kissing on my hand or a pillow.*

### 🔵 4. Would You Rather
*   **The Vibe:** Impossible dilemmas and mind-bending situational choices.
*   **Description:** Two-pronged choices engineered to spark heavy debates and structural disagreements among group members. No middle ground allowed—forcing players to explicitly choose the lesser of two bizarre evils.
*   **Sample Dilemmas:**
    *   *Would you rather always have to say everything on your mind, OR never be able to speak again?*
    *   *Would you rather fight one horse-sized duck, OR a hundred duck-sized horses?*

---

## 📜 The Golden Rule: absolute Flexibility

> ⚠️ **Rule #1 of VIBE: There are no rigid rules.**

Every single mechanic, forfeit, and structural condition inside VIBE is **100% flexible** and open to group interpretation. 

*   **Customizing Forfeits:** While certain modes explicitly use the word *"Drink"*, this is a variable token placeholder. The group can collectively define the consequence to fit the exact context of the evening. Forfeits can easily mean:
    *   Sips of water or carbonated soda.
    *   Losing a tournament life/point block from a starting pool of 5 points.
    *   Performing a quick physical forfeit (e.g., 5 push-ups).
    *   Doing an embarrassing task dictated entirely by the rest of the players.
*   **Skipping/Veto Controls:** If a card doesn't fit the current room energy, any player can use a collective veto to swipe it away. The interface supports simple 3D flip card animations—click to reveal, swipe or click again to clear the deck slot cleanly.
*   **The Custom Prompt Injector:** Want to create specific group internal jokes or localized rules? Click the **"+"** icon in the header controls to open the real-time custom deck injector. Add entries instantly, and they will be cleanly mixed directly into the active Fisher-Yates array rotation.

---

## 🛠️ Technology Stack & Local Storage Engine

*   **Languages:** HTML5, CSS3 (Modern Flexbox/Grid architecture with CSS Variables), Native ES6+ Vanilla JavaScript.
*   **Zero Dependencies:** No external React, Vue, Tailwind, or NPM packages required. Pure runtime engine execution directly inside standard rendering environments.
*   **State Persistence Matrix:** Uses standard browser `localStorage` variables to back up active party positions. If the host machine suffers an accidental page reload or closing action, the state recovery engine instantly re-maps the current deck array index, preventing loss of game progress.
*   **Animations:** Linear 145-degree glassmorphic layouts utilizing heavy `-webkit-backdrop-filter` rules for clean blur properties on high-end smartphone displays, along with custom CSS transforms for 3D card flips.

---

## 🚀 Deployment Instructions

As a fully self-contained client-side single-page application (SPA), VIBE requires zero backend servers or build steps to compile.

1.  **Fork or Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/vibe.git](https://github.com/YOUR_USERNAME/vibe.git)
    ```
2.  **Launch Directly:**
    *   Open `index.html` natively inside any mainstream web browser.
    *   Alternatively, serve via simple Python tooling:
        ```bash
        python -m http.server 8080
        ```
3.  **GitHub Pages Compatibility:**
    *   Go to **Settings -> Pages** inside your repository.
    *   Set the Build and Deployment source branch to `main` (or root path).
    *   Hit save, and your application link will be live in seconds under an absolute SSL ecosystem.
