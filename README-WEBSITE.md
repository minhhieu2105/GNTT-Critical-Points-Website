# CCP Critical Points website

The static site is in the website folder and contains three public pages:

- index.html — application homepage
- privacy.html — privacy policy
- terms.html — terms of service

The GitHub Actions workflow at .github/workflows/deploy-website.yml publishes the website folder to GitHub Pages after Pages is enabled for this repository.

## Enable GitHub Pages

In the repository, open Settings → Pages and choose GitHub Actions as the build and deployment source. The first deployment normally provides a preview URL at:

https://minhhieu2105.github.io/GNTT-Critical-Points-Website/

## Use a domain you own for OAuth brand verification

Google requires the application homepage and privacy policy to be hosted on a verified domain owned by the project owner. The shared GitHub Pages address is useful for previewing the site. Google requires a verified domain owned by the project owner, so do not submit the shared address unless you can verify that exact domain in Google Search Console. A custom domain you control is the reliable option.

After choosing a domain you own:

1. Add the custom domain in Settings → Pages.
2. Create the DNS record requested by GitHub Pages at your domain provider.
3. Verify the domain in Google Search Console using an account that is an owner or editor of the Google Cloud project.
4. Use URLs on that same domain for the homepage, privacy policy, and terms.
5. Add the owned domain to OAuth Authorized domains, then submit Verify branding.

The privacy policy should stay aligned with the actual OAuth scopes and the Google Sheets/Drive account and access permissions configured for the app.
