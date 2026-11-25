# The AI Campaign — Mindora AI

A standalone, responsive learning website for the 8-module, 24-lesson programme.

## Included
- Complete course map and lesson pages with learning outcomes, practice activities and reflection checks
- 5D framework: Discover, Define, Develop, Distribute, Diagnose
- Learner profile and local progress tracking
- Portfolio workspace with local save/delete
- Reusable candidate/client engagement settings
- Two-signatory Certificate of Participation layout
- Downloadable JSON verification record and print-to-PDF certificate
- Mobile-responsive design and nonpartisan ethical-use guidance

## Run locally
Open `index.html` in a modern browser. No build step or server is required.

## Publish with Cloudflare Pages
1. Extract this ZIP.
2. Upload the contents of this folder to the public GitHub repository `mindoraAi/mindora-ai-campaign` (the `index.html` must be at the repository root).
3. In Cloudflare Pages, create a project connected to that repository.
4. Use no framework preset, no build command, and set the output directory to `/` (repository root).
5. Deploy and test the generated URL on desktop and mobile.

## Important implementation notes
- Learner profiles, progress, portfolio entries and engagement settings are stored in the browser's local storage on the current device/browser. They are not yet synchronised across devices or stored in a central database.
- The verification record is a downloadable JSON record; the current package does not provide a public verification server or automatic QR validation.
- Signature images are optional and must be authentic, supplied and authorised by the relevant signatories. The site does not fabricate signatures.
- Certificate wording is Certificate of Participation. There is no pass-mark exam and payment is not a condition of participation recognition.
- This is an educational template, not legal advice, election compliance advice, accreditation or endorsement.
