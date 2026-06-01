# trexselector.github.io

Source for the **T-Rex Selector** website, served at <https://trexselector.com>.

## Hosting

- Hosted on **GitHub Pages** from the `trexselector` organization, repo
  `trexselector.github.io` (served at the org root).
- The site is **plain static HTML** committed directly to `main` — no build step.
- The custom domain `trexselector.com` is configured via the `CNAME` file.

## Deploy

Edit `index.html`, commit, and push to `main`. GitHub Pages publishes automatically.

```sh
git add -A
git commit -m "Update site"
git push
```

## DNS

Apex `trexselector.com` points to GitHub Pages:

- A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- (optional) `www` CNAME → `trexselector.github.io`
