# mWinery - Matveev Winery Landing Page

A beautiful, elegant single-page landing page for Matveev Winery, showcasing their premium family-owned winery with a focus on craftsmanship, heritage, and modern aesthetics.

## Features

- ✨ Elegant, minimalistic design with warm earthy tones
- 📱 Fully responsive (mobile-first approach)
- 🎨 Custom color palette (burgundy, beige, gold, deep green)
- 🔤 Elegant typography (Playfair Display for headers, Lato for body)
- 🎭 Smooth scroll animations on scroll
- 🖼️ Interactive gallery slider
- 📝 Contact form
- ♿ Accessible and semantic HTML

## Sections

1. **Hero Section** - Full-screen vineyard background with logo and call-to-action
2. **Our Story** - About the winery and family history
3. **Our Wines** - Product catalog with 4 wine varieties
4. **Our Philosophy** - Values and winemaking approach
5. **Gallery** - Interactive image slider showcasing the winery
6. **Visit Us** - Contact information and form
7. **Footer** - Links and copyright information

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

```bash
npm run build
npm start
```

## Customization

### Colors

The color palette is defined in `tailwind.config.js`:
- `burgundy`: #8B1538
- `wine`: #722F37
- `beige`: #F5E6D3
- `gold`: #D4AF37
- `deep-green`: #2D5016
- `warm-gray`: #5C4B3A

### Images

Currently, the site uses placeholder SVG backgrounds. To add real images:

1. Add your images to `/public/images/` directory
2. Update the component files to reference the actual image paths

For example, in `Hero.tsx`, replace the SVG background with:
```tsx
<div className="w-full h-full bg-cover bg-center" style={{
  backgroundImage: 'url("/images/vineyard.jpg")'
}}></div>
```

## Tech Stack

- **Next.js 14** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Google Fonts** - Playfair Display & Lato

## License

© 2025 Matveev Winery. All rights reserved.

