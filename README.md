# વિશ્વાસ (Vishwas)

A milestone payment tracker for freelancers, in Gujarati and English.

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) ![Languages: Gujarati + English](https://img.shields.io/badge/languages-Gujarati%20%2B%20English-blue)

**Live demo (phone and PC, no install):** https://1darshankumarsavsani-blip.github.io/Vishwas/

## Features

- Split a project into milestones with due dates
- Share one link with your client; they approve each milestone without logging in
- Trust score = share of milestones delivered on or before the due date
- Owner sign-in with Google; data in Firestore

## Download

This is a web app: open the live demo. No APK or exe is published.

## Tech stack

- Web: single-file HTML/CSS/JavaScript
- Backend: Firebase Authentication and Firestore (security rules in the project)

## Project structure

```text
docs/  website (single index.html, GitHub Pages)
.github/  issue templates
```

## Build from source

Open `docs/index.html` in a browser. To use your own Firebase project, replace the values in the Firebase config in the page.

## Privacy

The app does not hold or move money. The client pays the owner directly (UPI) and the owner marks the milestone paid.

## Honest notes

The owner flow was tested with a mock; client approval and rules were checked over the REST API. The AI scoping idea is not built.

## Contributing

Bug reports and ideas are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and the issue templates. Please report security problems as described in [SECURITY.md](SECURITY.md).

## License

MIT, see [LICENSE](LICENSE).

## Author

Darshankumar Savsani, DARSHAN CORPORATION, Rajkot. GitHub: [1darshankumarsavsani-blip](https://github.com/1darshankumarsavsani-blip), organization: [DARSHAN-CROP](https://github.com/DARSHAN-CROP).
