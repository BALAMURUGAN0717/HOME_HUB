# HOMEHUB – Premium Home Appliances E-Commerce Platform

> **Tagline:** *Smart Living Starts at Home.*

HOMEHUB is a complete, modern, fully functional Home Appliances E-Commerce web application built with **React JS**, **Three.js**, and modern CSS. Designed to deliver an internationally recognized shopping experience for premium electronics, it combines interactive 3D web visualizations with a robust frontend e-commerce architecture.

---

## 🌟 Key Features

### 1. 3D Web & Motion Experience
- **Interactive Three.js 3D Hero Section**: Rotating futuristic appliance monument with holographic materials, particle clouds, orbital tech rings, and mouse/touch gyroscope tracking.
- **Interactive 3D Product Stage (`Appliance3DViewer`)**: Real-time 3D model orbiting and 360-degree rotation view on the Product Details page.
- **Micro-interactions & Animations**: 3D card hover elevation, smooth glassmorphic header, floating spec pills, and celebratory order confetti.

### 2. Full Product Catalog (40+ Appliances)
- **10 Core Categories**:
  1. Refrigerators (Double Door, Triple Door, French Door, Side-by-Side)
  2. Washing Machines (AI Front Load, EcoBubble Top Load, Washer-Dryer)
  3. Air Conditioners (5-Star Dual Inverter, PM2.5 Clean Air)
  4. Televisions (4K OLED, Neo QLED, Google TV)
  5. Kitchen Appliances (Digital Air Fryers, Food Processors, OTGs)
  6. Microwave Ovens (Charcoal Convection, Slim Fry)
  7. Dishwashers (Intensive Kadhai Wash, TrueSteam)
  8. Vacuum Cleaners (Laser Detect Cordless, LiDAR Robot Mops)
  9. Water Purifiers (Active Copper RO+UV, Alkaline)
  10. Fans & Coolers (BLDC Smart Inverter Fans, Honeycomb Coolers)
- **Top International & Indian Brands**: Samsung, LG, Sony, Bosch, Whirlpool, Voltas, IFB, Philips, Dyson, Kent, Havells, Haier.
- **Rich Product Metadata**: Realistic INR (`₹`) pricing, original MRP strike-through, discount badges, 5-Star BEE energy ratings, technical specifications matrix, warranty certificates, and stock levels.
- **Resilient Image Handling**: Dual image galleries with automatic fallback SVG graphics to prevent broken images.

### 3. Faceted Search, Filtering & Sorting
- **Instant Search**: Autocomplete drop-down preview with thumbnail, brand, and live price.
- **Multi-Filter System**:
  - Filter by Category (10 categories)
  - Filter by Brands (checkboxes with count)
  - Max Price Slider (₹3,000 to ₹1,50,000+)
  - Customer Rating (4.0★ & 4.5★ and above)
  - Discount Range (20%+, 30%+, 40%+)
  - In-Stock Only filter
- **Sorting Options**: Featured, Price: Low to High, Price: High to Low, Customer Rating, Newest, Best Sellers.
- **View Modes**: Switch between Grid and List view.
- **URL Synchronization**: Direct deep linking via `?category=...`, `?brand=...`, `?search=...`.

### 4. Shopping Cart & Promo Coupons
- Add / remove items, increment/decrement with stock validation.
- Free Express Delivery Progress Bar (Unlocks at ₹10,000).
- Working Promo Coupons:
  - `HOME10`: 10% OFF on all appliances
  - `WELCOME15`: 15% OFF for new buyers
  - `SAVE500`: Flat ₹500 instant discount
- LocalStorage persistence across browser reloads.

### 5. Product Comparison Matrix
- Compare up to **4 appliances side-by-side**.
- Comprehensive specification comparison table (Price, Brand, Energy Rating, Warranty, Capacity, Dimensions, Power, and Special Features).
- Quick "Add to Cart" directly from the comparison matrix.

### 6. Wishlist
- Save favorite appliances with one click.
- "Move to Cart" functionality and stock availability status.

### 7. Multi-Step Checkout & Payment Simulation
- **Step 1**: Customer Contact details.
- **Step 2**: Delivery Address (supports saved address selection or new address).
- **Step 3**: Order Review with item breakdown.
- **Step 4**: Simulated Payment Gateway:
  - **Cash on Delivery (COD)**: Payment during unboxing.
  - **UPI (Google Pay / PhonePe / Paytm)**: Interactive QR code & demo VPA.
  - **Credit / Debit Card Simulator**: Pre-filled sandbox testing mode.
- *Notice*: Pure simulated frontend checkout; no sensitive banking data is gathered or stored.

### 8. Order Tracking with 6-Stage Visual Timeline
- Track by Order ID (e.g., `HH-782914` or newly created orders).
- 6-Stage Timeline:
  1. `Order Placed`
  2. `Order Confirmed`
  3. `Processing`
  4. `Shipped`
  5. `Out for Delivery`
  6. `Delivered`
- Includes carrier tracking ID, assigned logistics vehicle, estimated delivery date, and unboxing technician appointment.

### 9. User Dashboard
- **My Orders**: Complete order history, items purchased, invoice totals, and track link.
- **Saved Addresses**: Add, manage, and delete delivery locations.
- **My Profile**: Update name, phone, and contact details.
- **Account Settings**: WhatsApp notification preferences.

### 10. Admin Demo Control Panel
- Clearly labeled frontend demo panel.
- **Key Metrics**: Total Revenue, Total Orders, Catalog Items, Customer Count.
- **Product Management**: Add new appliance, edit price & stock, delete with confirmation, and "Reset to 42 Default Products" button.
- **Live Order Management**: Change order status directly via dropdown (`Processing` -> `Shipped` -> `Delivered`), which updates the customer's live tracking view in real time.
- **Sales Analytics**: Category revenue breakdown.

### 11. Dark Mode / Light Mode System
- Full theme support using CSS variables and root attributes.
- Smooth transitions affecting all cards, modals, headers, inputs, and footers.
- Sun/Moon toggle in the navigation bar, saved in LocalStorage.

---

## 🛠️ Technology Stack

- **HTML5 & CSS3**: Modern variables, glassmorphism, responsive grid & flexbox layouts.
- **JavaScript (ES6+)**: Clean modular architecture.
- **React 18**: Function components, hooks, React Context API for global state.
- **Three.js**: Interactive 3D WebGL hero model and 360-degree product stage viewer.
- **React Router DOM v6**: Client-side routing and deep links.
- **Lucide React Icons**: Cohesive iconography.
- **Canvas Confetti**: Celebration animation on order confirmation.
- **Vite 5**: Ultra-fast build and development environment.

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm (v9 or higher)

### Installation
Clone or navigate to the repository folder:

```bash
cd homehub
npm install
```

### Run Locally in Development Mode
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) (or the port Vite outputs) in your browser.

### Build for Production
```bash
npm run build
```
This produces an optimized production build inside the `dist/` directory.

### Preview Production Build
```bash
npm run preview
```

---

## 🔐 Demo Credentials

Quick demo accounts are pre-configured with instant login buttons on the Login page:

| Role | Email | Password |
| :--- | :--- | :--- |
| **Demo Customer** | `user@homehub.com` | `user123` |
| **Demo Admin** | `admin@homehub.com` | `admin123` |

---

## ☁️ Vercel Deployment

The project is pre-configured with `vercel.json` for seamless Single Page Application (SPA) routing:

```json
{
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/index.html"
    }
  ]
}
```

To deploy to Vercel:
1. Push your code to GitHub / GitLab / Bitbucket.
2. Import the project in Vercel.
3. Framework Preset: **Vite**.
4. Build Command: `npm run build`.
5. Output Directory: `dist`.
6. Click **Deploy**.

---

## 📄 License
MIT License. © HOMEHUB Technologies Pvt. Ltd. Smart Living Starts at Home.
