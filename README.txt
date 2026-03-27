Trail Guide — GitHub Pages Package

This package is prepared for deployment to GitHub Pages.

What is included:
- index.html
- manifest.json
- sw.js
- icons/
- .nojekyll

Recommended deployment:
1. Create a GitHub repository
2. Upload the contents of this folder to the repository root
3. In GitHub:
   - go to Settings > Pages
   - set Source to 'Deploy from a branch'
   - choose your main branch
   - choose the /(root) folder
4. Wait for Pages to publish

Important notes:
- The app is set up with relative paths, so it should work on a project Pages URL
  such as https://USERNAME.github.io/REPOSITORY/
- After updating the app, GitHub Pages and service worker caching may briefly keep an older version.
  If that happens, refresh twice or clear the site data for the page.

Optional:
- If you use a custom domain later, this package should still work.

