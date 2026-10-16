# balancetest-privacy

Hosts the [Balance Test privacy policy](privacy.md) and [terms of use](terms.md) as a
GitHub Pages site.

**Currently private on purpose.** GitHub Pages on the free plan only serves public
repositories, so the pages go live in two steps when Balance Test ships:

1. Repo → **Settings → General → Danger Zone → Change visibility → Public**
2. **Settings → Pages** → Deploy from a branch → `main` / `/ (root)` → Save

The public URLs will then be:

- Privacy policy: <https://lobicode.github.io/balancetest-privacy/privacy/>
- Terms of use: <https://lobicode.github.io/balancetest-privacy/terms/>

The privacy policy URL goes into Play Console → App content → Privacy policy, and both
are linked from the app's Settings → About screen.

## Updating the documents

The sources of truth are `docs/privacy-policy.md` and `docs/terms-of-use.md` in the
`BalanceTest` repo. After editing them there, mirror both here (only the cross-links
differ: they use the public URLs above).
