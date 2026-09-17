# Sililo Simushi — Portfolio

Same file structure/architecture as the reference project you worked on for your client — plain HTML/CSS/JS, no build step, drop it straight onto GitHub Pages.

## Where to put your own information

### 1. Photos (assets/img/) — REQUIRED
These are currently placeholders labeled "YOUR PHOTO" — replace the files (keep the same filenames):
- `hero-profile1.png` (605x847) — big hero photo, right side of the homepage
- `home-perfil1.png` (521x714) — photo in the About Me section
- `Icon.png` (1024x1024) — your favicon/browser tab icon (currently an "SS" monogram — swap if you want a logo instead)

### 2. Project screenshots (assets/img/) — OPTIONAL
Currently placeholder graphics labeled with the project name:
- `project-1.png` — Vantage (Job Board)
- `project-2.png` — Silwambi Legacy
- `project-3.png` — Restaurant Management System
- `project-4.png` — Event Registration System
Replace with real screenshots of each project (recommended size ~1900x870px, PNG).

### 3. Resume PDF (assets/pdf/) — REQUIRED for the "Resume" button to work
Add a file named exactly:
- `Sililo-Simushi-Resume.pdf`
The Resume buttons in the header and About section already link to this path.

### 4. Text content — already filled in with your real information
Open `index.html` and search for these if you want to update anything further:
- Contact info: email, phone, location (search "sililo.simushi")
- Projects: titles, tech stack, live links (search "projects__title")
- Experience/Education (search "work__title")
- Skills/Tools (search "services__skill")
- GitHub link (search "silwambiwakakuwe") — if your second GitHub account (the one with your CodeAlpha tasks) is different, replace this URL everywhere it appears.

## What was intentionally left out
- Testimonials section — removed, since fake quotes attributed to real people would be dishonest. Add it back once you have real feedback from a mentor, supervisor, or colleague — I can help you build that section when you do.
- Client's social links (LinkedIn/TikTok/Instagram/Facebook) — removed since those were his, not yours. Add your own if you have them (search "contact__social" and "home__social" in index.html).

## To deploy
1. Rename this folder's contents to a new GitHub repo (or push as-is).
2. In the repo Settings → Pages, set source to your main branch.
3. Live at `https://<your-username>.github.io/<repo-name>/`.
