HIREHUB — INTERACTIVE DEMO
==========================

Start here:
1. Extract the ZIP into a new folder.
2. Open index.html in a modern browser.
3. Click Try Job Seeker Demo, Try Recruiter Demo, or Try Gigs Demo.
4. Use Reset demo at the bottom to restore the original sample data.

If opening the file directly does not work, run a local server from this folder:
  python -m http.server 8000
Then visit:
  http://localhost:8000

What works in demo mode:
- Role shortcuts and local demo account registration/login.
- Job search, posting, applications, recruiter status updates.
- Local gig browsing, posting, and gig applications.
- Career Bridge keyword-based skill gap analysis.
- CV builder with browser print-to-PDF.
- Portfolio projects, interview question bank and sample feedback.
- Reporting and basic demo moderation.
- Browser localStorage persistence and reset.

Important limitations:
- This is a local demo, not production authentication.
- No data is sent to a real recruiter or stored in a shared database.
- Career Bridge and interview feedback use simple demo logic, not a live AI API.
- Currency display conversion uses fixed illustrative rates, not live exchange rates.
- The language selector is a prototype; not every screen is translated yet.
- Supabase, secure backend functions, production security rules, and deployment have not been configured.
- Demo data is stored in this browser only. Do not enter real passwords or sensitive information.

Validation performed:
- JavaScript syntax check with Node.js passed.
- Removed a startup exception caused by references to navigation elements that were not present in the page.
- A full automated end-to-end browser run was not completed in this environment, so test the main flows on your own device.
