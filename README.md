# Ayelah Labs website

Public one-pager for [ayelahlabs.com](https://ayelahlabs.com). Product: [zkx402](https://github.com/ayelahlabs/zkx402).

Static HTML. No build. Output directory: `/`.

GitHub Pages is publishing this branch at <https://ayelahlabs.github.io/website/> until Namecheap DNS moves. The `CNAME` file is absent on purpose: with it present, GitHub redirects that hostname to `ayelahlabs.com`, which still points at Namecheap parking. Asset links are relative so they load under `/website/` and at the apex.

Custom domain, when DNS can be changed: Cloudflare Pages on the Free plan.

1. Cloudflare → Workers & Pages → Create → Connect GitHub `ayelahlabs/website`
2. Build command: none. Output directory: `/`
3. Custom domain: `ayelahlabs.com` and `www.ayelahlabs.com`
4. At Namecheap, replace `dns1.registrar-servers.com` and `dns2.registrar-servers.com` with the two nameservers Cloudflare assigns for the zone. Apex Pages domains have to be a zone on the same Cloudflare account.

Contact used on the page: `hello@ayelahlabs.com` (set up Cloudflare Email Routing before applying to AWS Activate).
