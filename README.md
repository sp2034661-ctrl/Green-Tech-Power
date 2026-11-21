# GreenTech Power - Solar Energy EPC & Rooftop Solutions

A modern, high-performance, responsive multi-page web platform for **GreenTech Power**, leading solar energy EPC company in Uttar Pradesh (Lucknow, Kanpur, Ayodhya, Varanasi).

## 🚀 Key Features

- **PM Surya Ghar Muft Bijli Yojana & UP NEDA Integration**: Built-in subsidy calculations up to ₹1,08,000.
- **Dedicated Multi-Page Architecture**:
  - `index.html` - Premium landing page with verified solar installation video showcase, real engineer cutout hero, statistics counter, interactive project tabs, and client testimonials.
  - `services.html` - Comprehensive residential, commercial, battery storage, and hybrid solar service packages with clean card layouts and feature matrices.
  - `projects.html` - Filterable portfolio of verified UP installations (Villa Rooftops, Logistics Hubs, Industrial Plants, Educational Campuses, and Hotels) with high-contrast metric chips and unique photos.
  - `calculator.html` - Interactive solar capacity and subsidy estimator with real-time bill savings calculator.
  - `about.html` - Company pedigree, MNRE/UPPCL certifications, and engineering standards.
  - `contact.html` - Lead capture form, Lucknow headquarters address, direct dial helpline, and WhatsApp booking.
- **Interactive UI & Polish**:
  - Instant Consultation & Quote Modals with pre-filled service selection.
  - Live Project Video player with custom play/pause overlay.
  - Category filter tabs with instant filtering.
  - Responsive layouts optimized for mobile, tablet, and ultra-wide screens.

## 🛠️ Tech Stack

- **HTML5 & Vanilla CSS3**: Clean semantic design with custom design system, glassmorphism badges, and smooth transitions.
- **Vanilla JavaScript**: Lightweight, modular event handlers for modals, calculator engine, video controller, and portfolio filters.
- **Font Awesome 6.5 & Google Fonts**: DM Sans, Inter typography.

## 🌐 Running Locally

Serve the site with any static HTTP server:

```bash
# Python 3
python -m http.server 8080
```

Navigate to `http://localhost:8080/`.

## Form email delivery

The site survey, quote, contact, and newsletter forms submit to `salesgreentechpower2@gmail.com` through [FormSubmit](https://formsubmit.co/) using standard HTML POST. FormSubmit shows its confirmation or thank-you page after a submission. The first submission triggers an activation email at that address. Open it and confirm the form before expecting lead emails. Check the spam folder if the activation message does not appear.

CAPTCHA is disabled on these forms to remove the extra step. A hidden honeypot field helps filter basic automated submissions; FormSubmit may still apply its own spam limits.

Serve the site over HTTP or HTTPS when testing forms; FormSubmit does not support submitting pages opened as local `file://` documents. The newsletter form sends a signup request to the sales inbox; adding that address to a mailing list is a separate step.
