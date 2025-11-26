# Official Portfolio — **devbabul.github.io**

A fast, elegant personal site for **Babul Khan** — Graphic Designer, Web Developer & Presentation Designer. Showcases skills, services, portfolio, testimonials, and a contact form in a clean single-page experience.

[![Live Preview](https://devbabul.github.io/assets/img/Live_Preview_Thumbnail.jpg)](https://devbabul.github.io/)

> 🔗 **Live site:** https://devbabul.vercel.app  
> 🌐 **(Optional) GitHub Pages:** https://devbabul.github.io  
> 🖥️ **(Website):** https://www.devbabul.live <br>  
> 🧑🏻‍💻 **(Cat Profile):** Scan below QR Code  

<a href="https://www.devbabul.live" target="_blank">
  <img src="https://devbabul.github.io/assets/img/HeartQR.png" alt="QR Code" width="150">
</a>

---

## ✨ Features

- **Hero + About + Resume** sections with clear CTAs  
- **Services** with copy tuned for conversions  
- **Filterable Portfolio** grid with large visuals  
- **Testimonials** carousel/cards  
- **Contact** section (email + WhatsApp quick links)  
- **Responsive** layout for mobile, tablet, desktop  
- Lightweight **HTML / CSS / JavaScript** stack (no heavy frameworks)

---

## 📁 Project Structure

```
devbabul.github.io/
├─ assets/
│  ├─ css/            # Stylesheets
│  ├─ js/             # JavaScript
│  └─ img/            # Images (portfolio, testimonials, icons, etc.)
├─ index.html         # Main single-page site
└─ thank_you.html     # Optional thank-you/confirmation page
```

> If you add more sections or assets, keep this tree updated for contributors.

---

## 🚀 Getting Started (Local)

1. **Open CMD**
   Win+R type `CMD` hit Enter

2. **Clone**
   ```bash
   git clone https://github.com/devbabul/devbabul.github.io.git
   ```

3. **Change Directory to Site**
   ```bash
   cd devbabul.github.io
   ```
4. **Run locally**
   ```bash
   start index.html
   ```,
   
   - Double-click `index.html`, **or**
   - Use VS Code **Live Server** extension → “Open with Live Server”

---

## ☁️ Deployment

### Option A — GitHub Pages (recommended for this repo name)
- Keep repository name **devbabul.github.io**
- Push to `main` — Pages auto-serves at `https://devbabul.github.io`
- (Optional) Add a custom domain via **Settings → Pages → Custom domain** and commit a `CNAME` file

### Option B — Vercel
- Import the repo on **vercel.com**
- Framework preset: **Other**
- Build command: _none_ (static)
- Output dir: `/`  
- Deploy — get an instant preview + production URL

---

## 🧩 Customize Content

- **Profile & intro text:** edit the **Hero** and **About** blocks in `index.html`  
- **Skills & percentages:** update progress bars/values in the **About/Skills** area  
- **Resume:** modify education & experience lists in the **Resume** section  
- **Services:** tweak headings & descriptions to match offers  
- **Portfolio:** add/remove project cards (image, title, category)  
- **Testimonials:** replace photos, names, and quotes  
- **Contact:** set your email/WhatsApp links (mailto, wa.me)

> Tip: keep images under ~250KB for snappy loads. Use `.webp` where possible.

---

## 🔒 SEO & Metadata (quick wins)

- Add correct **title**, **description**, **OG** and **Twitter** meta tags in `<head>`
- Include a **favicon** and **social preview** image (1200×630)
- Use semantic headings (`h1`–`h3`) for better indexing

---

## 🛠️ Scripts (optional helpers)

- **Optimize images:** use tools like `squoosh.app` or `imagemin`  
- **Lint HTML/CSS:** `npm i -D htmlhint stylelint` (if you want a CI check)

---

## 🧑‍💻 Author

**Babul Khan**  
Graphic Designer | Web Developer | PPT Designer  
📧 **Email:** devbabulkhan@gmail.com  
🔗 **Portfolio:** https://devbabul-github-io.vercel.app

---

## 📜 License

This repository currently has no explicit license.  
- If you want it **open-source**, add an `MIT` license.  
- If you prefer **all rights reserved**, add a simple notice: `© Babul Khan`.

---

## 🤝 Contributing

Issues and PRs are welcome for:
- Bug fixes (layout, responsiveness, accessibility)
- Copy improvements (typos, clarity)
- New portfolio entries or section refinements

Please keep PRs small and focused.

---

## 🧭 Roadmap (ideas)

- Add a **blog** or **case studies** section  
- Dark mode toggle  
- Micro-animations (AOS/GSAP) with reduced-motion support  
- Lightweight analytics (Plausible)  

---

**Enjoy the site!** If you use this template for your own portfolio, drop a ⭐️ on the repo.