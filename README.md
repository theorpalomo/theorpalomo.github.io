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
| `assets/pse-symbol.png` | Paris School of Economics symbol used as the browser-tab icon |
| `assets/icons.svg` | Institution, email, and CV icons below the portrait |
| `assets/brazil.svg` | Brazil flag in the footer |

This is plain HTML and CSS. It has no package installation, build step, tracking scripts, or external font dependency. The expandable abstract uses a native HTML `details` element, with Figure 10 aligned to the right on wider screens and stacked below on phones. Its title matches the paper: “Effective Tax Rate by Income Groups, All Taxes.” Biography, abstract, and research paragraphs use justified alignment. Presentation lists remain visible.

External website and paper links use `target="_blank" rel="noopener noreferrer"` to open in a new tab. Internal page, section, and CV links stay in the same tab; email links open the visitor's email application.

## Publish

In **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**, then Save. The `.nojekyll` file tells Pages to serve the files directly. Updates to `main` will then publish automatically.

## Update content in your browser

Open the relevant file, click the pencil icon, edit the text, and select **Commit changes**. To review a change before publication, save it on a separate branch and open a pull request. Merge the pull request into `main` when ready to publish. Allow several minutes for GitHub Pages to update.

To replace the CV or photograph, open its folder and choose **Add file → Upload files**, using the existing filename. Check PDF links after an update. Keep only material intended for public access in this repository.

## Local preview

From the repository folder, run `python -m http.server 8000` and open `http://localhost:8000` in your browser.

## Content provenance

The first version migrates the public biography, research descriptions, paper links, figure, and CV from https://sites.google.com/view/theopalomo/. The portrait was supplied directly by Theo. The visual design is original, informed by the academic website examples Theo shared.

Upcoming presentations include FGV-EESP on 14 December 2026 and the PSE Applied Seminar on 16 February 2027; Theo confirmed the latter year. Update the Fall 2026 visiting statement and upcoming presentations after they have passed.

The PSE symbol is the favicon associated with `parisschoolofeconomics.eu`, retrieved via Google's favicon service. The Brazil flag comes from [flag-icons](https://github.com/lipis/flag-icons); its MIT license is included in `assets/flag-icons-LICENSE.txt`.
