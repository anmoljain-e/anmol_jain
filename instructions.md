# Project Requirements Document: Web Platform & Mini-Game Suite

---

## 1. Context
We are developing an online gaming website built around learning games for children. This project is focused on the complete design and front-end development phase of a premium, multi-level educational portal featuring interactive gameplay, reward logic and a child-safe responsive interface that scales seamlessly from desktop monitors down to mobile and tablet screens.

This is a front-end implementation brief intended for deployment use and final evaluation. It is not a backend server engineering or live database infrastructure specification. The final deliverable is a complete code package including working pages, four functional browser games, local storage integration and layout styling, ready for launch configuration.

---

## 2. About the Client & Target Audience
The target platform framework is commissioned by BrightPlay to streamline supplementary primary education through play. The vision is a bright, high-quality, kid-first digital space that combines core syllabus subjects, adaptive game sessions, progress visualization and intuitive interactions. 

The primary users are children aged 6 to 12 years and secondary users include parents and school teachers who pick games for kids. The interface must utilize simple vocabulary, big buttons, clear iconography and vibrant colors to empower independent discovery.

---

## 3. Main Goal
Design and deliver a complete web application architecture and functional interface package for a multi-level learning portal covering home landing zones, filtered games libraries, an isolated gameplay core and a localized reward dashboard, ensuring an optimized layout structure for both desktop environments and tablet touch interfaces.

---

## 4. Scope of Work

### A. Pages & Views Layout
* **Home / Landing Page:**
    * **Hero Container:** High-contrast introductory banner displaying the brand name, a short line and a clear "Start Playing" call-to-action button.
    * **Subject Matrix:** A horizontal sequence or multi-column row displaying stylized navigation cards for core subjects (Maths, English, Science, Logic). On desktop and tablet screens, these cards display in a multi-column row to maximize space utilization.
    * **Featured Grid:** A modular grid display highlighting 4 to 6 curated game recommendation slots, adapting from a 3-column grid on desktop to a 2-column layout on tablets.
    * **Workflow Guide:** A brief structural workflow breaking down platform usage into 3 simple, step-by-step educational illustrations.
    * **Global Footer:** Base navigational strip consolidating structural informational links like About, Contact and For Parents.
* **Games Library Page:**
    * A grid of game cards, each embedding a game name, subject, an icon or image and a "Play" button.
    * **Filter Panel:** Interactive filter states segregating entries by subject category and age brackets covering 6 to 8, 9 to 10 and 11 to 12 years. It renders as a sidebar on desktop viewports and a top-expanding accordion menu on tablets.
    * **Alphanumeric Search:** A real-time text input filter matching alphanumeric user inputs against explicit game names.
* **Game Play Page (Shared Architecture):**
    * **Status Header:** Global control strip tracking game name, active numeric scores and remaining lives or duration counts.
    * **Central Gameplay Arena:** Isolated, centrally aligned container component executing active application logic. It uses generous scaling boundaries optimized for desktop pointer control and wide tablet touch zones.
    * **Session State Controls:** Easily accessible interactive triggers executing pause states and immediate match resets.
    * **End-State Overlay:** Post-match overlay displaying performance breakdowns, final score, stars earned, a "Play Again" retry hook and a "Back to Library" navigation button.
* **Progress / Rewards Dashboard:**
    * Prominent text metrics plotting cumulative lifetime points stored within the active browser session.
    * A milestone badge display mapping out unlocked configurations for bronze, silver and gold achievements.
    * An index ledger tracking a simple list of games previously completed by the client instance.
* **About / For Parents Page:**
    * Explanatory text frames detailing the non-commercial, ad-free environment engineered for children. Uses multi-column typographic setups on wider desktop screens to prevent overly long line measures.

### B. Functional Mini-Games to be Built
The platform must deploy at least four fully playable browser-executable mini-games, integrated with explicit tutorial instructions prior to initialization, active live scoring, visual or auditory feedback vectors on interaction events and clear end-state conditions:
1. **Maths Game ("Speedy Maths" / "Are You Smarter Than a 5th Grader?" Trivia Style):** An adaptive fast-paced mental arithmetic challenge where children solve addition, subtraction or multiplication problems within a strict time threshold. It uses a trivia presentation style scaled perfectly for reading across tablet and desktop monitors.
2. **English Game ("Word Builder"):** A spelling and character matching interface where users fill in missing characters or link words to cartoon graphics.
3. **Science Game ("Sort It Out"):** A sorting application utilizing touch-friendly drag-and-drop mechanics to group items into correct classification boundaries (e.g., living vs. non-living).
4. **Logic Game ("Memory Match" / "Matrix Match"):** A spatial logic puzzle using matrix grids, grid navigation patterns or card-flipping memory match sequences to challenge cognitive recognition.

---

## 5. Visual Design System & Color Palette

### Color Palette Specification

The interface must strictly employ the following hexadecimal color codes to guarantee brand consistency and high visual contrast:

| Role Identifier   | Hexadecimal Code | Explicit Application Bounds                                                                       |
| :---------------- | :--------------- | :------------------------------------------------------------------------------------------------ |
| **Deep Navy**     | `#1E3A8A`        | Main brand color, headers, navigation bars, and primary interface elements.                       |
| **Bright Blue**   | `#3882F6`        | Primary buttons, links, interactive elements, and secondary highlights.                           |
| **Teal Green**    | `#108981`        | Science subject accents, success indicators, correct answer feedback, and positive notifications. |
| **Amber Yellow**  | `#F59E0B`        | Call-to-action buttons, highlights, badges, and mascot illustrations.                             |
| **Coral Red**     | `#EF4444`        | Maths subject accents, alerts, error messages, and score deductions.                              |
| **Royal Purple**  | `#885CF6`        | Logic subject accents, special achievements, and premium highlight elements.                      |
| **Off White**     | `#F8FAFC`        | Page backgrounds, content cards, and internal game canvas frames.                                 |
| **Charcoal Gray** | `#1F2937`        | Main text, heading titles, icons, and footer backgrounds.                                         |
| **Medium Gray**   | `#6B7280`        | Subtext, captions, helper text, and secondary descriptive content.                                |


### Typography & Component Layout Rules
* Poppins (Bold for headings, Regular for body)
* **Body Content:** Rendered in highly legible fonts (Poppins) with a strict minimum base size of 16px to support developing eyes.
* **Interactive Controls:** Massive, high-tactility tap blocks with explicit bold typography, configured for large tablet touch-targets and easy desktop pointer interactions.

---

## 6. Technical Stack

| Layer Matrix | Architecture Specification |
| :--- | :--- |
| **Scripting Core** | Plain HTML5, native CSS3 and structural Vanilla JavaScript (ES6+) or a framework like React. |
| **External Controls** | No paid backend, server or database is required. Only free or original assets are permitted. |
| **Data Persistence** | Web Browser LocalStorage APIs for profile state mapping and reward logging. |
| **Responsive Engine** | Native CSS3 incorporating multi-column layouts and media querying optimized for mobile, tablet and desktop breakpoints. |

---

## 7. Deliverables

| No. | Item Description | Format Requirements |
| :--- | :--- | :--- |
| **1** | **Basic Floor plans / View Layouts** | Fully functional front-end files spanning all core views (Home, Library, Gameplay, Rewards and About). |
| **2** | **Four Working Games Delivered** | At least four operational internal browser game packages embedded directly into the workspace. |
| **3** | **Responsive Design Assets** | Modular CSS3 stylesheets ensuring perfect layout adaptation across desktop, tablet and mobile screens. |
| **4** | **Source Code Delivered** | Clean, commented and well-organized source files provided in a single zip or public repository link. |
| **5** | **Read Me and Run Steps** | A comprehensive `README.md` file featuring setup guidelines, local run steps, a list of games built and an asset attribution log. |

---

## 8. Scope Boundaries & Exclusions

* **IN-SCOPE:** All front-end page layouts listed in the scope; all four functional browser games; responsive desktop/tablet/mobile styling and local reward storage systems; clean, commented source code and readme instructions.
* **OUT-OF-SCOPE:** Real user accounts with email and password login; online multiplayer functionality; payment gateways or subscription features; a custom server or live backend database; mobile app versions compiled for native app stores.