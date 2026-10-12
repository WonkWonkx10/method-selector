# Pick Your Lens: AP Research Method Selector (web version 9, Oct 11, 2026)

One file runs the whole site: `index.html`. No build step, no accounts, no student data leaves the browser.

## Put it on GitHub Pages (about 5 minutes)

1. Sign in at github.com and click New repository. Name it `method-selector`. Set it to Public. Click Create repository.
2. On the new repository page click "uploading an existing file". Drag in `index.html`, `.nojekyll` and this `README.md`. Click Commit changes.
3. Open Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main` and folder to `/ (root)`. Click Save.
4. Wait about a minute, then refresh the Pages screen. It shows the address, in the form `https://YOUR-USERNAME.github.io/method-selector/`.
5. Open the address, click Start, and walk one path. Put that link in Canvas.

To update later: upload a new `index.html` over the old one. The address does not change.

## What is inside

- The question path as built in Storyline, minus the doorway screen, removed Oct 11, 2026 (question, little r or Big R gate, the fork, family questions).
- 25 method cards: 15 landing cards, 9 pointer cards and the Document analysis redirect card. Text for 24 is from card docs 28a to 28e, version 2. The Meta-analysis pointer card was added in version 7 from dossier 27d, row 45.
- The instrument check: 70 alignment rows (S4 version 2 table with the voice-pass notes), plus 48 proposed rows (R71 to R120).
- Other methods: 43 second-tier entries (Program evaluation removed in version 6).
- Glossary: 23 terms from the build kit.
- Source lines are always shown (no switch). In version 4 they hold only author, year and page; the filing codes were stripped by script.
- The page tells students the AP sample papers are in Canvas Files, folder "AP Research Sample Papers 2016-2025", and that textbook resources are in Canvas.
- "How to use" page: the tool is a suggestion, what is clickable, where matching papers are, how to justify a method. Start opens it first. From version 9 it shows 12 pictures of real screens from the tool.
- No due dates appear in the student text.

## One switch

Near the top of the script in `index.html`: `var APPLY_PROPOSED_ROWS = true;`
It is ON since version 5: the proposed alignment rows for the pointer cards and Ethnography (R71 to R112) and, from version 7, for Meta-analysis (R113 to R120) are applied. Set it to `false` to go back to the generic caution note for those cards.

## Checked in version 5

- All 23 Read more pages opened (Oct 11, 2026).
- 64 of 69 journal links confirmed and now shown with title, author, year and journal, each marked as a study or an article about the method. Five could not be checked because the site blocked the check; they are labelled on the page.
- The 44 Other methods entries were compared with dossiers 27a to 27f; three wording fixes were made.
- Lesson numbers removed from the cards and glossary.

## Added in version 6

- All 69 original journal links are now identified (the five that were blocked were confirmed through their DOI records).
- Ten cards that had no journal study gained one open-access study each (79 journal links in all); every card now has at least one study that used the method.
- Other methods: Program evaluation removed; the lens entry is now "Critical and feminist approaches".
- The page points students to Canvas Files, folder Textbook Resources.

## Added in version 7

- Meta-analysis is now a pointer card in the Quantitative family (closest landing: Secondary / archival data analysis). Students reach it three ways: a fifth answer on the quantitative question "Where do your numbers come from?", a second button on the "little r" stop screen, and the All cards and Other methods tabs.
- Eight proposed alignment rows for Meta-analysis (R113 to R120): dataset and texts are CAUTION, the other six tools are MISFIT. These were drafted in this session from the dossier definitions and have not been reviewed.
- The stop screen now has a Back button.
- The Lucy example on the Meta-analysis card is new wording, not from a card doc.

## Changed in version 8

- Meta-analysis wording now says it creates new information by combining the measurements other studies reported (card, stop screen and tool-check note). No other change.

## Changed in version 9

- The "How to use" page now shows 12 pictures taken from the tool itself (All cards, a pointer card's buttons, a MISFIT result, the top bar, a question screen, the top and bottom of a method card, the tool check, the summary, See it done, In the AP samples, and a source line). A red outline in a picture marks the thing to click; the outline is not in the real tool.
- Each picture has a light and a dark copy, and the page shows the one that matches the device. The pictures are stored inside `index.html`, so the site is still one file. The file grew from 289,884 bytes to about 1.68 MB.
- The pictures use the Lucy question ("Is daily play time related to obedience scores in pet dogs?") and the Correlational card.
- If a card or screen is reworded later, the pictures will not change by themselves. They have to be taken again.
- Nothing else changed: the question path, the 25 cards, the alignment rows, Other methods and the Glossary are the same as version 8.
