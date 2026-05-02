# Bruce Dean Schulz — Electronic Portfolio

## File Structure

```
portfolio/
├── index.html                  ← Home page
├── CIS_ClassList.html          ← Course syllabi listing
├── projects.html               ← Project showcase
├── styles.css                  ← Shared external stylesheet
├── BruceSchulzResume.pdf       ← YOUR RESUME (add this file)
├── SchulzB_Unit4_Ex2A.html     ← Assignment submission page
├── syllabi/
│   ├── CIS130_Syllabus.pdf     ← Add all syllabus PDFs here
│   ├── CIS131_Syllabus.pdf
│   └── ... (see syllabi/README.txt for full list)
└── projects/
    ├── project1/               ← Add project docs/screenshots here
    └── csharp/
```

## TODO Before Submitting

1. **Resume** — Add `BruceSchulzResume.pdf` to the `portfolio/` root folder
2. **Syllabi** — Add all PDF syllabi to the `syllabi/` folder (see syllabi/README.txt)
3. **Projects** — Update `projects.html` with your actual project descriptions, screenshots, and code samples
4. **Deploy to GitHub Pages**:
   - Push this folder to a GitHub repo (e.g., `portfolio`)
   - Go to repo Settings → Pages → set source to `main` branch / root
   - Your site will be live at: `https://toebyybryant.github.io/portfolio/`
5. **Update submission link** — Open `SchulzB_Unit4_Ex2A.html` and update the `href` with your actual GitHub Pages URL

## Hosting on GitHub Pages (Quick Steps)

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/ToebyyBryant/portfolio.git
git push -u origin main
```

Then enable GitHub Pages in the repo settings.
