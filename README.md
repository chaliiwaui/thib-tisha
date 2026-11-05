<p align="center">
  <a href="https://thib-tisha.netlify.app/">
    <picture>
      <source height="150" media="(prefers-color-scheme: dark)" srcset="./public/img/logo/brand/brand-center-dark.png">
      <img height="150" alt="Thib-tisha" src="./public/img/logo/brand/brand-center.png">
    </picture>
  </a>
</p>

<h1 align="center">Thib-tisha</h1>

<p align="center">
  Advanced 🛡️ 2-way-SMS-factor authentication ensuring online security.<br>
  Front-end concept for a two-factor authentication service — landing page, sign-up, login, SMS code verification and a dashboard, built with Tailwind CSS and Flowbite.
</p>

<p align="center">
  <a href="https://thib-tisha.netlify.app/">🌐 Live Site</a> •
  <a href="#-pages">📄 Pages</a> •
  <a href="#-quick-start">🚀 Quick Start</a> •
  <a href="#-contributing">🤝 Contributing</a>
</p>

<p align="center">
  <a href="https://app.netlify.com/sites/thib-tisha/deploys"><img src="https://api.netlify.com/api/v1/badges/1b1453d2-ca69-4fac-b2a0-01526543bd20/deploy-status" alt="Netlify Status"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind-3-06B6D4?logo=tailwindcss" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Flowbite-1-1C64F2?logo=flowbite" alt="Flowbite">
  <img src="https://img.shields.io/badge/Vite-4-646CFF?logo=vite" alt="Vite">
</p>

---

## 📇 Description

Thib-tisha ("verify" in Swahili) is a concept for a security product that adds a second factor to sign-in using 2-way SMS verification. This repository holds the **static front-end**: the marketing page and the sign-up → login → SMS-code → dashboard screens. There is no backend yet — forms do not submit anywhere and the SMS/2FA logic is not implemented.

## 📄 Pages

| File             | Description                                                    |
| ---------------- | -------------------------------------------------------------- |
| `index.html`     | Landing page: hero, features, partners and trusted-client logos |
| `signup.html`    | Account creation form                                          |
| `login.html`     | Login form                                                     |
| `2fa.html`       | SMS verification-code entry                                    |
| `dashboard.html` | Signed-in dashboard mock-up (Flowbite components)              |

## ✨ Product vision

The concept the UI is designed around:

- Two-factor authentication for enhanced security
- 2-way SMS verification for reliable access control
- Real-time alerts for suspicious activities and activity logs
- Quick setup and easy integration with existing systems

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/chaliiwaui/thib-tisha.git
cd thib-tisha

# Install dependencies
npm install

# Start the Vite dev server
npm run dev
```

## 📦 Scripts

| Script            | Description                                  |
| ----------------- | -------------------------------------------- |
| `npm run dev`     | Vite development server                      |
| `npm run build`   | Build all five pages to `dist/`              |
| `npm run preview` | Build, then preview on the local network     |

## 🏗️ Structure

```
thib-tisha/
├── public/img/
│   ├── favicon/          # Favicons, site.webmanifest, browserconfig.xml
│   ├── logo/brand/       # Brand logos (light/dark)
│   ├── logo/partners/
│   └── logo/trusted-clients/
├── index.html
├── signup.html
├── login.html
├── 2fa.html
├── dashboard.html
├── style.css             # Tailwind directives + Space Grotesk @font-face
├── tailwind.config.js    # Custom blue palette, Flowbite plugin
├── postcss.config.js
└── vite.config.js        # Multi-page inputs (+ Flowbite bundle)
```

## 🛠 Tech

- **Tailwind CSS 3** with a custom blue scale and the Space Grotesk typeface
- **Flowbite 1** components (navbar, modals, dashboard widgets)
- **Vite 4** multi-page build, deployed to Netlify

## 🚀 Deployment

Deployed on Netlify at [thib-tisha.netlify.app](https://thib-tisha.netlify.app/) from `npm run build` → `dist/`.

## 🤝 Contributing

1. Fork this repository onto your own GitHub account.
2. Create a new branch for your changes: `git checkout -b your-branch-name`
3. Make your changes, commit them and push them to your branch.
4. Submit a pull request to the main repository.

If you have any questions about contributing, reach out to the project contributors — contributions of all kinds are welcome.

### 👥 Contributors

Made with 💙 by:

- [Jackson Makinda](https://github.com/chaliiwaui) - UX/UI Designer &amp; Front-end Developer
- [Elia Mkumbo](https://github.com/Era360) - Front-end &amp; ML Developer
- [Aloyce Nerey](https://github.com/BossNerey) - React Developer
- [Muhammed Singano](https://github.com/ms3c) - C, C++, Java &amp; Python programmer
- Kelvin Katarama
- Paschal - System Developer

## 📄 License

No license has been chosen yet.

## 👤 Author

**Jackson Makinda** - [makindajackson.com](https://makindajackson.com)

- 📧 Email: me@makindajackson.com
- 💼 LinkedIn: [Jackson Makinda](https://linkedin.com/in/makindajack)
- 🎨 Dribbble: [@makindajack](https://dribbble.com/makindajack)
- 🐦 Twitter: [@makindajack](https://twitter.com/makindajack)

---

Built with ❤️ in Dar es Salaam, Tanzania 🇹🇿
