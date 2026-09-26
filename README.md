# GymDesk — Privacy Policy

The public privacy policy for the GymDesk Android app (`com.rslabs.gymdesk`) and web app,
served as a static page via GitHub Pages.

**Live URLs**
- Privacy policy: https://riyazshaikh16in.github.io/gymdesk-privacy/
- Account deletion: https://riyazshaikh16in.github.io/gymdesk-privacy/delete-account/

These are the URLs the Google Play listing, the Data safety form and the "Delete account URL"
field point at. Play requires a privacy-policy URL that is publicly reachable without a login and
does not expire — hence a separate public repo rather than a page in the (private) app repo.

## Editing

`index.html` and `delete-account/index.html` are the whole site — no build step, no dependencies.
Edit and push to `main`; GitHub Pages redeploys within a minute or so.

When the policy changes in a way that affects what is collected, update the "Last updated" date
near the top of `index.html`, and keep the Play Data safety form in sync.
