GitHub label manager
====================

Simple single-page application to manage labels for GitHub issues/PRs.

Features:
---------

 - Supports labelling PRs on repositories where issues are disabled. ~~this isn't possible with the normal GitHub UI (yet?).~~ **GitHub now supports this natively: https://github.com/blog/1866-the-new-github-issues**
 - Uses the official GitHub API entirely from the client-side/browser.
 - Built using jQuery, Foundation, FontAwesome, Moment and jQuery.Linq.

**Disclaimer:** I built this as a playground for the GitHub API and jQuery, so use at your own risk.

Usage:
------

Open http://akoeplinger.github.io/github-label-manager and click on the wrench icon on the top right.
Enter the repository you want to view and a personal access token from your GitHub settings.
The token is saved in your browsers `localStorage` and doesn't get sent anywhere other than to GitHub.

After clicking "Save", the issue/PR list should start loading. 

**Note:** if you just need read-only access e.g. to view issues/PRs, leave out the token.
