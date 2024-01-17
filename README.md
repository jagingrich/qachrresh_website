# Interactive Map: Archaeology of Qach Rresh

Code, text, images, and GIS files that support this interactive map: Jared Gingrich, January 17, 2024

This repository contains the text and images (.txt and .jpg files) that are read by the web map to load the descriptions that accompany the features of the interactive map. Updating or replacing the files in the Data tree of this repository will update the descriptions and images of the web map. Uploading additional description files/directories with corresponding web identifiers to the features file(s) will add additional description options to the map.

QachRreshInteractivePlan.html is the most up-to-date version of the code for the interactive web map. index.html is the stable verison of QachRreshInteractivePlan.html used for web hosting. Functions that build and update the interactive map are contained in QachRreshInteractivePlan.js, while web formating can be found in QachRreshInteractivePlan.css. Separately, the standalone text read/format function is located in formatText_js.js, which allows for formating text from a web-hosted .txt file for html output, based on input formatting characteristics.  

**File Upload and Naming Notes:**
* Text description files should be a .txt file, ideally with UTF-8 encoding
* Image files should be in .jpg format
* Image files should all have the same name with a sequential image tag ("Image1", Image2", etc.) that corresponds to the order in which they will be displayed
* The number of image files should correspond to the number of captions in the text description file:
  * If there are fewer captions than images in the corresponding directory, not all images will be displayed
  * If there are more captions than images in the corresponding directory, the additional captions will not have images attached
