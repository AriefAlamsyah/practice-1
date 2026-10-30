# Lentera Kriya — Agency Website

A 3-page website for **Lentera Kriya**, a fictional small Indonesian digital agency based in Bandung, that **builds websites** and **manages social media** for UMKM (small and growing local businesses).

The site is written in Indonesian and has one main goal: getting visitors to **contact the agency**, mainly through WhatsApp and otherwise through a contact form.

> **Live site:** _[add your Vercel link here]_

---

## Who it's for

Small business owners such as local shops, culinary businesses, fashion stores, clinics and service businesses. Most of them:

- browse on their **phone**, often arriving from Instagram or WhatsApp
- are **busy** and **not technical**
- want three quick answers: *Can you help my business? How much does it cost? Can I trust you?*

Each page answers one of those questions.

---

## The 3 pages

### 1. Beranda (Home): "Can you help my business?"
The whole story in one scroll:

| Section | What it shows |
|---|---|
| Hero | What the agency does and for whom, plus the main button "Konsultasi Gratis via WhatsApp" |
| Masalah | 4 common problems business owners face online |
| Layanan Kami | Short intro to the two services, linking to the Layanan page |
| Manfaat | 4 reasons a business should be online |
| Kenapa Memilih Kami | Honest strengths: simple language, clear prices, WhatsApp contact, support after launch |
| Portofolio Pilihan | 3 highlighted projects |
| Cara Kerja | The 4-step process: Konsultasi → Penawaran → Pengerjaan → Selesai & Pendampingan |
| Testimoni | Client quotes (to be filled with **real** testimonials only) |
| Ajakan Penutup | Final invitation to chat on WhatsApp or fill in the form |

### 2. Layanan & Portofolio (Services): "What do I get, and how much?"
For visitors who are already interested and want details:

| Section | What it shows |
|---|---|
| Header | Short intro, with quick-jump buttons to each service |
| Pembuatan Website | What's included, and what kinds of websites it suits |
| Pengelolaan Media Sosial | What's included, and which platforms (Instagram, Facebook, TikTok) |
| Paket & Harga | 4 packages with starting prices, split into **Website** and **Media Sosial** tabs |
| Portofolio | 6 projects with a **filter** (All / Website / Social Media); click a project to open its story |
| FAQ | 6 common questions that open when clicked |
| Ajakan Penutup | Free consultation button |

### 3. Tentang Kami & Kontak (About & Contact): "Who are you, and how do I reach you?"
Shows the people behind the agency and makes contacting them easy:

| Section | What it shows |
|---|---|
| Header | Team introduction with a team photo |
| Cerita Kami | Why the agency was started |
| Cara Kami Bekerja | 4 values: honest, easy to understand, responsive, growing together |
| Tim Kami | Team members with photo, name and role |
| Angka | Key numbers such as clients and projects (optional, **real** numbers only) |
| Hubungi Kami | WhatsApp, email, Instagram, address and working hours, plus a short 5-field contact form |
| FAQ Kontak | 3 quick questions before reaching out |

---

## On every page

- **Menu bar** fixed at the top: logo on the left, links and a "Hubungi Kami" button on the right. On phones the links fold into a ☰ menu.
- **Floating WhatsApp button** in the bottom-right corner, with a small "Ada pertanyaan? Chat kami!" bubble.
- **Footer** with navigation, services, contact details and social media links.
- **WhatsApp buttons with ready-made messages.** Each button opens WhatsApp with its own pre-written message, such as the package name, so the agency knows where each lead came from.

---

## Design

- **Colors:** soft black and warm off-white, with warm greys in between. They are softened on purpose, no pure black or pure white, so the site is easy on the eyes. WhatsApp green is kept for the WhatsApp button.
- **Font:** Plus Jakarta Sans, a clean typeface designed in Indonesia.
- **Mobile first:** designed for phones, then adjusted for tablets and laptops.
- **Fits every screen:** text, buttons and spacing shrink smoothly on smaller screens, and nothing sticks out the side, even on very narrow windows. On phones, buttons are centered.
- **Simple and readable:** short sentences, one idea per section, big tap-friendly buttons and labelled form fields.

---

## How it's built

- **Plain HTML and CSS only**, with no JavaScript, no frameworks and no build step.
- The menu, price tabs, portfolio filter, project pop-ups and FAQ all work with HTML and CSS alone.
- **One shared style file** for all pages, so a change in one place updates the whole site.
- The contact form is sent through **FormSubmit**, a free service that forwards messages to the agency's email.

### Files

| File | What it is |
|---|---|
| `index.html` | Beranda (Home) |
| `layanan.html` | Layanan & Portofolio |
| `tentang.html` | Tentang Kami & Kontak |
| `css/style.css` | The shared styles for all pages |

---

## Viewing it on your computer

Download or clone this repository and **double-click `index.html`**. It opens in your browser, and nothing needs to be installed.

## Putting it online

The site is ready for **Vercel**. Import this repository, keep the framework preset as **Other**, and deploy. Every update pushed to `main` goes live automatically.

---

## About the sample content

This is a **practice project**. Everything about the agency is **fictional but realistic**, so the site looks finished:

- **Agency:** Lentera Kriya, founded in 2022 in Bandung
- **Team:** Raka Pratama (Web Developer), Nadia Putri (Social Media Specialist), Dimas Ardiansyah (Graphic Designer)
- **Clients and portfolio:** Dapur Rina Bakery (Bandung), Butik Laras (Surabaya), Klinik Gigi Senyum Sehat (Jakarta), Kopi Senja (Yogyakarta), Bengkel Jaya Motor (Semarang), Sari Alam Herbal (Malang)
- **Prices:** Website Starter from Rp 1.500.000, Website Bisnis from Rp 3.500.000, Sosmed Basic from Rp 1.200.000/month, Sosmed Growth from Rp 2.500.000/month
- **Numbers:** 40+ clients, 65+ projects, 4 years, 12 cities

A small note in the footer of every page says the content is fictional.

### Turning it into a real agency website
Swap the sample content for real details:

- [ ] Agency name, logo, address and working hours
- [ ] **WhatsApp number**: the current one (0812-3456-7890) is a sample and may belong to a stranger
- [ ] **Email**: halo@lenterakriya.id is not a real inbox, so the contact form won't deliver messages until it's changed
- [ ] Instagram account and social media links
- [ ] The live website address in the contact form (currently set to lentera-kriya.vercel.app)
- [ ] Real prices, numbers, team members and photos, replacing the striped photo boxes and initials
- [ ] Real portfolio projects and **real testimonials** (with the clients' permission)
- [ ] Remove the "proyek latihan" note in the footer

> **Honesty rule for a real launch:** only show real numbers, real projects and real testimonials. Never invent them.
