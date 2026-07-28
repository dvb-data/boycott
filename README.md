# Myanmar Boycott List Search

A simple, embeddable search tool for checking if a company or product is on the Myanmar military-linked business boycott list.

## Overview

This is a single-page HTML application that allows users to search and verify whether a company, product, or service is linked to the Myanmar military junta and should be boycotted.

## Features

- **Search**: Type any company or product name to check if it's on the boycott list
- **Category Filter**: Filter results by business category (Banking, Construction, Food & Beverage, etc.)
- **Bilingual Support**: Company names in both English and Myanmar (Burmese) where available
- **Visual Indicators**: 
  - Red cards for boycotted items
  - Green cards for items not found on the list
- **Responsive Design**: Works on desktop and mobile devices

## Categories

The boycott list includes companies across multiple sectors:

| Category | Examples |
|----------|----------|
| Banking and Finance | Myawaddy Bank, Innwa Bank |
| Communications | Mytel, MECtel |
| Construction | Rhino Cement, Tristar Steel |
| Food and Beverage | Dagon Beer, Myanmar Beer |
| Real Estate | Star Bes |
| Transportation | Myawaddy Tours and Travel |
| ...and more |

## Usage

### Standalone

Simply open `boycott.html` in any modern web browser.

### Embed in iframe

```html
<iframe src="boycott.html" width="100%" height="600" frameborder="0"></iframe>
```

### Embed with custom height

```html
<iframe 
  src="boycott.html" 
  width="100%" 
  height="800" 
  style="border: none; max-width: 720px; margin: 0 auto; display: block;">
</iframe>
```

## Data Source

The boycott list is compiled from:
- Justice For Myanmar
- DVB Data Team

> **Note**: The list is subject to change over time. For the latest verification, please check the original sources.

## Brand Names

Most brand/product names are listed in English as they appear on product packaging.

## Technical Details

- Pure HTML/CSS/JavaScript - no external dependencies
- All data is embedded in the HTML file
- Search is performed client-side for instant results
- No server or API calls required

## Browser Support

Works on all modern browsers:
- Chrome / Edge
- Firefox
- Safari

## License

This tool is provided for public use to support the boycott movement against military-linked businesses in Myanmar.

---

**Source**: DVB Data Team / Justice For Myanmar
