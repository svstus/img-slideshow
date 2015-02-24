img-slideshow
============

See the [github page](https://svstus.github.io/img-slideshow/components/img-slideshow/) for more information.

## Summary

An simple element to display multiple images as slideshow.

### Example

```html
<link rel="import" href="../core-animated-pages/transitions/cross-fade.html" >
<img-slideshow width="1248" height="462" transitions="cross-fade-all" duration="3000"
      srcs='["images/01.jpg",
      "images/02.jpg",
      "images/03.jpg",
      "images/04.jpg"]'>
</img-slideshow>
```
### Attributes

#### srcs

List of images to be displayed.

#### trasitions

Space separeted list of transtions to be used in between pages.

#### width

Width of all images.

#### height

Height of all images.

#### duration

Time interval in between switching images.
