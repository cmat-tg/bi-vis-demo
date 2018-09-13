# Setup
`cd` to root project directory.

`npm install`

`npm start`

Page should be running on localhost:8080 now.  The BI iframes can take a moment to load.  Currently the old BI iframes are still present, will need to swap them out (see TODO below).

## TODO
Will need to swap out the iframe IDs on lines: 94 and 98 of `index.html` with the new IDs of the published Power BI dashboards.

Dashboards are in `./vis`.  There are two of them, one for each nav tab in `index.html` with an assocaited name "Detailed View" and "Executive View".  Will need to publish each separately in order to get two different iframes to put on each tab.

Currently iframe sizing (may need to be tweaked):
`width="1200" height="700"`