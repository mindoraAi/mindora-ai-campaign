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
- Certificate ID, QR link and a simple certificate-reference page. Students do not need to download or upload technical verification files.
- No final examination and no pass mark. A certificate is available after all 24 lessons are marked complete and the learner confirms participation. Payment is not part of the certificate eligibility rule.
- Nonpartisan ethical-use guidance; certificate signature by a candidate/client representative is not political endorsement.

## Run locally
Open `index.html` in a modern browser. For QR generation, use HTTPS or a local web server. The QR generator is loaded from cdnjs; if unavailable, the verification link remains available.

## Publish with Cloudflare Pages
1. Keep `index.html`, `verify.html`, `README.md` and the existing `assets/` folder together in the `The_AI_Campaign_MindoraAI_Final_Release/` directory.
2. For updates to an existing deployment, replace only the files supplied in the update package; keep the existing `assets/` folder unchanged unless an update explicitly includes replacement assets.
3. The current Cloudflare Pages project can continue using its configured output directory `The_AI_Campaign_MindoraAI_Final_Release`, with no framework preset and no build command.
4. After committing changes to the connected GitHub branch, allow Cloudflare Pages to deploy automatically. Test the course and `/verify.html` on desktop and mobile.

## Important implementation notes
- Learner profiles, lesson progress, portfolio entries, engagement settings and locally uploaded signature images are stored in the current browser's local storage. They are not synchronised across devices and are not stored in a central database.
- The QR code opens a simple reference page displaying the certificate ID and instructions for requesting confirmation from Mindora AI. The page does not expose JSON files, hashes or technical verification codes to students.
- The reference page is not a central issuer registry and does not independently authenticate the issuer or signatures. Authoritative confirmation must be provided by Mindora AI. A production-grade public registry would require a trusted backend and issuer-controlled signing process.
- Signature images must be authentic and authorised by the relevant signatories. The Founder signature is left blank until the authentic image is supplied/approved. The candidate/client representative's name and title are configurable for each engagement.
- Certificate wording is Certificate of Participation. There is no final exam or pass mark; all 24 lessons must be completed and participation confirmed. Payment is not a condition for recognition.
- The course is a professional learning programme, not legal advice, election compliance advice, government accreditation or professional licensure.


Certificate experience update (November 2026)
- Certificate generation includes a celebratory reveal and confetti animation.
- Print styling keeps the certificate visible and correctly laid out in the browser print dialog; choose “Save as PDF” to download it.
- The student-facing JSON verification download has been removed. QR codes now open a clean reference page that explains how to request issuer confirmation.
