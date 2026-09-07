# Portfolio Website Project Documentation

## 1. Student Information
* **Name:** Cholla Sidhartha
* **SAP ID:** 590021764
* **Program / Batch:** B.Tech Computer Science and Engineering (2nd Year, Core CS), UPES Dehradun
* **Date:** September 7, 2026

---

## 2. Template & Starting Point
* **Starting Point:** Built from scratch without pre-packaged templates, CSS UI frameworks (such as Bootstrap or Tailwind), or Node/npm build tools.
* **Core Technologies:** Semantic HTML5, standard CSS3, vanilla JavaScript, and lightweight animation utilities integrated via public CDN endpoints (GSAP, ScrollTrigger, Lenis).

---

## 3. AI Tools & Attribution
* **AI Tool 1 (Concept Structuring & Idea Generation):** Used ChatGPT to explore general layout concepts, content wireframes suitable for an engineering student, and high-level UX behavior patterns.
* **AI Tool 2 (Code Scaffolding & Technical Implementation):** Used Gemini to synthesize the drafted layout requirements into clean, zero-npm code, implement responsive styling, coordinate the JavaScript animation loops, and debug script interactions.

---

## 4. Prompts & Direction Strategy

Rather than requesting a ready-made website in a single command, the development relied on a multi-stage approach. An initial architectural blueprint and UX guidelines were formulated using an exploratory AI session, then adapted and supplied to the coding assistant through iterative feedback prompts.

### Stage 1: Structural Scaffolding & Initial Prompt
> "Create a complete, single-file personal portfolio using pure HTML, CSS, and modern vanilla JavaScript without any npm or local build tool dependencies. Structure the layout around standard sections: a fixed top navigation, a hero introduction, an about section featuring student background information and technical tools (HTML, CSS, JS, Python, C, C++, Bash), a projects showcase with clear summaries and tags, an interactive contact area, and a footer linking a documentation download. Keep the visual language clean, modern, and uncluttered, with readable typography and subtle contrast. Integrate a custom SVG preloader overlay that hides cleanly once window assets resolve."

### Stage 2: Motion, Scrolling, and Interaction Polish
> "Review the single-page layout and enhance the overall interaction flow. Introduce smooth momentum-based page scrolling via a lightweight script and incorporate scroll-driven section transitions. Replace static card grids with a continuous horizontal viewing sequence that activates when scrolling through the projects section. Add microinteractions across buttons, interactive elements, and ambient background details so the site feels responsive to user movement without disrupting layout readability."

### Stage 3: Fine-Tuning & Content Balance
> "Adjust the copy across the page to ensure the tone remains clear, straightforward, and student-focused rather than overly promotional. Refine the continuous scrolling text strip to emphasize key academic and technical interests (such as Data Structures & Algorithms, Systems, and Frontend). Add intuitive tactile feedback to the project cards on hover and ensure all interactive elements cleanly adapt across varying viewport sizes."

---

## 5. Implementation Approach & Methodology

1. **Information Architecture & Planning:**
   Mapped out all required assignment components to guarantee full coverage of the evaluation rubric: Navigation, Intro, About with a remotely hosted profile asset, Projects, Contact, and the Footer documentation trigger.

2. **Semantic Skeleton Setup:**
   Constructed the single-page DOM structure utilizing native semantic tags (`<nav>`, `<main>`, `<section>`, `<footer>`) to maintain accessible markup and clean document flow.

3. **Styling & Layout Architecture:**
   - Established a responsive grid and flexbox layout using fluid CSS units (`clamp()`, `vh`, `%`) to support both mobile and desktop screens.
   - Implemented high-contrast typography, border styling, and custom hover states using native CSS pseudo-classes and transitions.

4. **Motion Engine & Interaction Layer:**
   - Integrated Lenis via CDN for smooth scroll handling and bound its frame update to GSAP’s ticker to eliminate layout jitter.
   - Configured ScrollTrigger to handle pinned horizontal card progression across the Projects section and subtle parallax shifts on the About image.
   - Wrote native JavaScript event listeners to handle the 3D card tilt dynamics, continuous ticker marquee, and clipboard copy utility in the contact section.

5. **Packaging & Verification:**
   Placed the documentation file directly in the root repository alongside `index.html` to ensure direct one-click downloading from the hosted site. Linked external image assets to a secure remote storage host to keep the repository footprint minimal.

---

## 6. Live Deployment Links
* **Live Website URL:** https://Saaho007-Collab.github.io/portfolio/
* **GitHub Repository URL:** https://github.com/Saaho007-Collab/portfolio/