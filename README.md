# product-catalog-complex

## Overview
A modern, interactive single-page product catalog application that allows users to search and sort products in real-time. The application features a clean, responsive design with smooth animations and an intuitive user interface.

## Features
- **Real-time Search**: Filter products by name with case-insensitive search as you type
- **Multiple Sort Options**: Sort products by:
  - Price: Low to High
  - Price: High to Low
  - Name: A-Z (alphabetical)
- **Live Result Count**: Displays the number of products matching current filters
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient backgrounds, smooth animations, and card-based layout
- **Category Icons**: Visual icons representing different product categories
- **No Results Handling**: User-friendly message when no products match the search criteria

## Setup Instructions
1. Clone the repository
2. Open index.html in a web browser
3. The application runs entirely client-side

## Usage
1. **Search Products**: Type in the search box to filter products by name. The results update instantly as you type.
2. **Sort Products**: Use the dropdown menu to change the sort order. Choose from price-based or alphabetical sorting.
3. **View Results**: The result count updates automatically to show how many products match your current search and sort criteria.
4. **Browse Products**: Scroll through the product grid to view all matching items with their prices and categories.

## Code Explanation

### Data Management
- Product data is embedded directly in the JavaScript as a JSON object
- The application maintains two arrays: `allProducts` (original data) and `filteredProducts` (current view)

### Search Functionality
- The search input listens for `input` events
- Filters products using case-insensitive string matching on product names
- Updates the display in real-time

### Sorting Logic
- Three sort options implemented using JavaScript's `sort()` method
- Price sorting uses numerical comparison
- Name sorting uses `localeCompare()` for proper alphabetical ordering
- Sorting is applied after filtering to maintain search results

### Display Updates
- The `updateDisplay()` function handles all UI updates
- Uses document fragments for efficient DOM manipulation
- Implements staggered animations for product cards
- Shows "No Results" message when appropriate

### Security
- Implements HTML escaping to prevent XSS attacks
- Uses `textContent` for user-generated content

## Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, gradients, and animations
- **Bootstrap 5.3.0**: CSS framework for responsive design and utilities
- **Bootstrap Icons 1.10.0**: Icon library for visual elements
- **Vanilla JavaScript**: No frameworks, pure ES6+ JavaScript for functionality

## License
MIT License

---
✅ **Note:** This repository has been updated for **Round 2** of the evaluation cycle.