# Web Technologies — Assignment Portfolio

Eight responsive webpages built with **plain HTML5 and hand-written CSS3** — no CSS framework,
no utility-class library, no build step. All styling lives in a single commented `<style>` block
inside each page.

**Live site:** https://areeshakhan25.github.io/web-assignments/

---

## Contents

### Assignment 1 — Components, layout and page composition

| # | Page | Description |
|---|------|-------------|
| 1 | [Practical Questions Showcase](assignment-1/question-1/) | Eight UI components — profile card, product cards, notice box, login form, website header, about section, faculty cards and footer |
| 2 | [University Admission Webpage](assignment-1/question-2/) | COMSATS admissions page with programme cards, requirements, important dates and a highlighted application box |
| 3 | [Product Advertisement Page](assignment-1/question-3/) | Laptop and smartphone product cards with image, features, a distinct price panel and an outlined "Buy Now" button |
| 4 | [Faculty Portal Login](assignment-1/question-4/) | Split-screen CUOnline sign-in with validated fields, a CSS-drawn captcha and a password toggle |
| 5 | [Restaurant Menu Website](assignment-1/question-5/) | Tasty Bites — header, hero banner, four themed menu categories and a contact footer |

### Assignment 2 — Forms, sidebars, typography and navigation

| # | Page | Description |
|---|------|-------------|
| 1 | [Campus Management System](assignment-2/question-1/) | CUI Wah login portal over a full-bleed campus photograph with frosted panels |
| 2 | [Sidebar, Fonts & Horizontal Nav](assignment-2/question-2/) | All three parts on one page: a styled sidebar, two paired Google Fonts, and a horizontal navigation list |
| 3 | [Contact Form Page](assignment-2/question-3/) | Two-column enquiry page on a CSS-generated teal pattern with a custom select control |

---

## Reports

Full write-ups with objectives, implementation tables, annotated code snippets and screenshots:

- [`docs/Assignment-1-Report.docx`](docs/Assignment-1-Report.docx)
- [`docs/Assignment-2-Report.docx`](docs/Assignment-2-Report.docx)

---

## Structure

```
.
├── index.html                    Landing page with routing to every question
├── assignment-1/
│   ├── question-1/               index.html + screenshot.png
│   ├── question-2/
│   ├── question-3/
│   ├── question-4/
│   └── question-5/
├── assignment-2/
│   ├── question-1/
│   ├── question-2/
│   └── question-3/
├── docs/                         Assignment reports (.docx)
└── README.md
```

Each question folder contains an `index.html` and a `screenshot.png` of the rendered page.

---

## Techniques demonstrated

- **Box model** — margin, padding, border, outline, and `min-`/`max-` width constraints
- **Layout** — CSS Grid for two-dimensional layouts, Flexbox for rows and card alignment
- **Design tokens** — CSS custom properties declared once on `:root` and reused throughout
- **Typography** — Google Fonts paired to separate display headings from body copy
- **CSS-generated art** — gradients and pseudo-elements in place of image files
- **Responsiveness** — media queries reflowing every layout for tablet and phone widths
- **Accessibility** — semantic elements, `aria-label`s, and visible focus states on all controls

## Running locally

No build step is required — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

---

Submitted by **Areesha Khan** · Web Technologies
