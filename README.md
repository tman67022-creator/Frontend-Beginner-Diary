# Frontend Beginner Diary

A small collection of static HTML lesson pages created while learning core HTML and basic layout techniques. This repository is a beginner-friendly "diary" of short examples and explanations that demonstrate common HTML elements and simple page structure.

Live demo: https://tman67022-creator.github.io/Frontend-Beginner-Diary/

## Features / Topics covered
- Headings (h1–h6)
- Paragraphs, line breaks and horizontal rules
- Images, videos and media embedding
- Hyperlinks and external links
- Text formatting (bold, italic, underline, strikethrough)
- Preformatted text (`<pre>`)
- Superscript & subscript
- Semantic HTML (header, main, section, article, aside, footer, nav)
- Lists (ordered and unordered)
- Tables
- Forms and common input types

## Project structure
All site pages are static HTML stored in the docs/ folder so they can be hosted via GitHub Pages.

docs/
  - index.html        — Home/table of contents
  - headings.html
  - para.html
  - media.html
  - formating.html
  - pre.html
  - supersub.html
  - semantic.html
  - lists.html
  - CSS/index.css     — main stylesheet
  - Images/            — image assets used by pages
  - Video/             — video assets used by pages

## Technologies
- HTML5
- CSS (single stylesheet at docs/CSS/index.css)
- Google Fonts (Kdam Thmor Pro)
- Font Awesome icons

## Preview locally
Option A — open a page directly
1. Open docs/index.html in your browser.

Option B — run a simple local server (recommended)
```bash
git clone https://github.com/tman67022-creator/Frontend-Beginner-Diary.git
cd Frontend-Beginner-Diary/docs
python -m http.server 8000
# then open http://localhost:8000 in your browser
