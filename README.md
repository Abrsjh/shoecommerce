# 👟 SoleStride - Premium Shoe E-Commerce Store

A beautiful, cutting-edge e-commerce website built with Astro and Tailwind CSS, designed for a modern shoe shopping experience.

## ✨ Features

- **Modern Design**: Sleek, responsive interface with smooth animations
- **Fast Performance**: Built with Astro for optimal loading speeds
- **Tailwind CSS**: Utility-first styling with custom design system
- **Product Showcase**: Beautiful product cards with hover effects
- **Newsletter Integration**: Email subscription functionality
- **Vercel Ready**: Optimized for Vercel deployment

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/Abrsjh/shoecommerce.git

# Navigate to project directory
cd shoecommerce

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:4321`

## 📚 Tech Stack

- **Framework**: [Astro](https://astro.build) - Modern static site generator
- **Styling**: [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- **Fonts**: Inter from Google Fonts
- **Icons**: Heroicons (SVG)
- **Images**: Unsplash API

## 📦 Project Structure

```
/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── ProductCard.astro
│   │   ├── Features.astro
│   │   ├── Newsletter.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.mjs
├── package.json
└── vercel.json
```

## 🛠️ Build Commands

| Command | Action |
|---------|--------|
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview build locally before deploying |

## 🌐 Deployment to Vercel

### Option 1: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Option 2: Deploy via Vercel Dashboard

1. Push your code to GitHub
2. Go to [Vercel](https://vercel.com)
3. Import your repository
4. Vercel will auto-detect Astro and configure settings
5. Click "Deploy"

### Option 3: Deploy Button

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Abrsjh/shoecommerce)

## 🎨 Customization

### Colors

Edit `tailwind.config.mjs` to customize the color scheme:

```js
theme: {
  extend: {
    colors: {
      primary: '#111827',    // Dark gray
      secondary: '#6366f1',  // Indigo
      accent: '#f59e0b',     // Amber
    },
  },
}
```

### Products

Edit the `products` array in `src/pages/index.astro` to add/modify products.

## 📝 License

MIT License - feel free to use this project for your own purposes.

## 🚀 Live Demo

Once deployed, your site will be live at: `https://shoecommerce.vercel.app`

---

Built with ❤️ using Astro and Tailwind CSS
