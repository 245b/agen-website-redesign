# Agen Website Redesign

A modern, high-performance website for Agen - an AI-powered autonomous development platform. Built with Next.js 15, TypeScript, and featuring advanced animations inspired by leading tech platforms like Huly.io.

## 🚀 Features

### Core Technologies
- **Framework**: Next.js 15 (App Router) with static export
- **Language**: TypeScript for type safety
- **Styling**: Tailwind CSS + Custom design tokens
- **Animations**: Framer Motion for smooth transitions
- **Components**: Radix UI primitives + shadcn/ui
- **State**: Zustand for global state management
- **Query**: TanStack Query for async data

### Design Features
- **Advanced Animations**: WebGL-powered backgrounds, morphing blobs, particle effects
- **Glass Morphism**: Modern frosted glass effects throughout
- **Interactive Elements**: Magnetic cursors, 3D card tilts, scroll-triggered animations
- **Dark Mode First**: Sophisticated dark theme with cyan/purple accents
- **Responsive Design**: Flawless experience from mobile to 4K
- **Performance**: 60fps animations, optimized bundle size, lazy loading

## 🎨 Design Inspiration

The design combines elements from:
- **Huly.io**: Clean layouts, professional gradients, glass morphism
- **Devin.ai**: Technical aesthetics, terminal previews
- **Modern Trends 2025**: Interactive 3D, scroll animations, neo-brutalism touches

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/245b/agen-website-redesign.git

# Navigate to project
cd agen-website-redesign

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## 🏗 Project Structure

```
agen-website/
├── app/                  # Next.js app directory
│   ├── layout.tsx       # Root layout
│   ├── page.tsx         # Home page
│   └── globals.css      # Global styles
├── components/
│   ├── sections/        # Page sections
│   │   ├── hero.tsx     # Hero section with animations
│   │   ├── features.tsx # Features grid
│   │   ├── process.tsx  # Process workflow
│   │   └── showcase.tsx # Product showcase
│   └── ui/              # Reusable components
│       ├── background-effects.tsx
│       ├── navigation.tsx
│       └── button.tsx
├── lib/                 # Utilities
└── public/              # Static assets
```

## 🎯 Key Improvements

### Performance
- First Contentful Paint < 1.5s on 3G
- 60fps animations on mid-range devices
- JavaScript bundle < 300KB gzipped
- WebP images with lazy loading

### Accessibility
- WCAG 2.1 AA compliant
- Full keyboard navigation
- Screen reader optimized
- Semantic HTML structure

### SEO
- Static site generation
- Optimized meta tags
- Structured data
- Sitemap generation

## 🔧 Configuration

### Environment Variables
```env
NEXT_PUBLIC_API_URL=your_api_url
NEXT_PUBLIC_ANALYTICS_ID=your_analytics_id
```

### Tailwind Config
Custom design tokens are defined in `tailwind.config.ts`:
- Color palette: Cyan, purple, blue gradients
- Typography scale: 8px to 88px
- Animation presets: Float, morph, glitch, shimmer
- Custom shadows and blurs

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers: iOS Safari 14+, Chrome Mobile

## 🚢 Deployment

The site is configured for static export and can be deployed to:
- Vercel (recommended)
- Netlify
- AWS S3 + CloudFront
- Any static hosting service

```bash
# Build static files
npm run build

# Output will be in 'out' directory
```

## 📝 License

MIT License - feel free to use this project for your own purposes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

Built with ❤️ using Next.js, TypeScript, and modern web technologies.