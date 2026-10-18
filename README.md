# Visual Learning Group @UoB

A responsive, static group website for Visual Learning Group @UoB intended for GitHub Pages. It uses plain HTML, CSS and JavaScript; no build step or package installation is required.

## Preview locally

Open `index.html` in a browser, or run a small local server from this directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Add the published URL as a custom domain only if the group has arranged one.

## Updating content

- Edit `people` and `publications` in `data.js`.
- Add a person only after confirming their current role and group membership. The six people categories are prepared in the interface; currently unverified categories stay empty.
- For portraits, add a `photo` URL to the relevant person record in `data.js`. The interface falls back to initials if an image cannot load. Current portraits are loaded from University of Birmingham staff pages; confirm image reuse terms before redistributing copies.
- Add news and openings in `index.html` as updates are confirmed; the current opening section directs prospective members to verified researcher profile pages.

## Content scope

The faculty roster contains the supplied academic staff plus honorary faculty; Jian Liu’s lab directory also provides current research fellows, PhD students and alumni: [Jian Liu Lab people](https://sites.google.com/site/jiankliu/people). Public staff pages confirm current academic roles for several profiles; where the supplied page did not clearly establish a current University title, the card points readers to that profile without guessing. The publication archive aggregates 421 linkable records across 1997–2026 from faculty and honorary faculty public publication lists, research profiles, and Google Scholar records. Coverage varies because source pages differ in scope and update frequency; follow each researcher’s profile for their authoritative full bibliography, and check records before publishing corrections or new additions. Entries are grouped by year and sorted by venue within each year.

## University brand

The palette follows Birmingham’s official digital primary colours: black `#1B1B1B`, white `#FAFAFA` and gold `#C59A00`. Body text uses Manrope. Headings use Larken if licensed and available, with Georgia as a local fallback; the licensed University font has not been redistributed. The group mark is a separate geometric motif and does not imitate or replace the University crest/wordmark lockup. See the [University brand portal](https://brand.birmingham.ac.uk/) for the official assets and usage rules.

The header uses the official positive University logo lockup supplied by the Brand Portal. The opening visual uses the University’s own Edgbaston campus aerial image featuring Old Joe; both are linked to their institutional source URLs and include descriptive alternative text.
