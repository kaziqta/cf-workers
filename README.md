#A combination of:

* [Bypass Cache on Cookie](https://github.com/pmeenan/cf-workers/tree/master/cache-bypass-on-cookie) - bypasses cache for logged users (WordPress in that case)
* [Fast Google Fonts](https://github.com/cloudflare/worker-examples/tree/master/examples/fast-google-fonts) - Rewrites the HTML and puts the browser-specific Google Fonts CSS directly in the HTML (eliminating the round trips for fetching the CSS and improving overall page rendering performance). Proxies the font files through the same domain as the page, eliminating the round-trips to connect to Google's servers and allowing HTTP/2 priorities to work correctly.
