# download-product-images
Implement download of product images on  product pages in Shopify

Using JSZip - https://stuk.github.io/jszip/ - to create a zip download of all product images on a product page in Shopify.
Useful on wholesale sites where customers would like a copy of product images.

To use, create a snippet called 'image downloader' and copy code to that snippet.

Adjust code for the theme you are working with; ie button classes.

Decide where you want the download button to display and render the snippet to the product template.

The zipped file will be the product handle and the images zipped in the file will have the product handle with sequential numbers to the end of each file name.
