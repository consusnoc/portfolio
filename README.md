# Consuelo Romano — Portfolio

Personal portfolio of Consuelo Romano, product designer focused on accessibility and complex enterprise products.

A static site: plain HTML and CSS with a little JavaScript, no build step.

## What's here

| Path | What it is |
|---|---|
| `index.html` | The whole site: home, two case studies (Log this Place, Haccess), About and writing |
| `images/` | Case study and About images |
| `cv.pdf` | The CV, opened from the site menu |
| `cv-source.html` | Editable source of the CV; print it to PDF (A4, no margins) to update `cv.pdf` |
| `design-system/index.html` | The design system: layout, spacing, type, color, components and rules |
| `LogoC.svg` | Logo mark |

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Adding a writing post

In `index.html`, copy one `<article id="note-…">` block, give it a new id starting with `note-`, and add a matching row to the Writing list on the home page.
