# Avi Muwal – Portfolio

Static portfolio site (HTML + CSS, no build step).

Files:
- `index.html` – the page
- `style.css` – styles
- `resume.pdf` – your resume; linked from the nav, hero buttons and contact section

## Deploy on Vercel (easiest)
1. Put this folder in a GitHub repo (or use the Vercel CLI: `npm i -g vercel`, then run `vercel` inside this folder).
2. On vercel.com choose **Add New → Project**, import the repo.
3. Framework Preset: **Other**. Leave build command and output directory empty. Click **Deploy**.
4. Your site will be live at `https://<project-name>.vercel.app`, and the resume at `/resume.pdf`.

## Deploy on Render
1. Push this folder to a GitHub repo.
2. On render.com choose **New → Static Site** and connect the repo.
3. Build command: leave empty. Publish directory: `.`
4. Click **Create Static Site**. It will be live at `https://<name>.onrender.com`.

## Updating
Edit the files, commit and push. Both platforms redeploy automatically.
