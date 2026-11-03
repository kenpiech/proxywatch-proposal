# proxywatch: project proposal

Project proposal for Design, Build, Ship (MPCS 51238, Autumn 2026).

`index.html` is one static HTML file, with no framework and no build step, deployed on Vercel.

The page is meant to be shared by link only. `robots.txt` blocks all crawlers, and the page also sets `noindex, nofollow` in a meta tag and in an `X-Robots-Tag` header (`vercel.json`) for any crawler that fetches it anyway.
