# bioinsightcustomdeal.org

Public interstitial for the BioInsight custom deal Jira service desk.

People hitting this URL often are not on Illumina VPN. The page warns them, then
redirects to:

https://jira.illumina.com/servicedesk/customer/portal/2

## Live now

https://kgmoore.github.io/bioinsightcustomdeal/

## Attach bioinsightcustomdeal.org later

1. Register `bioinsightcustomdeal.org`.
2. Add a `CNAME` file in this repo containing `bioinsightcustomdeal.org`.
3. Point DNS at GitHub Pages (A records for apex, or CNAME for www).
4. In **Settings → Pages**, set the custom domain and wait for HTTPS.
