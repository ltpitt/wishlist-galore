# wishlist-galore 🇮🇹

In this repo I keep my wishlists

## Italian Wishlist

A beautiful, mobile-first single-page application to display items to bring from Italy.

### Features

- 📱 **Mobile-First Design**: Fully responsive and optimized for all devices
- 🎨 **Modern UI**: Beautiful gradient background with card-based layout
- ✨ **Smooth Animations**: Subtle animations using Animate.css
- 🔄 **Dynamic Content**: Items loaded from external JSON file
- 🎯 **Font Awesome Icons**: Visual icons for each item
- 🔗 **External Links**: Direct links to more information about each item

### How to Use

1. Open `index.html` in a web browser
2. Items are automatically loaded from `items.json`

### How to Update Items

Edit the `items.json` file to add, remove, or modify items. Each item follows this structure:

```json
{
  "name": "Item Name",
  "description": "Item description in any language",
  "icon": "fa-solid fa-icon-name",
  "link": "https://example.com"
}
```

**Finding Font Awesome Icons:**
Browse available icons at [Font Awesome](https://fontawesome.com/icons) and use the class name (e.g., `fa-solid fa-heart`)

### Technologies Used

- **Bootstrap 5.3.2**: Responsive grid and utilities
- **Font Awesome 6.4.2**: Icon library
- **Animate.css**: Animation library
- **Google Fonts (Poppins)**: Typography
- **Vanilla JavaScript**: Dynamic content loading
