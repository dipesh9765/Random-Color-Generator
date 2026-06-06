# Color Game

A Stroop-style color game display for events. Show it on a screen while players call out answers.

## How it works

Each round shows:

- A **full-screen background color** (random)
- A **color name** in the center, written in a **different** color (also random)

Example: yellow background with the word **GREEN** shown in green text.

Each round includes a **1-second countdown** at the top — players guess before time runs out.

Use **Next** / **Previous** to move through rounds. Keyboard shortcuts: `→` or `Space` for next, `←` for previous.

## Run locally

Open `index.html` in any web browser.

## Deploy to GitHub Pages

1. Create a new GitHub repository and push this folder:

   ```bash
   git init
   git add .
   git commit -m "Add color game display page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. On GitHub, go to **Settings → Pages**.

3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.

4. Choose branch **main** and folder **/ (root)**, then save.

5. After a minute or two, your site will be live at:

   `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Files

| File | Purpose |
|------|---------|
| `index.html` | Game page (HTML, CSS, and JavaScript) |
| `.nojekyll` | Tells GitHub Pages not to use Jekyll processing |
