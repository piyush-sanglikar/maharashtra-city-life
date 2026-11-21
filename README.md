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

