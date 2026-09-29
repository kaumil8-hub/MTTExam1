# MTT Exam 1 Study Studio

A self-contained study app based on three supplied Fall 2026 MTT lecture decks.

- 400 original practice questions: 65 translation/dental technology, 168 biomarkers, 167 gene therapy/CRISPR.
- 25 study-note sections with PDF page references.
- Practice and exam modes, shuffled questions and answer options, balanced mixed sets.
- Answer explanations, missed-question review, and progress saved in the current browser.
- Keyboard: A/S/D/F or 1/2/3/4 to select; Enter to check or continue when a button is not focused.

Open `index.html` locally, or visit the repository's GitHub Pages site. No build tools or external scripts are required.

## Scope

All 70 pages of Lecture 1, 54 pages of Lecture 2, and 56 pages of the third supplied lecture are covered. The third source file is labeled “Lecture 5 Crispr and gene therapy and dentistry v1 2026.pdf” but is labeled Lecture 3 in the app at the student's request. Follow any narrower cutoff set by the instructor.

These are original study questions, not an official exam or a prediction of its contents. The app's Scope & clarifications page separates inconsistent or dated slide wording from the scored material. Original slide PDFs are not republished.

## Verification

Checked unique question stems, answer-option integrity, source-page bounds, sampling without repeats, shuffled answer-key mapping, practice/exam scoring, unanswered items, duplicate-check prevention, missed-bank updates, and saved session state. Browser interaction checks are performed on the deployed page.

## Storage

Progress stays in localStorage in the current browser. It does not sync between devices. Resetting progress asks for confirmation. Clearing browser data removes progress.

## Expanded question bank and exam mode

400 questions: 65 for Lecture 1, 168 for Lecture 2, and 167 for Lecture 3. The new-recall filter isolates the latest 100 direct-recall additions (15 / 43 / 42). The 50-question exam always samples 10 / 20 / 20 by lecture, shuffles questions and choices, and reveals explanations after submission.
