Gourav Kumar Bathwal — Portfolio

Files:
- index.html — static portfolio page
- styles.css — styling
- Gourav_Bathwal_Resume_WithPortfolio.pdf — your resume (copy)
- Gourav_Bathwal_Resume_WithPortfolio.txt — plain text resume
- .github/workflows/deploy.yml — GitHub Pages deployment workflow
- .nojekyll — disables Jekyll processing on GitHub Pages

## Quick Start

### Local Preview
Open `index.html` in a browser to preview the site locally.

### Deploy to GitHub Pages

1. Create a new public repository named `gourav-portfolio` on GitHub (or any name you prefer).

2. Initialize Git in this folder and push:
```bash
cd C:\Users\goura\Downloads\gourav-portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/gourav-portfolio.git
git push -u origin main
```

3. Configure GitHub Pages:
   - Go to your repository settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch and `/ (root)` folder
   - Save

4. The site will be live at `https://YOUR_USERNAME.github.io/gourav-portfolio` once the workflow completes.

Update the portfolio link in your resume after deployment: replace `https://example.com/gourav-portfolio` with your actual GitHub Pages URL.

