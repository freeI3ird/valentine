# valentine
Valentine Project for my fiancé Nehal Aggarwal

# Valentine's page for Nehal 💕

A small single-page site: “Nehal, will you be my valentine?” with Yes/No buttons, confetti, and your photos.

## Host on GitHub Pages

1. **Create a new repo** on GitHub (e.g. `valentine-nehal`). Do **not** add a README (you already have one).

2. **Add your two photos** in the `images` folder (same size/style so they feel in sequence):
   - `images/start.jpg` — starting photo (question page)
   - `images/both.gif` — photo or GIF after she clicks “Yes”  
   You can use `.jpg`, `.jpeg`, `.png`, or `.gif` for either. If you use different names (e.g. `start.gif`, `both.jpg`), update the `src` in `index.html` to match.

3. **Push the project** to GitHub:
   ```bash
   cd /path/to/valentine-project
   git init
   git add .
   git commit -m "Valentine page for Nehal"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/valentine-nehal.git
   git push -u origin main
   ```

4. **Turn on GitHub Pages**
   - Repo → **Settings** → **Pages**
   - Under **Source**, choose **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → Save

5. **Open the site** at:  
   `https://YOUR_USERNAME.github.io/valentine-nehal/`

Images will load only after you add `start.jpg` and `both.gif` (or your chosen names) to the `images` folder and push.
