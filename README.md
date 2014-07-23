GitHub label manager
====================

Simple single-page application to manage labels for GitHub issues/PRs.
Supports labelling PRs on repositories where issues are disabled, this isn't possible with the normal GitHub UI (yet?).
Uses the official GitHub API entirely from the client-side/browser.

Built using jQuery, Foundation, FontAwesome and a few other libraries.

Open https://akoeplinger.github.io/github-label-manager and click on the wrench icon on the top right.
Enter the repository you want to view and a personal access token from your GitHub settings.
The token is saved in your browsers `localStorage` and doesn't get sent anywhere other than to GitHub.

*Note* if you only need read-only access e.g. to view issues/PRs, leave out the token.
