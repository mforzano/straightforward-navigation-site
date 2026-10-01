# Straightforward Navigation website

A small Jekyll/GitHub Pages site for Straightforward Navigation. Site copy is in `index.md`; the shared HTML layout is `_layouts/default.html` and styles are in `assets/site.css`. This is a public website repository. App code and private infrastructure stay in the separate private repository.

## Preview and publishing

GitHub Pages builds the `main` branch from `/`. Edit `index.md` for the home page and push to publish. Do not announce a public app download or an email signup until those services actually exist.

The site was first built and checked at the project preview URL. The current `_config.yml` and `CNAME` target `https://straightforwardnavigation.com`; the repository's Pages custom domain must also match. While DNS still points to registrar parking, the domain will not serve this site. Avoid using the former preview URL as a stable public link after enabling the custom domain.

## Domain setup

The GitHub Pages custom domain is set to `straightforwardnavigation.com`; change DNS only after confirming that setting remains in place. In the DNS manager for the domain, remove the registrar's parked root A record and replace it with the four GitHub Pages A records for `@`:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Replace the parked `www` entry with a CNAME for `www` pointing to `mforzano.github.io` (not to the project path or to the apex domain). Keep MX, TXT, and other unrelated records unchanged. Once DNS and GitHub's certificate are ready, enable **Enforce HTTPS** in Settings → Pages. Do not use wildcard DNS. Check actual DNS and both domain variants before calling the migration complete.

GitHub's current instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
