# HealthAI Dashboard

A modern, responsive health and wellness dashboard built with HTML, TailwindCSS, and AlpineJS. The application provides comprehensive health tracking, including activity monitoring, nutrition planning, sleep analytics, and more.

## Features

- **Dashboard Overview**
  - Daily health statistics
  - Activity timeline
  - Motivational quotes and tips
  - Quick access to key metrics

- **Health Metrics**
  - Heart rate monitoring
  - Blood pressure tracking
  - Sleep quality analysis
  - Weekly activity overview
  - Health insights and recommendations

- **Nutrition Planning**
  - Calorie tracking
  - Macro-nutrient monitoring
  - Meal planning
  - Progress visualization

- **Exercise Tracking**
  - Workout schedules
  - Activity monitoring
  - Progress tracking
  - Exercise recommendations

- **Mental Wellness**
  - Mood tracking
  - Meditation sessions
  - Stress management
  - Wellness insights

## Tech Stack

- HTML5
- TailwindCSS 3.4.0 - Utility-first CSS framework
- AlpineJS 3.13.3 - Lightweight JavaScript framework
- Font Awesome 6.5.1 - Icon library
- ApexCharts - Interactive data visualization
- Google Fonts (Inter & Montserrat) - Typography

## Project Structure
```
healthai-dashboard/
├── src/
│   └── input.css          # TailwindCSS input file
├── index.html             # Main application file
├── output.css            # Generated TailwindCSS styles
├── package.json          # Node.js dependencies and scripts
├── tailwind.config.js    # TailwindCSS configuration
└── README.md             # Project documentation
```

## Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)
- Python3 (for local development server)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd healthai-dashboard
```

2. Install Node.js dependencies:
```bash
npm install
```

3. Build the CSS:
```bash
npm run build
```

## Development

1. Start the TailwindCSS watcher (automatically rebuilds CSS on changes):
```bash
npm run watch
```

2. Start the local development server:
```bash
python3 -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Building for Production

To build the CSS for production:
```bash
npm run build
```

## Customization

The application can be customized through:
- `tailwind.config.js` - Modify theme, colors, fonts, and other design tokens
- `src/input.css` - Add custom CSS styles
- `index.html` - Modify layout and components

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- TailwindCSS team for the amazing CSS framework
- AlpineJS team for the lightweight JavaScript framework
- Font Awesome for the comprehensive icon library