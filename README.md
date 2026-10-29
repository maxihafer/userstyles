# userstyles

Userstyles for [Stylus](https://github.com/openstyles/stylus).

## GitLab – Vercel Dark

GitLab themed with the colors of Zed's Vercel Dark theme.

### Install

1. Install the Stylus extension ([Chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Firefox](https://addons.mozilla.org/firefox/addon/styl-us/)).
2. Open [gitlab-vercel-dark.user.css (raw)](https://raw.githubusercontent.com/maxihafer/userstyles/main/gitlab-vercel-dark.user.css). Stylus shows its install page.
3. Click **Install style**.
4. In GitLab, go to **Preferences** and set **Color theme** to **Dark**.

Stylus checks the repo for updates automatically. To update right away, open the Stylus manager and click **Check for updates**.

### Domains

The style applies to `gitlab.com` and any host starting with `gitlab.` (for example `gitlab.example.com`). For other hosts, edit the `@-moz-document` line in the Stylus editor.

### Development

1. In your browser's extension settings, enable **Allow access to file URLs** for Stylus.
2. Open the local file via `file:///path/to/userstyles/gitlab-vercel-dark.user.css`.
3. Enable **Live reload** on the install page and keep the tab open.

Edits to the file then apply immediately. Bump `@version` when pushing so installed copies pick up the update.
