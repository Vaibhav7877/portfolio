# Vaibhav Paliwal — Portfolio

Personal portfolio website for Vaibhav Paliwal, Software Test Engineer (ETL & QA).

A single-page, responsive site built with plain HTML and CSS (no build step, no dependencies).

## Structure

- `index.html` — the entire site (styles are inline in the `<head>`)
- `Vaibhav-Paliwal-Resume.pdf` — resume file for the "Download Resume" button (add this yourself)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## View locally

Just open `index.html` in any web browser.

## Deploy on GitHub Pages

1. Create a new **public** repository on GitHub (e.g. `portfolio`).
2. From this folder, run:

   ```bash
   git remote add origin https://github.com/Vaibhav7877/portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/ (root)**, then **Save**.
6. After a minute, your site will be live at:

   `https://vaibhav7877.github.io/portfolio/`

## Update the site

Edit `index.html`, then:

```bash
git add .
git commit -m "Update portfolio"
git push
```
