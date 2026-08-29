Frontend-Beginner-Diary
A small multi-page HTML project created while learning the fundamentals of HTML. This repository demonstrates common HTML elements and simple layouts across a set of lesson pages, with a lightweight CSS file for styling.

Live demo: https://tman67022-creator.github.io/Frontend-Beginner-Diary/

What this project covers
This project is a beginner-friendly diary of HTML topics, including examples and short explanations:

Headings (h1–h6)
Paragraphs, line breaks and horizontal rules
Images, videos and media embedding
Hyperlinks
Text formatting (bold, italic, underline, strikethrough, etc.)
Preformatted text (<pre>)
Superscript & subscript
Semantic HTML (header, main, section, article, aside, footer, nav)
Lists (ordered and unordered)
Tables
Forms and input types
Project structure
docs/
index.html — Home/table of contents
headings.html
para.html
media.html
formating.html
pre.html
supersub.html
semantic.html
lists.html
CSS/index.css — project stylesheet
Images/, Video/ — media assets used by pages
Note: the site is authored as static HTML pages inside the docs/ folder.

Technologies
HTML5
CSS (single stylesheet at docs/CSS/index.css)
Google Fonts (Kdam Thmor Pro)
Font Awesome icons
Preview locally
Option A — open in your browser

Open docs/index.html directly in a browser.
Option B — run a simple local web server (recommended)

Clone the repo: git clone https://github.com/tman67022-creator/Frontend-Beginner-Diary.git
Serve the docs directory: cd Frontend-Beginner-Diary/docs python -m http.server 8000
Open http://localhost:8000
Deploy (GitHub Pages)
This project is already deployed using GitHub Pages from the repository's docs/ folder. To configure or redeploy:

Settings → Pages → Source: choose the branch (main) and folder /docs.
Notes & suggestions for improvement
Accessibility: review alt text for all images and ensure form controls have associated labels (they mostly do).
Use semantic form action/validation if you plan to collect data (current form uses a mailto-style action).
CSS: consider splitting layout and theme styles or adopting a reset/normalize and more responsive patterns.
Add meta tags (description, theme-color) and improve page titles for SEO.
Replace large inline SVG/ASCII art inside <pre> with smaller or lazy-loaded content if it affects page load.
Contributing
This project is intended for learning. Feel free to:

Open issues for bugs or suggestions
Create pull requests if you want to add examples, fix typos, or improve styling
Suggest enhancements to the structure or accessibility
Author
Created by Tman67022 (Tusya Kumar) as part of a frontend learning journey.

Contact: tman67022@gmail.com
