# Dirt Road | Public Informational Website
Soul Kitchen & Confections - A dark luxury culinary studio & gifting house.

## How to Deploy to GitHub & Vercel
1. Create a new repository on GitHub named `dirt-road-website` (or `dirt-road-site`).
2. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Dirt Road public website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/dirt-road-website.git
   git push -u origin main
   ```
3. In Vercel:
   - Click **Add New...** -> **Project**.
   - Import `dirt-road-website`.
   - Framework Preset: **Other** (Static Site).
   - Root directory: `./`
   - Click **Deploy**.
