# FAIR Self-Assessment Checklist

An interactive, single-page checklist for assessing one research object (a dataset, workflow, software repository, or protocol) against the 15 [FAIR Guiding Principles](https://www.go-fair.org/fair-principles/). Wherever you answer **Partly** or **No**, the page opens a concrete fix and points you to the right resource.

Built as the take-home companion to the **FAIR by Design** workshop (KIDS26, St. Jude Children's Research Hospital).

**Live version:** https://YOUR-USERNAME.github.io/fair-self-assessment-checklist/

## What it does

- **Walks through all 15 principles** (Findable, Accessible, Interoperable, Reusable) as cards, with Yes / Partly / No answers and an evidence line for each.
- **Shows fixes on demand.** Guidance unfolds only when an answer is Partly or No.
- **Optional folder scan.** Drop a folder or files from your own work and the page looks for the files a FAIR package normally has (README, metadata, data dictionary, license, provenance, scripts), then suggests an answer and the evidence file for each principle. You confirm every answer.
- **Live score** by dimension (Yes out of 15).
- **"My first fix" plan:** pick the principle to fix first, the one improvement, who can help, a target date, a completion test, and a re-assessment date.
- **Resource directory** covering repositories, registries, and standards used in the workshop, with how to use each and what to watch out for.
- **Copy my results** to paste into a note or email.
- **Light and dark themes**, and print styles.

## Using it

Open `index.html` in any modern browser. There is nothing to install or build.

## Privacy

The page has no server and sends nothing anywhere.

- Scanned files are read inside your browser only.
- Answers are saved in your browser's `localStorage` on that device. Use **Copy my results** before closing the tab or switching devices.
- **Do not scan identifiable patient or participant data.** Use a de-identified sample, or skip the scan and answer the questions yourself.
- Zip files are not opened (unzip first). PDF and Word files are recognized by file name only.

## How the checklist is meant to be used

1. Choose **one** research object to assess.
2. Answer **Yes** only if you can point to a file or URL as evidence, and note it in the evidence line.
3. Never invent a DOI, license, unit, or clinical definition. Write "unknown, requires clarification".
4. Remember that **Accessible does not mean open**. Controlled access can be fully FAIR.
5. Start with the cheapest fix (a README, data dictionary, license statement, or recorded software versions), then re-run the checklist.

## Repository contents

| File | Purpose |
|---|---|
| `index.html` | The complete app: HTML, CSS, JavaScript, and embedded graphics in a single file |
| `README.md` | This file |

The file is large (about 2.4 MB) because the workshop graphics are embedded as base64 images so the checklist works offline as one portable file.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/fair-self-assessment-checklist/`.

## Sources and attribution

- FAIR by Design workshop site: https://doraaobodo.github.io/fair-by-design/
- Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data* 3, 160018 (2016). https://doi.org/10.1038/sdata.2016.18
- The "how to use" notes in the resource directory also draw on each resource's own documentation (Zenodo, Dryad, GO FAIR, and others), as cited in the page footer.

## License

TODO: choose a license before making the repository public.

- Code: e.g. MIT.
- Text and graphics: e.g. CC BY 4.0. Confirm the license and attribution terms of the workshop materials and the embedded graphics before choosing.

## Contributing

Issues and pull requests are welcome. Because `index.html` embeds large images, please describe changes in the pull request so reviewers don't have to diff the base64 data.

## Citation

If you use or adapt this checklist, please cite the FAIR by Design workshop and the FAIR Guiding Principles paper above. A `CITATION.cff` can be added once the authors and license are settled.
