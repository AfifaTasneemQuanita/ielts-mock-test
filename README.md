# IELTS Academic Mock Test — GitHub Pages Version

This is a static, interactive IELTS Academic-style mock test for 1-to-1 teaching.

## What is included
- Listening: 4 parts, 40 original questions
- Reading: 3 original passages, 40 questions
- Writing: Task 1 + Task 2
- Speaking: Parts 1, 2 and 3, with browser recording/upload support
- Autosave in the browser using `localStorage`
- Manual-review workflow: no answer key and no automatic grading
- Submission export as a JSON file
- Red-and-white responsive design

## Important note about Listening
The supplied Listening scripts are original. The website uses the browser's built-in speech synthesis as a practice fallback. For a more realistic test, you can later record the scripts yourself and replace the speech-synthesis button with audio files.

## Publish on GitHub Pages
1. Extract this ZIP.
2. Create a GitHub repository, for example `ielts-mock-test`.
3. Upload **the files inside this folder** to the repository root. `index.html` must be visible at the top level.
4. Commit the files.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`.
8. Save. GitHub will provide your public site URL.

## Student submission workflow
1. Student opens your GitHub Pages link.
2. Student enters name and completes the test.
3. Answers save automatically in that browser.
4. Student opens **Review & Export**.
5. Student clicks **Download submission JSON**.
6. Student sends the downloaded JSON file to you.
7. You review the answers manually.

## Privacy
Do not upload student submission JSON files or speaking recordings to a public GitHub repository.

## Local preview
If you have Python installed, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Opening `index.html` directly with `file://` may prevent the JSON data files from loading in some browsers, so use GitHub Pages or a local web server.
