# Student Setup Guide — MMI5192E

Follow these steps to turn this template into your own personal website,
hosted for free on GitHub Pages.

## 1. Create your own copy

1. Go to <https://github.com/DrLuarn/DrLuarn.github.io>.
2. Click the green **"Use this template"** button → **"Create a new
   repository"**.
   - This gives you a brand-new, independent repo with no connection back to
     the instructor's repo — nothing you do here can ever affect it.
3. Owner: your own GitHub account.
4. Repository name: **exactly** `your-username.github.io` (replace
   `your-username` with your actual GitHub username). This exact name is
   required for GitHub Pages to serve it at the root of your own domain.
5. Visibility: **Public**.
6. Click **Create repository**.

## 2. Turn on GitHub Pages

1. In your new repo, go to **Settings → Pages**.
2. Under "Build and deployment", set **Source** to **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. After a minute or two, your site will be live at
   `https://your-username.github.io/`.

## 3. Make it your own

Edit these files directly on GitHub (or clone the repo locally and push your
changes) — see the main [README.md](README.md) for what every file does.

1. **`profile.txt`** — replace every value with your own name, titles,
   education, email, LinkedIn, About Me text, phone, and location.
2. **`mypic.jpg`** — replace with your own photo (keep the same filename).
3. For each unit you complete, add your screenshot(s) to **`pic/`** as
   `unit{N}_1.jpg`, `unit{N}_2.jpg`, … (any of `.jpg/.JPG/.jpeg/.JPEG/.png/.PNG`
   work), and optionally add a matching **`URL/URL{N}_{i}.txt`** with a
   caption and a demo link.
4. Commit and push your changes — GitHub Pages updates automatically within
   a minute or two.

**Do not edit** `projects.txt`, `index.html`, `student.html`, `unit.html`, or
`style.css` — the unit list is pulled live from the instructor's site, and the
pages already work correctly once `profile.txt` is filled in.

## 4. Join the class directory

Submit your student ID and your new site's URL
(`https://your-username.github.io/`) through the Google Form linked from the
**Student Portfolio** button on the home page (or directly from
`student.html`), so you show up in the class directory.

## 5. Getting a fix Prof. Luarn makes later

Occasionally Prof. Luarn will update one of the **shared** files in the
course site — `index.html`, `style.css`, `unit.html`, or `student.html`. If
you already created your site before such an update, it won't reach you
automatically. Since these files never contain your personal content (that
all lives in `profile.txt`, `mypic.jpg`, `pic/`, `URL/`, and `p1/`, which
you'll keep either way), it's always safe to just replace them with the
latest version.

**If Prof. Luarn sends you the updated file directly** (e.g. a new
`index.html`), this is the simplest way to apply it — no git needed:

1. Open your own repo on GitHub (`https://github.com/your-username/your-username.github.io`).
2. Click **"Add file" → "Upload files"**.
3. Drag in the file you were sent, keeping the **exact same filename**
   (e.g. `index.html`). GitHub will overwrite the existing file with that name.
4. Scroll down and click **"Commit changes"**.
5. Your GitHub Pages site updates automatically within a minute or two.

**If you'd rather grab the latest version yourself**, no git needed either:

1. Open the file on the instructor's repo, e.g.
   <https://github.com/DrLuarn/DrLuarn.github.io/blob/main/index.html>.
2. Click the **Raw** button, select all the text, and copy it.
3. Open the same file in **your own** repo on GitHub, click the pencil
   (✏️ Edit) icon.
4. Select all the existing content, paste in what you copied, and click
   **Commit changes**.
5. Your GitHub Pages site updates automatically within a minute or two.

**If you're comfortable with git/terminal**, this does the same thing for
`index.html` in one step (run it inside your cloned repo folder):

```bash
curl -o index.html https://raw.githubusercontent.com/DrLuarn/DrLuarn.github.io/main/index.html
git add index.html
git commit -m "Update index.html from course template"
git push
```

Swap `index.html` for `style.css`, `unit.html`, or `student.html` to update
any of those the same way.

---

Questions or stuck on a step? Ask in class or reach out to Prof. Luarn.
