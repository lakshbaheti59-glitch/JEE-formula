# JEE Formula Atlas

This folder is the complete GitHub Pages edition of the JEE Formula Atlas. It is deliberately flat: there are no source, asset, dependency, or build folders to upload.

## Files

- `index.html` — Trigonometry atlas and the website home page
- `quadratic.html` — Quadratic Equations atlas
- `.nojekyll` — tells GitHub Pages to publish the files exactly as supplied

Both HTML files are self-contained. Their styles, fonts, formula data, KaTeX rendering and application code are embedded inside the files.

## Upload everything in one operation

1. Create an empty GitHub repository.
2. On its main page, choose **Add file → Upload files**.
3. Open this `JEE-Formula-Atlas-GitHub-Ready` folder on your computer.
4. Select everything in this folder together and drag it onto GitHub's upload page.
5. Commit the upload to the `main` branch.
6. Open **Settings → Pages** in the repository.
7. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

GitHub will provide the public website address after deployment. The Trigonometry and Quadratic Equations pages link to one another automatically, including when the repository is hosted under a GitHub Pages subpath.

## Local use

Double-click `index.html` or `quadratic.html`. No installation, terminal, web server or internet connection is required.
