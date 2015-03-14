---
layout: page
---

## Demos

+ [Horizontal Carousel](demo/horizontal/)
+ [Vertical Carousel](demo/vertical/)

## Download

### CSS

+ [infinite-carousel.css](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.css) *or*
+ [infinite-carousel.min.css](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.min.css)

### JavaScript

+ [infinite-carousel.js](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.js) *or*
+ [infinite-carousel.min.js](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.min.js)

## Usage

Infinite Carousel works with a container element and a set of child item elements.

### Markup

{% highlight html %}
<div class="infinite-carousel-shell">
  <div id="container" class="infinite-carousel-group">
    <div class="infinite-carousel-group-item">1</div>
    <div class="infinite-carousel-group-item">2</div>
    <div class="infinite-carousel-group-item">3</div>
    <div class="infinite-carousel-group-item">4</div>
  </div>
</div>
{% endhighlight %}

### JavaScript

{% highlight javascript %}
/**
 * Required arguments are:
 * - a container element (string)
 * - a direction ('horizontal' or 'vertical')
 * - the number of items that are visible at once
 */
var infinitecarousel = new InfiniteCarousel('#container', 'horizontal', 3 {
  // optional options object (defaults are listed)

  timerDuration: 2000,
  // set time between advances in milliseconds

  transitionDuration: '1s'
  // the duration of the animation
});
{% endhighlight %}

## Browser Support

Tested in the latest versions of:

+ Chrome
+ Firefox
+ Opera
+ Safari

## License

Infinite Carousel is released under the [MIT license](https://github.com/jonchretien/infinite-carousel/blob/master/LICENSE.txt).