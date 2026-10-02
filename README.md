# Lakshya Shah — Modern Creative-Agency Portfolio

A sleek, editorial-style personal portfolio website designed in the aesthetic of a high-end creative agency for **Lakshya Shah** (Web Developer &amp; UI Designer). Built purely with semantic **HTML5**, **Vanilla CSS**, and lightweight JavaScript for the mobile drawer menu and scroll events.

Zero frameworks. Zero build steps. 100% responsive, accessible, and ready to deploy in under two minutes on **GitHub Pages**, **Netlify**, or **Vercel**.

---

## 🌟 Live Preview

- **Live URL**: `https://lakshya-shah.github.io/Lakshya.Shah.github.io/`

---

## 🚀 Included Interactive Projects (Fully Built)

All 4 featured case studies in the portfolio are fully implemented standalone projects located in the [`projects/`](file:///c:/Users/D-1/Downloads/portfolio/projects) directory. Clicking on any project card in the portfolio takes you directly to its live interactive showcase:

1. **[Aura Studio Platform](file:///c:/Users/D-1/Downloads/portfolio/projects/aura-studio.html)** (`projects/aura-studio.html`)
   - High-end dark creative agency website with glowing gradients, spatial computing feature banner, global metrics strip, and selected case studies.
2. **[Chronos Design System](file:///c:/Users/D-1/Downloads/portfolio/projects/chronos-design-system.html)** (`projects/chronos-design-system.html`)
   - Interactive UI toolkit with live button variant/size switchers, click-to-copy color token cards with toast feedback, and design system documentation.
3. **[Pinky Sales — Shop Management Suite](https://pinkysales.in)** (Live at `https://pinkysales.in` &amp; case study in `projects/pinky-sales.html`)
   - Full-stack published retail operating system and inventory control suite featuring real-time Supabase sync, PDF invoice generation, and customer balance ledgers.
4. **[Nomad Atlas Magazine](file:///c:/Users/D-1/Downloads/portfolio/projects/nomad-atlas.html)** (`projects/nomad-atlas.html`)
   - Editorial architectural publication with classic serif typography, drop-cap lead articles, reading badges, and an aesthetic 3-column photo grid.

---

## 📐 Design & Features

- **Agency Editorial Aesthetics**: Off-white canvas (`#f5f3ee`), near-black typography (`#111111`), and an electric lime accent (`#d4ff3f`).
- **Oversized Typography**: Styled using **Syne** (bold headlines), **Space Grotesk** (numbers & badges), and **Inter** (body copy).
- **Curated Agency Layout**:
  1. **Sticky Glassmorphic Navbar**: Lakshya Shah brand name with a live pulse status indicator, center navigation, and a pill-shaped "Let's Talk" button. Collapses into a mobile drawer.
  2. **Hero Section**: Huge two-line headline (*"I design clarity. I build growth."*), avatar social proof banner, and an editorial image collage with floating stat chips (`+2 Years`, `+10 Projects`) plus an SVG **rotating circular text badge**.
  3. **Marquee Ticker Strip**: Continuous CSS-animated ticker strip showcasing core disciplines.
  4. **Editorial About Statement**: Bold philosophical hook (*"Design is not decoration. It is direction."*), concise bio, performance metric cards, and a skills deck.
  5. **Featured Work**: Grid of case studies with rounded images, hover zoom effects, and slide-in arrow badges linking to the 4 created projects.
  6. **What I Bring to the Table (Services / Skills)**: 4 alternating numbered rows (01–04) with taglines, 5-bullet capability lists, and high-impact imagery.
  7. **Testimonials**: 3 client review cards with 5-star ratings, quotes, and client avatars.
  8. **High-Impact CTA**: Dark editorial call-to-action banner (*"Create something that knows where it's going."*) with direct contact info.
  9. **Footer**: Quick navigation links, social network links (GitHub, LinkedIn, Instagram, X/Twitter, Dribbble), dynamic copyright year, and a "Back to top" button.
- **Custom CSS Touches**:
  - Film grain/noise texture overlay
  - SVG circular text badge rotating on an infinite loop
  - CSS variables for instantaneous theming
  - Card hover zooms and smooth link interactions
  - Back-to-top button and scroll-linked navigation highlights

---

## 🛠️ Tech Stack

- **HTML5**: Semantic, accessible structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **Vanilla CSS3**: Custom properties (CSS variables), CSS Grid, Flexbox, keyframe animations, `@media` queries.
- **Vanilla JavaScript**: Minimal helper (~40 lines) for the mobile hamburger toggle, dynamic year, and sticky header backdrop blur.
- **Google Fonts**: [Syne](https://fonts.google.com/specimen/Syne), [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter).
- **Asset Photography**: High-resolution curated editorial photography via [Unsplash](https://unsplash.com).

---

## 📁 File Structure

```text
portfolio/
├── index.html                       # Main portfolio homepage for Lakshya Shah
├── style.css                        # Design tokens, typography, grid layouts, animations
├── README.md                        # Documentation & GitHub Pages deployment guide
└── projects/
    ├── aura-studio.html             # Project 1: Creative agency platform
    ├── chronos-design-system.html   # Project 2: Interactive UI toolkit & tokens
    ├── pinky-sales.html             # Project 3: Pinky Sales shop management suite case study
    └── nomad-atlas.html             # Project 4: Editorial architectural magazine
```

---

## 💻 How to Run Locally

Because this project uses plain HTML, CSS, and JS with no build dependencies, you can run it immediately without `npm install` or compilers:

### Option 1: Direct File Open
Simply double-click `index.html` in your file explorer, or drag and drop it into any web browser (Chrome, Safari, Edge, Firefox).

### Option 2: VS Code Live Server (Recommended)
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey) if you haven't already.
3. Right-click `index.html` and select **"Open with Live Server"**.
4. The site will launch automatically at `http://127.0.0.1:5500/`.

### Option 3: Terminal / Command Line
If you have Python installed:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🚀 How to Deploy on GitHub Pages (Step-by-Step)

Follow these steps to publish your portfolio for free on **GitHub Pages**:

### Step 1: Create a GitHub Repository
1. Log in to [GitHub](https://github.com).
2. In the top-right corner, click the **`+`** icon and select **New repository**.
3. Name your repository (e.g. `portfolio` or `<your-username>.github.io`).
4. Set the visibility to **Public**.
5. Leave "Initialize this repository with a README" **unchecked** (we already have this README).
6. Click **Create repository**.

### Step 2: Push Your Code to GitHub
Open your terminal inside this portfolio directory and run:

```bash
# 1. Initialize git
git init

# 2. Stage all files
git add .

# 3. Commit the files
git commit -m "feat: launch Lakshya Shah creative portfolio with 4 projects"

# 4. Rename main branch
git branch -M main

# 5. Link to your GitHub repository
git remote add origin https://github.com/Lakshya-Shah/Lakshya.Shah.github.io.git

# 6. Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages in Repository Settings
1. Go to your repository page on GitHub (`https://github.com/Lakshya-Shah/Lakshya.Shah.github.io`).
2. Click the **Settings** tab (the gear icon on the top navigation bar).
3. In the left sidebar under the "Code and automation" section, click **Pages**.
4. Under **Build and deployment**:
   - **Source**: Select **Deploy from a branch**.
   - **Branch**: Choose `main` and leave the folder set to `/(root)`.
5. Click **Save**.

### Step 4: Access Your Live Site
1. Wait 60 to 90 seconds while GitHub Actions builds and publishes your site.
2. Refresh the **Pages** settings page. A banner will appear at the top:
   > *"Your site is live at https://lakshya-shah.github.io/Lakshya.Shah.github.io/"*
3. Click the link to view your live portfolio with all 4 interactive projects!

---

## ⚡ Alternative Free Hosting

- **Netlify**: Drag and drop the `portfolio` folder directly into [Netlify Drop](https://app.netlify.com/drop). Deploys in 5 seconds.
- **Vercel**: Import the GitHub repository into [Vercel](https://vercel.com) with standard static site defaults.

---

## 📄 License

Open-source and free to use for personal or commercial portfolios under the **MIT License**.
