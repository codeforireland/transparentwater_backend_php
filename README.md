# codeforireland-water-pwa
Frontend progressive web app for Code for Ireland Transparent Water project.

This is a minimal progressive web app with a map interface that calls the water data via XHR. 

# Back end

The async function getData handles the data call. Needs to be updated to retrieve and store data locally for offline use.

# Installation

Needs to be on an SSL webserver, and you'll need to modify the manifest.json file to reflect its location if you don't choose the same directory name. Otherwise no installation other than uploading the files.

# Icons

Should be in a directory images/icons as per manifest.json.

# Offline

While there's an offline.html as required by PWA spec, it doesn't really do anything. Similarly, the ServiceWorker file sw.js is not so much minimal as dummy. There are options for loading Leaflet map tiles offline - see: https://stackoverflow.com/questions/43608919/html-offline-map-with-local-tiles-via-leaflet

# UI

Could do with some work!
