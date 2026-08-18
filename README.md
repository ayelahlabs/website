# Ayelah Labs website

Public one-pager for [ayelahlabs.com](https://ayelahlabs.com). Product: [zkx402](https://github.com/ayelahlabs/zkx402).

Static HTML. Deploy with Cloudflare Pages:

1. Cloudflare → Workers & Pages → Create → Connect GitHub `ayelahlabs/website`
2. Build command: none. Output directory: `/`
3. Custom domain: `ayelahlabs.com` (and `www` if you want it)

Point Namecheap nameservers at Cloudflare, or add an A/CNAME at Namecheap to the Pages target Cloudflare shows after the first deploy.

Contact used on the page: `hello@ayelahlabs.com` (set up Cloudflare Email Routing before applying to AWS Activate).
