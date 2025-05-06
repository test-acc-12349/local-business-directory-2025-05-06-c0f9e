# Local Business Directory

> Discover the best local businesses in one place - A modern, responsive directory website with a clean 3-column grid layout.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
  - [Directory Items](#directory-items)
  - [Categories](#categories)
  - [Hero Section](#hero-section)
  - [Styling](#styling)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

Local Business Directory is a modern web platform designed to showcase local businesses in an organized, searchable format. The responsive layout ensures optimal viewing across all devices, while the intuitive category system makes finding businesses easy.

## Features

- ✨ Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- 🖼️ Image optimization
- 🚀 Fast loading times
- 📊 Business metrics display
- 🎨 Customizable styling

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Basic knowledge of HTML/CSS
- Text editor (VS Code recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/local-business-directory

# Navigate to project directory
cd local-business-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure

```
local-business-directory/
├── src/
│   ├── components/
│   │   ├── DirectoryGrid.js
│   │   ├── CategoryFilter.js
│   │   └── SearchBar.js
│   ├── data/
│   │   └── businesses.json
│   └── styles/
│       └── main.css
├── public/
│   └── images/
├── index.html
└── README.md
```

## Customization Guide

### Directory Items

Add or edit businesses in `src/data/businesses.json`:

```json
{
  "businesses": [
    {
      "id": "1",
      "name": "Business Name",
      "category": "Restaurant",
      "address": "123 Main St",
      "phone": "(555) 123-4567",
      "image": "business-image.jpg"
    }
  ]
}
```

### Categories

Modify categories in `src/data/categories.js`:

```javascript
export const categories = [
  "Restaurant",
  "Retail",
  "Services",
  "Entertainment"
];
```

### Hero Section

Update the hero section in `index.html`:

```html
<div class="hero">
  <h1>Your Custom Heading</h1>
  <p>Your custom description text</p>
</div>
```

### Styling

Customize colors and styles in `src/styles/main.css`:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #f8f9fa;
}
```

## Deployment

1. Build the project:
```bash
npm run build
```

2. Deploy to your preferred hosting platform:
- Netlify
- Vercel
- GitHub Pages

## Custom Domain Setup

1. Purchase a domain from your preferred registrar
2. Add DNS records:
```
A     @     76.76.21.21
CNAME www   yourdomain.com
```
3. Configure SSL certificate
4. Update deployment settings

## Troubleshooting

Common issues and solutions:

| Issue | Solution |
|-------|----------|
| Images not loading | Check path in businesses.json |
| Categories not filtering | Clear browser cache |
| Styling not updating | Run build process again |

## Support & Resources

- 📚 [Documentation](https://docs.example.com)
- 💬 [Community Forum](https://forum.example.com)
- 🐛 [Issue Tracker](https://github.com/yourusername/local-business-directory/issues)
- 📧 [Support Email](mailto:support@example.com)

### Contributing

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

### License

MIT License - feel free to use this project for personal or commercial purposes.

---

**Need Help?** Join our [Discord community](https://discord.gg/example) for real-time support.