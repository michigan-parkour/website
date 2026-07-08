# Michigan Parkour Club Website

Static website for Michigan Parkour Club at `https://michiganparkour.com`.

This repository, `https://github.com/michigan-parkour/website`, is the active
site for `michiganparkour.com`. The older `umichparkour.com` site and older
GitHub Pages/archive copies are legacy only and should not receive normal
content or photo updates.

## Local Preview

```sh
npx serve .
```

## Cloudflare Pages

Use these settings:

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`
- Production branch: `main`

## Canonical Domain

Use `https://michiganparkour.com` as canonical. If the old website is redirected,
send all old `umichparkour.com` and `www.umichparkour.com` variants to
`https://michiganparkour.com/` with a `308 Permanent Redirect` after testing.
The site is mostly one page, so old paths should redirect to the homepage unless
a specific path mapping is intentionally documented.

## Content Notes

- The text is adapted from the previous club website.
- The images are local copies from the shared Google Photos album.
- Avoid University trademarks, the Block M, and `umich` naming in domains, handles, or repository names.
