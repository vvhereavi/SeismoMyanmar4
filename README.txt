SeismoMyanmar — images/ folder
==============================

Files in this folder:
  favicon.svg        — site favicon (referenced from each HTML page's <head>)
  avatar-zth.svg     — placeholder avatar for "Zay Thura Htet" (About Us page)
  avatar-syte.svg    — placeholder avatar for "Shwe Yee Thoon Eain" (About Us page)
  avatar-zbmh.svg    — placeholder avatar for "Zwe Bhone Man Htet" (About Us page)

Replacing placeholders with real photos:
  Drop your real headshot photos into this folder, e.g.:
    ZTH.jpeg
    Syte.png
    ZBMH.jpeg
  Then edit about-us.html and change the three <img src="images/avatar-*.svg">
  references to point at your real files (e.g. <img src="images/ZTH.jpeg">).
  Keep the same CSS classes (w-full h-full object-cover) so the circle
  crop is preserved.
