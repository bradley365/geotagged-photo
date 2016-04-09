# geotagged-photo
HTML5 single page app to create a CSV file from GPS tagged photos for mapping.

###Description
This app reads the GPS-related EXIF tags from photos taken with a device using location services with the camera. *The photos and the EXIF tags are not uploaded to a server* but are read and the information is presented on your browser by a JavaScript.  This app uses a cache-manifest to store the html and JavaScripts in the browser's cache so it can be used when a network connection is not available.

It has been tested on Opera 36.0, Chrome 49.0 (Android & Windows), Firefox 42, Internet Explorer 11, Safari 9 (iPhone).  Because iOS does not allow downloading files, the CSV data is presented in a new window where it can be copied to a message or email.

Tips for using the GPS data in a mapping application are included at the bottom of the page after selecting photos.

See a [Demo](http://bradley365.elementfx.com/geotagged-photo/).


###Attribution
Original source of the [exif-js](https://github.com/exif-js/exif-js) library use in this app : [exif-js and contributors - https://github.com/exif-js/exif-js](https://github.com/exif-js/exif-js).

*exif.js modified*: [bradleyn365](https://github.com/bradley365), March2016

*CDN's/API's* used in this app:

[Font Awesome by Dave Gandy - http://fontawesome.io](http://fontawesome.io)

[Google Fonts (Roboto) https://www.google.com/fonts](https://www.google.com/fonts)


###License
The MIT License (MIT)

Copyright (c) 2016 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
