# golink

Private shortlink service from Tailscale for a tailnet.

**Source:** [https://github.com/tailscale/golink](https://github.com/tailscale/golink)

## Custom Search Provider

To make it easier to use, set up a custom search provider in your browser.

In Vivaldi, go to Settings → Search and add a new search engine:
- **Name:** golink
- **Nickname:** go
- **URL:** `http://go/%s` (or `https://go/%s` if using HTTPS)

Once configured, type `go <shortlink>` in the address bar to navigate.

Similar setup is available in Chrome, Firefox, and Edge.
