# Kiva site (retired)

This repository hosted the site for
[Kiva](https://github.com/codetakt/kiva).

The site has moved to [https://kiva.software](https://kiva.software),
and its source code is now maintained in
[codetakt/kiva-site](https://github.com/codetakt/kiva-site).

This repository is retired and is planned to be archived. The remaining
`index.html` only redirects visitors to the new site.

The page uses valid HTML5 with an immediate (0-second) meta refresh, a canonical
URL, and a fallback link. Google Search treats an immediate meta refresh as a
[permanent redirect](https://developers.google.com/search/docs/crawling-indexing/301-redirects#meta-refresh).
This is an HTML redirect, not an HTTP 301 or 308 response; those require
server-side configuration.
