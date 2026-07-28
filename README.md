# Myanmar Boycott List Search

A search tool for checking if a company or product is on the Myanmar military-linked business boycott list or the international Dirty List.

## Overview

A single-page HTML application that allows users to search and verify whether a company, product, or service is linked to the Myanmar military junta or international authoritarian regimes and should be boycotted.

## Features

- **Two Lists** — Toggle between Myanmar Boycott List and international Dirty List
- **Instant Search** — Type any company or product name for instant results
- **Category Filter** — Filter results by business category
- **Bilingual Support** — Company names in both English and Myanmar (Burmese) where available
- **Company Logos** — Auto-matched logos with fallback initials
- **Detail Modal** — Click any result to see products, categories, and warnings
- **Responsive Design** — Works on desktop and mobile devices

## Project Structure

```
boycott/
  index.html                 # Main application
  data/
    boycott-data.js          # Company records and product data
  logo/
    *.png, *.jpg, *.svg      # Company logos
  Myanmar_Boycott_List.xlsx  # Source data spreadsheet
```

## Lists

### Myanmar Boycott List (236 records)

Myanmar military-linked businesses across sectors:

| Category | Examples |
|----------|----------|
| Banking and Finance | Myawaddy Bank, Innwa Bank |
| Communications | Mytel, MECtel |
| Construction | Rhino Cement, Tristar Steel |
| Food and Drink | Dagon Beer, Myanmar Beer |
| Media | Myawaddy Television, MWD TV |
| Transport | Parami Express, Shwe Mann Thu |

### Dirty List (228 records)

International companies linked to military or authoritarian regimes:

| Category | Examples |
|----------|----------|
| Defence & Aerospace | AVIC, Rosoboronexport |
| Technology | Apple, Google, Microsoft |
| Communications | Huawei, ByteDance/TikTok |
| Shipping & Maritime | COSCO, Sinokor |
| Energy & Oil Gas | Halliburton, CNPC |

## Usage

### Standalone

Open `index.html` in any modern web browser.

### Embed in iframe

```html
<iframe src="index.html" width="100%" height="600" frameborder="0"></iframe>
```

### Embed with custom styling

```html
<iframe
  src="index.html"
  width="100%"
  height="800"
  style="border: none; max-width: 720px; margin: 0 auto; display: block;">
</iframe>
```

## Data

Data is stored in `data/boycott-data.js` and includes:

- **`MYANMAR_RECORDS`** — Myanmar boycott list with company names, categories, and Burmese names
- **`DIRTY_RECORDS`** — International dirty list with company names and categories
- **`PRODUCT_DATA`** — Product/service details for select companies

## Data Source

- [Justice For Myanmar](https://www.justiceformyanmar.org/)
- [Burma Campaign UK](https://www.burmacampaign.org.uk/)
- DVB Data Team

> **Note**: The list is subject to change over time. For the latest verification, please check the original sources.

## Technical Details

- Pure HTML/CSS/JavaScript — no frameworks, no build step
- Client-side search — no server or API calls required
- Data loaded from external JS file for easy updates
- Company logos auto-matched by name with multi-extension fallback

## Browser Support

Works on all modern browsers:

- Chrome / Edge
- Firefox
- Safari

## License

This tool is provided for public use to support the boycott movement against military-linked businesses in Myanmar.

---

**Source**: DVB Data Team / Justice For Myanmar / Burma Campaign UK
