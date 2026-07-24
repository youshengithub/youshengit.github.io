# Shen You - Academic Homepage

Personal academic homepage built with [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it: `shenyou-cityu.github.io` (or `<yourusername>.github.io`)
3. Make it **Public**
4. Don't initialize with README

### Step 2: Fork the template

```bash
# Option A: Use the acad-homepage template directly
# Go to https://github.com/RayeRen/acad-homepage.github.io
# Click "Use this template" → "Create a new repository"
# Name it: <yourusername>.github.io
```

### Step 3: Replace key files

Copy the following files to your forked repo:

| This file | → | Destination in repo |
|-----------|---|---------------------|
| `_config.yml` | → | `_config.yml` |
| `_pages/about.md` | → | `_pages/about.md` |
| `images/avatar.jpg` | → | `images/avatar.jpg` |
| `images/unibreak.svg` | → | `images/unibreak.svg` |
| `images/sopa.svg` | → | `images/sopa.svg` |
| `images/queryeff.svg` | → | `images/queryeff.svg` |
| `files/cv.pdf` | → | `files/cv.pdf` |

### Step 4: Update _config.yml

Change `repository` to match your GitHub username:
```yaml
repository: "YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io"
```

### Step 5: Enable GitHub Pages

1. Go to repo **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / root
4. Save → your site will be live at `https://<username>.github.io`

---

## 📝 Customization Checklist

- [ ] Update `_config.yml`: email, github username, googlescholar URL
- [ ] Replace `images/avatar.jpg` with your photo
- [ ] Add CV PDF to `files/cv.pdf`
- [ ] Update paper links in `_pages/about.md` with actual DOI/IEEE links
- [ ] Add news items to the News section
- [ ] Replace SVG paper images with actual paper figures (500×300px recommended)

## 📄 Papers

| Paper | Venue | Year | Citations |
|-------|-------|------|-----------|
| UniBreak: Unified Evolutionary Token-Level Jailbreaking | IEEE TEVC | 2026 | - |
| SOPA: Sensitivity-Oriented Poisoning Attack | IEEE TEVC | 2025 | 1 |
| Query-Efficient AE Attack via Multi-Objective Optimization | IEEE TEVC | 2022 | 18 |
