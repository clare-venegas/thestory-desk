# The Story Desk — Cloudflare Pages deploy

This folder is the complete site. Upload the folder as-is.

## Files
- index.html — main site (Home, Founders & CEOs, Higher Education, Nonprofits & Ministry)
- audit.html — Executive Silence Audit (free tool)
- oped-framework.html — 5-Minute Op-Ed Framework (free tool)
- enrollment-checklist.html — The Seventeen-Year-Old Test (free tool)
- donor-checklist.html — Donor Journey Checklist (free tool)
- sprint.html — First Op-Ed in 14 Days
- presidential-pilot.html — Presidential Voice Pilot
- campaign-kickstart.html — Campaign Calendar Kickstart
- one-story-workshop.html — One Story Workshop
- speaking.html — Speaking

## Deploy
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Upload assets.
2. Name the project (e.g. thestory-desk), drag this folder in, Deploy.
3. Custom domains → add thestory-desk.com (and www), follow the DNS prompts.

Cloudflare serves clean URLs automatically: /audit, /speaking, etc.
Audience pages: /#founders, /#highered, /#nonprofit.

## Updating
Edit the source project, re-export index.html (or the tool file), and upload a new deployment.
Tool email capture posts to MailerLite; booking links go to the Google Calendar booking page.
