# Rajaguruprasath Raveendran – Personal GitHub Pages Site

Clean, modern, single-page academic/professional portfolio website.

**Live site will be available at:**  
`https://YOUR_GITHUB_USERNAME.github.io`

---

## How to Deploy (5–10 minutes)

### 1. Create the repository
1. Log in to [GitHub](https://github.com).
2. Click **New repository**.
3. Repository name **must be exactly**:  
   `YOUR_GITHUB_USERNAME.github.io`  
   (replace `YOUR_GITHUB_USERNAME` with your actual GitHub username).
4. Set visibility to **Public**.
5. Do **not** initialize with a README (we already have one).
6. Click **Create repository**.

### 2. Upload the files
**Option A – GitHub web interface (easiest)**
1. On the new empty repository page, click **uploading an existing file**.
2. Drag and drop (or select) the two files:
   - `index.html`
   - `README.md`
3. Commit the changes.

**Option B – Git command line**
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
cd YOUR_GITHUB_USERNAME.github.io
# Copy index.html and README.md into this folder
git add .
git commit -m "Initial portfolio site"
git push origin main
```

### 3. Enable GitHub Pages
1. Go to the repository → **Settings** → **Pages** (left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Branch: `main` (or `master`), folder: `/ (root)`.
4. Click **Save**.

After 1–2 minutes your site will be live at:  
**https://YOUR_GITHUB_USERNAME.github.io**

---

## Customization Tips

- Edit `index.html` directly (all content is in one file).
- Change colors: search for `primary-` classes or edit the Tailwind config at the top.
- Add a photo: place an image in the same folder and update the Hero section.
- Add more publications or sections as needed.

---

## Contact links included
- Email: raja.guruprasath@gmail.com
- LinkedIn: https://www.linkedin.com/in/rajaguruprasath-raveendran-228135a/
- ORCID: https://orcid.org/0000-0003-4251-0511
- Google Scholar: https://scholar.google.com/citations?user=2udv9CYAAAAJ&hl=en

---

Built with plain HTML + Tailwind CSS (CDN). No build step required.
