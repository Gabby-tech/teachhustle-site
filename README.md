# 🟡 TeachHustle – Official Website

> **Learn the Skills. Hustle the Dream.**  
> Nigeria's boldest online tech education platform — built for hustlers, dreamers, and the next generation of technopreneurs.

---

## 🌐 Live Site

[teachhustle.vercel.app](https://teachhustle.vercel.app) ← *(update with your real URL)*

---

## 📁 Project Structure

```
teachhustle-site/
├── index.html        # Main website (single-page)
├── README.md         # You're reading it
└── assets/           # Optional: add images, favicon, etc.
```

---

## 🚀 Deploy in 3 Steps

### 1. Clone or download this repo
```bash
git clone https://github.com/YOUR_USERNAME/teachhustle-site.git
cd teachhustle-site
```

### 2. Push to GitHub
```bash
git add .
git commit -m "Initial TeachHustle site"
git push origin main
```

### 3. Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New → Project**
3. Import your GitHub repo
4. Vercel auto-detects it as a **Static Site**
5. Click **Deploy** — you're live in seconds ✅

> 💡 To connect a custom domain (e.g. `teachhustle.com`), go to **Vercel → Project → Settings → Domains**.

---

## ⚙️ Configuration

### EmailJS (Contact Form)
The contact form uses [EmailJS](https://emailjs.com) — no backend required.

1. Sign up at [emailjs.com](https://emailjs.com)
2. Create a **Service** (Gmail, Outlook, etc.)
3. Create an **Email Template** with these variables:
   - `{{from_name}}` — sender's name
   - `{{from_email}}` — sender's email
   - `{{subject}}` — message subject
   - `{{message}}` — message body
4. Copy your **Service ID**, **Template ID**, and **Public Key**
5. In `index.html`, replace:
```js
const EMAILJS_SERVICE_ID  = "YOUR_SERVICE_ID";
const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID";
const EMAILJS_PUBLIC_KEY  = "YOUR_PUBLIC_KEY";
```

---

### Mailchimp (Email Signup)
The signup form connects to your Mailchimp audience.

1. Log in to [mailchimp.com](https://mailchimp.com)
2. Go to **Audience → Signup Forms → Embedded Forms**
3. Copy your **Form Action URL** (looks like `https://xxxx.us21.list-manage.com/subscribe/post?u=...&id=...`)
4. In `index.html`, replace:
```js
const MAILCHIMP_URL = "YOUR_MAILCHIMP_FORM_ACTION_URL";
```

---

## 🎨 Brand Colors

| Color | Hex |
|-------|-----|
| TeachHustle Gold | `#E8A000` |
| Gold Light | `#FAC75A` |
| Gold Dark | `#B87800` |
| Black | `#0A0A0A` |
| White | `#FFFFFF` |

---

## 📦 Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | HTML5, CSS3, Vanilla JS |
| Fonts | Inter (Google Fonts) |
| Email | EmailJS |
| Subscribers | Mailchimp |
| Hosting | Vercel |

---

## 📬 Contact

Built by the **TeachHustle** team.  
📧 hello@teachhustle.com  
📸 [@teachhustle](https://instagram.com/teachhustle) on Instagram  
🎵 [@teachhustle](https://tiktok.com/@teachhustle) on TikTok

---

*© 2026 TeachHustle. Built for Nigerian hustlers worldwide. 🇳🇬*
