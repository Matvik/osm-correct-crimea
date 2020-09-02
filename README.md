Open Street Map - Mapbox GL styles to get correct Crimea borders. 
==================================================================

Unfortunately, due to the annexation of Crimea by the Russian Federation, it is shown on Open Street Maps as a disputed territory with a double border. At the same time, we want to see it as part of Ukraine.

For correct work, please register on the service [cloud.maptiler.com](https://cloud.maptiler.com/) and get your acccess key there. Then replace `<YOUR MAPTILER KEY>` with this key in file `ukraine_correct_crimea_uk.json` (or `ukraine_correct_crimea_en.json`) on the lines 3 and 18.

By default, the map is in Ukrainian. If you want to have latin labels - uncomment line 36 and comment line 35 in `index.html` to change included style file.

Feel free to change styles according to your wishes.
