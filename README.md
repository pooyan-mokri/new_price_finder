# TheMoak Price Finder

A fast, offline-capable price finder web application for TheMoak eyeglasses products.

## Features

- **Real-time Search**: Search products as you type by name or attributes
- **Offline Support**: Data is cached in browser for offline access
- **Responsive Design**: Works on desktop and mobile devices
- **Fast Performance**: Instant search results with no loading delays
- **Persian Language Support**: Full RTL support with Persian interface

## How to Use

1. Open `index.html` in any modern web browser
2. The app will automatically load product data from `new.csv`
3. Type in the search box to find products instantly
4. View product prices and all attributes in detailed cards

## Technical Details

- **No dependencies**: Pure HTML, CSS, and JavaScript
- **LocalStorage**: Data persists between sessions for offline use
- **CSV Parsing**: Automatic parsing of product database
- **Brand Colors**: Uses TheMoak logo colors (blue #3949AB and light green #AFFFB4)

## File Structure

```
├── index.html          # Main application file
├── new.csv            # Product database
└── README.md          # Documentation
```

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Data Format

The CSV file contains eyeglasses products with the following information:
- Product name
- Price (in Tomans)
- Multiple attributes (color, material, collection, gender, shape)

## Offline Usage

After the first visit, the app saves all data locally. You can:
1. Bookmark the page
2. Use it without internet connection
3. Data automatically updates when online

## Updates

To update product data:
1. Replace `new.csv` with new data
2. Refresh the browser
3. New data will be cached automatically

---

**TheMoak Price Finder** - Find your perfect eyewear instantly
