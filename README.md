# HearthTerm website

Public product, privacy, and terms pages for HearthTerm by Gosh Apps.

This repository contains the website and its assets. HearthTerm is proprietary
software; see [LICENSE.txt](LICENSE.txt) for the application license.

## Hosting

GitHub Pages publishes the `main` branch at its root. `.nojekyll` keeps the site
buildless. All CSS, icons, and screenshots are served from this repository;
there are no third-party scripts, analytics, or font requests.

The public site is intended to be available at:

https://goshitsarch-eng.github.io/hearthterm-site/

## Editing

Edit `index.html`, `privacy.html`, `terms.html`, and `assets/site.css`, then push
the changes to `main`. GitHub Pages will publish the updated files. Keep the
privacy policy consistent with the application's actual behavior and update
its effective date when its practices change.

## Custom domain and Google OAuth

The website can also be served from an owned custom domain through GitHub Pages.
Add that domain in the repository's Pages settings and configure its DNS using
[GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

Google's OAuth domain-verification guidance requires a Search Console Domain
property verified through DNS by a Google Cloud project owner. Publishing a
GitHub Pages site does not complete that verification or Google OAuth review.
See [Google's domain verification instructions](https://support.google.com/cloud/answer/13804266?hl=en).

When switching domains, update the canonical/social URLs, `robots.txt`, and
`sitemap.xml`, as well as the Google OAuth home-page and policy links.

## Contact

Email [linouser@gmail.com](mailto:linouser@gmail.com).
