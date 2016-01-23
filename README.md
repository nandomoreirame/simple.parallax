jQuery SimpleParallax
=====================

[demo](http://nandomoreira.me/simple.parallax/)

### Usage

Include jQuery and simple.parallax.js scripts in your HTML

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="js/simple.parallax.js"></script>
```

Add the JS

```js
$(document).ready(function() {
  $('.parallax').sparallax();
});
```

Add the CSS

```css
.parallax {
  background-repeat: no-repeat;
  background-position: 50% 0;
  -webkit-transition: background-position .2s ease-in;
  -moz-transition: background-position .2s ease-in;
  -o-transition: background-position .2s ease-in;
  transition: background-position .2s ease-in;
  -webkit-background-size: cover;
  background-size: cover;
}
```

Add class `parallax` in your HTML

```html
<section class="parallax" data-parallax-speed="10">
  <div>Your parallax container...</div>
</section>
```

---

### Copyright and license

It is under [the MIT license](/LICENSE).

Enjoy :yum:
