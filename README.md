# what is this?

view this page on a phone: <https://gazs.github.io/lightboxie/>

this is an toy to emulate the sort of mobile friendly "tilt-to-explore" lightbox effect
seen on facebook instant articles.

when holding a phone in the default portrait orientation, tapping on a
landscape picture will enlarge it to fill the whole screen. tilting the
phone left-right will slide the off screen parts of the image into view.

# things to do:
- filter for visible elements so we don't unnecessarily animate
  everything
- add helper functions to initialize script (eg only certain images, or
  all images on load, etc)
- load higher res version of image when (while?) zoomed in
- integrate it with our normal lightbox lib

# faq

- why is the sample picture a photo of kristin cavallari?
	- after following [500 days of kristin](http://gawker.com/tag/500-days-of-kristin), a long-running injoke on the late gawker.com, i've been desensitised to this image.
