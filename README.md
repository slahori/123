# Sandeep | Digital Marketing Portfolio

A responsive, single-page portfolio for entry-level Digital Marketing, SEO, PPC and Social Media roles.
Plain HTML, CSS and JavaScript. No build step and no dependencies.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole website (content, styles, scripts) |
| `404.html` | Page shown for broken links on GitHub Pages |
| `favicon.svg` | Browser tab icon |
| `robots.txt` | Lets search engines crawl the site |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
| `assets/images/` | Put your project screenshots here |

## Publish on GitHub Pages

1. Sign in at github.com and click **New repository**.
2. Name it `your-username.github.io` for the address `https://your-username.github.io`, or any name (e.g. `portfolio`) for `https://your-username.github.io/portfolio/`. Set it to **Public** and click **Create repository**.
3. Click **uploading an existing file**, unzip this package on your computer, and drag in **everything inside the folder** (including the `assets` folder and the hidden `.nojekyll` file). Click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
5. Wait 1 to 2 minutes and refresh. Your live link appears at the top of the Pages screen.

## Update your details

Open `index.html` (on GitHub, click the file and then the pencil icon) and edit:

- **Email and LinkedIn:** the `CONFIG` object at the top of the `<script>`.
- **Skills, tools, KPIs, projects:** the `SKILLS`, `TOOLS`, `KPIS` and `CASES` lists. Each KPI row is `["Label","[XX%]",60]`: replace the middle value with your real figure and the number (0 to 100) sets the bar fill.
- **About text, phone, location:** replace the highlighted `[bracketed]` placeholders in the HTML.
- **Real vs sample work:** in `CASES`, change `Sample project` to `Real client project` only for genuine client work.
- **Page title and description:** the `<title>` and `<meta name="description">` near the top.

## Add project images

1. Save an image in `assets/images/` (for example `seo-case.jpg`).
2. In the `CASES` template line in `index.html`, replace `<div class="shot">...</div>` with:
   `<img src="assets/images/seo-case.jpg" alt="Describe the image" style="width:100%;border-radius:14px">`

## Before you share it

- Replace every `[placeholder]`. Do not leave invented or sample figures presented as real results.
- Check the site on your phone.
