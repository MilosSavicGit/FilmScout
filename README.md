# FilmScout v1.0

By Miloš Savić · ScoutPlatform

Film discovery focused on Italy, France, Spain and smaller European cinematographies, recognised world cinema and US independent films. Styling follows MusicScout.

## Included

- Current cinema and country sections, with regional/festival selectors.
- Festival and national award sources.
- Critics’ Choices: selected films from the Guardian, Sight and Sound, Film Comment, Screen Slate, The Film Stage and MUBI Notebook; Criterion retrospective discovery.
- A dedicated Best documentaries page.
- A Fellini retrospective, the author’s personal introduction, and chronological directed works from 1950 to 1990.
- Other director retrospectives and themed collections available through the retrospective archive.
- Back navigation and external source/YouTube search links opening in new tabs.

## Run locally

Open `index.html` in a modern browser. No build, package installation, API key or backend is required.

## Upload using GitHub’s website

1. Create a repository named `FilmScout` in your GitHub account.
2. Extract the ZIP on your computer.
3. Use **Add file → Upload files** and upload the extracted files to the repository root. Upload `index.html`, not the ZIP itself. If Windows hides `.gitignore` or `.nojekyll`, create them using **Add file → Create new file** and copy their contents (leave `.nojekyll` empty).
4. Commit the upload to `main` with the message `FilmScout v1.0`.
5. To publish, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
6. Use the published URL shown by GitHub Pages. For a repository named `FilmScout` under `MilosSavicGit`, the default project URL is `https://milossavicgit.github.io/FilmScout/`.
7. Optionally create a release tagged `v1.0.0` to mark this baseline.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Optional command-line upload

Run these commands from the extracted folder after creating an empty GitHub repository:

```sh
git init
git add .
git commit -m "FilmScout v1.0"
git branch -M main
git remote add origin https://github.com/MilosSavicGit/FilmScout.git
git push -u origin main
```

## Updating content

All styles, data and behaviour are inside `index.html`:

- `films`: current cinema and award entries.
- `criticLists`: source-specific editorial selections.
- `felliniFilms`: chronological retrospective entries.
- `felliniDefaultView`: the author’s introductory text.
- `directors` and `collections`: other planned retrospectives.

The introduction’s editing area saves private changes in that browser’s local storage when supported. Typing there does **not** update the public website or the repository. To publish an edited introduction, update `felliniDefaultView` in `index.html` and commit it. A previously saved local draft can override the embedded introduction in that browser.

## Editorial and technical notes

This is a curated snapshot, researched in October 2026, rather than a live feed. Recheck recognition, dates and links before later updates. The personal Fellini introduction expresses the author’s view; its medical anecdote has not been independently verified.

Critics’ selections are subsets; linked original lists may include studio films. Country/region emphasis may differ from production nationality, and overlaps are intentional. Best documentaries collects award winners and nominees rather than a new numerical ranking.

Title artwork is typographic, not official film posters. Trailer buttons open searches, not guaranteed official trailers or full films. FilmScout hosts no video. Streaming availability and subscriptions depend on provider and region.

The app contains no analytics, forms sent to a server or embedded third-party players. Fonts use the MusicScout Inter/system font stack without a font download dependency.

No open-source licence has been selected. Third-party film material and linked editorial content remain with their respective rights holders.
