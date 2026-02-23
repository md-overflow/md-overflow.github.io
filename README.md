# Md Mudassir Ahmed — Portfolio Website

A modern, dark-themed portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies — just open and go.

## File Structure

```
portfolio/
├── index.html              ← Homepage
├── css/
│   └── style.css           ← All styles (design system + components)
├── js/
│   └── main.js             ← Interactions, animations, scroll effects
└── pages/
    ├── about.html          ← About me + skills + timeline
    ├── projects.html       ← Project showcase with filter
    ├── blog.html           ← Blog posts with search
    └── contact.html        ← Contact form (Formspree)
```

## Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Dark theme with electric blue/cyan accents
- ✅ Scroll animations (fade-up)
- ✅ Animated skill bars
- ✅ Project filter by category
- ✅ Blog search
- ✅ Cursor glow effect (desktop)
- ✅ Working contact form (via Formspree)
- ✅ Active nav link highlighting
- ✅ Mobile hamburger menu

## Customise

### 1. Replace placeholder content
- Open each `.html` file and update name, bio, projects, blog posts, and contact info
- Search for `#` placeholder links and replace with your actual GitHub/LinkedIn URLs

### 2. Add your photo
In `pages/about.html`, replace the `.portrait-placeholder` div with:
```html
<img src="../assets/images/your-photo.jpg" alt="Md Mudassir Ahmed" style="width:100%; height:100%; object-fit:cover; border-radius:4px;" />
```

### 3. Enable the contact form
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form and copy your Form ID
3. In `pages/contact.html`, replace `YOUR_FORM_ID` in the form action URL

### 4. Add your resume
Place your resume PDF in `assets/` and update the download link in `pages/about.html`:
```html
<a href="../assets/resume.pdf" class="btn btn-outline" download>Download CV</a>
```

## Deploy to GitHub Pages (Free)

### Step 1: Create GitHub repo
Create a new repository named exactly: `yourusername.github.io`

### Step 2: Push your files
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
- Go to your repo → Settings → Pages
- Source: Deploy from branch → `main` → `/ (root)`
- Save → your site will be live at `https://yourusername.github.io`

## Optional: Custom Domain
1. Buy a domain (Namecheap ~$10/year)
2. In GitHub Pages settings, add your custom domain
3. At your domain registrar, add a CNAME record pointing to `yourusername.github.io`

---

Built with ❤️ for Md Mudassir Ahmed
