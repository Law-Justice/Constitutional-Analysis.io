# The Constitution: Constitutional Analysis

Students **choose one** of three ways to complete the Constitutional Analysis assignment. All three ask for the same thinking, and students turn in one file on Google Classroom.

| Option | What it is | Students submit |
|---|---|---|
| 1. 3D game, two looks (`blocky-3d/`, `storybook-third-person/`) | Walk Philadelphia in 1787, hear the Convention debates, climb parkour trials to the Article scrolls, then travel through eight scenes from 1791 to 1992 for the amendments. Block-world and storybook (Wind Waker style) both use a camera behind the player. Needs WebGL. | Essay (Word document) from the game |
| 2. Pixel-art game (`pixel-art/`) | The same story as a top-down walkable game. Runs on almost any device, including phones. | Essay (Word document) from the game |
| 3. Written assignment (`text-assignment/`) | **The original Word document, unchanged.** | The completed document |

Students start at `index.html`, which explains the options and how to turn the work in.

## The original assignment is preserved

`text-assignment/Primary Source_ Constitutional Analysis.docx` is a byte-for-byte copy of the document you provided. SHA-256: `0d8992a45de39044959960ffdda6e26ba1f0a5e779a9da1f1b4a61327f66fa92`. The games reproduce its questions exactly: for each Article, the branch(es), primary powers, primary limitations and other structural information; for each Amendment, the freedoms protected, provided or taken away, and the era and context.

## How the games map to the assignment

* **Convention scenes (chapters 0 to 5):** Madison greets you outside. The debates then move **indoors** to the Assembly Room of the State House, where Washington presides from the dais and Randolph, Sherman, Morris and Mason sit among the delegates' tables. A rider with news of Shays' Rebellion meets you outside. Together the scenes explain why the Articles of Confederation failed, the Virginia Plan, the Great Compromise, and the Committee of Style. Each scene has a primary source, a "lawyer's lens" idea and a check question.
* **Seven Article scrolls:** one per Article. Each gives the debate behind it, a text excerpt, a legal-lens concept, check questions, and a writing box with the four assignment questions (minimum 40 words).
* **Signing and ratification (chapters 6 to 9):** Franklin's closing speech and the signing, George Mason's refusal and the demand for a bill of rights, the Federalist and Anti-Federalist pamphlet fight, and Madison's 1789 proposals.
* **Eight scenes through time.** After the signing, every era is its own place with its own look, weather, set dressing, and cast, announced by a title card with the year and setting. Each amendment gets a story beat, a **“How we got here” timeline of dated events**, the text, a legal-lens concept, a check question, and a writing box with the two assignment questions (minimum 20 words).
  * Part 2, The Bill of Rights, 1791 (Amendments I–X): snowbound Philadelphia. Guides: James Madison, Mercy Otis Warren, George Mason.
  * Part 3, The Early Republic, 1795–1804 (XI–XII): half-built Washington City. Guides: John Marshall, Thomas Jefferson.
  * Part 4, War and Reconstruction, 1865–1870 (XIII–XV): ash, mud, and tents. Guides: Frederick Douglass, Thaddeus Stevens, Hiram Revels.
  * Part 5, The Progressive Era, 1913–1920 (XVI–XIX): cars, telephone poles, and suffrage banners. Guides: Robert La Follette, Wayne B. Wheeler, Alice Paul.
  * Part 6, Depression, War, and the Two-Term Limit, 1933–1951 (XX–XXII): a gray breadline. Guides: Franklin D. Roosevelt, Pauline Sabin, Harry Truman.
  * Part 7, The Civil Rights Era, 1961–1971 (XXIII–XXVI): television and picket signs. Guides: Martin Luther King Jr., Birch Bayh.
  * Part 8, A Student Revives an Amendment, 1982–1992 (XXVII): a Texas campus. Guide: Gregory Watson.
  * Epilogue, Constitution Day: the Hall of Echoes opens for the final reflection.
* **Final reflection:** a legal-lens reflection at the monument (minimum 100 words).
* **Essay document (.docx):** name and date, the title "Constitutional Analysis", Part 1 (Articles 1 to 7), Part 2 (Amendments 1 to 27), the reflection, and a one-line game record with a completion code.

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

Libraries (`lib/three.min.js`, `lib/jspdf.umd.min.js`) are bundled locally with a CDN fallback. The essay Word document is built by the game itself and needs no library (the PDF library is no longer used).

## Teacher review: the new timelines and guides

The dated “How we got here” events for all 27 amendments, the guides’ introductions, and the crowd characters’ lines were written by the game’s author, not taken from a source. Please spot-check them before use, in particular: the Georgia bill threatening death over *Chisholm v. Georgia* (Amendment XI), the 36 ballots in the 1801 House election (XII), the Memphis and New Orleans riots of 1866 (XIV), Delaware’s empty Senate seat (XVII), Pauline Sabin’s role in repeal (XXI), and the dates for Gregory Watson’s paper and the 1992 ratification (XXVII). The guides appear through narration rather than invented direct quotations. The crowd characters are fictional composites and their lines are illustrative.
