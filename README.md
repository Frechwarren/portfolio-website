# Frech Warren Estampador — Portfolio Website

> AI Systems Architect · Voice AI Engineer · Full-Stack Developer

A dark, terminal-inspired portfolio website built as a single self-contained HTML file. Designed to convert — for technical recruiters, startup founders, agency owners, and business operators who need serious AI and software engineering work done.

---

## Live Site

**[frechwarren.dev](https://frechwarren.dev)** *(replace with your deployed URL)*

---

## About This Project

This portfolio was built from scratch as a single `index.html` file — no frameworks, no build tools, no dependencies. Everything ships in one file including embedded audio recordings of real Voice AI cold calls.

### Design Direction

- **Dark terminal / CLI aesthetic** — grid background, monospace labels, `>_` prompt style, section numbers
- **Font stack** — Bebas Neue (headlines) · Inter (body) · JetBrains Mono (labels, chips, code)
- **Color palette** — `#0C0C0C` background · `#4ADE80` neon green accent · `#EFEFEF` text
- **Animations** — fade-up scroll reveals, blinking cursor, pulsing availability dot, animated audiogram

---

## Features

- ✅ **Live audio players** — two real Voice AI cold call recordings with animated audiogram visualizer powered by the Web Audio API
- ✅ **Contact form** — connected to Formspree, forwards all submissions to Gmail
- ✅ **Scroll animations** — IntersectionObserver fade-up on all sections
- ✅ **Active nav highlighting** — nav links highlight as you scroll through sections
- ✅ **Fully responsive** — mobile-first, works on all screen sizes
- ✅ **Single file** — no build step, no dependencies, deploy anywhere

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | About | Bio, proof points, what I build |
| 02 | What I Do | 6 service cards with pain-point hooks |
| 03 | Featured Projects | Voice AI systems, NLiteSports, Hotshot Circuit + more |
| 04 | Skills & Technologies | Full tech stack grouped by category |
| 05 | Track Record | Timeline of work experience |
| 06 | My Process | 4-step process for working together |
| 07 | Contact | Formspree-powered form → Gmail |

---

## Tech Stack

```
HTML5 · CSS3 · Vanilla JavaScript · Web Audio API
Fonts: Bebas Neue · Inter · JetBrains Mono (Google Fonts)
Form: Formspree
Deployment: Vercel
```

---

## Deployment

This site is a single HTML file. To deploy:

### Vercel (recommended)
1. Push `index.html` to a GitHub repo
2. Import the repo on [vercel.com](https://vercel.com)
3. Deploy — done

### Netlify
1. Drag and drop `index.html` onto [netlify.com/drop](https://app.netlify.com/drop)
2. Live instantly

### Manual
Upload `index.html` to any static hosting provider.

---

## Contact Form Setup

The contact form uses [Formspree](https://formspree.io). To configure your own:

1. Sign up at formspree.io
2. Create a new form
3. Replace the form ID in the `action` attribute:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```
4. Set your notification email in Formspree dashboard

---

## Audio Players

Two embedded Voice AI cold call recordings showcase real outbound AI agents in action. Audio is base64-encoded directly into the HTML — no external files needed.

The audiogram visualizer uses the **Web Audio API**:
- 52 frequency bars animated in real time from actual audio data
- Green bars animate during playback, idle state shows flat gray bars
- Seek bar with live progress tracking
- Only one player plays at a time

> **Note:** Audio playback requires a web server (HTTP/HTTPS). Files opened directly from disk (`file://`) may not play due to browser security restrictions. Works fully on Vercel and any hosted environment.

---

## Customization

All design tokens are CSS variables at the top of the file:

```css
:root {
  --bg: #0C0C0C;
  --surface: #161616;
  --green: #4ADE80;
  --green-dim: #1a3a24;
  --text: #EFEFEF;
  --muted: #777777;
  --font-display: 'Bebas Neue', Impact, sans-serif;
  --font-body: 'Inter', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;
}
```

---

## Projects Featured

| Project | Stack | Link |
|---------|-------|------|
| Voice AI Systems | Retell AI · Vapi · ElevenLabs · Twilio SIP | Flagship |
| NLiteSports | React · NestJS · MongoDB · DigitalOcean | [talent.nlitesports.com](https://talent.nlitesports.com) |
| Hotshot Circuit | React Native · NestJS · Supabase · WebSockets | [GitHub](https://github.com/Frechwarren) |
| Dental Service App | NestJS · React · MongoDB · Docker · AWS EKS | [GitHub](https://github.com/Frechwarren/dental-service-app) |
| AI Cover Letter Generator | Python · Streamlit · OpenAI API | [GitHub](https://github.com/Frechwarren/AI.Cover.Letter.Generator) |
| AI Resume Analyzer | Python · PyPDF2 · OpenAI API | [GitHub](https://github.com/Frechwarren/simpleaipdfanalyser) |
| AI Chatbot | JavaScript · HTML/CSS · OpenAI API | [GitHub](https://github.com/Frechwarren) |
| IG Clone | React · Node.js · MongoDB · JWT | [GitHub](https://github.com/Frechwarren/IG-clone-project) |

---

## Contact

**Frech Warren Estampador**
📧 frechwarren120415@gmail.com
💻 [github.com/Frechwarren](https://github.com/Frechwarren)

> Open to full-time roles, freelance projects, and contract work — worldwide and remote.
