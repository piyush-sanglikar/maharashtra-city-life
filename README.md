# 🏙️ City Life: AI-Powered Smart City Exploration & Safety Platform
> *"Explore Smarter. Travel Safer. Experience More."*

An ethical, intelligent, and interactive smart city exploration web platform anchored on **Pune, Maharashtra, India**. Built for tourists, students, residents, and families to experience the city while navigating urban complexity with truthful source attribution and zero fabricated metrics.

---

## 🌟 Key Features

1. **Smart City Dashboard & City Pulse**:
   - Live real-time weather integration via Open-Meteo REST API (temperature, conditions, wind speed, humidity) with automatic offline snapshot fallback.
   - Verified Municipal & Weather Alerts ticker (Pune Municipal Corporation engineering notices & IMD Pune advisories).
2. **Context-Aware City Exploration**:
   - 12 verified Pune landmarks across Historical, Cultural, Food & Dining, Parks, Student/Budget, and Public Facility categories.
   - Parametric filters: Dietary (Pure Veg / Veg Options 🥦), Accessibility (Wheelchair accessible step-free vs. steps ♿), and Budget tiers (Free, ₹, ₹₹).
   - Real-time search by landmark name, neighborhood, or keywords.
3. **Trust-Aware City Safety Intelligence**:
   - Sourced safety pins on the interactive map with clear verification levels:
     - 🟢 **Official Notices** (PMC Engineering / Traffic Police)
     - 🟡 **Community Verified** (Validated citizen submissions)
     - ⚪ **Unverified Reports** (Newly submitted community notices under review)
   - **Zero Fabrication Pledge**: Strictly excludes synthetic "crime scores" or artificial "danger zones".
4. **Citizen Incident Reporting**:
   - Submission modal with category selection (Streetlight Outage, Road Hazard/Pothole, Waterlogging, Public Facility Issue).
   - Interactive Pin Dropper: Tap "Drop Pin Report", click anywhere on the map, and submit a location-grounded report.
5. **Transparent Place Comparison**:
   - Side-by-side comparison matrix for up to 3 places.
   - Evaluates admission costs, operating hours, wheelchair accessibility, and dietary options with clear disclosures when registry data is unavailable.
6. **Smart Route Planner**:
   - Multi-modal routing (Walking 🚶, Cycling 🚲, Driving 🚗).
   - Travel corridor hazard detection: Alerts travelers if their path passes near an active reported incident or road diversion.
   - Visual polyline overlay on the interactive map.
7. **Rule-Based City Assistant**:
   - Grounded, deterministic assistant answering queries on budget spots, pure vegetarian dining, heritage sites, and weather warnings with zero AI hallucinations.

---

## 🛠️ Technologies Used

- **HTML5 & Vanilla JavaScript**: Fast, dependency-free client application.
- **Tailwind CSS (via CDN)**: Modern, responsive dark-mode design system.
- **Leaflet.js (via CDN)**: Open-source interactive geospatial mapping.
- **CartoDB Voyager Vector Tiles**: Clean, high-performance map rendering.
- **Open-Meteo API**: Open-access real-time weather service with zero API key requirement.

---

## 🚀 How to Run Locally (Zero Installation)

No Node.js, npm, or local servers are required!

1. Open `city-life-deploy` in your file explorer.
2. Double-click **`index.html`** or right-click and open with **Google Chrome** or **Microsoft Edge**.
3. The platform will run instantly in your browser.

---

## 🌐 Deploy to GitHub & Vercel in 2 Minutes

### Step 1: Upload to GitHub (Via Browser — No Git CLI Needed)
1. Go to [github.com/new](https://github.com/new) and create a new repository named `city-life`.
2. On the repository page, click **"uploading an existing file"**.
3. Drag and drop all files from `city-life-deploy`:
   - `index.html`
   - `vercel.json`
   - `README.md`
4. Click **"Commit changes"**.

### Step 2: Deploy to Vercel (1-Click)
1. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **"Add New..."** -> **"Project"**.
3. Select your `city-life` repository.
4. Framework Preset: Leave as **"Other"** (Vercel automatically detects `index.html` as a static site).
5. Click **"Deploy"**.
6. Your live public URL (e.g., `https://city-life.vercel.app`) will be live in 10 seconds!
