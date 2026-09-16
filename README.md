# Liftwright

Public pages for **Liftwright**, a strength-training log for iPhone.

- [Privacy policy](https://nafisanjum15-ship-it.github.io/liftwright/) — the page App Store Connect links to.
- [Support](https://nafisanjum15-ship-it.github.io/liftwright/support/) — contact address and common questions.

`index.html` is generated from the policy that ships inside the app
(`MicrofactorWorkouts/Resources/PrivacyPolicy.md`) by `DevTools/build-privacy-page.py`,
so the hosted page and the in-app screen are always the same text. Edit the
markdown in the app repo, re-run the script, and push the result here.

`support/index.html` is hand-written and has no counterpart in the app; the app
links to it. Both pages share `style.css`.

The support address on those pages is the only place it is published, so it can
be changed here without shipping an app update.
