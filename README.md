# ezbelly.com

Static site for `www.ezbelly.com`, served via GitHub Pages.

Hosts the home page and privacy policy for the **My People** Google OAuth app.

## Files

- `index.md` — home page (purpose of the app)
- `privacy.md` — privacy policy (served at `/privacy`)
- `CNAME` — custom domain (`www.ezbelly.com`)
- `_config.yml` — Jekyll config (Cayman theme)

## Deploy

Push to `main`. GitHub Pages builds automatically.

## DNS

Point `www.ezbelly.com` at GitHub Pages with a CNAME record:

```
www.ezbelly.com  CNAME  <github-username>.github.io
```

For apex (`ezbelly.com`), add A records to GitHub's IPs:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
