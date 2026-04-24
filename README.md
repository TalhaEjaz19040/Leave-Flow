# LeaveFlow – Leave Management System
### COMP-463 Cloud Computing | PAF-IAST

A fully functional **frontend-only Leave Management System** deployed on Vercel.

---

## 📋 Project Overview

This project demonstrates cloud deployment concepts using Vercel as a SaaS frontend hosting platform with CI/CD via GitHub integration.

---

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| Dashboard | `index.html` | Summary stats, charts, recent leaves |
| Apply Leave | `apply.html` | Leave application form with validation |
| Leave History | `history.html` | Filterable table of all leave records |
| Admin Panel | `admin.html` | Dept. Head + HR approval workflow |

---

## 🛠️ Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom properties, Grid, Flexbox, animations
- **JavaScript** – DOM manipulation, filtering, dynamic rendering
- **Google Fonts** – Syne + DM Sans
- **Vercel** – Cloud deployment platform
- **GitHub** – Version control & CI/CD trigger

---

## ☁️ Deployment Steps

### Step 1 – Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Leave Management System"
git remote add origin https://github.com/YOUR_USERNAME/leave-management.git
git push -u origin main
```

### Step 2 – Deploy on Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click **"Add New Project"**
4. Import your repository
5. Click **"Deploy"** — Vercel auto-detects static HTML
6. Get your live URL: `https://your-project.vercel.app`

---

## ✅ Features

- **Dashboard** — stat cards, bar chart (leaves/month), donut chart (type distribution), recent requests table
- **Apply Leave** — employee info form, leave type selector, date picker, auto day counter, form validation
- **Leave History** — searchable/filterable table, status badges, pagination UI
- **Admin Panel** — tabbed Dept. Head card view + HR table, interactive Approve/Reject buttons, live state updates

---

## 👨‍🎓 Submitted By

- **Course**: COMP-463 Cloud Computing
- **Institution**: PAF-IAST
- **Instructor**: Luqman Shahzad