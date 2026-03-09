# Personal Website

A personal website built with HTML, CSS, and vanilla JS. No frameworks, no build steps — just files.

## 📁 File Structure

```
index.html        ← Homepage with navigation grid
shared.css        ← Shared styles for all inner pages
about.html        ← About me
projects.html     ← Projects
now.html          ← What I'm up to (/now page)
blog.html         ← Writing / blog
interests.html    ← Interests
reading.html      ← Reading list
contact.html      ← Contact & links
```

## 🚀 Deploying to GitHub Pages

1. **Create a new GitHub repo** named exactly: `yourusername.github.io`
   (replace `yourusername` with your actual GitHub username)

2. **Upload all these files** to the root of the repo:
   - Drag & drop into GitHub's web interface, OR
   - `git init`, `git add .`, `git commit -m "initial"`, `git remote add origin ...`, `git push`

3. **Enable GitHub Pages** (it may already be on for `username.github.io` repos):
   - Go to the repo → Settings → Pages
   - Source: Deploy from branch → `main` → `/ (root)`
   - Click Save

4. **Your site goes live** at `https://yourusername.github.io` within ~1 minute.

## ✏️ Customizing

### Change your name
Search for `Your Name` across all files and replace with your actual name.

### Update the tagline & tags
In `index.html`, update the `.tagline` text and `.tag` spans.

### Fill in the content
Each page has placeholder text in the format:
- **Bold**: what to replace
- Italics or quotes: hints on what to write

### Add your real links
In `contact.html`, update:
- `youremail@wisc.edu`
- GitHub, LinkedIn, Twitter handles
- Link `resume.pdf` to your actual resume (add the PDF to the repo root)

### Update the /now page
The `/now page` should be updated whenever something changes — new semester, new project, new obsession. It's meant to be a living document.

### Add real blog posts
For each post, create a new HTML file (e.g. `post-ai-safety.html`) using the same nav + shared.css pattern, then link to it from `blog.html`.

## 🎨 Colors

All colors are CSS variables defined at the top of `shared.css`:

```css
--plum:     #3b1f5e   ← dark purple, headings
--violet:   #6b3fa0   ← medium purple, accents
--lavender: #a67fd4   ← light purple, subtle text
--lilac:    #d8c4f0   ← very light purple, borders
--cream:    #fdf9ff   ← background
--ink:      #1e0f33   ← body text
```

Adjust any of these to tweak the whole site at once.
