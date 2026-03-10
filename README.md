# Anaya's Personal Website

Purple-themed personal site with butterfly favicon, dark/light mode, scroll navigation, and floating side art.

## 📁 Files

```
index.html        ← Homepage (scrollable sections + icon grid)
shared.css        ← Shared styles + dark mode vars
about.html        ← About Anaya
projects.html     ← Projects
now.html          ← /now page (Spring 2026)
blog.html         ← Writing / blog
interests.html    ← Interests
reading.html      ← Reading list
contact.html      ← Contact & links
```

## 🚀 Deploying to GitHub Pages

1. Create a repo named: `yourusername.github.io`
2. Upload all files to the root of the repo
3. Go to **Settings → Pages → Deploy from branch → main → / (root)**
4. Live at `https://yourusername.github.io` within ~1 min

## ✏️ What to update

- Replace `anaya@wisc.edu` with your real email in `contact.html`
- Replace `@yourusername` / `@yourhandle` with your real handles in `contact.html`
- Fill in project details in `projects.html`
- Add real reading list entries in `reading.html`
- Fill in `now.html` with your actual Spring 2026 courses and current projects
- Add blog posts as new `.html` files using the same nav/shared.css pattern

## 🎨 Theming

Colors are CSS vars at the top of `shared.css`. Both light and dark themes are defined there. The dark mode preference is saved to `localStorage` so it persists across page loads.

## 🦋 Favicon

The butterfly SVG favicon is inline in the `<link rel="icon">` tag in each HTML file — no external file needed.
