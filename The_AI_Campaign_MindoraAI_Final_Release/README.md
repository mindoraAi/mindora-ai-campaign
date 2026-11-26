# The AI Campaign — Mindora AI

Standalone, responsive training website for the 8-module, 24-lesson programme.

## Included
- Eight modules and 24 expanded lessons, with learning outcomes, detailed notes, applied examples, practical activities and reflection checks.
- The 5D framework: Discover, Define, Develop, Distribute and Diagnose.
- Approved Mindora AI brain-and-circuit logo, lesson branding and a faint page watermark.
- Navigation links to the Mindora AI parent website and Mindora AI Academy.
- Learner profile, local lesson progress and portfolio workspace.
- Reusable engagement settings for each candidate/client, including candidate name, elective position, location, engagement name and dates.
- Two-signatory Certificate of Participation: Founder / Programme Lead plus a configurable candidate/client representative.
- Optional upload of authentic, authorised signature images. No signature is fabricated or imitated.
- Certificate ID, QR link, downloadable JSON verification record and static verification page.
- No final examination and no pass mark. A certificate is available after all 24 lessons are marked complete and the learner confirms participation. Payment is not part of the certificate eligibility rule.
- Nonpartisan ethical-use guidance; certificate signature by a candidate/client representative is not political endorsement.

## Run locally
Open `index.html` in a modern browser. For QR generation and certificate hash verification, use HTTPS or a local web server. The QR generator is loaded from cdnjs; if unavailable, the verification link remains available.

## Publish with Cloudflare Pages
1. Extract this ZIP.
2. Upload the **contents** of this folder to the public GitHub repository `mindoraAi/mindora-ai-campaign`. Put `index.html`, `verify.html`, `README.md` and the `assets/` folder at the repository root (do not upload the enclosing folder as an extra level).
3. In Cloudflare Pages, connect the GitHub repository.
4. Choose no framework preset, no build command, and set the output directory to `.` (repository root).
5. Deploy and test the course and `/verify.html` URL on desktop and mobile.

## Important implementation notes
- Learner profiles, lesson progress, portfolio entries, engagement settings and locally uploaded signature images are stored in the current browser's local storage. They are not synchronised across devices and are not stored in a central database.
- The QR code opens a static verification page using the certificate ID. The user must upload the accompanying JSON verification record for its integrity hash and details to be checked.
- The static verification flow is not a central issuer registry and does not cryptographically authenticate the issuer or signatures. A production-grade public registry would require a trusted backend and issuer-controlled signing process.
- Signature images must be authentic and authorised by the relevant signatories. The Founder signature is left blank until the authentic image is supplied/approved. The candidate/client representative's name and title are configurable for each engagement.
- Certificate wording is Certificate of Participation. There is no final exam or pass mark; all 24 lessons must be completed and participation confirmed. Payment is not a condition for recognition.
- The course is a professional learning programme, not legal advice, election compliance advice, government accreditation or professional licensure.
