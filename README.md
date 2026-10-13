# TrayMaster pages

Static site for the TrayMaster game, published with GitHub Pages:

- `index.html` - landing page
- `privacy/` - privacy policy
- `delete-account/` - how to request deletion of your data

## Keeping it accurate

The policy and the Play Console Data safety form must match what the game actually does, so update both
when the game's data use changes (and the "Last updated" date in `privacy/index.html`). The contact email
is deepsleepover9000@gmail.com.

## Publish with GitHub Pages

1. Create a GitHub repository (for example `traymaster-pages`) and push this folder to it.
2. In the repository: Settings -> Pages -> Build and deployment -> Source: "Deploy from a branch",
   branch `main`, folder `/ (root)`.
3. The site is then served at `https://<your-github-user>.github.io/<repository-name>/`.
   The privacy policy URL is `https://<your-github-user>.github.io/<repository-name>/privacy/`.

Use that URL in the Play Console (App content -> Privacy policy) and in the game's Settings
(`PrivacyPolicyRow` in `SettingsSectionPanel.prefab`).
