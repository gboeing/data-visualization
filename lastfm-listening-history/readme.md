# Download, analyze, and map Last.fm listening history

To see this analysis live, check out my article ["Analyzing Last.fm Listening History"](http://geoffboeing.com/2016/05/analyzing-lastfm-history/)

This project comprises 5 steps:
  1. Use [lastfm_downloader.ipynb](lastfm_downloader.ipynb) to downloaded your listening history from the [Last.fm API](http://www.last.fm/api)
  1. Use [lastfm_analysis.ipynb](lastfm_analysis.ipynb) to analyze and visualize the downloaded data
  1. Use [musicbrainz_downloader.ipynb](musicbrainz_downloader.ipynb) to download full artist details (including place of origin) from the [Musicbrainz API](https://musicbrainz.org/)
  1. Use [musicbrainz_geocoder.ipynb](musicbrainz_geocoder.ipynb) to geocode and map all the artists you've played
  1. Use [musicbrainz_lastfm_leaflet.ipynb](musicbrainz_lastfm_leaflet.ipynb) to consolidate and dump these lat-long points to GeoJSON for leaflet web mapping
