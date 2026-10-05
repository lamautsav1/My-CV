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
- Checked browser rendering and navigation at mobile and desktop widths; no horizontal overflow or file errors were found.

## Decisions and preferences
- Keep the site as a self-contained HTML file with embedded CSS and JavaScript; load GSAP, ScrollTrigger, and Lenis from CDNs.
- Use deep navy, white, electric blue, and teal; Space Grotesk headings and Inter body text.
- Keep the CV content editable from the top-level `CV` object.
- The hero uses the initials "UL" rather than a GitHub identicon.

## In progress
Nothing. The requested profile, experience, education, and contact updates are implemented and checked.

## Still to do
- Place the real PDF at `./assets/CV.pdf` or change `CV.cvUrl` to its relative path; no PDF/assets directory currently exists.
- Replace `FACEBOOK_URL`, `INSTAGRAM_URL`, and `WHATSAPP_NUMBER` in `CV.socials` with the real profile URLs and WhatsApp number.
- The contact form uses `mailto:` and has no server-side submission.
- Make any further changes the user requests when work resumes.

## Exact stopping point
The requested content updates are complete. Checks confirmed the old title and Age/customer-support wording are absent, the title/metadata and role summary are updated, all requested employer/school links render, social placeholders are disabled until configured, and Download CV points to `./assets/CV.pdf`. Desktop and refreshed mobile views have no horizontal overflow; GSAP/ScrollTrigger/Lenis and reduced-motion behavior remain intact. No unresolved file errors are known.

## Important context
- Workspace: `d:\Documents\MY CV`
- Main site: `index.html`
- Profile details and all supplied contact links are in the `CV` object near the top of `index.html`.
- The contact form relies on the visitor having an email app configured.
- The project remains a standalone HTML file; CDN animations need an internet connection.
- Social placeholders live under `CV.socials`; configured external links open in a new tab.

## Next logical step
When returning, read this progress file and `index.html`, then continue with the next CV change the user requests. The main remaining setup is to supply the PDF and real social URLs/number.

## CONTINUE FROM HERE
Read this progress file and `index.html`, understand the previous work and current state, then continue my CV work from exactly where we stopped. Do not redo completed work; ask what CV change I want next if it is not specified.