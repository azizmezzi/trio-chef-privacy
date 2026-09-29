# Trio Chef — Privacy & Support

Official public website for the Trio Chef privacy policy and support contact.

## Published pages

- `index.html` — Trio Chef home and support page
- `privacy.html` — privacy policy for the current release

The site is static, has no build step, and uses no cookies, analytics, trackers, or external assets. It is designed to be hosted directly with GitHub Pages.

## Privacy verification

The policy was checked against the local Trio Chef 1.0 source on September 29, 2026. The reviewed release:

- works offline and requires no account or custom backend;
- stores progress, settings, earned in-game currencies, cosmetics, tutorial state, and aggregate play counters locally through the app (subject to device-level backup settings);
- has no production advertising, in-app purchasing, analytics, or remote crash-reporting SDK;
- does not request access to location, contacts, photos, camera, or microphone; and
- includes a mock rewarded-ad service only in development builds.

Re-review the policy and store data-safety declarations before publishing any release that adds network services, advertising, purchases, accounts, cloud saves, analytics, or crash reporting.

## GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, then select the repository's default branch and the root (`/`) folder. GitHub Pages will serve the site over HTTPS.

## Local preview

Open `index.html` directly in a browser, or run a simple static file server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Support

Email [triochef.support@gmail.com](mailto:triochef.support@gmail.com).
