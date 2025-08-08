# Core Sans R15 Thin Font Hosting

This repository hosts the **Core Sans R15 Thin** font file for use in HTML email styling, particularly in Microsoft Power Automate flows.

## Usage

You can reference the font file using a public URL from GitHub Pages or a CDN like jsDelivr.

### Example CSS

```css
@font-face {
  font-family: 'Core Sans R15 Thin';
  src: url('https://yourusername.github.io/core-sans-font-host/CoreSansR15-Thin.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

.custom-font {
  font-family: 'Core Sans R15 Thin', sans-serif;
  font-size: 16px;
  color: #333;
}

