# Cassiopeia - Flower Store

A modern, responsive e-commerce website for a flower retail store, built with Next.js and powered by Firebase.

## 🚀 Live Website

[https://dh-cassiopeia.web.app](https://dh-cassiopeia.web.app/)

## 📋 About the Project

Cassiopeia is an e-commerce platform specializing in flowers, plants, gifts, and related products. The website features a clean, user-friendly interface with full responsiveness across all devices.

### Key Features

- **Product Catalog**: Browse flowers, plants, gifts, and discounted items
- **Search & Filter**: Advanced search functionality with filtering options
- **Shopping Cart**: Add, remove, and manage cart items
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Static Site Generation**: Fast loading with Next.js pre-rendering
- **Real-time Database**: Firebase integration for dynamic content

## 🛠️ Technology Stack

- **Frontend Framework**: Next.js 11.1.2 (with Static Generation)
- **UI Library**: React 17.0.2
- **State Management**: Redux Toolkit, Redux
- **Styling**: SASS/SCSS
- **Backend/Database**: Firebase (Realtime Database, Hosting, Analytics, Admin SDK)
- **Additional Libraries**:
  - @splidejs/react-splide (Carousel/slider)
  - react-slideshow-image (Image slideshow)
  - slick-carousel (Carousel)
- **Development Tools**: ESLint, Cross-env

## 📁 Project Structure

```
cassiopeia/
├── api/                    # API routes
├── components/             # Reusable React components
│   ├── contents/          # Content-specific components
├── fonts/                 # Custom fonts
├── function/              # Utility functions
├── handle_data_functions/ # Data handling utilities
├── hooks/                 # Custom React hooks
├── pages/                 # Next.js pages (App Router)
├── public/                # Static assets
├── reducers/              # Redux reducers
├── redux/                 # Redux slices
├── pure_functions/        # Pure utility functions
├── styles/                # Stylesheets
│   ├── global/           # Global styles
│   └── scss/             # SCSS modules
├── database.rules.json    # Firebase database rules
├── firebase.json          # Firebase configuration
├── next.config.js         # Next.js configuration
├── package.json           # Dependencies and scripts
└── store.js              # Redux store configuration
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- Firebase account and project

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cassiopeia.git
   cd cassiopeia
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Firebase**
   - Create a Firebase project at [https://console.firebase.google.com/](https://console.firebase.google.com/)
   - Enable Realtime Database, Hosting, and Analytics
   - Copy your Firebase config to a `.env.local` file or configure in the code

4. **Configure environment variables** (if needed)
   - Add your Firebase configuration keys

### Running the Application

**Development mode:**
```bash
npm run dev
```
The app will be available at `http://localhost:3000`

**Build for production:**
```bash
npm run build
```

**Start production server:**
```bash
npm start
```

**Export static files:**
```bash
npm run build && next export
```

## 📱 Usage

- **Home Page**: Browse featured products and categories
- **Product Categories**: Flowers, Plants, Gifts, Discounts
- **Search**: Use the search bar to find specific products
- **Filters**: Apply filters to narrow down product results
- **Cart**: Add items to cart and proceed to checkout
- **Product Details**: View detailed information about individual products

## 🎨 Design

The design is based on a free UI kit from Behance: [Cassiopeia Flower Store UI Kit](https://www.behance.net/gallery/96992647/Cassiopeia-Flower-store-Free-UI-kit) by Alice Samokhina.

## 📊 Status

The project is essentially complete and functional. Future updates may include additional Next.js features and enhancements.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is private and not licensed for public use.

## 📞 Contact

For questions or support, please contact the project maintainer.
