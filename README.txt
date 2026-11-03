RipeVision updated research website
====================================

Contents
- index.html: standalone website with the RipeVision research section, 10 survey charts, searchable response table, and audio players.
- data/survey-data.json: survey response and chart data used to build the page.
- assets/audio/industry-interviews/: 6 clips from Ripe_Vision_Interview2_Clips 1.zip
- assets/audio/individual-interviews/: 5 clips from Ripe_Vision_Interview_Individual_Clips 1.zip

Deploy
1. Unzip this package.
2. Open index.html locally to preview (internet is needed for Google Fonts and Chart.js CDN).
3. Back up the current GitHub repository before replacing files.
4. Upload index.html, data/, and assets/ into the root of the RipeVision repository, preserving folder structure.
5. Commit changes. GitHub Pages will publish the update after it rebuilds.

Privacy
The response table excludes timestamps but still contains submitted survey answers. Confirm permission to publish the responses before keeping the repository public. Audio clips are also public once pushed to a public GitHub repository.

Audio format
Original M4A clips are preserved. Browser support for M4A varies; current Chrome/Edge should generally play them. If a clip fails, convert it to MP3 and update its path in index.html.
