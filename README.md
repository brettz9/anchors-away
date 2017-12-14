# anchors-away

[![Greenkeeper badge](https://badges.greenkeeper.io/brettz9/anchors-away.svg)](https://greenkeeper.io/)

Simple file to redirect an HTML page to another page including the anchors.

Since anchors are not sent to the server in regular web requests such that
they can be detected and including in redirects, this HTML file includes
some JavaScript which can do the job.

# Usage

1.  Clone this repository. (This is also available via `npm i anchors-away`, but
    as you'll wish to customize the URL, this approach is not very useful and
    only meant at the moment for discoverability.)
2.  In `index.html`, alter the `<a href>` value to point to your desired webpage.
3.  Optionally customize the rest of the page.

# To-dos

1.  Refactor as a module for importing into one's own HTML.
