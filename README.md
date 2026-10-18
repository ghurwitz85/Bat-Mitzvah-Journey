# My Bat Mitzvah Journey

A lightweight, mobile-friendly Hebrew and bat mitzvah preparation companion for two learners. Built as a static site, so it can be hosted on GitHub Pages without a server or build step.

## Features

- Separate profiles for Ella (older learner) and Margot (younger learner). Exact birthdays are intentionally not embedded in the public app source.
- Separate browser-local progress, notes, reading assignments, ceremony dates, and checklist state for each learner.
- Adaptive practice guidance with Starter, Builder, and Reader levels; each daughter has a different suggested starting level, which can be changed at any time.
- Hebrew vocabulary flashcards and quizzes, Torah portion lookup links, Torah reflection prompts, d’var Torah outline, service vocabulary, and practice checklist.
- No accounts, analytics, or backend. Progress is stored in the browser on the current device; it does not sync across devices.

## Run locally

Open `index.html` in a browser. No build tools are required.

## Publish with GitHub Pages

1. Create a new GitHub repository named `Bat-Mitzvah-Journey` under `ghurwitz85`.
2. Upload the contents of this folder to the repository root (make sure `index.html` is at the root).
3. In **Settings → Pages**, select **GitHub Actions** as the build and deployment source, or use the included workflow.
4. After the first successful deployment, the project site will be at `https://ghurwitz85.github.io/Bat-Mitzvah-Journey/`.

The included workflow publishes the static site on pushes to `main`. GitHub Pages sites are public by default, so don't add private family details beyond what you are comfortable making public. The app source avoids publishing the children’s exact birthdays. The profile names are first names only; use a private repository if you want to keep the source code private, and remember that GitHub Pages websites are public by default on most plans.

## Important educational note

This is a learning aid, not a substitute for the family's rabbi, cantor, Hebrew teacher, or tutor. The service date, assigned aliyah/verses, Haftarah, reading tradition, and trope melody must be confirmed with the congregation. The current portion finder opens a reference resource; it does not yet automatically calculate or verify the exact assigned passage.
