# simple-jquery-slideshow
**Simple jQuery-based slideshow to showcase photographer portfolio and EXIF metadata of each image**

 This is a simple webpage that has all <script> inline to discover all images inside /images directory and load them as <figure> in the html. Then it **shuffle** the order of <figure> tags to show/hide in the **slideshow**. Images are **lazy loaded** and the script load the next image while showing the current image.

 The script also read the EXIF and XMP metadata and add them as <figcaption>. It extract and show
 * original date of photoshoot,
 * photographers name,
 * camera model,
 * exposure time,
 * F number,
 * ISO,
 * focal length, and
 * keywords
 in the metadata.


 ### How to use
 Just add your photos in /images directory and browse the index.html. You cand edit the index.html as your need.
 [Demo Slideshow](https://sghiaseddin.com/demo-slideshow/)


 ### Contribution
 The following codes has been used as vendor without any changes:
 * [Exif.js](https://github.com/exif-js/exif-js)
 * [XMP Parser](https://github.com/semeniuk/xmp-js)


 ### Changelog
 * v1.0.0 initial release
