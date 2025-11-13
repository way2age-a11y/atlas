# Atlas InSites

**Turn everyday questions into actionable community insights**

A resident and user support platform that transforms everyday questions and barrier reports into site-specific insights for planners across accessibility, age-friendly services, transportation, housing, parks, campuses, and workplaces.

---

## 🌟 Features

- **Service Navigation Portal** - Residents find the programs and resources they need
- **Intelligent Feedback Collection** - Location-based barrier reporting and questions
- **Planner Dashboard** - Auto-tagged insights, visual hotspots, and analytics
- **One-Click Reporting** - Generate compliance and transparency reports instantly
- **Fully Accessible** - WCAG 2.1 AA compliant
- **Responsive Design** - Works seamlessly on all devices
- **Zero Side Padding** - Optimized for embedding in Kajabi or other platforms

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18 or higher
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/atlas-insites.git
cd atlas-insites

# Install dependencies
npm install

# Start development server
npm run dev
```

Your site will be running at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist/` folder.

---

## 📧 Contact Form Setup

The contact form uses **Web3Forms** for email delivery:

1. Go to [web3forms.com](https://web3forms.com)
2. Sign up with your email
3. Get your Access Key
4. Open `/components/ContactPage.tsx`
5. Replace `YOUR_WEB3FORMS_ACCESS_KEY_HERE` with your key
6. Rebuild and redeploy

---

## 🌐 Deployment

See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed instructions on:
- Deploying to Cloudflare Pages (recommended)
- Deploying to Netlify or Vercel
- Setting up custom domains
- Configuring environment variables

**Quick Deploy to Cloudflare Pages:**

```bash
npm run build
# Upload the dist/ folder to Cloudflare Pages
```

---

## 📁 Project Structure

```
atlas-insites/
├── components/           # React components
│   ├── ContactPage.tsx   # Contact form with Web3Forms
│   ├── HowItWorksPage.tsx
│   ├── SolutionsPage.tsx
│   ├── PricingPage.tsx
│   └── ui/              # ShadCN UI components
├── styles/
│   └── globals.css      # Global styles and Tailwind
├── App.tsx              # Main app component with routing
├── index.html           # HTML entry point
├── package.json         # Dependencies
├── vite.config.ts       # Vite configuration
└── DEPLOYMENT.md        # Deployment guide
```

---

## 🎨 Tech Stack

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **Web3Forms** - Contact form backend
- **ShadCN UI** - Component library

---

## 📱 Pages

- **Home** - Hero, features, dashboard preview
- **About Us** - Company story and mission
- **How It Works** - Platform explanation
- **Solutions** - 6 sector-specific solutions
- **Pricing** - Contact-based pricing
- **Contact** - Working contact form

---

## 🔧 Customization

### Update Colors
Edit `/styles/globals.css` to change the color scheme.

### Update Content
All content is in the component files - easy to edit!

### Add Analytics
Add your tracking code to `/index.html`

---

## ♿ Accessibility

This site is built to WCAG 2.1 AA standards:
- Semantic HTML
- ARIA labels on all interactive elements
- Keyboard navigation support
- Screen reader tested
- Sufficient color contrast
- Focus indicators

---

## 📄 License

Copyright © 2024 Atlas InSites. All rights reserved.

---

## 🤝 Support

Questions? Contact us at [hello@atlasinsites.com](mailto:hello@atlasinsites.com)

---

**Built with ❤️ for accessible and age-friendly communities**
