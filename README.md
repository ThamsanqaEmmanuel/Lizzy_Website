# LJ CO Traders (Pty) Ltd — Company Website

> *Delivering Clean Spaces, Professional Service, and Lasting Impressions.*

A clean, mobile-responsive single-page website for **LJ CO Traders (Pty) Ltd**, a South African cleaning services company. Built with plain HTML, CSS, and JavaScript — no frameworks, no database, no build tools required.

---

## 🌐 Live Features

- **Hero section** with call-to-action buttons
- **About section** with company registration details
- **Services section** — Commercial, Residential, Industrial, Specialised & Facilities Support
- **Why Choose Us** section
- **Contact section** with active links:
  - 📱 WhatsApp link (opens WhatsApp chat directly)
  - 📞 Click-to-call phone link
  - 📧 Email link
- **Quote Request Modal** — customers fill in their details and submit an enquiry
- **EmailJS integration** — two emails fire on every submission:
  1. Enquiry notification sent to the business
  2. Automatic confirmation reply sent to the customer
- **Floating WhatsApp button** (always visible, pulses to attract attention)
- Fully **mobile responsive**

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom, no framework) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Oswald + Inter |
| Email | [EmailJS](https://www.emailjs.com) (free tier) |

---

## 📁 File Structure

```
/
└── index.html      # Entire website — HTML, CSS, and JS in one file
└── README.md       # This file
```

---

## ✉️ Email Setup (EmailJS)

The contact form uses [EmailJS](https://www.emailjs.com) to send emails without a backend server.

The following keys are already configured in `index.html`:

| Variable | Value |
|---|---|
| `EJ_PUBLIC_KEY` | Your EmailJS Public Key |
| `EJ_SERVICE_ID` | Your EmailJS Service ID |
| `EJ_TPL_NOTIFY` | Template ID — enquiry notification to business |
| `EJ_TPL_REPLY` | Template ID — auto-reply to customer |

### Email Templates

**Template 1 — Enquiry Notification** (sent to the business)

Uses these variables:
- `{{customer_name}}` — full name from form
- `{{customer_email}}` — customer's email
- `{{customer_phone}}` — customer's phone number
- `{{service_type}}` — service selected
- `{{message}}` — optional additional details

**Template 2 — Auto-Reply** (sent to the customer)

Uses these variables:
- `{{customer_name}}` — customer's full name
- `{{service_type}}` — service they enquired about

---

## 🚀 Deployment

This is a static site — no server or build step needed. You can host it anywhere:

### Option 1 — GitHub Pages (free)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2 — Netlify (free, recommended)
1. Go to [netlify.com](https://www.netlify.com) and sign up
2. Click **"Add new site" → "Import an existing project"**
3. Connect your GitHub repo
4. Click **Deploy** — done, live in seconds with a free HTTPS URL

### Option 3 — Direct upload
Simply open `index.html` in any web browser — it works offline too.

---

## 📞 Contact Information

| Detail | Value |
|---|---|
| Company | LJ CO Traders (Pty) Ltd |
| Registration | 2026/436773/07 |
| Contact Person | Paledi Kgomo |
| Phone / WhatsApp | 068 006 3084 |
| Email | ethamsanqa@gmail.com |
| Address | 5859 Extension 4, Soshanguve South Ext 4, Soshanguve, Gauteng, 0152 |

---

## 📄 License

This website and its content are the property of **LJ CO Traders (Pty) Ltd**. All rights reserved © 2026.
