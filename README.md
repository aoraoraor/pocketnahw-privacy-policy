# Pocket Nahw: privacy policy

The public privacy policy of the **Pocket Nahw** Arabic grammar app, in Arabic and English, served by GitHub Pages:

**https://aoraoraor.github.io/pocketnahw-privacy-policy/**

- `index.html` is the whole site: one self-contained page (no external scripts, fonts, cookies or analytics). Arabic and English are on the same page; `?lang=ar` or `?lang=en` picks the language, otherwise the browser language does.
- The app opens this URL from «المساعدة والخصوصية» → «سياسة الخصوصية» (`privacyPolicyUrl` in `nahw_app_2/lib/services/external_links.dart`), adding `?lang=` for the app's language. Use the same URL in Google Play Console → App content → Privacy policy.

## Hosting

GitHub → this repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save. The site is live a minute later.

## Updating

Edit both languages in `index.html` and change the "Last updated" date in both. Keep the policy in step with the app's real data practices (`nahw_app_2/docs/ANALYTICS.md`, `docs/BACKUP_RESTORE.md`) and with the Play Console Data safety form.

© 2026 Ahmed Orabi. All rights reserved.
