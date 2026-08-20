# AdCut.app — Production Website

Static HTML website prepared for Cloudflare Pages.

## Deploy
1. Create a GitHub repository, for example `adcut-app`.
2. Put the contents of this folder at the repository root.
3. In Cloudflare: Workers & Pages → Create → Pages → connect the repository.
4. Framework preset: None.
5. Build command: `exit 0`.
6. Build output directory: `/` (the repository root).
7. Deploy.
8. In the Pages project, add custom domain `adcut.app`.
9. If `adcut.app` is an apex domain, Cloudflare requires the domain to be a Cloudflare zone with nameservers pointed to Cloudflare.
10. Add `www.adcut.app` as a redirect to `https://adcut.app`.

The site contains:
- `/` homepage
- `/download`
- `/privacy`
- `/support`
- `/about`
- `/changelog`
- `/404`

## Before public launch
- Replace the "Coming soon" browser-store buttons with the final Firefox/Chrome listing URLs.
- Configure a real support/contact email or support form.
- Confirm the PayPal destination.
- Verify all product claims and usage statistics before publishing.
