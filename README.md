# The Constitution: Constitutional Analysis

Students **choose one** of three ways to complete the Constitutional Analysis assignment. All three ask for the same thinking, and students turn in one file on Google Classroom.

| Option | What it is | Students submit |
|---|---|---|
| 1. 3D game, two looks (`blocky-3d/`, `storybook-third-person/`) | Walk Philadelphia in 1787, hear the Convention debates, climb parkour trials to the Article scrolls, then follow the amendments through the Hall of Echoes. Block-world and storybook (Wind Waker style) both use a camera behind the player. Needs WebGL. | Essay PDF from the game |
| 2. Pixel-art game (`pixel-art/`) | The same story as a top-down walkable game. Runs on almost any device, including phones. | Essay PDF from the game |
| 3. Written assignment (`text-assignment/`) | **The original Word document, unchanged.** | The completed document |

Students start at `index.html`, which explains the options and how to turn the work in.

## The original assignment is preserved

`text-assignment/Primary Source_ Constitutional Analysis.docx` is a byte-for-byte copy of the document you provided. SHA-256: `0d8992a45de39044959960ffdda6e26ba1f0a5e779a9da1f1b4a61327f66fa92`. The games reproduce its questions exactly: for each Article, the branch(es), primary powers, primary limitations and other structural information; for each Amendment, the freedoms protected, provided or taken away, and the era and context.

## How the games map to the assignment

* **Convention scenes (chapters 0 to 5):** Madison greets you outside. The debates then move **indoors** to the Assembly Room of the State House, where Washington presides from the dais and Randolph, Sherman, Morris and Mason sit among the delegates' tables. A rider with news of Shays' Rebellion meets you outside. Together the scenes explain why the Articles of Confederation failed, the Virginia Plan, the Great Compromise, and the Committee of Style. Each scene has a primary source, a "lawyer's lens" idea and a check question.
* **Seven Article scrolls:** one per Article. Each gives the debate behind it, a text excerpt, a legal-lens concept, check questions, and a writing box with the four assignment questions (minimum 40 words).
* **Signing and ratification (chapters 6 to 9):** Franklin's closing speech and the signing, George Mason's refusal and the demand for a bill of rights, the Federalist and Anti-Federalist pamphlet fight, and Madison's 1789 proposals.
* **Hall of Echoes:** eight guides (Mercy Otis Warren, Ruth Bader Ginsburg, John Marshall, Frederick Douglass, Alice Paul, Franklin D. Roosevelt, Martin Luther King Jr., and the older James Madison) lead through all 27 Amendments in order. Each gets the history, the text, a legal-lens concept, a check question, and a writing box with the two assignment questions (minimum 20 words).
* **Final reflection:** a legal-lens reflection at the monument (minimum 100 words).
* **Essay PDF:** name and date, the title "Constitutional Analysis", Part 1 (Articles 1 to 7), Part 2 (Amendments 1 to 27), the reflection, and a one-line game record with a completion code.

## Keyboard-only play

Every game can be played without a mouse. In dialogue: arrow keys (or W A S D) move between answers and buttons; E, Z or Enter selects; number keys jump to an answer; Ctrl+Enter saves what you are writing. Esc opens the satchel, where Left/Right (or 1 to 6) switch tabs.

## For the teacher: please review before use

All historical narration, quotations, dates, and check questions were written for this project and should be reviewed for accuracy. Items worth a second look:

* The Great Compromise vote (five states to four), thirty-nine signers and three refusals (Randolph, Mason, Gerry), Delaware ratifying first on December 7, 1787, and New Hampshire as the ninth state.
* Madison's notes being published in 1840, and Franklin's speech being read by James Wilson.
* Amendment details: Chisholm v. Georgia (11th), the 1800 tie and 36 House ballots (12th), the Pollock decision (16th), the 100-day ratification of the 26th, the 202 years and Gregory Watson's story for the 27th.
* Excerpts of Amendments 5, 6, 12, 14, 23 and 25 are shortened with ellipses.
* Morris's reading of the Preamble and the first sentence of each Article is labeled a dramatized reading.

The games require about 34 written answers, so plan several class periods.

## Hosting on GitHub Pages

1. Create a repository and upload the contents of this folder (keep `index.html` at the top level).
2. Settings, Pages, deploy from the main branch, root folder.
3. The three games and the written assignment are linked from `index.html`. Each game saves progress in the student's own browser.

Libraries (`lib/three.min.js`, `lib/jspdf.umd.min.js`) are bundled locally with a CDN fallback.
