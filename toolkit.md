# Prompt-Powered Kickstart: Building a Beginner's Toolkit for TailwindCSS

**Moringa School AI Capstone Project**
**Student:** Hellen Muthoni Wanjiru
**Date:** March 2025
**Cohort:** Moringa School — Software Development

---

## 1. Title & Objective

### What technology did I choose?
**TailwindCSS** — a utility-first CSS framework for building modern, responsive web interfaces directly in HTML.

### Why did I choose it?
As a Fashion Designer and Creative Director, having a personal portfolio website is essential. I wanted to learn a modern frontend technology that would let me build something visually elegant without writing complex custom CSS from scratch. TailwindCSS felt like the perfect bridge — it gives you full creative control through simple utility classes, which mirrors how I think about design: building up a look piece by piece.

### What is the end goal?
Build and deploy a **personal portfolio landing page** that showcases my fashion design work, skills, experience, and contact information — live on the internet via GitHub Pages.

---

## 2. Quick Summary of TailwindCSS

### What is it?
TailwindCSS is a utility-first CSS framework. Instead of writing CSS in a separate stylesheet, you apply pre-built utility classes directly in your HTML — classes like `text-center`, `bg-black`, `p-4`, and `rounded-xl` that each do one specific thing.

### Where is it used?
TailwindCSS is used by thousands of companies worldwide — from startups to large tech firms — to build websites, dashboards, landing pages, and web applications. It is one of the most popular CSS frameworks as of 2025.

### One real-world example
The customer-facing pages of companies like **Vercel**, **Loom**, and **GitHub's newer UI components** are built using TailwindCSS.

---

## 3. System Requirements

| Requirement | Detail |
|---|---|
| **OS** | Windows, macOS, or Linux |
| **Editor** | VS Code (recommended) |
| **Browser** | Chrome, Firefox, or Edge |
| **Internet** | Required (for CDN version) |
| **Node.js** | Not required for CDN approach |
| **npm/pip** | Not required for CDN approach |

> **Note:** For this beginner project, we use the **Tailwind CDN** (a script tag in HTML). This means zero installations — just a browser and a text editor.

---

## 4. Installation & Setup Instructions

### Method Used: Tailwind via CDN (Beginner-Friendly)

No installs needed. Just add this one line inside the `<head>` of your HTML file:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

### Step-by-step setup:

**Step 1 — Open VS Code**
Launch VS Code on your computer.

**Step 2 — Create a project folder**
```
my-portfolio/
├── index.html
└── Msoo.jpg   ← (your photo, same folder)
```

**Step 3 — Create index.html**
In VS Code, create a new file called `index.html`.

**Step 4 — Add the HTML boilerplate**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-black">
  <h1 class="text-4xl font-bold text-center mt-10">Hello, World!</h1>
</body>
</html>
```

**Step 5 — Open in browser**
Right-click `index.html` → Open with → your browser. You should see "Hello, World!" styled with Tailwind.

That's it — Tailwind is working! ✅

---

## 5. Minimal Working Example

### What it does:
A simple styled "Hello World" card that demonstrates core Tailwind utility classes — background color, padding, rounded corners, shadow, and text styling.

### Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Tailwind Hello World</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="min-h-screen bg-gray-100 flex items-center justify-center">

  <!-- Card component -->
  <div class="bg-white rounded-2xl shadow-lg p-10 max-w-sm text-center">
    <h1 class="text-3xl font-bold text-gray-800 mb-2">Hello, Tailwind!</h1>
    <p class="text-gray-500 text-sm mb-6">Your first styled component 🎉</p>
    <a href="#"
       class="bg-black text-white text-xs uppercase tracking-widest px-6 py-3 rounded-full hover:bg-gray-800 transition">
      Get Started
    </a>
  </div>

</body>
</html>
```

### Expected output:
A centered white card on a light gray background, with a bold heading, subtitle text, and a black pill-shaped button that darkens on hover.

### Key Tailwind classes used:

| Class | What it does |
|---|---|
| `min-h-screen` | Makes body fill the full screen height |
| `flex items-center justify-center` | Centers content horizontally & vertically |
| `bg-white` | Sets background to white |
| `rounded-2xl` | Applies large rounded corners |
| `shadow-lg` | Adds a large drop shadow |
| `p-10` | Adds padding on all sides |
| `text-3xl font-bold` | Large bold text |
| `hover:bg-gray-800` | Darker background on hover |
| `transition` | Smooth animation on state change |

---

## 6. AI Prompt Journal

This section documents the AI prompts used throughout the project, how the AI responded, and my reflections on its usefulness.

---

### Prompt 1
**Prompt used:**
> "I am a total beginner in web development. I want to learn TailwindCSS to build a personal portfolio landing page. Can you explain what TailwindCSS is and how to get started without installing anything?"

**AI's response summary:**
The AI explained that TailwindCSS is a utility-first CSS framework and recommended using the CDN approach for beginners — simply adding a `<script>` tag to HTML, with no npm or Node.js required. It gave a clear first example with `bg-white`, `p-4`, and `text-center`.

**Evaluation:**
Very helpful. It removed the intimidation of "installing" something and gave me a path to see results immediately. The CDN suggestion was the right call for a beginner.

---

### Prompt 2
**Prompt used:**
> "I am a fashion designer. Build me a full personal portfolio landing page using TailwindCSS via CDN. It should have a hero section with my name and photo, a skills section, a collections/portfolio section, an experience section, and a contact section. Make it look editorial and high-fashion — dark charcoal and cream palette with gold accents."

**AI's response summary:**
The AI generated a complete, multi-section HTML file with Cormorant Garamond and Montserrat fonts, a split hero layout, scrolling marquee, skills grid, portfolio cards, experience timeline, tools section, contact form, and footer — all styled to match a high-fashion editorial aesthetic.

**Evaluation:**
Extremely helpful. The output was production-quality and far beyond what I could have built from scratch in a short time. The AI understood the aesthetic brief (editorial, fashion, gold accents) and translated it into code. This demonstrated how AI can accelerate the design-to-code workflow significantly.

---

### Prompt 3
**Prompt used:**
> "Update the portfolio with my real information: my name is Hellen Muthoni Wanjiru, I studied at Maseno University, I worked at Nemari Living Interiors as Branch Manager and Creative Lead. My email is muthonihellen441@gmail.com, phone is +254 705 762 929, Instagram is @hellenmuthoni. Use my uploaded CV and portfolio PDF to fill in all sections accurately."

**AI's response summary:**
The AI read through the CV and portfolio PDF, extracted all relevant details — education, experience, skills, software tools, portfolio themes — and rebuilt the entire page with real content replacing all placeholder text. It also integrated the uploaded photo (`Msoo.jpg`) into both the hero and about sections.

**Evaluation:**
This was the most impactful prompt. It showed how AI can process documents and synthesize them into a functional web output. The result was a page that genuinely represents me — not a generic template.

---

### Prompt 4
**Prompt used:**
> "Explain what each Tailwind class in my hero section does, so I can understand and learn from my own code."

**AI's response summary:**
The AI broke down each utility class line by line — explaining `min-h-screen`, `grid`, `grid-template-columns`, `backdrop-filter`, `object-fit`, `letter-spacing`, and animation classes — in plain English.

**Evaluation:**
Very educational. Reading AI explanations of code I had already seen in action made the concepts stick much faster than reading documentation alone.

---

## 7. Common Issues & Fixes

### Issue 1 — Photo not showing
**Problem:** The `<img>` tag showed a broken image icon.
**Cause:** The image file (`Msoo.jpg`) was not in the same folder as `index.html`.
**Fix:** Move both files into the same folder. The `src` attribute must match the filename exactly, including capitalisation.
```html
<!-- Correct -->
<img src="Msoo.jpg" alt="Hellen Muthoni" />
```

---

### Issue 2 — Tailwind classes not working
**Problem:** Classes like `bg-black` or `text-center` had no effect.
**Cause:** The Tailwind CDN `<script>` tag was missing or placed after the `<body>` tag.
**Fix:** Place the script in the `<head>` section:
```html
<head>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
```

---

### Issue 3 — Google Fonts not loading
**Problem:** Custom fonts (Cormorant Garamond, Montserrat) were not rendering.
**Cause:** No internet connection, or the `<link>` tag was placed after the `<script>` tag.
**Fix:** Place the Google Fonts `<link>` before the Tailwind script, and ensure you have internet access when opening the file.

---

### Issue 4 — Page layout broken on mobile
**Problem:** The two-column hero looked squished on a phone screen.
**Cause:** Fixed grid layout without responsive breakpoints.
**Fix:** Add a media query or use Tailwind's responsive prefixes like `md:grid-cols-2`:
```html
<div class="grid grid-cols-1 md:grid-cols-2">
```

---

### Issue 5 — GitHub Pages showing blank page
**Problem:** Site deployed but showed a blank white page.
**Cause:** The file was not named `index.html` (e.g. it was named `portfolio.html`).
**Fix:** Rename the main file to `index.html` — GitHub Pages looks for this file by default.

---

## 8. References

### Official Documentation
- [TailwindCSS Official Docs](https://tailwindcss.com/docs) — Complete reference for all utility classes
- [TailwindCSS CDN Setup](https://tailwindcss.com/docs/installation/play-cdn) — How to use Tailwind without npm

### Fonts
- [Google Fonts — Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond)
- [Google Fonts — Montserrat](https://fonts.google.com/specimen/Montserrat)

### Hosting
- [GitHub Pages Docs](https://docs.github.com/en/pages) — How to deploy a static site for free

### Learning Resources
- [Tailwind CSS Crash Course — Traversy Media (YouTube)](https://www.youtube.com/watch?v=dFgzHOX84xQ)
- [TailwindCSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
- [W3Schools HTML Basics](https://www.w3schools.com/html/) — HTML fundamentals reference

### AI Tool Used
- [Claude by Anthropic](https://claude.ai) — Used for learning, code generation, debugging, and documentation throughout this project.

---

## Reflection

This capstone project taught me that **AI is not a replacement for learning — it is an accelerator.** By prompting Claude with specific, context-rich requests, I was able to go from zero web development experience to a fully deployed, professional-looking portfolio website in under a week.

The most valuable lesson was learning to **read and understand the code the AI produced**, not just copy-paste it. Breaking down each Tailwind class, experimenting with colours and layouts, and debugging errors myself gave me genuine technical confidence.

As a fashion designer, I now see web design as another medium for creative expression — and TailwindCSS as a tool I will continue to use.

---

*Submitted for Moringa School AI Capstone · 2025*
*Hellen Muthoni Wanjiru · muthonihellen441@gmail.com*
