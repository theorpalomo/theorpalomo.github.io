# Theo Palomo — academic website

Personal academic website, hosted at https://theorpalomo.github.io/ with GitHub Pages.

## Files

| File | What to edit |
| --- | --- |
| `index.html` | Biography, affiliations, contact information, upcoming presentations |
| `research.html` | Papers, coauthors, abstracts, presentations, and media links |
| `assets/style.css` | Colors, fonts, spacing, and mobile layout |
| `assets/photo.png` | Homepage portrait |
| `files/cv.pdf` | CV; replace this file while keeping its name to preserve the link |
| `assets/tax-progressivity.jpg` | Research figure from the existing website |

This is plain HTML and CSS. It has no package installation, build step, tracking scripts, or external font dependency. Expandable research sections use native HTML `details` elements.

## Publish

In **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**, then Save. The `.nojekyll` file tells Pages to serve the files directly. Updates to `main` will then publish automatically.

## Update content in your browser

Open the relevant file, click the pencil icon, edit the text, and select **Commit changes**. To review a change before publication, save it on a separate branch and open a pull request. Merge the pull request into `main` when ready to publish. Allow several minutes for GitHub Pages to update.

To replace the CV or photograph, open its folder and choose **Add file → Upload files**, using the existing filename. Check PDF links after an update. Keep only material intended for public access in this repository.

## Local preview

From the repository folder, run `python -m http.server 8000` and open `http://localhost:8000` in your browser.

## Content provenance

The first version migrates the public biography, research descriptions, paper links, figure, and CV from https://sites.google.com/view/theopalomo/. The portrait was supplied directly by Theo. The visual design is original, informed by the academic website examples Theo shared.

The existing homepage listed a PSE Applied Seminar on 16 February 2026 under upcoming presentations. That entry is omitted here pending confirmation of its year. The FGV-EESP seminar date is retained as listed. Update the Fall 2026 visiting statement and upcoming presentation after they have passed.
