# Personal website: Shaik Basheeruddin Shah

A plain HTML site for GitHub Pages. It has no build step and nothing to install.

## One-time setup (about 10 minutes)

1. Create a free account at https://github.com, e.g. with the username `basheershah`.
2. Click **New repository**. Name it exactly `<your-username>.github.io`, e.g. `basheershah.github.io`. Set it to **Public**, then click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in **everything inside** this folder: `index.html`, `research.html`, `publications.html`, `teaching.html`, the `assets` folder, and `.nojekyll`. Then click **Commit changes**.
   - `.nojekyll` is a hidden file. If your computer hides it, the site still works.
4. Wait 1–2 minutes, then open `https://<your-username>.github.io`.
   - If it doesn't load, go to **Settings → Pages**, set Source to *Deploy from a branch*, choose branch `main` and folder `/ (root)`, and click **Save**.

## Add your photo

Upload a square photo named exactly `profile.jpg` into `assets/img/`: go to **Add file → Upload files** inside that folder. Until you do, the site shows "SBS" initials.

## Add LinkedIn

On each of the 4 `.html` files, click the pencil icon. Search for `YOUR-LINKEDIN-URL`, paste your LinkedIn link in its place, and delete the `<!--` and `-->` around that line. Then click **Commit changes**.

## Monthly update (about 2 minutes)

1. Open `index.html` on GitHub and click the pencil icon (Edit).
2. Find the comment `MONTHLY UPDATE`. Copy the example block inside it and paste it just below the comment.
3. Change the month and the bullet text, then click **Commit changes**. The site updates in about a minute.
4. Also change "Last updated" in the footer of `index.html`.

To add a paper, open `publications.html`, copy one `<li>...</li>` line, paste it at the top of the right section, and edit the text.

To update your CV, upload the new PDF to `assets/cv/` with the same name, `Basheer_Shah_CV.pdf`. Your existing link keeps working.
