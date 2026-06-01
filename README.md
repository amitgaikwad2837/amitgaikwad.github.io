# Amit Gaikwad — Portfolio Website

Personal portfolio website for **Amit Gaikwad**, Director of Engineering & AI-Native Platform Leader.

Live site: `https://amitgaikwad.github.io` *(after deployment)*

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Complete single-file portfolio website |
| `README.md` | This file |

---

## Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create your GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon (top right) → **New repository**
3. Set the repository name to exactly: `amitgaikwad.github.io`
   > The name must match your GitHub username. If your username is different, use `yourusername.github.io`
4. Set visibility to **Public**
5. Click **Create repository**

---

### Step 2 — Upload your files

**Option A — Upload via browser (easiest):**

1. Open your new repository on GitHub
2. Click **Add file** → **Upload files**
3. Drag and drop `index.html` into the upload area
4. Scroll down → click **Commit changes**

**Option B — Using Git (recommended for future updates):**

```bash
# Clone the repo
git clone https://github.com/amitgaikwad/amitgaikwad.github.io.git
cd amitgaikwad.github.io

# Copy your files into the folder
cp /path/to/index.html .
cp /path/to/README.md .

# Push to GitHub
git add .
git commit -m "Initial portfolio launch"
git push origin main
```

---

### Step 3 — Enable GitHub Pages

1. In your repository, click **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main** and folder to **/ (root)**
5. Click **Save**

---

### Step 4 — Your site is live!

Wait 1–3 minutes, then visit:

```
https://amitgaikwad.github.io
```

> GitHub will show a banner in the Pages settings when the site is published.

---

## Add a Custom Domain (Optional — ~$12/year)

A custom domain like `amitgaikwad.com` looks far more professional.

1. Buy a domain from [Namecheap](https://namecheap.com) or [Cloudflare](https://cloudflare.com/products/registrar/)
2. In your domain DNS settings, add these records:

```
Type    Host    Value
A       @       185.199.108.153
A       @       185.199.109.153
A       @       185.199.110.153
A       @       185.199.111.153
CNAME   www     amitgaikwad.github.io
```

3. In GitHub → Settings → Pages → **Custom domain**, enter `amitgaikwad.com`
4. Check **Enforce HTTPS**

---

## Update Your Portfolio

Whenever you want to make changes:

1. Edit `index.html` locally
2. Push the updated file to GitHub:

```bash
git add index.html
git commit -m "Updated projects section"
git push origin main
```

GitHub Pages automatically rebuilds and deploys within ~1 minute.

---

## Post-Launch Checklist

- [ ] Site loads at `https://amitgaikwad.github.io`
- [ ] Test on mobile (open on your phone)
- [ ] Add portfolio URL to your LinkedIn profile (Edit profile → Website)
- [ ] Add portfolio URL to your resume header
- [ ] Add portfolio URL to your email signature
- [ ] Submit URL to [Google Search Console](https://search.google.com/search-console) for indexing
- [ ] Add [Google Analytics](https://analytics.google.com) tracking ID to `index.html` (optional)

---

## Customization Tips

| What to change | Where in `index.html` |
|---|---|
| Profile photo | Add `<img>` tag in the hero section |
| Hero headline | Search for `hero-h1` |
| Stats numbers | Search for `stat-num` |
| Project cards | Search for `project-card` |
| Contact email | Search for `amit.gaikwad37@gmail.com` |
| LinkedIn URL | Search for `linkedin.com/in/amit-gaikwad` |
| Accent color (blue) | Change `--accent: #1a4fff` in `:root` |

---

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript — no frameworks, no dependencies
- Google Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- Scroll-reveal animations via Intersection Observer API
- Fully responsive (mobile, tablet, desktop)
- Page size: ~30KB — loads in under 1 second

---

## Contact

**Amit Gaikwad**
- Email: amit.gaikwad37@gmail.com
- LinkedIn: [linkedin.com/in/amit-gaikwad-6385415b](https://linkedin.com/in/amit-gaikwad-6385415b)
- Phone: +91 80079 90088
- Location: Pune, Maharashtra, India
