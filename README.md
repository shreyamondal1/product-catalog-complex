# product-catalog-complex

## Overview
A modern, responsive single-page application that displays a product catalog with filtering capabilities and real-time statistics. The application parses product data from JSON and presents it in an elegant, user-friendly interface with Bootstrap cards.

## Features
- **Product Display**: Shows all products in a responsive grid layout with Bootstrap cards
- **Product Information**: Each card displays product name, price (formatted with dollar sign), and category
- **Category Filtering**: Dropdown filter to view products by category or all products
- **Total Inventory Value**: Real-time calculation and display of total inventory value
- **Statistics Dashboard**: Displays comprehensive catalog statistics including:
  - Total number of products
  - Number of categories
  - Average price
  - Highest and lowest prices
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient backgrounds, smooth animations, and intuitive interface
- **Icon Integration**: Font Awesome icons for enhanced visual appeal

## Setup Instructions
1. Clone the repository
2. Open index.html in a web browser
3. The application runs entirely client-side

## Usage
1. **Browse Products**: View all products displayed in card format on the main page
2. **Filter by Category**: Use the dropdown menu to filter products by specific categories
3. **View Total Value**: The total inventory value updates automatically based on filtered products
4. **Check Statistics**: Scroll down to view comprehensive catalog statistics

## Code Explanation
The application is built as a single-page application with embedded JavaScript:

- **Data Management**: Product data from products.json is embedded directly in the JavaScript code
- **Dynamic Rendering**: Products are dynamically rendered as Bootstrap cards using JavaScript template literals
- **Filtering Logic**: Category filter updates the display in real-time without page reload
- **Value Calculation**: Total inventory value is calculated using Array.reduce() method
- **Statistics**: Real-time statistics are computed from the current filtered product set
- **Error Handling**: Includes try-catch blocks and user-friendly error messages
- **Security**: HTML escaping prevents XSS attacks

## Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Modern JavaScript for functionality
- **Bootstrap 5.3.0**: Responsive framework and components
- **Font Awesome 6.4.0**: Icon library for visual elements
- **No external dependencies**: All code runs client-side without a server

## License
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR