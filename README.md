# PDF Page Picker

A static web app that extracts chosen pages from a PDF, in any order, into one new PDF. It works on desktop and mobile, and files never leave the browser (uses [pdf-lib](https://pdf-lib.js.org/)).

## How it works
1. Choose or drop a PDF. The app shows its page count.
2. Enter how many pages you want.
3. Enter each page number, then tap **Create PDF**.

## Deploy on GitHub Pages
1. Create a new GitHub repository (e.g. `pdf-page-picker`).
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**, set **Source** to `Deploy from a branch`, choose `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://<your-username>.github.io/pdf-page-picker/`.

Or from the command line:

```bash
git init && git add . && git commit -m "PDF Page Picker"
git branch -M main
git remote add origin https://github.com/<your-username>/pdf-page-picker.git
git push -u origin main
```
