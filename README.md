# Personal homepage

A minimal, light personal website for **wangzz887412-code**, built with HTML and CSS. No JavaScript, external fonts, third-party assets, package dependencies, dependency manifest, lockfile, or build step is required.

## Files

- `index.html` — introduction, learning interests, and GitHub profile link.
- `styles.css` — responsive layout and visual styling.
- `README.md` — preview and deployment instructions.

## Preview locally

Open `index.html` directly in a modern web browser. Keep `styles.css` in the same folder.

Alternatively, from this directory run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

On Windows, use `py -m http.server 8000 --bind 127.0.0.1` if `python3` is unavailable.
Open <http://127.0.0.1:8000/> on the same device. Stop the preview server with Ctrl+C. This previews the site locally; it does not publish to GitHub Pages.

## Publish to GitHub Pages

1. Sign in to GitHub yourself. Do not share passwords, verification codes, or tokens with AI.
2. Create a **public** repository named exactly `wangzz887412-code.github.io`. If it already exists, inspect and preserve its current contents before updating it.
3. Upload the files **inside this folder** to the repository root. `index.html` and `styles.css` must be beside each other at the root, not nested inside a `github_homepage/` folder. Commit the upload to `main`.
4. Open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/(root)**, then save.
5. Check the deployment result in GitHub's **Actions** tab. Publication can take up to 10 minutes.

Repository address after creation: <https://github.com/wangzz887412-code/wangzz887412-code.github.io>

**These addresses identify the intended deployment, not evidence that publication has succeeded.**

Only publish the website files. Never upload the private homework report, student ID, credentials, or the entire homework directory.

## Source and assistance

Deployment instructions follow GitHub's official [Pages quickstart](https://docs.github.com/en/pages/quickstart).
The HTML, CSS, and these instructions were prepared with AI assistance after the owner selected a minimal-public-information introduction and light visual style. The owner must personally review the public introduction and verify the deployed page.
