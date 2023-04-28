# jQueryCarousel: Simple jQuery Infinite Carousel

jQueryCarousel is a lightweight, easy-to-use, and responsive infinite carousel plugin built with HTML and jQuery. It allows you to showcase images or content in an infinite loop, making it perfect for displaying portfolios, product showcases, or any other content that needs a smooth scrolling experience.

## Features

- Infinite looping
- Responsive design
- Touch swipe support
- Customizable through CSS
- Lightweight and easy to integrate
- Supports navigation controls and pagination

## Prerequisites

- jQuery 1.7 or higher

## Installation

1. Clone this repository or download the ZIP file:

```bash
git clone https://github.com/yourusername/jQueryCarousel.git
```

2. Add the jQuery library and jQueryCarousel files to your HTML file:

```html
<!-- Add jQuery -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

<!-- Add jQueryCarousel CSS -->
<link rel="stylesheet" href="path/to/jquery.carousel.css" />

<!-- Add jQueryCarousel JS -->
<script src="path/to/jquery.carousel.js"></script>
```

3. Create an HTML structure for your carousel:

```html
<div class="carousel">
  <div class="carousel-items">
    <div class="carousel-item">
      <!-- Your content here -->
    </div>
    <!-- Add more carousel-item elements as needed -->
  </div>
</div>
```

4. Initialize the carousel using jQuery:

```javascript
$(document).ready(function() {
  $('.carousel').jQueryCarousel();
});
```

## Options

You can customize the behavior of the carousel by passing an options object to the `jQueryCarousel()` function:

```javascript
$('.carousel').jQueryCarousel({
  autoplay: true,
  autoplaySpeed: 3000,
  pauseOnHover: true,
  swipeThreshold: 50,
  arrows: true,
  pagination: true
});
```

- `autoplay`: Enable or disable autoplay (default: `true`)
- `autoplaySpeed`: Autoplay speed in milliseconds (default: `3000`)
- `pauseOnHover`: Pause autoplay when hovering over the carousel (default: `true`)
- `swipeThreshold`: Minimum swipe distance to trigger navigation (default: `50`)
- `arrows`: Show or hide navigation arrows (default: `true`)
- `pagination`: Show or hide pagination (default: `true`)

## Contributing

Contributions are welcome! Please open an Issue or Pull Request to suggest improvements, bug fixes, or add new features.

## License

This project is made available under the MIT License. See the [LICENSE](LICENSE) file for details.
