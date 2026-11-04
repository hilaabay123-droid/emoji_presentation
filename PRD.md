# Product Requirements Document (PRD)

## Project: The Secret Language of Emojis: Generational Semiotics & Interactive Arcade

### 1. Executive Summary & Overview
**The Secret Language of Emojis** is an interactive, single-file HTML presentation deck exploring the historical, semiotic, and sociolinguistic evolution of emojis across four generational cohorts: Baby Boomers, Generation X, Millennials, and Generation Z.

The project translates academic semiotics (signifier, signified, referent) into an engaging web application featuring real-time Three.js 3D elements, interactive mini-games, empirical data visualizations, and procedural audio synthesis.

---

### 2. Objectives & Key Results (OKRs)
- **O1: Intergenerational Translation:** Demystify tonal dissonance and workplace passive-aggression caused by emoji misinterpretations (e.g., 👍, 🙂, 💀).
- **O2: Deep Interactivity:** Ensure 100% of slides contain interactive UI components, games, or dynamic 3D visualizations.
- **O3: Architectural Elegance:** Package the entire experience—including styles, animations, games, 3D WebGL renderers, Web Audio synthesizers, and behind-the-scenes Python processing logic—into a standalone, zero-dependency single-file HTML deliverable (`emoji_presentation.html`).

---

### 3. Core Technical Architecture & Stack
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Markup & Semantics** | HTML5 (Strict LTR) | Semantic layout with `<main>`, `<section class="slide">`, `<header>`, `<footer>` |
| **Styling & Design System** | Modern CSS3 | Glassmorphism (`backdrop-filter: blur(24px)`), neon gradients, CSS grid & flexbox |
| **Typography** | Google Fonts | `Plus Jakarta Sans` (UI & Body), `JetBrains Mono` (Data, HUD, & Stats) |
| **3D Rendering** | Three.js (r128) | Ambient background particle field and Slide 1 3D smiling emoji with mouse gaze-tracking |
| **Audio Synthesizer** | Web Audio API | Procedural sound generation (whoosh, click, flip, chime, catch, bomb, victory) |
| **Behind-the-Scenes Logic** | Python 3 via Brython | Statistical distribution modeling and non-repeating trivia puzzle generation |
| **State Management** | Pure Vanilla JavaScript | Zero external runtime dependencies for core slide navigation and mini-games |

---

### 4. Slide-by-Slide Specifications

#### Slide 1: Title & Hero
- **Header:** Cultural Semiotics & Generational Linguistics.
- **Title:** The Secret Language of Emojis.
- **Hero Stats:** 10B+ daily volume, 84% workplace friction rate, 4 syntax models.
- **Interactive Three.js 3D Feature:**
  - Fully modeled 3D smiling emoji head with glossy yellow material, eye sockets, pupils, glints, rosy cheeks, and curved smile arc.
  - Continuous 360-degree turntable rotation around the Y-axis.
  - Interactive mouse/touch drag orbiting.
  - **Gaze Tracking:** Real-time mouse coordinate listener that steers pupils and eye groups to track cursor movement across the screen.

#### Slide 2: Emoji Dictionary (Gen Z vs. Gen X Perspectives)
- **Layout:** Responsive 8-card grid highlighting key divergent emojis (👍, 🙂, 💀, 🧢, 🤡, 💅, 🫠, ☕).
- **Dual Perspective Panels:**
  - **Gen X / Pragmatic:** Literal, task-oriented sign-off.
  - **Gen Z / Subversive:** Post-ironic, deadpan, or inverted subtext.
- **Interactivity:** Category filter tabs (*All*, *Workplace Hazards*, *Youth Inversion*, *Sass & Praise*), real-time search input, and click-to-expand cultural lore dialog.

#### Slide 3: Memory Game
- **Objective:** Pair 6 slang/cultural emojis with their authentic generational meanings (12 cards total).
- **Pairs:** 💀 ↔ "Dying of Laughter", 🧢 ↔ "Calling Out a Lie", 👍 ↔ "Dismissive Hostility", 🤡 ↔ "Acting Foolish", 💅 ↔ "Sassy Mic Drop", 🫠 ↔ "Smiling Through Dread".
- **Features:** 3D CSS flip transformations, live moves counter, elapsed timer, matches tracker, victory modal with celebratory chime, and deck restart button.

#### Slide 4: Popular Emoji Analytics
- **Data Visualization:** Clean HTML/CSS graphical horizontal bar chart displaying global transmission shares:
  - 😂 Tears of Joy (10.2%)
  - ❤️ Red Heart (8.4%)
  - 🤣 Rolling Laughter (6.8%)
  - 👍 Thumbs Up (5.4%)
  - 😭 Loudly Crying (4.9%)
  - 🙏 Folded Hands (4.1%)
  - 💀 Skull (3.9%)
  - 🥰 Smiling with Hearts (3.5%)
- **Category Filter Tabs:** *All-Time Global*, *Gen Z Peak*, and *Workplace Slack*.
- **Analytical Insights:** Semiotic Inflation Law breakdown and the Canadian $82,000 👍 court precedent.

#### Slide 5: Emoji Wordle
- **Game Mechanics:** 6 rows × 5 letter tiles, virtual QWERTY keyboard with color feedback, physical keyboard input routing.
- **Clue Structure:** Text-only descriptive clues (e.g., *"The morbid bone glyph that Gen Z uses to signify extreme laughter"* for `SKULL`).
- **Tile States:** 🟩 Correct position, 🟨 In word / wrong position, ⬛ Absent. Staggered flip animations and win/loss notifications.

#### Slide 6: Guess the Country by Emoji Triad
- **Game Mechanics:** Up to 3 emojis describe a specific nation (e.g., 🗼 🥖 🍷 for France, 🍣 🗻 🗾 for Japan, 🍕 🏛️ 🛵 for Italy).
- **Features:** Text input box with Enter key submission, alias normalization (e.g., "USA" / "America" for United States), streak counter, hint revealing continent and capital, and random new puzzle generation.

#### Slide 7: Emoji Avatar Builder
- **Customizer Canvas:** Live 160px circular preview stage with layered z-indexes and dynamic glowing background auras.
- **Layering Matrix:**
  - Base Face: 😀, 😎, 😉, 😆, 😐, 🤯, 💀, 👽, 🐱
  - Headwear / Hat: 🚫, 🥳, 🎩, 👑, 🤠, 🧢, 🎓, 🎧
  - Eyewear: 🚫, 🕶️, 👓, 🧐, 🥽, ⭐
  - Decorative Accents: 🚫, ✨, 🔥, ❤️, 💧, 🥸
- **Actions:** 🎲 *Randomize Avatar* generator and 📋 *Copy Glyph Stack* to clipboard.

#### Slide 8: Trivia Challenge
- **Quiz System:** 6 in-depth multiple-choice questions testing workplace communication etiquette, Canadian contract law, and slang origins.
- **Scoring & Feedback:** Real-time streak multiplier (+25 bonus per streak), immediate green/red option highlights, detailed cultural explanations, and final rank badge evaluation.

#### Slide 9: Historical Evolution (NTT DoCoMo to Unicode)
- **Chronology:**
  1. *1999 (Tokyo):* Shigetaka Kurita creates 176 12×12 pixel pictograms for NTT DoCoMo i-mode.
  2. *2010 (Unicode):* Unicode 6.0 integrates 722 emojis as computing characters.
  3. *2011–2015 (Smartphones):* Native keyboards on iOS & Android; 😂 named Oxford Word of the Year.
  4. *2016+ (Cultural Artifact):* MoMA permanent collection acquisition and binding courtroom legal precedents.
- **Interactive Feature:** "Toggle 12px Pixel View" demo rendering retro high-contrast pixelation.

#### Slide 10: "Catch the Emoji" Arcade Mini-Game
- **Arcade Engine:** Smooth 60 FPS animation loop with falling emojis (💖 +30, ⭐ +20, 💀 +15, 😂 +10, 🔥 +25).
- **Bomb Penalty:** 💣 deducts 50 points, breaks combo multiplier, removes 1 life, and triggers a stage screen shake.
- **HUD & Systems:** 30-second countdown timer, 3 hearts/lives system, floating score popups (+20!, -50 💣) at click position, and high-score persistence.

#### Slide 11: Closing & Thank You Finale
- **Design:** Glassmorphic frosted hero card surrounded by animated floating thank-you emojis (🙏, 💖, ✨, 🚀, 🎭, 🌟) and glowing pulsating hearts (❤️, 💖, 💜, 💙).
- **Actions:** Quick replay button to restart presentation from Slide 1 or jump directly into mini-games.

---

### 5. Non-Functional Requirements
- **Performance:** Smooth 60 FPS on desktop and mobile browsers; zero memory leaks during animation loops.
- **Usability:** Keyboard navigation (Arrow keys, Spacebar, Page Up/Down, Home, End, F for Fullscreen, M for Mute).
- **Accessibility:** High contrast text ratios, visible focus outlines, ARIA labels on navigation buttons, and LTR layout enforcement.
- **Self-Containment:** Runs offline directly from the local file system (`file:///`) with no required build step or external web server.
