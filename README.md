# Street Food Finder - Uttar Pradesh 🍜🤖

A modern, AI-powered interactive web application for discovering authentic Uttar Pradesh street food near you with intelligent personalized recommendations, real reviews, and beautiful UI showcasing the rich culinary heritage of UP.

## ✨ Features

### 🤖 AI-Powered Intelligence
- **Smart Search Suggestions** - AI analyzes your query and provides intelligent suggestions
- **Personalized Recommendations** - Machine learning algorithm considers your preferences, ratings, and search history
- **Contextual Understanding** - AI understands ingredients, cuisine types, and location preferences
- **Real-time Processing** - Instant AI analysis with visual feedback

### 🎯 Smart Recommendations
- **Location-based filtering** - Find authentic UP street food within your preferred radius
- **Multi-factor AI ranking** - Combines location, ratings, user preferences, and behavioral patterns
- **Time-based suggestions** - AI considers time of day for optimal food recommendations
- **Price preference learning** - Adapts to your budget patterns over time

### 🔍 Advanced Search & Filtering
- **AI-enhanced search** - Intelligent autocomplete with contextual suggestions
- **Real-time search** - Search by food name, cuisine type (Awadhi, Mughlai, etc.), or ingredients
- **Comprehensive filters** - UP cuisine types, INR price range, dietary restrictions
- **Smart suggestions** - Popular UP street food terms with AI-powered relevance

### 🍽️ Rich Food Details
- **Authentic UP street food** - Tunday Kababi, Banarasi Kachori, Agra Petha, and more
- **Detailed information** - Traditional ingredients, vendor heritage, cultural significance
- **Community reviews** - Real ratings and reviews from UP food lovers
- **Interactive ratings** - Rate and review your favorite UP street foods with AI learning

### 💫 Modern UI/UX
- **Smooth animations** - Powered by Framer Motion
- **Responsive design** - Works perfectly on all devices
- **Glass morphism effects** - Modern, elegant visual design
- **Interactive elements** - Hover effects and micro-interactions
- **AI visual feedback** - Beautiful loading states and processing indicators

### 🏪 Vendor Information
- **Heritage vendor profiles** - Information about legendary UP food vendors
- **Location details** - Addresses across UP cities (Lucknow, Varanasi, Agra, Kanpur, etc.)
- **Cultural context** - Stories behind famous food establishments
- **Authentic experiences** - Connect with traditional UP food culture

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd street-food-recommender
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### 🌐 Deploy to Vercel

#### Quick Deploy
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/street-food-finder-up)

#### Manual Deployment
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Production deployment
vercel --prod
```

**Live Demo**: [street-food-finder-up.vercel.app](https://street-food-finder-up.vercel.app)

For detailed deployment instructions, see [DEPLOYMENT.md](./DEPLOYMENT.md)

## 🛠️ Technology Stack

### Frontend
- **React 18** - Modern React with hooks and concurrent features
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Smooth animations and transitions
- **Lucide React** - Beautiful, customizable icons

### Build Tools
- **Vite** - Fast build tool and dev server
- **ESLint** - Code linting and quality
- **PostCSS** - CSS processing
- **Autoprefixer** - Automatic vendor prefixes

## 🍛 Featured UP Street Foods

### Authentic Specialties
- **Lucknowi Tunday Kababi** - World-famous galouti kebabs that melt in your mouth
- **Banarasi Kachori Sabzi** - Crispy kachoris with spiced aloo sabzi from Varanasi
- **Agra Petha & Dalmoth** - Traditional sweet petha with spicy dalmoth namkeen
- **Kanpur Thaggu Ke Laddu** - Legendary besan laddus made with pure ghee
- **Allahabad Chaat Combo** - Authentic Prayagraj-style chaat platter
- **Mathura Pedha & Lassi** - Sacred city's famous pedha with creamy lassi

### Regional Cuisines
- **Awadhi** - Royal cuisine from Lucknow with rich gravies and kebabs
- **Mughlai** - Influenced by Mughal cooking traditions
- **Traditional Sweets** - Heritage mithai from famous UP sweet shops
- **Street Chaat** - Tangy, spicy chaat varieties from different UP cities
- **Regional Specialties** - Unique foods specific to UP districts

### 💰 **Realistic UP Pricing (INR):**
- Tunday Kababi: ₹180
- Kachori Sabzi: ₹40
- Petha & Dalmoth: ₹120
- Thaggu Ke Laddu: ₹60
- Chaat Combo: ₹80
- Pedha & Lassi: ₹90

### 🤖 **AI Features:**
- **Smart Search** - AI-powered suggestions and contextual understanding
- **Personalized Recommendations** - Machine learning based on user behavior
- **Intelligent Filtering** - AI considers preferences, ratings, and search patterns
- **Real-time Processing** - Instant AI analysis with visual feedback
- **Behavioral Learning** - Adapts to user preferences over time

## 📱 Key Components

### Core Components
- **RecommendationCard** - Individual food item display with INR pricing
- **SearchBar** - AI-enhanced search with smart suggestions
- **FilterPanel** - Comprehensive filtering options with INR ranges
- **FoodDetailModal** - Full-screen food details with cultural context
- **RatingComponent** - Interactive star ratings with AI learning

### AI Components
- **AISmartSearch** - Intelligent search suggestions and recommendations
- **AIRecommendationEngine** - Personalized recommendations based on user behavior
- **Smart Filtering** - AI-powered contextual filtering and suggestions

### Layout Components
- **Header** - Navigation and user actions
- **RecommendationGrid** - Responsive grid layout
- **App** - Main application container

## 🎨 Design Features

### Visual Design
- **Gradient backgrounds** - Beautiful color transitions
- **Glass morphism** - Modern translucent effects
- **Card-based layout** - Clean, organized content
- **Responsive grid** - Adapts to all screen sizes

### Interactions
- **Hover animations** - Smooth element transitions
- **Click feedback** - Visual response to user actions
- **Loading states** - Elegant loading indicators
- **Smooth scrolling** - Enhanced navigation experience

## 📊 Data Structure

The application uses a comprehensive data model including:

- **FoodItem** - Complete food information with ratings
- **Vendor** - Restaurant/vendor details and location
- **Rating** - User reviews and ratings
- **FilterOptions** - Search and filter preferences
- **UserPreferences** - Personalized user settings

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Project Structure
```
src/
├── components/          # React components
├── types/              # TypeScript type definitions
├── data/               # Mock data and constants
├── App.tsx             # Main application component
├── main.tsx            # Application entry point
└── index.css           # Global styles
```

## 🌟 Future Enhancements

- **Real-time location tracking**
- **Social features and user profiles**
- **Vendor management dashboard**
- **Mobile app development**
- **Advanced recommendation algorithms**
- **Integration with mapping services**
- **Push notifications for new vendors**
- **Offline functionality**

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Unsplash** - Beautiful food photography
- **Lucide** - Elegant icon set
- **Tailwind CSS** - Excellent utility framework
- **Framer Motion** - Smooth animation library

---

**Built with ❤️ for food lovers everywhere!**