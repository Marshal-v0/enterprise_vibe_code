# 2690 website

Standalone copy of the approved Home Base website, prepared September 17, 2026.

Current review site: https://2690-final-copy.indigo-hq.com/home-base-v2/

## Run locally

From this directory:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. No build step, package installation, or backend is required.

## Files

- `index.html`: page content, navigation, and inline SVG diagrams.
- `refined.css`: responsive styles and self-hosted Archivo font declaration.
- `assets/`: Archivo font, its SIL Open Font License, and founder portraits.

This directory is a standalone site, separate from the existing EVC Hugo website. Configure the production host with `sites/2690` as its publish directory. The site is served from the domain root. All asset paths are relative. The HQ preview badge and internal project files are excluded.

## Production launch for Mike

The intended domain is `2690.ai`. This handoff does not configure hosting, DNS, or deployment automation.

1. Choose a static host and publish this directory as its document root. No build command is needed.
2. Connect `2690.ai`, enable HTTPS, and choose whether `www.2690.ai` redirects to the apex domain.
3. Remove the `noindex,nofollow` robots meta tag in `index.html` when production is ready to be indexed. Keep it for review deployments.
4. Add the canonical URL `https://2690.ai/` and production Open Graph/Twitter metadata. Add a social preview image if desired.
5. Verify the live page at desktop and phone widths, including navigation anchors, founder links, images, and the booking link.

Current booking destination: https://cal.com/mattlady/2690-fit-call

Current contact email: matt@enterprisevibecode.com

Update the email only after its replacement mailbox is working. No credentials are required by the website.

## Content and design constraints

Preserve the maroon and pale-blue theme, useful diagrams, visible FAQ/scope content, and the content-sized mobile hero. There are two booking CTAs. The qualified initial review is at no charge, with follow-up within one week of receiving agreed materials. This does not promise a free implementation.

The source keeps founder career experience separate from agency client results. Commercial terms and pricing remain as approved in the page.
