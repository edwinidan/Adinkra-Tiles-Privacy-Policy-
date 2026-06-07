# Adinkra Tiles Privacy Policy Website

This is the static privacy policy website for the Flutter game **Adinkra Tiles**.

This page is designed to be hosted publicly (e.g., via GitHub Pages, Vercel, Netlify, or any basic static web host) so it can be referenced in the Google Play Console for store publication.

## Tech Stack & Design
- **Core:** Standard HTML5 and Vanilla CSS.
- **Branding:** Ghanaian-inspired visual styling including a dark green/teal background, a warm parchment/cream card for text readability, and antique gold accents.
- **Fonts:** Custom typography powered by Google Fonts (*Cinzel* and *Nunito*).
- **Responsive:** Designed to scale fluidly from desktop displays to mobile screens.

## Files In This Folder
- `index.html`: The main privacy policy document containing all disclosure sections.
- `styles.css`: The responsive styling sheet.
- `adinkra tiles logo.png`: The game icon/logo displayed in the website header.
- `README.md`: This file.

## How to Preview Locally

To view the website locally, you can use any static file server:

### Option 1: VS Code Live Server
If you are using Visual Studio Code, you can install the **Live Server** extension, open this folder, and click **"Go Live"** in the status bar.

### Option 2: Python (Built-in)
If you have Python installed, navigate to this folder in your terminal and run:
```bash
python3 -m http.server 8000
```
Then open your browser and navigate to `http://localhost:8000`.

### Option 3: Node.js (npx)
If you have Node.js installed, you can start a simple server using:
```bash
npx serve .
```
Then open the address output in the terminal (usually `http://localhost:3000` or `http://localhost:5000`).

## How to Deploy

Because this website is completely static, deployment is quick and free:

### GitHub Pages (Recommended)
1. Commit these files into a GitHub repository.
2. Go to the repository settings, select **Pages** in the sidebar.
3. Under **Build and deployment**, set the source to **Deploy from a branch** and select your branch (e.g., `main`), then click **Save**.
4. GitHub will generate a public URL (e.g., `https://yourusername.github.io/your-repo-name/`) within a few minutes.

### Netlify
1. Create a free Netlify account.
2. Drag and drop this folder directly into the Netlify web dashboard upload box.
3. It will instantly publish the site and provide a public URL.

### Vercel
1. Install the Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory and follow the prompts.
