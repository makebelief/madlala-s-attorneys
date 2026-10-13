# Madlala S. Attorneys — Independent Website Concept

Static, responsive multi-page website using the C.O. Were-style structure. No build dependencies, no secrets, ready for Vercel static hosting.

## Setup
- Vercel preset: **Other**. Root and Output: `.` (project root).
- Local preview: `python3 -m http.server 8000` from this folder, then open http://localhost:8000
- New GitHub repo: `gh repo create madlala-s-attorneys --public --source=. --remote=origin --push`
- Deploy: `npx vercel --prod`

## Public listing contacts (confirm before official publication)
- Sbahle Madlala, director (public attorney listing).
- Office 203, Royal Place, 85 Eloff Street, Johannesburg, 2001.
- Mobile: +27 73 616 7233; office: +27 10 449 2318/9; email: sbahle@madlalasattorneys.co.za.
- Hours: Mon–Fri 9–5, Sat 9–1.
- Sources: https://www.attorneys.co.za/CompanyHomePage.asp?CompanyID=2121 and https://www.attorneys.co.za/AttorneyHomePage.asp?AttorneyID=9452&CompanyID=2121
- Photos supplied by user for concept; identification of the depicted individual has not been independently confirmed.
- The WhatsApp button opens the mobile number, but WhatsApp registration has not been independently verified.

## Important: independent unapproved demo
- The demo includes a visible independent-concept banner, `noindex` robots tags and `robots.txt` disallowing crawling. Before the firm approves a publicly indexed official site, verify contact and identity details, obtain consent to use its brand and photos, and remove the demo banner and noindex/disallow settings.
- `sitemap.xml` and canonical tags are configured for anticipated URL `https://madlala-s-attorneys.vercel.app`; amend if Vercel assigns a different project URL.
- Form opens the user's email client and does not submit to a backend.
- Pexels photos are third-party illustrative images accessed via external URLs. Availability must be verified in live deployment; they are not presented as actual staff/clients. Their sources are listed in `PHOTO-SOURCES.md`.
- Logo transparent versions are 4K-width raster enlargements of the uploaded 685px logo; not native vector quality. The supplied 400x550px portraits are preserved without AI facial reconstruction.

## Pages
Home, About Us, Practice Areas, Our Attorney, Insights, Contact, Privacy, Terms, 404.
