# Prompt-Powered Kickstart: Building a Beginner's Toolkit for TailwindCSS

**Moringa School AI Capstone Project**
**Student:** Hellen Muthoni Wanjiru
**Email:** muthonihellen441@gmail.com
**Date:** March 2025
**Cohort:** Moringa School — Software Development

---

## 1. Title & Objective

### What technology did I choose?
**TailwindCSS** — a utility-first CSS framework for building modern, responsive web interfaces directly in HTML.

### Why did I choose it?
As a Fashion Designer and Creative Director, having a personal portfolio website is essential. I wanted to learn a modern frontend technology that would let me build something visually elegant without writing complex custom CSS from scratch. TailwindCSS felt like the perfect bridge — it gives full creative control through simple utility classes, which mirrors how I think about design: building up a look piece by piece.

### What is the end goal?
Build and deploy a **personal portfolio landing page** that showcases my fashion design work, skills, experience, and contact information — live on the internet via GitHub Pages.

---

## 2. Quick Summary of TailwindCSS

### What is it?
TailwindCSS is a utility-first CSS framework. Instead of writing CSS in a separate stylesheet, pre-built utility classes are applied directly in HTML — classes like `text-center`, `bg-black`, `p-4`, and `rounded-xl` that each do one specific thing.

### Where is it used?
TailwindCSS is used by thousands of companies worldwide — from startups to large tech firms — to build websites, dashboards, landing pages, and web applications. It is one of the most popular CSS frameworks as of 2025.

### One real-world example
Companies such as **Vercel**, **Loom**, and **GitHub** use TailwindCSS in their customer-facing pages and UI components.

---

## 3. System Requirements

| Requirement | Detail |
|---|---|
| **OS** | Windows, macOS, or Linux |
| **Editor** | VS Code (recommended) |
| **Browser** | Chrome, Firefox, or Edge |
| **Internet** | Required (for CDN version) |
| **Node.js** | Not required for CDN approach |
| **npm / pip** | Not required for CDN approach |

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

**Step 3 — Create `index.html`**
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
Right-click `index.html` → Open with → your browser.
You should see **"Hello, World!"** styled with Tailwind. ✅ Tailwind is working!

---

## 5. Minimal Working Example

### What it does:
A simple styled card that demonstrates core Tailwind utility classes — background color, padding, rounded corners, shadow, and text styling.

### Code (with inline comments):

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Tailwind Hello World</title>
  <!-- Step 1: Load Tailwind via CDN — no installation needed -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<!-- bg-gray-100: light gray page background -->
<!-- min-h-screen: fills the full viewport height -->
<!-- flex items-center justify-center: centers content on the page -->
<body class="min-h-screen bg-gray-100 flex items-center justify-center">

  <!-- bg-white: white card background -->
  <!-- rounded-2xl: large rounded corners -->
  <!-- shadow-lg: drop shadow for depth -->
  <!-- p-10: padding on all sides -->
  <!-- max-w-sm: limits card width -->
  <!-- text-center: centers all text inside -->
  <div class="bg-white rounded-2xl shadow-lg p-10 max-w-sm text-center">

    <!-- text-3xl font-bold: large bold heading -->
    <!-- text-gray-800: dark gray text color -->
    <!-- mb-2: small margin below heading -->
    <h1 class="text-3xl font-bold text-gray-800 mb-2">Hello, Tailwind!</h1>

    <!-- text-gray-500: lighter muted text -->
    <!-- text-sm: smaller font size -->
    <!-- mb-6: margin below paragraph -->
    <p class="text-gray-500 text-sm mb-6">Your first styled component 🎉</p>

    <!-- bg-black: black button background -->
    <!-- text-white: white button text -->
    <!-- uppercase tracking-widest: spaced-out uppercase letters -->
    <!-- px-6 py-3: horizontal and vertical padding -->
    <!-- rounded-full: pill shape -->
    <!-- hover:bg-gray-800: darker on hover -->
    <!-- transition: smooth animation -->
    <a href="#"
       class="bg-black text-white text-xs uppercase tracking-widest
              px-6 py-3 rounded-full hover:bg-gray-800 transition">
      Get Started
    </a>
  </div>

</body>
</html>
```

### Expected output:
A centered white card on a light gray background, with a bold heading, subtitle text, and a black pill-shaped button that darkens smoothly on hover.

---

## 6. AI Prompt Journal

> This section documents the full structured prompts used during this project, the AI's responses, and personal reflections on their usefulness.

---

### Prompt 1 — Understanding the Technology

**Prompt used:**

```
I am a complete beginner in web development and I want to learn TailwindCSS
to build a personal portfolio website.

Please help me by:
1. Explaining what TailwindCSS is in simple terms
2. Telling me where and why it is used in real projects
3. Comparing it briefly to regular CSS so I understand the difference
4. Recommending the easiest way to get started without any installations

Context:
- My background: Fashion Design — I have no prior coding experience
- My goal: Build a portfolio landing page to showcase my work
- Tool I am using: VS Code on Windows
- Framework/Language: HTML + TailwindCSS (beginner level)
```

**AI's response summary:**
The AI explained TailwindCSS as a "design toolkit built into your HTML" — instead of writing a separate CSS file, you apply small, single-purpose classes like `text-center` or `bg-black` directly in your tags. It compared it to regular CSS (where you name classes yourself and write rules) vs Tailwind (where the classes already exist and you just pick them). It recommended the **CDN approach** — adding a single `<script>` tag — as the perfect starting point with zero setup.

**Evaluation of helpfulness:**
Extremely helpful. The fashion analogy the AI used — "utility classes are like a wardrobe of ready-made pieces you mix and match" — made the concept click immediately. It removed the fear of installations and gave a clear, actionable first step.

---

### Prompt 2 — Building the Portfolio Page

**Prompt used:**

```
I want to build a complete personal portfolio landing page using TailwindCSS via CDN.

Please help me by:
1. Creating a full HTML file with multiple sections: hero, about, skills, portfolio/collections, experience, and contact
2. Making the design look editorial and high-fashion — not generic
3. Using a dark charcoal (#1a1a1a) and cream (#f5f0e8) color palette with gold (#b8975a) accents
4. Adding smooth fade-in animations on the hero section
5. Including a scrolling marquee banner with fashion-related keywords
6. Making it fully responsive for mobile screens

Design brief:
- Aesthetic: Editorial, luxury fashion — think Vogue magazine layout
- Fonts: Cormorant Garamond (serif, elegant) + Montserrat (clean, modern)
- Mood: Dark, sophisticated, runway-ready
- Target user: A fashion designer showcasing their work to clients and employers

Language/Framework: HTML + TailwindCSS CDN + Google Fonts
```

**AI's response summary:**
The AI generated a complete multi-section portfolio page with a split hero layout (dark left panel, photo right panel), a gold vertical divider, fade-up animations using `@keyframes`, a scrolling marquee with fashion keywords, a skills grid with hover effects, portfolio collection cards, an experience and education section, a tools section, and a contact form — all in a single `index.html` file using the Tailwind CDN.

**Evaluation of helpfulness:**
The output far exceeded expectations. The AI understood the aesthetic brief deeply — the Cormorant Garamond + Montserrat pairing felt genuinely editorial, and the charcoal/cream/gold palette matched the high-fashion vision perfectly. This prompt demonstrated how giving detailed design context produces dramatically better results than a vague request.

---

### Prompt 3 — Personalising with Real Content

**Prompt used:**

```
I want to update the portfolio page with my real personal information from my CV and portfolio PDF.

Please help me by:
1. Replacing all placeholder names with my real name: Hellen Muthoni Wanjiru
2. Updating the hero tagline to reflect my actual background: Textile, Apparel Design and Fashion Merchandising
3. Filling in the experience section with my real job: Branch Manager & Creative Lead at Nemari Living Interiors, Kilimani, Nairobi (2025)
4. Adding my real education: BA Textile, Apparel Design and Fashion Merchandising + Interior Design with IT, Maseno University, Second Class Upper Division, 2021–2025
5. Replacing the skills with my actual competencies from my CV
6. Updating all contact details: email muthonihellen441@gmail.com, phone +254 705 762 929, Instagram @hellenmuthoni, location Nairobi, Kenya
7. Using my uploaded photo (Msoo.jpg) in both the hero and about sections

Uploaded files: CV (PDF) + Portfolio (PDF) + Msoo.jpg
Language/Framework: HTML + TailwindCSS CDN
```

**AI's response summary:**
The AI read both PDFs and extracted all relevant information — experience bullet points from the CV, portfolio themes and collection names from the portfolio document, and all contact details. It rebuilt the entire page with real content, replaced all placeholder text, and set the `<img src="Msoo.jpg">` tag in both the hero section and the about section with proper `object-fit: cover` and `object-position: center top` styling so the photo displayed correctly.

**Evaluation of helpfulness:**
This was the most impactful prompt of the entire project. It demonstrated that AI can act as a content extraction and transformation tool — reading documents and producing a fully personalised output. The portfolio went from a beautiful template to a genuine representation of my identity as a designer.

---

### Prompt 4 — Debugging a Layout Issue

**Prompt used:**

```
My portfolio page has a layout problem on mobile screens.

Please help me by:
1. Identifying which sections are breaking on small screens
2. Explaining what is causing the issue
3. Suggesting the correct Tailwind responsive classes to fix it
4. Showing me the before and after code for each fix

Current issue: The hero section uses a two-column grid that squishes on mobile.
The about section grid also overflows on small screens.

Language/Framework: HTML + TailwindCSS CDN
Screen size affected: Mobile (< 768px width)
```

**AI's response summary:**
The AI identified that the hero used a fixed `grid-template-columns: 1fr 1fr` CSS property that did not respond to screen size. It explained Tailwind's responsive prefix system (e.g. `md:` applies only at screens 768px and above), then showed how to change the grids to `grid-cols-1 md:grid-cols-2` so they stack on mobile and split on desktop. It also added `@media (max-width: 768px)` overrides in the `<style>` block for custom CSS sections.

**Evaluation of helpfulness:**
Very helpful and educational. The AI's explanation of how Tailwind's responsive prefixes work (`sm:`, `md:`, `lg:`) gave me a reusable mental model I can apply to any future layout. Seeing the before/after code side by side made the fix easy to understand and apply.

---

### Prompt 5 — Learning from the Code

**Prompt used:**

```
I want to make my TailwindCSS code more readable and help me understand what I built.

Please help me by:
1. Explaining what each Tailwind class in my hero section does, one by one
2. Identifying any classes that are doing the same thing so I can simplify
3. Suggesting more descriptive ways to group related classes using comments
4. Pointing out any inconsistent spacing or sizing patterns across sections

[Pasted hero section HTML code]

Language/Framework: HTML + TailwindCSS CDN
My learning goal: Understand every class I am using so I can build the next section myself
```

**AI's response summary:**
The AI went line by line through the hero section, explaining each utility class in plain English — e.g. `backdrop-filter blur(8px)` creates a frosted glass effect, `letter-spacing: 0.38em` creates the spaced-out uppercase label look, `object-position: center top` ensures the photo shows the face rather than being cropped at the middle. It also noted that `min-h-screen` and `height: 100vh` were being used inconsistently across sections and recommended standardising to `min-h-screen`.

**Evaluation of helpfulness:**
Invaluable for learning. This prompt turned the AI-generated code into a personal lesson. Reading explanations of code I had already seen in action made the concepts stick far faster than reading documentation alone. After this session, I felt confident enough to manually edit classes myself without asking the AI first.

---

## 7. Common Issues & Fixes

### Issue 1 — Photo not showing
**Problem:** The `<img>` tag showed a broken image icon.
**Cause:** `Msoo.jpg` was not in the same folder as `index.html`.
**Fix:** Keep both files in the same folder. The `src` attribute must match the filename exactly, including capitalisation.
```html
<!-- Correct -->
<img src="Msoo.jpg" alt="Hellen Muthoni" />
```

---

### Issue 2 — Tailwind classes not working
**Problem:** Classes like `bg-black` or `text-center` had no effect.
**Cause:** The Tailwind CDN `<script>` tag was missing or placed after the `<body>` content.
**Fix:** Place the script inside `<head>`:
```html
<head>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
```

---

### Issue 3 — Google Fonts not loading
**Problem:** Cormorant Garamond and Montserrat were not rendering.
**Cause:** No internet connection, or the `<link>` tag was placed incorrectly.
**Fix:** Place the Google Fonts `<link>` before the Tailwind script inside `<head>`, and ensure internet access.

---

### Issue 4 — Page layout broken on mobile
**Problem:** Two-column hero looked squished on a phone screen.
**Cause:** Fixed grid layout without responsive breakpoints.
**Fix:** Use Tailwind responsive prefixes:
```html
<div class="grid grid-cols-1 md:grid-cols-2">
```

---

### Issue 5 — GitHub Pages showing blank page
**Problem:** Site deployed but showed a blank white page.
**Cause:** Main file was not named `index.html`.
**Fix:** Rename the main file to exactly `index.html` — GitHub Pages requires this.

---

## 8. References

### Official Documentation
- [TailwindCSS Official Docs](https://tailwindcss.com/docs)
- [TailwindCSS CDN Setup](https://tailwindcss.com/docs/installation/play-cdn)
- [GitHub Pages Docs](https://docs.github.com/en/pages)

### Fonts
- [Google Fonts — Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond)
- [Google Fonts — Montserrat](https://fonts.google.com/specimen/Montserrat)

### Learning Resources
- [TailwindCSS Crash Course — Traversy Media (YouTube)](https://www.youtube.com/watch?v=dFgzHOX84xQ)
- [TailwindCSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
- [W3Schools HTML Basics](https://www.w3schools.com/html/)
- [Responsive Design with Tailwind — StackOverflow](https://stackoverflow.com/questions/tagged/tailwind-css)

### AI Tool Used
- [Claude by Anthropic](https://claude.ai) — Used for learning, code generation, debugging, and documentation throughout this project.

---

## Reflection

This capstone project taught me that **AI is not a replacement for learning — it is an accelerator.** The quality of the AI's output was directly proportional to the quality of the prompt. Vague prompts gave generic results. Detailed, structured prompts with context, numbered instructions, and specific goals gave production-quality outputs.

The five prompts in this journal represent a real learning journey — from understanding the basics, to building, personalising, debugging, and finally comprehending the code at a deep level. Each prompt built on the last.

As a fashion designer, I now see web design as another medium for creative expression — and structured AI prompting as a professional skill as valuable as any design tool.

---

*Submitted for Moringa School AI Capstone · 2025*
*Hellen Muthoni Wanjiru · muthonihellen441@gmail.com · +254 705 762 929*
