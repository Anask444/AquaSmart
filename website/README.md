# AquaSmart Website

Modern, premium, scalable Next.js website for AquaSmart - Smart Water Management System.

## Features

- 🎨 Beautiful, responsive design
- ⚡ Fast performance with Next.js
- 🔐 Firebase authentication
- 💳 Razorpay payment integration
- 📧 Email automation
- 📱 Mobile-first approach
- 🎯 SEO optimized
- 🌙 Dark mode support
- 📊 Analytics ready

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Form Handling**: React Hook Form
- **Backend**: Firebase
- **Payment**: Razorpay
- **UI Components**: Custom + Headless UI
- **Charts**: Recharts
- **Icons**: React Icons

## Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn
- Firebase account
- Razorpay account

### Installation

```bash
# Clone repository
cd website

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local
# Edit .env.local with your credentials

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
src/
├── components/      # Reusable React components
├── pages/          # Next.js pages and API routes
├── styles/         # Global and module styles
├── utils/          # Utility functions
├── hooks/          # Custom React hooks
├── types/          # TypeScript type definitions
├── data/           # Static data
└── config/         # Configuration files
```

## Available Scripts

```bash
# Development
npm run dev

# Production build
npm run build

# Start production server
npm start

# Linting
npm run lint

# Type checking
npm run type-check

# Code formatting
npm run format

# Testing
npm test
npm run test:watch

# Export static site
npm run export
```

## Key Pages

- **Home** (`/`) - Landing page with hero section
- **Products** (`/products`) - Product kits and pricing
- **Features** (`/features`) - Feature showcase
- **Pricing** (`/pricing`) - Subscription plans
- **Blog** (`/blog`) - Blog articles
- **FAQ** (`/faq`) - Frequently asked questions
- **Contact** (`/contact`) - Contact form
- **Book Demo** (`/book-demo`) - Demo booking
- **Order** (`/order`) - Place order
- **Privacy** (`/privacy`) - Privacy policy
- **Terms** (`/terms`) - Terms of service

## API Routes

- `POST /api/contact` - Contact form submission
- `POST /api/book-demo` - Book demo request
- `POST /api/place-order` - Place order
- `POST /api/subscribe` - Subscribe to newsletter
- `POST /api/feedback` - Submit feedback
- `POST /api/payment-webhook` - Razorpay webhook

## Environment Variables

See `.env.example` for all required variables.

## Deployment

### Vercel

```bash
vercel
```

### Firebase Hosting

```bash
npm run build
firebase deploy
```

## Security

- Environment variables for sensitive data
- Firebase security rules
- HTTPS only
- CORS configured
- Input validation
- Rate limiting on API routes

## Performance

- Image optimization
- Code splitting
- Lazy loading
- Caching strategies
- Minification
- CDN support

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing

See [CONTRIBUTING.md](../../CONTRIBUTING.md)

## License

MIT License - See [LICENSE](../../LICENSE)

## Support

- Email: support@aquasmart.com
- Website: www.aquasmart.com
