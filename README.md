# hussainbashashaik.dev — Personal Portfolio

Personal portfolio website for **Shaik Hussainbasha** — Aspiring Python Developer, AI/ML & Data Enthusiast. Built as a single-page, responsive site with a terminal-style hero animation, skills overview, projects, education/internship timelines, certifications, and a working contact form.

**Live site:** 

## ✨ Features

- Responsive single-page layout (mobile nav toggle, fluid grid sections)
- Animated terminal intro (`whoami.sh` style typing effect)
- Skills grid with an honest "proficient vs. learning" legend
- Project cards with live demo + source code links
- Education and internship timelines
- Certifications gallery with verification links
- Accessible, spam-protected contact form (honeypot + time-trap) powered by [Formspree](https://formspree.io)
- Scroll-reveal animations that respect `prefers-reduced-motion`

## 🛠️ Built With

- HTML5 & semantic markup
- CSS3 (custom properties, CSS Grid/Flexbox, no framework)
- Vanilla JavaScript (no build step required)
- Google Fonts — Space Grotesk, Inter, JetBrains Mono
- [Formspree](https://formspree.io) for contact form submissions

## 📁 Project Structure

```
.
├── index.html
└── assets/
    ├── img/
    │   ├── logo.png
    │   ├── profile.png
    │   ├── project-ml-app.png
    │   ├── project-User-app.png
    │   ├── project-github-app.png
    │   ├── project-Nasa-app.png
    │   └── ...certificate images
    └── resume/
        └── Shaik_Hussainbasha_Resume.pdf
```

## 🚀 Getting Started

This is a static site — no build tools or dependencies required.

1. Clone the repo
   ```bash
   git clone https://github.com/hussainbasha559/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in your browser, or serve it locally:
   ```bash
   npx serve .
   ```

## ⚙️ Configuration

The contact form submits to Formspree. To use your own form:

1. Create a free form at [formspree.io](https://formspree.io).
2. In `index.html`, update the `FORM_ENDPOINT` constant inside the `<script>` block near the bottom of the file with your own Formspree endpoint.



## 🧑‍💻 Projects Featured

| Project | Stack | Links |
|---|---|---|
| End-to-End Machine Learning Web App | Python, Streamlit | [Demo](https://shaikhussainbashaa9.streamlit.app/) · [Code](https://github.com/hussainbasha559/MINI_PROJECT-) |
| User Authentication / Portfolio Generator App | Node.js, MongoDB | [Demo](https://portfolio-generator-app-ugn4.onrender.com/) · [Code](https://github.com/hussainbasha559/Portfolio-Generator-App) |
| GitHub Profile Fetcher | HTML, CSS, JavaScript | [Demo](https://github-three-theta.vercel.app/) · [Code](https://github.com/hussainbasha559/GITHUB) |
| 3D Space Tracking (NASA Hackathon) | JavaScript | — |

## 📄 License

This project is open source. Feel free to fork it for your own portfolio — just swap in your own content, images, and links.

## 📬 Contact

- Email: [hussainbashashaik792@gmail.com](mailto:hussainbashashaik792@gmail.com)
- GitHub: [@hussainbasha559](https://github.com/hussainbasha559)
- LinkedIn: [Shaik Hussainbasha](https://www.linkedin.com/in/shaik-hussainbasha-aa66a7358)