# Norte Fitness website

Static site for nortefitness.com, hosted free on GitHub Pages.

## Files
- `index.html` the whole site (English and Spanish, toggle in the menu)
- `CNAME` tells GitHub Pages to serve the site on nortefitness.com
- `images/` put your photos here with these exact names (JPG, about 2000px wide is plenty):

| File | Where it shows |
|---|---|
| logo.svg, logo-full-black.svg, logo-black.svg | Norte logo (white for the site, black for light backgrounds) and tab icon, already included |
| hero.jpg | Big photo at the top (landscape) |
| why.jpg | "Why Norte" section (portrait works best) |
| work-1.jpg to work-6.jpg | "Our work" gallery |

All photos are already included and compressed. To swap one, replace the file with a new JPG of the same name.

## Put it online (one time, about 15 minutes)
1. Create a free account at github.com.
2. Click **New repository**, name it `nortefitness`, set it to **Public**, create it.
3. Click **uploading an existing file** and drag in `index.html`, `CNAME`, `README.md` and the `images` folder. Click **Commit changes**.
4. Go to **Settings > Pages**. Under Source pick **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
5. In the same page, Custom domain should already read `nortefitness.com`.
6. At your domain's DNS settings (Canva > Domains > Advanced settings, or your registrar), add:
   - Four **A** records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - One **CNAME** record for `www` pointing to `YOURUSERNAME.github.io`
7. Wait up to a few hours, then tick **Enforce HTTPS** in Settings > Pages.

## Contact form
The form is your Tally form (tally.so/r/M1DNYE). Turn on email notifications in Tally (Integrations or Settings > Notifications) so every submission lands in ivan@nortefitness.com.

## Editing later
Open `index.html` on GitHub, click the pencil, change the text, commit. The site updates in about a minute.
