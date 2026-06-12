# Elakanti Akhil Kumar's — Portfolio

A single-page personal portfolio website (HTML, CSS, vanilla JS) showcasing education, experience, skills, projects, and certifications.

## Features
- Responsive design with mobile nav
- Dark / Bright theme toggle (saved in localStorage)
- Typed.js animated role text
- Scroll-reveal animations
- Clickable CGPA badge linking to academic record (PDF)
- Resume download button

## Tech Stack
- HTML5 + CSS3 (custom properties for theming)
- Bootstrap 5 (layout/icons)
- Bootstrap Icons
- Typed.js (animated text)
- No build step / framework — pure static site

## File Structure
```
.
└── index.html   # everything (markup, styles, scripts) in one file
```

## Run Locally
Just open `index.html` in a browser, or serve it:
```bash
npx serve .
```

---

## Deploy to Vercel

### Option 1: Vercel CLI (fastest)
1. Install the CLI:
   ```bash
   npm i -g vercel
   ```
2. From the project folder, run:
   ```bash
   vercel
   ```
3. Follow the prompts (link/create project, accept defaults — Vercel auto-detects static sites). 
4. For a production deployment:
   ```bash
   vercel --prod
   ```

### Option 2: Vercel Dashboard (Git-based)
1. Push this project to a GitHub/GitLab/Bitbucket repo.
2. Go to [vercel.com](https://vercel.com) → **Add New... → Project**.
3. Import your repository.
4. Framework Preset: **Other** (no build command needed since it's static HTML).
   - Build Command: *(leave empty)*
   - Output Directory: *(leave empty / `.`)*
5. Click **Deploy**.
6. Vercel will give you a live URL like `https://your-project.vercel.app`.

### Option 3: Drag & Drop
1. Go to [vercel.com/new](https://vercel.com/new).
2. Drag the project folder (containing `index.html`) into the upload area.
3. Deploy — done.

## Custom Domain
After deployment, go to your project → **Settings → Domains** and add your custom domain (e.g., `akhilkumar.dev`), then update your DNS records as instructed by Vercel.
