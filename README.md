[NOTES.md](https://github.com/user-attachments/files/32266897/NOTES.md)
# Before you deploy

A few things I couldn't fill in without inventing content — grab these from your
own files and drop them in:

1. **Project screenshots.** I left dashed placeholder boxes in the Projects
   section for Sonar.ai and the Purdue Research Matchmaker. Swap the
   `.shot-placeholder` div in each project card for an `<img>` pointing at a real
   screenshot (e.g. `<img src="sonar-screenshot.png" alt="Sonar.ai dashboard">`).

2. **Resume PDF.** All resume buttons (hero "view resume" and the contact
   section's "View Resume" / "Download Resume") now point at
   `Arshia_Sharma_Resume.pdf`. Just make sure that file sits in the same
   folder as `index.html` when you deploy — no other setup needed. "View"
   opens it in a new tab; "Download" uses the HTML `download` attribute so it
   saves straight to the visitor's device instead of navigating away.

3. **Purdue Research Matchmaker live link.** I could only find a GitHub
   repo (`github.com/arshiasharma08/purdue_research`) for this one, not a
   public deployment — your old site said "publicly deployed" but I couldn't
   find the actual URL. If it's live somewhere, add a "live demo" button next
   to the GitHub button in that project card.

4. **Coursework.** I listed Calculus I as MA 16100 (Purdue's standard first
   calculus course) — double check that's the right course number for you.

## Deploying

This is a plain static site — `index.html`, `style.css`, `script.js`. You can
deploy it on Render (like your current site) as a Static Site, or drag-and-drop
the folder into Netlify/Vercel. No build step needed.
