# MBChooChoo, LLC website

A buildless GitHub Pages site containing only public website files. No app source code, credentials, forms, JavaScript, analytics, external fonts, or dependency installation is needed.

## Publish

1. Sign in to GitHub as `mbchoochoo26` and create a public repository named **mbchoochoo26.github.io**. If it already exists, inspect it before replacing anything.
2. Upload the **contents** of this `github-pages` folder to the repository root: `index.html`, `support.html`, `privacy.html`, `styles.css`, `.nojekyll`, and the `assets` folder. Do not upload the entire app workspace. The `index.html` file must be at the repository root, not inside another `github-pages` folder. GitHub's web upload accepts files and folders; drag the `assets` folder along with the HTML and CSS files.
3. Open repository **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Wait for GitHub Pages to finish deployment, then open the URLs below. Check each page on a phone and desktop. Enable **Enforce HTTPS** if it is not already enabled.

## Public URLs after deployment

- Company website: https://mbchoochoo26.github.io/
- App privacy policy: https://mbchoochoo26.github.io/privacy.html
- App support: https://mbchoochoo26.github.io/support.html

These URLs are planned destinations until GitHub reports a successful deployment.

## Apple enrollment

Use the homepage as the organization website, the privacy URL in App Store Connect's Privacy Policy URL field, and the support URL as the app's Support URL. Apple decides whether the organization website satisfies enrollment verification. Apple requires a publicly available, functional website on a domain associated with the organization and says minimal-content websites are not accepted. Its documentation does not explicitly approve or prohibit GitHub Pages subdomains.

Apple separately requires a work email associated with the organization's domain. The public Gmail support address in this site does not meet that work-email requirement. A custom domain with email hosting may still be needed for enrollment. GitHub Pages can serve the same site on a custom domain later; it does not provide email hosting.

## Content and privacy

Legal name and public contact were supplied by the owner: MBChooChoo, LLC; mbchoochoo26@gmail.com. App behavior was checked against the current Swift source, bundled policy, and privacy manifest on November 11, 2026. Support-email handling and GitHub hosting disclosures are described separately from app data collection. The current website contains no App Store download link because no published listing was supplied. The image is an existing app preview; it may differ from the latest build.

Review the policy when app behavior, support practices, hosting, or SDKs change. The policy makes no claim of legal certification or guaranteed Apple approval.

## Local preview

From this directory run `python3 -m http.server 8787 --bind 127.0.0.1`, then open http://127.0.0.1:8787/.

## References

- https://developer.apple.com/programs/enroll/
- https://developer.apple.com/app-store/review/guidelines/#privacy
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
