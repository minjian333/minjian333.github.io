# Minjian Zhang personal website

This is a lightweight static site designed to deploy cleanly on GitHub Pages.

## Local preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a GitHub repository, for example `minjianzhang.github.io`.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder.
6. Wait for the site to publish. Your URL will usually be:
   `https://minjianzhang.github.io/`

## Add a custom domain later

1. Buy a domain from any registrar you like.
2. In GitHub Pages settings, set the custom domain.
3. Point the domain's DNS records to GitHub Pages.
4. If you want the domain committed in the repo, add a file named `CNAME`
   containing only your domain name, for example:

```text
www.minjianzhang.com
```

## Notes

- The current site uses your provided photo and CV PDF.
- Contact info is intentionally minimal on the public page to reduce spam.
- You can expand this with Google Scholar, publications pages, or a blog later.
