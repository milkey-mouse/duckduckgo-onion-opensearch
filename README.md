# DuckDuckGo Onion HTML Opensearch

This is a custom [`opensearch.xml`](opensearch.xml) for [DuckDuckGo's onion site](https://3g2upl4pq6kufc4m.onion/). Visiting this page allows you to install the no-JS version of the onion site as your default search engine.

On the highest "security level" in Tor Browser, no JavaScript is executed, so whenever one searches you're redirected from the main search page to the HTML-only version. This redirect could easily be avoided if DuckDuckGo provided an opensearch meta tag for the HTML-only onion site. There are separate opensearch.xml files for the other 3 possible combinations (DuckDuckGo JS clearnet, DuckDuckGo HTML clearnet, DuckDuckGo JS onion) but not for the no-JS onion site.

Until now!
