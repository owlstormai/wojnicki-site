# wojnicki.com

Personal builder portfolio for Paul J. Wojnicki, Ph.D. One static page, no build step.

- `index.html` — the whole site (inline CSS + JS, Google Fonts)
- `shots/` — screenshots shown in the per-project viewer
- `vercel.json` — clean URLs and a couple of security headers

## Deploy

Import this repo in Vercel (framework preset: **Other**, no build command, output directory `.`).
Every push to `main` redeploys.

## Domain (GoDaddy → Vercel)

In Vercel → Project → Settings → Domains, add `wojnicki.com` and `www.wojnicki.com`, then in GoDaddy DNS:

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 76.76.21.21            |
| CNAME | www  | cname.vercel-dns.com   |

Use whatever values Vercel's Domains screen shows if they differ.
