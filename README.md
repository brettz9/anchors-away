# anchors-away

Simple file to redirect an HTML page to another page including the anchors.

Since anchors are not sent to the server in regular web requests such that
they can be detected and including in redirects, this HTML file includes
some JavaScript which can do the job.

# Usage

1. Clone this repository.
2. In `index.html`, alter the &lt;a href> value to point to your desired webpage.
3. Optionally customize the rest of the page.
