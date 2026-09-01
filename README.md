# Personal Portfolio

🌐 **Live Demo:** [English](https://iamjinminghe.github.io/CV/) · [中文](https://iamjinminghe.github.io/CV/zh.html)

A minimal, bilingual (English / 中文), fully responsive personal portfolio for presenting academic background, professional experience, research, and data-oriented projects.

> **中文说明：** 这是一个极简、支持中英双语且完全响应式的个人主页，用于展示教育背景、实习经历、科研项目与数据类项目。

---

## ✨ Features

- **Bilingual pages** — English (`index.html`) and Chinese (`zh.html`) with one-click switching.
- **Light / dark themes** — typography uses soft gray scales instead of pure black or pure white.
- **Responsive layout** — optimized for desktop, tablet, and mobile.
- **Project filtering** — Strategy, ESG, Quant & Data, and Field Research.
- **Smooth interactions** — lightweight animations and accordion interactions implemented in Vanilla JavaScript.
- **Zero build dependencies** — static HTML, CSS, and JavaScript only.

## 🔎 Featured Open-Source Projects

### NEEQ Annual Report Toolkit

A reproducible research-data pipeline for NEEQ annual reports, covering candidate consolidation, rule-based cleaning, exception-based manual review, PDF downloading, validation, and TXT conversion.

**Repository:** [NEEQ-Annual-Report-Toolkit](https://github.com/iamjinminghe/NEEQ-Annual-Report-Toolkit)

### Consulting Interview Notes Agent Skill

An open-source Agent Skill that transforms raw interview transcripts into structured, MECE, conclusion-driven consulting meeting notes. It restructures content by business logic rather than chronological Q&A and enforces strict rules such as number preservation and zero fact fabrication.

**Repository:** [consulting-interview-notes](https://github.com/iamjinminghe/consulting-interview-notes)

Both project cards on this portfolio link directly to their GitHub repositories through **View on GitHub → / 查看 GitHub →**.

## 🛠️ Tech Stack

- **Markup:** HTML5
- **Styling:** CSS3, Custom Properties, Flexbox, Grid
- **Scripting:** Vanilla JavaScript (ES6+)
- **Deployment:** GitHub Pages

## 🎨 Theme Design

The site keeps its text palette in global CSS variables so typography stays consistent across both themes.

```css
:root {
  --text-main: #3f3f46;
  --text-muted: #667085;
  --text-on-accent: #f4f4f5;
}

html[data-theme="dark"] {
  --text-main: #e4e4e7;
  --text-muted: #a1a1aa;
  --text-on-accent: #f1f1f3;
}
```

This intentionally avoids pure `#000000` and `#ffffff` for typography.

## 🚀 Local Preview

No build step is required. Open `index.html` directly in a browser, or start a simple local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
http://localhost:8000/zh.html
```

## 🌐 GitHub Pages Deployment

Because the portfolio is a static site, it can be deployed directly from the repository root.

1. Push `index.html`, `zh.html`, `.nojekyll`, and the updated `README.md` to the `main` branch.
2. Open the repository **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Once GitHub Pages finishes deploying, the live pages are:

   - English: `https://iamjinminghe.github.io/CV/`
   - 中文: `https://iamjinminghe.github.io/CV/zh.html`

> If the links above do not open immediately after pushing the files, check **Settings → Pages** and wait a few minutes for the first deployment.

## 📁 Repository Structure

```text
CV/
├─ index.html
├─ zh.html
├─ README.md
└─ .nojekyll
```

## 🙋‍♂️ About

I am He Jinming, an undergraduate at Nanjing University with interests spanning finance, empirical research, quantitative analysis, data pipelines, and strategy.

This portfolio is designed as a concise CV homepage, while selected technical projects link to their full GitHub repositories.
