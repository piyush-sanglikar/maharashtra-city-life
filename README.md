🏙️ City Life — Maharashtra Civic & Urban Explorer

Live Demo: maharashtra-city-life.vercel.app

An interactive, mobile-friendly civic mapping and smart urban exploration platform built for major cities across Maharashtra (Pune, Mumbai, Nagpur, and Nashik). Designed with a clean, Google Maps-inspired interface, it combines live municipal alerts, wheelchair-accessibility data, hazard-bypass routing, and a bilingual (English / मराठी) civic guide—with zero API keys or build tools required.

✨ Key Features

1. 🗺️ Google Maps-Style Interactive City Map

100% Keyless Map Layers: Switch seamlessly between Street (OpenStreetMap), Satellite + Labels (Esri World Imagery), Terrain (OpenTopoMap), and Dark Mode (CARTO Dark)—with zero API key configuration required.

Floating Search & Instant Autocomplete: Search landmarks, metro stations, pure-veg eateries, or active road alerts with category filter pills (Heritage, Food, Parks, Transit, Temples, Alerts).

Slide-Over Place Details Drawer: Tap any teardrop pin to view ratings, open hours, entry fees, nearest transit hubs, wheelchair accessibility status, and one-tap Save, Share, or Report actions.

GPS Blue Dot & Pin Dropping: Locate yourself via browser geolocation (Locate Me) or right-click / tap Mark Issue on Map to drop a custom red pin anywhere.

2. 🧭 Hazard-Aware Turn-by-Turn Directions

Supports Car/Auto, Metro/Bus, Walk, and Bike travel modes.

Automatically detects active municipal road diversions, waterlogging, or broken footpaths along a corridor and calculates a Hazard-Free Bypass Route.

3. ⚠️ Crowdsourced Civic Safety & Road Alerts

Citizens can submit live reports (Traffic Diversions, Potholes, Waterlogging, Broken Footpaths, Streetlight Outages) with exact map coordinates.

Community confirmation upvotes (3+ confirmations upgrade reports to Community Verified) persist automatically in localStorage.

4. 📋 Accessible Places Directory & Side-by-Side Comparison

33 Verified Venues across Pune (PMC), Mumbai (BMC), Nagpur (NMC), and Nashik (Nashik MC).

Filter by Wheelchair Friendly, Pure Veg, Budget (Free, ₹, ₹₹), and category, or compare up to 3 venues side-by-side.

5. 🤖 Hybrid AI & Offline Civic Helper + Bilingual UI (EN / मराठी)

Instant answers for wheelchair-friendly itineraries, transit connections, and food recommendations—seamlessly switching between Gemini AI (when configured) and a built-in deterministic Maharashtra Civic Rule Engine.

Full SEO optimization with Schema.org JSON-LD structured data, Open Graph social previews, and deep-link city URLs (#pune, #mumbai, #nagpur, #nashik).

🛠️ Tech Stack

Frontend: Semantic HTML5, Vanilla JavaScript (ES6+), Tailwind CSS (CDN)

Mapping Engine: Leaflet.js 1.9.4 + Keyless OpenStreetMap / Esri / OpenTopoMap / CARTO Tile Layers

Icons & Typography: Lucide Icons, Plus Jakarta Sans, JetBrains Mono

Persistence & SEO: Browser localStorage, Schema.org JSON-LD, Open Graph & Twitter Meta Tags

Hosting: Static Zero-Build Deployment on Vercel

🚀 Deployment (GitHub + Vercel)

This project is architected as a single self-contained index.html file—no Node.js, npm install, or bundler step is needed:

Place index.html and README.md in the root directory of your GitHub repository.

Import the repository into Vercel with Framework Preset set to Other (no build command).

Any push to main automatically deploys your updated site within ~30 seconds.

🚨 Emergency Helplines Integrated

National Emergency: 112

Pune (PMC): 1800-1030-222

Mumbai (BMC Disaster Cell): 1916

Nagpur (NMC): 0712-2567021

Nashik (Nashik MC): 1800-233-4455

📄 License

Open-source for civic innovation, urban accessibility, and educational use across Maharashtra.
