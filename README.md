# Fwd45 privacy policy site

Static GitHub Pages site for the privacy notice for **Was ich dich fragen wollte**.

## Publication status

`index.html` is a draft, not an approved legal notice. Do not use it as the App Store privacy-policy URL until the draft warning is removed and the following points are confirmed by Fwd45:

- Actual RevenueCat data fields, subprocessors, retention, and any transfers outside the EEA
- Contractual roles and legal bases for each processing purpose
- Final review of local storage and backup behavior on supported iOS and Android versions
- Approval of the policy text and publication date

The page is intentionally self-contained and does not load external fonts, analytics, or scripts.

## GitHub Pages setup

1. Create a public repository named `fwd45-privacy` under the Fwd45 GitHub account.
2. Push `index.html` to the root of the `main` branch.
3. In repository **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After the site is live at its `github.io` URL, configure the custom domain `datenschutz.fwd45.com` in **Settings > Pages**.
5. At the DNS provider for `fwd45.com`, create a `CNAME` record named `datenschutz` pointing to `lamess1.github.io` (or the GitHub Pages hostname shown in repository settings).
6. If GitHub offers domain verification, add its requested TXT record before enabling Pages on the custom domain.
7. Wait for GitHub to verify DNS and provision its HTTPS certificate, then enable **Enforce HTTPS**.
8. Confirm `https://datenschutz.fwd45.com` works before adding the same URL to App Store Connect and linking it from the app.

The repository contents and published page are public. Do not store credentials, customer data, or other private files here.
