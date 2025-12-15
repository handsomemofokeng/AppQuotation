# App Development Cost Estimator

A web-based tool designed to generate minimum viable product (MVP) cost estimates for mobile application development projects in the South African market (ZAR).

## Overview

This project provides an interactive interface for clients or stakeholders to select various features required for their app (e.g., User Authentication, Payment Gateway, Chat) and receive an instant, itemized cost estimate. It features a modern, dark-themed UI and includes print functionality for generating PDF quotes.

## Features

- **Interactive Quote Generation**: Real-time calculation of estimated costs based on selected features.
- **Detailed Breakdown**: Includes a fixed base setup cost and individual costs for add-on features.
- **Print-Ready Quotes**: dedicated print styles to generate clean, professional PDF quotes or physical prints.
- **Responsive Design**: Fully responsive layout that works on desktop and mobile devices.
- **Dark Theme**: A polished dark UI using a Slate/Gray and Amber color palette.

## Technologies Used

- **HTML5**: Semantic markup.
- **Tailwind CSS**: Utility-first CSS framework for styling and responsiveness (loaded via CDN).
- **JavaScript (Vanilla)**: Logic for state management, cost calculation, and DOM manipulation.

## How to Use

1. **Clone or Download** the repository.
2. **Open `index.html`** in any modern web browser.
3. **Select Features**: Click on the checkboxes to add features to your estimate.
4. **View Summary**: The sticky summary bar at the top updates automatically.
5. **Print Quote**: Click the "Print Quote" button to open the print dialog and save as PDF.

## Customization

You can easily customize the costs and features by editing the `FEATURES` array in the `<script>` section of `index.html`.

```javascript
const FEATURES = [
    { 
        id: 'auth', 
        name: 'User Authentication', 
        cost: 25000, 
        description: '...' 
    },
    // ...
];
```

## License

This project is open source and available for personal or commercial use.
