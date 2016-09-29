this is an toy to emulate the sort of mobile friendly lightbox effect
seen on facebook instant articles.

when holding a phone in the default portrait orientation, tapping on a
landscape picture will enlarge it to fill the whole screen. tilting the
phone left-right will slide the off screen parts of the image into view.

things to do:
- instead of ±90°, limit tilting to ±30° or similar
- filter for visible elements so we don't unnecessarily animate
  everything
- add helper functions to initialize script (eg only certain images, or
  all images on load, etc)
- integrate it with our normal lightbox lib
