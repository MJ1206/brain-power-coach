# Brain Power Coach — starter app

A small, responsive learning app for a 9-year-old. It includes:
- Mental maths questions with hints and explanations
- Logic multiple-choice puzzles
- English conversation prompts
- Public speaking prompts and a timer
- Read-aloud for prompts where the browser supports speech synthesis
- Stars, practice history, parent notes and JSON export
- Local-only storage on the device (no account or server database)

## Quick preview
Open `index.html` in a modern browser. Some browser features, such as offline caching and install prompts, require hosting over HTTPS.

## Install it on a phone
This is a Progressive Web App (PWA), not a native App Store/Play Store package.
1. Upload the contents of this folder to a static HTTPS host, such as GitHub Pages or Netlify.
2. Open the hosted app URL in Chrome on Android, then choose the browser menu and **Install app** or **Add to Home screen**.
3. On iPhone, open the URL in Safari, tap **Share**, then **Add to Home Screen**.

The app works offline after it has loaded once, provided the host/browser supports service workers. Progress is stored locally in that browser on that device; clearing browser data can erase it. Use the parent dashboard's export button to back up progress.

## Important notes
- The first version uses built-in question banks, not a live AI model. It does not send child data to an AI service.
- English and speaking prompts are practice prompts; the app does not automatically grade spoken language or pronunciation.
- For a child, use with parent supervision.
