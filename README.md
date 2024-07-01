# Zalando HTML Display for Digital Out of Home

# Add images to images folder

Keep the naming convention in such way images don't overide each other, so the total of images can be presented on the day after in random order. 
 >Images should be less than 1Mb preferably. Optimize images before uploading, example like [tinypng](https://tinypng.com/) is great to compress images reducing image filesizes and preserving quality.

* Navigate to the [images folder](https://github.com/dentsucreativestudio/zalando-ooh/tree/main/images) and click on the folder that image should be uploaded.
* Click on the **add file** dropdown button on top left. Select **upload files**. Either drag and drop or select the image from your computer, multiple images are allowed.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The images should be available within +-one minute to propagate in the server.

### Images folders
* Images [Image folder](https://github.com/dentsucreativestudio/zalando-ooh/tree/main/images)

# Data Entry

* Data [Data](https://github.com/dentsucreativestudio/zalando-ooh/blob/main/data/images.js)



### Edit Images:

The images on rotation for the photo shoot day are the top 3 in the list. When adding new images add them above the existing images.
Image path example: 'path/to/url' *// example -> https://dentsucreativestudio.github.io/zalando-ooh/images/zalando1.jpg* <br>

```
var settings = [
  //New images added above
  { image: 'https://dentsucreativestudio.github.io/zalando-ooh/images/zalando1.jpg'},
  { image: 'https://dentsucreativestudio.github.io/zalando-ooh/images/zalando2.jpg'},
  //all other images below
  { image: 'https://dentsucreativestudio.github.io/zalando-ooh/images/zalando3.jpg'},
  ...
];
 ```

* Navigate to [data folder](https://github.com/dentsucreativestudio/zalando-ooh/blob/main/data/) to edit and add new images to the list. 
* Click the **pencil icon** on top right corner to enter into edit mode. Make your chenges.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The data should be available within +-one minute to propagate in the server.





