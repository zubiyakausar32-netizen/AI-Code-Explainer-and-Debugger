# CodeLens AI

CodeLens AI is a static website made from HTML, CSS, and browser JavaScript.

## Open the site

Open `index.html` in a browser, then use the navigation to visit the Features, Workspace, and Bug Store pages.

The workspace analyzer checks for a limited set of common code patterns and can run JavaScript snippets. Bugs found by the analyzer or JavaScript execution are automatically saved in the Bug Store in the current browser's local storage. Saved findings include their error details, language, source, optional line and suggested fix; credential-like inline assignments are redacted from saved source. Successful runs are not saved.

The Bug Store supports searching, filtering by language and error type, viewing full details, and deleting individual findings. Because this project is a static site with no server or database, findings are local to the browser profile and origin and are not shared across browsers or devices.
