# Ethical Hacker Final Trainer

A standalone, mobile-friendly study companion for Cisco Networking Academy Ethical Hacker topics.

- 35 original multiple-choice practice questions, including command questions
- Flashcards in four sets: 10 + 10 + 10 + 5
- Known / need-review ratings, shuffle, and review filtering
- Full or per-set quizzes, explanations, scoring, and retrying mistakes
- Searchable reference with 30 command examples
- Browser-local progress storage, with an in-memory fallback when storage is unavailable
- English interface; no external scripts, fonts, or other runtime dependencies

## Use offline

Download `index.html` and open it in a browser with JavaScript enabled. Some mobile file-manager previews do not run JavaScript; open the file in a compatible browser instead.

## GitHub Pages

Choose **Settings → Pages → Deploy from a branch**, then select the `main` branch and the repository root (`/`).

## Verification

The standalone file was tested in Chrome with networking disabled, at widths of 320, 375, 390, 768, and 1440 pixels, plus a landscape viewport. Tests covered every flashcard, all quiz sets, perfect/zero/mixed scores, mistake retry, reload persistence, corrupted or blocked storage, and command search. There were no JavaScript page errors or HTTP requests. Mobile checks used touch and viewport emulation, not physical devices.

## Content

Questions are independently written practice material mapped to NetAcad course topics, not official Cisco exam questions or a prediction of the final exam. Topic and command references are linked inside the trainer. Commands are displayed as study text and are never executed by this page.
