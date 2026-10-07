
# NextGEN Technologies — Website

Clean, modern, high-end multi-page site for **NextGEN Technologies** (nextGEN UX tech).

## Structure

```
nextgen-tech/
├── index.html          # Home
├── about.html          # About / mission
├── services.html       # Full capabilities
├── contact.html        # Contact + Formspree form
├── css/styles.css      # Design system + MicroKit-style buttons
├── js/main.js          # Scroll, mobile menu, reveal animations
├── assets/
│   ├── logo-mark.jpg   # Geometric N mark
│   └── logo-wordmark.jpg # nextGEN UX + tech badge
└── README.md
```

## Design system

- **Typography**: Nunito Sans
- **Palette**: Black & white (matches your logos)
- **Header**: Minimal white/light + real logos
- **Motion**: 
  - Scroll-triggered reveals
  - Card hover lift
  - **MicroKit-inspired “Next Dot Fill” button** (black/white)
  - Floating hero badges
  - Smooth nav underline

## Formspree (Contact form)

1. Create a form at [formspree.io](https://formspree.io)
2. Open `contact.html`
3. Replace `YOUR_FORM_ID` in the form `action` attribute:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Adding MicroKit components (recommended next step)

MicroKit provides high-end micro-interactions via the shadcn registry.

To use them properly, convert this site to **Next.js + Tailwind**:

```bash
npx create-next-app@latest nextgen-app --typescript --tailwind --app
cd nextgen-app
# copy pages/components from this folder
npx shadcn@latest init
npx shadcn@latest add @microkit/next-dot-fill-button
npx shadcn@latest add @microkit/expanding-contact-button
# etc.
```

The current static site already includes a pure-CSS black/white version of the **Next Dot Fill Button** so the experience is polished without a build step.

## Local preview

Simply open `index.html` in a browser, or run a static server:

```bash
npx serve .
# or
python3 -m http.server 3000
```

## Brand assets

- Logo mark: `assets/logo-mark.jpg` (geometric N)
- Wordmark: `assets/logo-wordmark.jpg` (nextGEN UX + tech pill)

Both are used in header and footer (inverted in dark footer).
=======
- 👋 Hi, I’m @Mr-LERIN
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Mr-LERIN/Mr-LERIN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
