# Custom Tabs Project

A simple and elegant tab switching implementation using vanilla JavaScript, HTML, and CSS. This project creates an interactive tabbed interface that allows users to switch between different content sections seamlessly.

## Features

- Clean and responsive design
- Smooth tab switching functionality
- Customizable styling
- Pure JavaScript implementation (no dependencies)
- Mobile-friendly layout

## Project Structure

```
custom-tabs/
├── index.html
├── style.css
├── main.js
└── README.md
```

## Installation

1. Clone or download this repository to your local machine
2. Open `index.html` in your web browser
3. No additional setup or dependencies required

## Usage

The tab interface includes five sections:
- Home
- Services
- Projects
- Portfolio
- Contact

Click on any tab button to display its corresponding content. The active tab is highlighted with a black background, while inactive tabs maintain a blue background.

## Technical Implementation

### HTML
- Structured using semantic HTML5
- Tab buttons are implemented using `<button>` elements with `data-id` attributes
- Content sections are organized using `<p>` elements with matching IDs

### CSS
- Responsive design with flexbox
- Clean and modern styling
- Active states for visual feedback
- Mobile-friendly layout

### JavaScript
- Event delegation for efficient click handling
- Dynamic class toggling for tab switching
- Clean and maintainable code structure

## Customization

### Styling
You can customize the appearance by modifying the following CSS variables in `style.css`:
- Button colors (currently using `#073dab` for inactive and `#000` for active)
- Font sizes
- Spacing and padding
- Background colors

