🛒 NextShop - E-Commerce Homepage
Modern, responsive e-commerce homepage with clean design and robust error handling.

🚀 Live Demo
View Live Demo

✨ Features
Modern UI: Clean design with smooth animations
Responsive: Mobile-first, works on all devices
Product Grid: Dynamic products with ratings and pricing
Categories: Interactive category cards
Special Offers: Countdown timer for urgency
Error Handling: Graceful fallbacks for broken images

🛠️ Tech Stack
Next.js 14 (App Router)
TypeScript
Tailwind CSS
React Hooks

# Clone and install
git clone https://github.com/itstumpa/nextshop-homepage.git
cd nextshop-homepage
npm install

# Start development
npm run dev


📁 Structure
├── app/page.tsx              # Main homepage
├── components/ProductImage.tsx # Image component with fallbacks
├── utils/imageUtils.ts       # Image handling utilities
└── services/api.ts           # API integration


🔧 Environment
NEXT_PUBLIC_API_URL=http://localhost:3000

🚨 Issues Handled
## Image Loading Issue

### Problem Identified
The API returns image URLs pointing to `via.placeholder.com`, which is currently unavailable:
- Domain: via.placeholder.com
- Status: DNS resolution failure / Service down
- Impact: All product images fail to load

### Solution Implemented
- Graceful fallback system for broken external services
- Professional placeholder images with product information
- Proper error handling and loading states
- No console errors or 404s

### Recommendation
- Replace via.placeholder.com URLs with working image service

🚀 Performance
Image lazy loading
Optimized animations
Efficient re-renders
Fast loading states

📈 Future Enhancements
 Search Functionality - Product search with filters
 Cart Management - Add to cart with state persistence
 User Authentication - Login/signup integration
 Wishlist Feature - Save favorite products
 Product Reviews - User rating and review system
 Analytics Integration - Track user interactions
 PWA Support - Offline functionality
 Internationalization - Multi-language support

🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

⭐ Star if helpful! | Report Issues