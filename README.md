# Site Inspection – Water Discharge Calculation Form

Single-page web form (HTML/CSS/JS) that:
- takes the Unit Name & Address, machinery counts, and bleaching/printing tank sizes,
- calculates KLD values automatically (same formulas as the Excel sheet),
- on **Final submit** downloads a PDF, with an option to download an Excel file.

## Files
- `index.html` – the complete application (all styling and code are inside this one file)
- `.nojekyll` – tells GitHub Pages to serve the file as-is
- `README.md` – this note

## Run on GitHub Pages
1. Upload these files to the root of a GitHub repository.
2. Go to **Settings -> Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then **Save**.
4. After about a minute the site is live at `https://<username>.github.io/<repository-name>/`.

## Note
The PDF and Excel libraries (jsPDF, jsPDF-AutoTable, SheetJS) load from the cdnjs CDN, so an internet connection is needed for downloads.
