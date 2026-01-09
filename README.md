<div align="center">

  <img src="hero-image.webp" alt="Dragon Quest VII Guide Banner" width="100%" />

  <br />

  <h1>🐉 Dragon Quest VII Reimagined: The Adventure Log</h1>

  <p>
    <strong>The interactive, ad-free companion tool for the DQ7 Demo on Switch 2 & Steam.</strong>
  </p>

  <p>
    <a href="https://dq7reimagined.com"><strong>🚀 View Live Demo</strong></a>
    ·
    <a href="https://dq7reimagined.com/walkthrough/">Features</a>
    ·
    <a href="https://dq7reimagined.com/shards/">Tech Stack</a>
    ·
    <a href="https://dq7reimagined.com/characters/">Contributing</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Built%20With-Astro-orange?style=for-the-badge&logo=astro" alt="Astro" />
    <img src="https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind" />
    <img src="https://img.shields.io/badge/Performance-100%2F100-success?style=for-the-badge" alt="Lighthouse Score" />
    <img src="https://img.shields.io/github/license/knitout/dq7-guide?style=for-the-badge" alt="License" />
  </p>

</div>

<br />

## 🤔 Why this exists?

**Modern game wikis are broken.** 🐢

They are riddled with auto-playing video ads, massive layout shifts, and bloated JavaScript that drains your battery while you play.

As a massive JRPG fan, I wanted a tool that felt like a natural extension of the game menu—**fast, clean, and useful.**

So I built **The Adventure Log**. It's a "Zero-JS" (by default) static site that loads instantly and respects your time.

---

## ✨ Features

Here is why this is better than a text file on GameFAQs:

### 🧩 Interactive Shard Locator
Stop guessing which fragment you missed. Filter shards by **Region**, **Color**, and **Story Progress**.
*(Recommended: Add a screenshot of your Shard Filter UI here)*

### ✅ Local Progress Tracking
No login required. We use `localStorage` to save your checklist progress directly in your browser.
- [x] Track Found Shards
- [x] Mark Missable Items
- [x] Recruit Party Members

### ⚡ 100/100 Performance
Built with **Astro Island Architecture**. The site ships **0kb of JavaScript** for static content, only hydrating the interactive checklists when needed.

---

## 🛠 Tech Stack

This project is an experiment in building high-performance content sites.

- **Framework:** [Astro 5.0](https://astro.build/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Interactivity:** React (hydrated via `client:visible`)
- **State Management:** Nano Stores (for cross-component state)
- **Deployment:** Vercel / Netlify

---

## 🚀 Getting Started

Want to run this locally?

```bash
# Clone the repository
git clone [https://github.com/yourusername/dq7-guide.git](https://github.com/yourusername/dq7-guide.git)

# Install dependencies
npm install

# Start the dev server
npm run dev
