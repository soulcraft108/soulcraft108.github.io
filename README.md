# Soulcraft108 website (for the Pinterest app review)

Two static pages Pinterest requires for the app request: a standalone home page (`index.html`) and a privacy
policy (`soulcraft108-privacy-policy.html`), with shared `style.css`. No scripts, no cookies, no third-party
requests. Source of truth is this folder; the live copy is the `soulcraft108/soulcraft108.github.io` repo.

Live URLs once published:

- Website: https://soulcraft108.github.io/
- Privacy policy: https://soulcraft108.github.io/soulcraft108-privacy-policy.html

## Publish (one time, owner)

1. On github.com, signed in: avatar > Your organizations > New organization > Free plan. Name it `soulcraft108`.
   (If the name is taken, pick another that contains "soulcraft108" and tell Claude, since every URL changes.)
2. In the new org, create a **public** repo named exactly `soulcraft108.github.io` (empty, no README).
3. Add that repo to the Claude session (or upload the files in this folder to it, including `.nojekyll`).
4. Repo Settings > Pages: Source "Deploy from a branch", branch `main`, folder `/ (root)`. Wait 1-2 minutes.
5. Open both URLs above in a private window and check they load.

## Updating

Edit the files here, commit, then copy them to the `soulcraft108.github.io` repo. If the policy changes, update its
effective date.
