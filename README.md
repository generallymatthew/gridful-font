# Grid Typography Calculator

An interactive web-based tool for designing typographic grids and custom pixel fonts. Create poster designs with precise grid-based typography, paint custom font layouts cell-by-cell, and export printable designs.

## Features

- **Dynamic Grid Canvas** - Fill available space while maintaining aspect ratio with 60px fixed padding
- **Adjustable Grid Sizes** - Choose between 0.5", 1", or 2" grid cell sizes for your design
- **Interactive Cell Editing** - Click cells to toggle between states:
  - Empty (white)
  - Full black square
  - Top-left diagonal (½ square)
  - Top-right diagonal (½ square)
  - Bottom-left diagonal (½ square)
  - Bottom-right diagonal (½ square)
- **Printable Export** - Download your designs as PNG or SVG for printing
- **Automatic Calculations** - Real-time canvas dimension calculations based on text and grid configuration
- **Responsive Design** - Adapts to different viewport sizes

## How to Use

1. **Enter Text** - Type your poster text in the "Poster Grid Content" field (line separated)
2. **Adjust Grid Size** - Select 0.5", 1", or 2" from the grid size dropdown
3. **Edit Cells** - Click any cell in the grid to toggle through fill states and create custom patterns
4. **Download** - Click "Download Printable" to export your design as an image

## Technical Details

- **Pure HTML/CSS/JavaScript** - No build process or dependencies required
- **5×5 Grid Font** - Each letter is rendered as a 5×5 grid of cells with support for diagonal fills
- **Dynamic Scaling** - Preview scales automatically to fill available canvas space
- **Responsive Grid Generation** - Calculates optimal cell sizing based on text length and available space

## Project Structure

```
grid-calc/
├── grid_typographic_calculator.html   # Main application file
├── README.md                           # This file
├── .gitignore                          # Git ignore rules
└── .claude/
    └── launch.json                     # Dev server configuration
```

## Getting Started

### Local Development
1. Clone the repository
2. Open `grid_typographic_calculator.html` in a web browser
3. Or use the built-in dev server: `npx http-server .`

### GitHub Pages (Hosted Version)

This project is hosted on GitHub Pages! After pushing to GitHub, enable GitHub Pages:

1. Go to your repository settings on GitHub
2. Scroll to "GitHub Pages" section
3. Set "Source" to "Deploy from a branch"
4. Select "main" branch and "/" (root) as the deployment folder
5. Your site will be live at: `https://YOUR_USERNAME.github.io/grid-calc/`

**Access the tool:** Simply open the GitHub Pages URL in your browser to use the hosted version!

## Author

Matthew Barton - UX Designer

## License

MIT
