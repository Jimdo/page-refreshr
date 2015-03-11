# page-refreshr
Opens a given url in a fullpage width/height iframe and refreshes it by given interval (in seconds).
Useful e.g. to refresh frozen jimdash dashboards. Less raspberry pi rebooting necessary.

It's hosted on Github pages, no further setup needed.

## Usage
http://jimdo.github.io/page-refreshr/?interval=60&url=http://jimdo.com

### Url parameter:
Url parameter needs to be encoded, e.g. no `?` or `=` should be in there.

Won't work:
`http://jimdo.com?foo=bar`

Will work
`http://jimdo.com%3Ffoo%3Dbar`

Tested in Chrome only.
