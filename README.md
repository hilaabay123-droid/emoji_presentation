# 🎭 The Secret Language of Emojis
### *Generational Semiotics, Digital Kinesics & Interactive Arcade*

A cutting-edge, single-file HTML5 interactive presentation deck that explores how humble pictograms evolved from utilitarian 12×12 pixel pager icons in Tokyo into high-stakes, post-ironic generational cryptography across Baby Boomers, Generation X, Millennials, and Gen Z.

---

## 🌟 Live Interactive Features & Slide Breakdown

The presentation is structured into cohesive slides, each featuring high-end interactive mechanics and visuals:

1. **Slide 1: Title & Hero (Three.js 3D Smiling Emoji)**
   - Custom 3D smiling emoji rendered via Three.js with continuous 360° rotation.
   - **Gaze Tracking:** The emoji's pupils and eye assemblies track the user's mouse cursor in real-time across the screen.
   - Interactive mouse/touch dragging for manual 3D rotation.

2. **Slide 2: Generational Emoji Dictionary**
   - Interactive card grid presenting emojis with side-by-side perspectives: **Gen X Pragmatic Literalism** vs. **Gen Z Post-Ironic Subversion**.
   - Category filtering (*Workplace Hazards*, *Youth Inversion*, *Sass & Praise*) and instant search.

3. **Slide 3: Memory Match Mini-Game**
   - Generational matching game pairing emojis (💀, 🧢, 👍, 🤡, 💅, 🫠) with their authentic cultural interpretations.
   - Live moves counter, elapsed timer, 3D flip card animations, and victory banner.

4. **Slide 4: Popular Emoji Analytics**
   - Clean graphical statistical horizontal bar chart visualizing global transmission volume percentages (😂 10.2%, ❤️ 8.4%, 🤣 6.8%, 👍 5.4%, etc.).
   - Category switches for *All-Time Global*, *Gen Z Peak*, and *Workplace Slack*, complete with case study notes (e.g., Canada's $82,000 👍 court ruling).

5. **Slide 5: Emoji Wordle**
   - Playable Wordle game with 6 rows of 5 letter tiles, virtual QWERTY keyboard, and physical keyboard support.
   - Uses text descriptions as clues instead of pictures.

6. **Slide 6: Guess the Country by Emoji Triad**
   - Trivia game presenting up to 3 emojis describing a nation (e.g., 🗼 🥖 🍷 for France, 🍣 🗻 🗾 for Japan).
   - Text input with auto-alias matching, hint button (continent and capital), and random puzzle generator.

7. **Slide 7: Interactive Emoji Avatar Builder**
   - Real-time customizer layering base faces, headwear/hats, eyewear/glasses, decorative accents, and ambient glows.
   - Includes 🎲 *Randomize* and 📋 *Copy Glyph Stack* functions.

8. **Slide 8: Generational Trivia Challenge**
   - Multiple-choice quiz testing knowledge of workplace Slack etiquette, legal contract precedents, and slang origins.
   - Instant scoring with streak multiplier (+25 pts per streak) and feedback.

9. **Slide 9: Historical Evolution (NTT DoCoMo to Unicode)**
   - Chronological breakdown from Shigetaka Kurita's 1999 DoCoMo 12×12 pixel set to Unicode 6.0 and MoMA's permanent architecture collection.
   - Retro "Toggle 12px Pixel View" demo.

10. **Slide 10: "Catch the Emoji" Arcade Mini-Game**
    - Fast-paced arcade game with falling emojis (💖 +30, ⭐ +20, 💀 +15, 😂 +10, 🔥 +25).
    - Dodge bombs (💣 -50 pts, lose a heart, screen shake).
    - Features a 30-second timer, 3 lives system, combo multipliers, and high-score tracking.

11. **Slide 11: Presentation Finale & Thank You**
    - Glassmorphic closing card surrounded by animated floating thank-you emojis and glowing hearts.
    - Quick-navigation buttons to replay from Slide 1 or jump directly into mini-games.

---

## 🛠️ Technology Stack & Architecture

- **Markup:** Semantic HTML5 (Strict Left-to-Right `dir="ltr"`).
- **Styling:** Vanilla CSS3 featuring glassmorphism (`backdrop-filter: blur(24px)`), radiant neon gradients, and responsive CSS grid/flexbox.
- **Typography:** Google Fonts (`Plus Jakarta Sans` for titles/UI, `JetBrains Mono` for data and counters).
- **3D Graphics:** [Three.js (r128)](https://threejs.org/) for ambient particle constellations and the interactive Slide 1 3D gaze-tracking emoji.
- **Audio:** Native Web Audio API procedural synthesizer (whooshes, clicks, flips, catches, bomb blasts, chimes) with mute toggle (`M`).
- **Behind-the-Scenes Python Engine:** [Brython](https://brython.info/) executing client-side Python 3 script (`#python-backend`) for data distribution models and non-repeating trivia puzzle selection, with zero raw code blocks displayed on screen.

---

## 🚀 How to Run

No build step, Node.js runtime, or local server is required.

1. Clone or download the repository.
2. Double-click `emoji_presentation.html` or open it in any modern browser (Chrome, Edge, Firefox, Safari).
3. Use the navigation buttons, indicator dots, or keyboard shortcuts:
   - `Right Arrow` / `Page Down` / `Space`: Next Slide
   - `Left Arrow` / `Page Up`: Previous Slide
   - `Home` / `End`: First / Last Slide
   - `F`: Toggle Fullscreen
   - `M`: Toggle Sound Effects

---

## 📁 Repository Structure

```text
├── emoji_presentation.html  # Standalone single-file interactive presentation deck
├── PRD.md                  # Comprehensive Product Requirements Document
└── README.md               # Project documentation and feature overview
```

---

## 📄 License
MIT License. Created for education, cultural research, and interactive fun!
