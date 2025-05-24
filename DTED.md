 Downloading SRTM DTED2 elevation models from USGS.

This is all gonna be a text how-to - a bit late to do screenshots. This is a HOWTO on loading DTED on to your ATAK EUD so you can use the "Elevation Tools" function on ATAK.

This is for individual tiles. And manually loading digital elevation onto the /atak/DTED folder. Check the CivTAK wiki for instructions to download batches of DTED data to ATAK.
THIS IS NOT A VECTOR ELEVATION MAP (CONTOURS, ETC.)

Now on to download and loading DTED tiles on your TAK EUD.

Downloading from web.

Step 1: Register for an account at https://earthexplorer.usgs.gov/

Step 2: Enter Search Criteria - Highlight your desired location. (Easiest is to zoom in to the map region you wanna download and "Use Map"

Step 3: Click "Results" - Select the files that are for that region (Download Icon) - Download the "DTED 1 Arc-second" file. Download what you need.

Loading onto ATAK.

You gotta rename the files for ATAK to recognize the DTED files. Take note of the lat/long on the file naming convention.

    Original File from USGS: s99_e122_1arc_v3.dt2

    Make Folder on ATAK Device: e122 (or) /atak/DTED/e122/

    Rename: s99_e122_1arc_v3.dt2 > s99.dt2

    Move: s99.dt2 to /atak/DTED/e122

    Final: /atak/DTED/e122/s99.dt2

Restart ATAK and when you're done.

https://github.com/rick51231/atak-dted-dp-downloader
https://github.com/rick51231/atak-dted-dp-downloader/releases/tag/v.1.0.0
