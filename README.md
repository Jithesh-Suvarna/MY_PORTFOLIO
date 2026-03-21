# MY_PORTFOLIO
# 🚀 Jithesh Suvarna — Personal Portfolio

> *"I don't just study data — I build things with it."*

A clean, dark, gold-accented personal portfolio website built with vanilla HTML, CSS, and JavaScript. Features an animated background, project showcase, contact form with email delivery, and a password-protected admin dashboard.

🌐 **Live Site:** [jithesh-suvarna.github.io/portfolio](https://jithesh-suvarna.github.io/portfolio)

---

## ✨ Features

- **Animated background** — floating gold orbs + twinkling stars on canvas
- **Custom cursor** — gold dot + ring (desktop only)
- **Project showcase** — 5 projects with animated canvas visuals
- **Contact form** — sends directly to Gmail via EmailJS + saves to Firebase
- **Admin dashboard** — password-protected, add/delete projects with image upload
- **Fully responsive** — mobile, tablet, desktop
- **Smooth scroll + reveal animations** on scroll

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Email | EmailJS (delivers to Gmail) |
| Database | Firebase Firestore |
| Storage | Firebase Storage |
| Fonts | Cormorant Garamond, DM Sans, Space Mono |
| Hosting | GitHub Pages |

---

## 📁 Project Structure

```
portfolio/
├── index.html       # Main portfolio page
├── admin.html       # Password-protected admin panel
└── README.md        # You're reading this!
```

---

## ⚙️ Setup & Deployment

### 1. Firebase Setup
- Create a project at [console.firebase.google.com](https://console.firebase.google.com)
- Enable **Firestore** and **Storage**
- Copy your config and replace the placeholders in both `index.html` and `admin.html`:

```js
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    ...
};
```

### 2. EmailJS Setup
- Sign up at [emailjs.com](https://www.emailjs.com)
- Connect your Gmail account
- Create a template with `{{from_name}}`, `{{from_email}}`, `{{message}}`
- Replace in `index.html`:

```js
const EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';
const EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';
const EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
```

### 3. Deploy to GitHub Pages
- Push files to a public GitHub repo
- Go to **Settings → Pages → Deploy from branch → main**
- Site goes live at `https://YOUR_USERNAME.github.io/REPO_NAME`

---

## 🔐 Admin Panel

Access at `/admin.html`

```
Email:    ********@gmail.com
Password: ********
```

Features:
- View all contact messages
- Add new projects with image upload
- Delete projects and messages

> ⚠️ Change the password before deploying publicly!

---

## 📬 Contact

| Platform | Link |
|---|---|
| Email | jitheshsuvarna9731829845@gmail.com |
| LinkedIn | [linkedin.com/in/jithesh-suvarna](https://linkedin.com/in/jithesh-suvarna-412002395/) |
| GitHub | [github.com/Jithesh-Suvarna](https://github.com/Jithesh-Suvarna) |
| Instagram | [@_jithx09](https://instagram.com/_jithx09) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Built with passion & AI · © 2025 Jithesh Suvarna</p>