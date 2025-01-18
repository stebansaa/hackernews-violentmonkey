# HackerNews Enhanced Readability

A Violentmonkey/Tampermonkey userscript that enhances the readability of Hacker News while preserving its minimalist design philosophy. This script improves typography, spacing, and overall reading experience without compromising the site's familiar layout.

## Installation

1. Install a userscript manager for your browser:
   * [Violentmonkey for Chrome](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)
   * [Violentmonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/)
   * [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   * [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

2. Install the script:
   * Click the "Install" button above, or
   * Create a new script in your userscript manager and paste the content of `hn-readability.user.js`

## Features

* **Improved Typography**
  * Larger, more readable font sizes
  * Optimized line height and spacing
  * Better contrast ratios
  * Preserved Verdana font family

* **Enhanced Layout**
  * Optimal content width
  * Subtle visual separation between items
  * Improved vertical rhythm
  * Responsive design for all devices

* **Accessibility**
  * Clear focus indicators
  * Enhanced color contrast
  * Better keyboard navigation
  * Improved text scaling

## Customization

Edit these variables in the script to customize the appearance:

```javascript
// Font size (default: 18px)
--hn-font-size-base: 18px;

// Content width (default: 1000px)
--hn-max-width: 1000px;

// Text color (default: #222)
--hn-text-color: #222;
```

## Browser Support

* Chrome/Chromium (latest)
* Firefox (latest)
* Safari (latest)
* Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

## License

[MIT License](LICENSE)

## Version History

* **2.4.0**
  * Enhanced visual hierarchy
  * Improved mobile responsiveness

* **2.3.0**
  * Added customization options

* **2.2.0**
  * Improved accessibility features

* **2.1.0**
  * Initial release

## Support

Open an issue on GitHub if you need help or want to report a bug.
