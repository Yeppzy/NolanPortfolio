# Deployment notes

This portfolio is a static website. You can upload this whole folder to any static hosting provider.

## What to upload

Upload these files and folders exactly as they are:

- all `.html` files
- `styles.css`
- `script.js`
- `assets/photos/`

Keep the filenames in `assets/photos/` unchanged. The site automatically tries refreshed files with the same names and checks the next numbered project images such as `Gaudi 24.webp`.

## Easiest hosting options

Good simple options are Netlify, Vercel, GitHub Pages, or any classic web hosting with FTP/cPanel. Because this is static HTML/CSS/JS, you do not need a backend server.

## Domain

Buy a domain from a registrar such as Namecheap, GoDaddy, Websupport, Forpsi, Cloudflare Registrar, etc. After hosting the site, point the domain DNS to the hosting provider. The hosting provider will show the exact DNS records, usually either nameservers or a CNAME/A record.

## Before publishing

Open `index.html` or run a local preview server and check:

- homepage
- Works
- at least one project page
- mobile width
- all images visible
- contact links correct

## Adobe font

The site loads Neue Helvetica through Adobe Typekit:

`https://use.typekit.net/swh4lwj.css`

Make sure your Adobe kit allows the final domain after you buy it.
