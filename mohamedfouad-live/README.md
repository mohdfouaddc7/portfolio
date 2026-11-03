# mohamedfouad.com

One page, no build step. `index.html` plus `assets/img/`.

## Go live on GitHub Pages
1. Create a new public repository on GitHub (any name).
2. On the repo page click "uploading an existing file", drag in everything inside this folder (index.html, CNAME, .nojekyll, robots.txt, sitemap.xml, README.md and the `assets` folder), then "Commit changes".
3. Settings -> Pages -> Build and deployment -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
4. Your link appears on that same page within a minute: https://<your-username>.github.io/<repo-name>/

## Your domain (when you want it)
Settings -> Pages -> Custom domain: mohamedfouad.com (the CNAME file is already in the repo). Then at your domain registrar point the domain at GitHub Pages using the DNS records in GitHub's Pages docs, and remove the domain from Google Sites.

## Editing
Everything is in index.html. Images live in assets/img. Forms post to Web3Forms with your existing key.
