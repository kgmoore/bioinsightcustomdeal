# bioinsightcustomdeal.org

Public interstitial for the BioInsight custom deal Jira service desk.

People hitting this URL often are not on Illumina VPN. The page warns them, then
redirects to:

https://jira.illumina.com/servicedesk/customer/portal/2

## Live (GitHub Pages)

While the custom domain is being pointed, the same page is served from:

https://kgmoore.github.io/bioinsightcustomdeal/

## Custom domain

1. Register `bioinsightcustomdeal.org` (any registrar).
2. Add DNS records for GitHub Pages (Apex or `www` — see GitHub docs for current IPs / `CNAME`).
3. In the GitHub repo **Settings → Pages**, confirm custom domain `bioinsightcustomdeal.org` and enable HTTPS once DNS propagates.

This folder is the source of truth. The public GitHub repo mirrors these files for hosting.
