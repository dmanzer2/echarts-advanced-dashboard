# Advanced ECharts Dashboard

An interactive dashboard built with [ECharts](https://echarts.apache.org/) for advanced data visualization, featuring multiple chart types, dynamic data, and export functionality.

## Features

- **Sales & Temperature (Dual Axis):** Bar and line chart with dual y-axes, custom tooltips, and animated transitions.
- **Scatter Plot with Regression Line:** Visualizes correlation and regression with interactive tooltips.
- **Performance Metrics (Large Dataset):** Optimized line charts for large datasets with zoom and pan.
- **Multi-Series Comparison:** Grouped bar and line chart for comparing multiple product series.
- **Responsive Layout:** Charts resize automatically with the window.
- **Dynamic Data:** Update charts with new random data at the click of a button.
- **Export:** Download any chart as a PNG image.
- **Legend-Driven Axis Labels:** Axis names and labels hide/show in sync with legend toggles for a clean UI.

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- No build tools required

### Installation

1. Clone this repository:
   ```sh
   git clone <your-repo-url>
   cd echarts-advanced-dashboard
   ```
2. Open `index.html` in your browser.

## Project Structure

```
echarts-advanced-dashboard/
├── index.html         # Main dashboard HTML and JS
├── assets/
│   └── styles.css     # Custom styles
├── package.json       # (Optional) For future dependency management
└── README.md          # Project documentation
```

## Usage

- **Update Data:** Click the "Update Data" button to generate new random data for all charts.
- **Toggle Animation:** Enable or disable chart animations.
- **Export Charts:** Download the current view of each chart as a PNG image.
- **Legend Interaction:** Click legend items to show/hide series and their corresponding y-axis labels.

## Customization

- Modify chart options in `index.html` to change chart types, colors, or data generation logic.
- Edit `assets/styles.css` for custom dashboard styling.

## Dependencies

- [ECharts 5.x](https://echarts.apache.org/)
- [Normalize.css](https://necolas.github.io/normalize.css/)

## License

MIT License
