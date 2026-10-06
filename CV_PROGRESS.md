# CV Website Progress

## What we were working on
A single-page personal CV website for Utsav Lama, IT & Application Support Specialist, in `index.html`.

## Completed
- Built the responsive page with Hero, About, Experience, Skills, Education, Projects, Awards & Certifications, Contact, and Footer sections.
- Added sticky navigation with active-section highlighting, a mobile menu, and reduced-motion support.
- Added the cinematic pinned hero using GSAP 3.12.5, ScrollTrigger, and Lenis 1.1.20 from CDNs. It reveals the name, transitions it to an outline, moves it to the navbar's UL mark, and expands a blue wipe into the existing page.
- Added heading/card/timeline reveals, About line reveals, a drawing timeline line, parallax shapes, a scroll progress bar, a desktop-only custom cursor, and magnetic hero buttons.
- Added SEO title and description, an inline UL favicon, and an initials-based hero graphic.
- Grouped editable page content in the `CV` object near the top of the HTML.
- Added email, phone, GitHub, project links, and a contact form that opens the visitor's email app.
- Updated the title and summary to IT & Application Support Specialist, with experience phrased for corporate/main-branch IT and application support, branch/internal users, functional testing, UAT, and coordination with external developers.
- Removed Age, linked Newmew and all three education institutions, added their phone links, and added Facebook/Instagram/WhatsApp placeholders.
- Added the project-root PDF `cvs (1).pdf`; the navbar downloads it as `Utsav-Lama-CV.pdf`.
- Replaced the social placeholders with the Facebook, Instagram, and WhatsApp details now in `CV.socials`.
- Checked browser rendering and navigation at mobile and desktop widths; no horizontal overflow or file errors were found.

## Decisions and preferences
- Keep the site as a self-contained HTML file with embedded CSS and JavaScript; load GSAP, ScrollTrigger, and Lenis from CDNs.
- Use deep navy, white, electric blue, and teal; Space Grotesk headings and Inter body text.
- Keep the CV content editable from the top-level `CV` object.
- The hero uses the initials "UL" rather than a GitHub identicon.

## In progress
Nothing. The CV PDF link and social details are now configured; no site edits are underway.

## Still to do
- The contact form uses `mailto:` and has no server-side submission.
- No required CV-site changes are currently pending.

## Exact stopping point
The requested content updates are complete. The Download CV button resolves to `./cvs%20%281%29.pdf` and downloads as `Utsav-Lama-CV.pdf`. The old title and Age/customer-support wording are absent; employer, education, phone, and social links are configured. Desktop and refreshed mobile checks found no horizontal overflow; GSAP/ScrollTrigger/Lenis and reduced-motion behavior remain intact. Static checks found no file errors. The browser was reloaded on `index.html` and the download link was verified; its restored scroll position was not recorded.

## Important context
- Workspace: `d:\Documents\MY CV`
- Main site: `index.html`
- Profile details and all supplied contact links are in the `CV` object near the top of `index.html`.
- The contact form relies on the visitor having an email app configured.
- The project remains a standalone HTML file; CDN animations need an internet connection.
- Social URLs and the WhatsApp number live under `CV.socials`; configured external links open in a new tab.

## Next logical step
When returning, read this progress file and `index.html`, then continue with the next CV change the user requests. There are no known missing CV assets or social details.

## CONTINUE FROM HERE
Read this progress file and `index.html`, understand the previous work and current state, then continue my CV work from exactly where we stopped. Do not redo completed work; ask what CV change I want next if it is not specified.