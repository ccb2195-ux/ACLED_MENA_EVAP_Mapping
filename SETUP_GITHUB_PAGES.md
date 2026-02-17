# GitHub Pages Setup Guide

## Quick Start

Follow these steps to publish your ACLED MENA visualization to GitHub Pages:

### 1. Verify Files Are Ready

Make sure you have these files in your repository:
- ✅ `index.html` (main website)
- ✅ `ACLED_MENA_Map2.html` (interactive map)
- ✅ `density_plot.png` (timeline chart)
- ✅ `README.md` (optional but recommended)

### 2. Commit and Push to GitHub

```bash
# Make sure all files are added to git
git add index.html ACLED_MENA_Map2.html density_plot.png

# Commit with a descriptive message
git commit -m "Add website files for GitHub Pages"

# Push to GitHub
git push origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/YOUR_USERNAME/ACLED_MENA_EVAP_Mapping`
2. Click on **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment

### 4. Access Your Site

Your site will be available at:
```
https://YOUR_USERNAME.github.io/ACLED_MENA_EVAP_Mapping/
```

GitHub will show you the exact URL in the Pages settings.

---

## Mobile Optimization Features

Your site includes:
- ✅ Responsive layout that adapts to screen size
- ✅ Touch-friendly map controls
- ✅ Optimized image loading
- ✅ Readable text on all devices
- ✅ Fast loading times

---

## Customization Tips

### Change Colors
Edit the `header` gradient in `index.html`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adjust Map Height
Change the `padding-bottom` percentage in `.map-container`:
- 60% = wide aspect ratio (current)
- 75% = taller map
- 56.25% = 16:9 ratio

### Update Content
- Edit the text in `<section>` tags
- Add your name or organization in the footer
- Update the description in the `<meta>` tag

---

## Troubleshooting

**Site not showing up?**
- Check that GitHub Pages is enabled in Settings
- Ensure files are in the root directory (not a subfolder)
- Wait a few minutes after pushing changes

**Map not displaying?**
- Verify `ACLED_MENA_Map2.html` is in the same folder as `index.html`
- Check the browser console for errors (F12)

**Image not loading?**
- Ensure `density_plot.png` is committed and pushed
- File names are case-sensitive on GitHub Pages

---

## Need to Update the Site?

Just edit the files, commit, and push:
```bash
git add .
git commit -m "Update website content"
git push origin main
```

Changes appear automatically after 1-2 minutes!
