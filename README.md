# 🚐 VanNav Pro

> Professional navigation for van and HGV drivers — built by a driver, for drivers.

**Live app:** [kc-ops2.github.io/Vannav-pro](https://kc-ops2.github.io/Vannav-pro)

---

## What is VanNav Pro?

VanNav Pro is a mobile-first navigation web app designed specifically for professional van and HGV drivers in the UK. Unlike generic sat-nav apps, VanNav Pro understands the real challenges of commercial driving — low bridges, weight restrictions, clean air zones, HGV speed limits, and community hazard reporting.

---

## Key Features

### Navigation
- 🗺️ TomTom-powered truck/van routing with vehicle dimension awareness
- 🔀 Multi-route alternatives — Fastest, Shortest, Eco
- 📍 Address autocomplete and reverse geocoding
- 💾 Save and reload favourite routes

### Drive Mode
- 🏙️ 3D MapLibre GL drive mode with pitch toggle
- 🔊 Voice turn-by-turn instructions (Full / POI + Alerts / Alerts only / Off)
- 🪟 HUD windscreen projection mode
- 📡 GPS position snapping to route line
- ✂️ Route trimming as you drive
- 🔄 Automatic rerouting when off route
- 📶 Offline fallback — continues on cached route when signal drops

### Speed & Safety
- 🚗 Vehicle-aware UK speed limits (Van, LGV, HGV, Coach, Motorhome)
- 🛣️ Road type detection — Motorway / Dual / Single / Built-up
- ⚠️ Speed warning with pulsing alert when over limit
- 📷 Live speed cameras via OpenStreetMap

### Alerts & Hazards
- 🌉 20 UK low bridges with height restrictions
- 🚇 18 UK road tunnels with clearance data
- 🚫 17 UK Clean Air Zones
- ⛰️ 15 notorious steep hills
- 🚨 Community hazard reports (Firebase real-time database)
- 🔔 Real-time community hazard proximity alerts

### Stops Along Route
- ⛽ Fuel stations
- ⚡ EV charging
- 🅿️ Lorry parks
- 🛣️ Motorway services
- 😴 Rest areas
- 🍽️ Food
- ☕ Coffee
- 🏧 ATM

### Other
- 🚦 Live traffic overlay (TomTom flow tiles)
- 📍 Proximity POI — stops appear on map as you approach within 150m
- 🌍 Multi-country support (feature branch) — GB, FR, DE, NL, BE, ES, IE, IT, PL
- 📱 PWA — installable on Android home screen
- 🌙 Day/night theme
- 🌐 5 languages — English, French, German, Spanish, Polish
- 📏 Imperial and metric units

---

## Vehicle Profiles

24 presets across 4 categories — van, LGV, HGV, coach, motorhome. Set your height, width, weight and length once and the app handles the rest.

---

## Tech Stack

- **Map rendering:** Leaflet.js 1.9.4 (2D) + MapLibre GL 4.1.2 (3D)
- **Routing & traffic:** TomTom Routing + Traffic API
- **Geocoding:** Nominatim / OpenStreetMap
- **Speed cameras:** OSM Overpass API
- **Community reports:** Firebase Realtime Database
- **Hosting:** GitHub Pages
- **No framework** — pure HTML, CSS, JavaScript

---

## Roadmap

- [ ] Multi-stop route planning
- [ ] Lane guidance
- [ ] Live fuel prices
- [ ] Taxi driver mode
- [ ] Android / Play Store release (Capacitor)
- [ ] Android Auto support
- [ ] Multi-country speed limits (in progress — feature/multi-country branch)

---

## Legal

© 2026 VanNav Pro. All rights reserved.  
See [LICENCE](./LICENCE) for terms.
