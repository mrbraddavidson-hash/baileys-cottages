# Bailey's Cottages & Moira Lake Angler Field Guide

**Live Production URL:** [https://baileys-cottages.pages.dev](https://baileys-cottages.pages.dev)  
**Location:** 141 Lahey Road, Madoc, Ontario K0K 2K0 • Moira Lake (FMZ 18)  
**Established:** 1943  

---

## Overview

Bailey's Cottages is a historic 80-year-old family vacation and fishing resort on the pristine shores of Moira Lake in Centre Hastings, Ontario. This repository contains the complete production web application, interactive bathymetric angling map, species catch showcase, cabin reservation portal, and 71-photo heritage archive.

---

## Key Features

1. **Moira Lake Interactive Topography & Bathymetric Chart**:
   - Depth soundings up to 30 ft maximum depth kettle hole
   - Dynamic bathymetric contour lines (5ft, 10ft, 15ft, 20ft, 25ft, 30ft)
   - 8 field-verified hotspots (Papoose Island Channel, Stony Island Reef, Green Island Shallows, North Basin Deep Hole, Moira River Inflow Delta, Eastern Cabbage Drift, Southern River Outflow Reach, Bailey's Private Launch)
   - Live live-sonar acoustic depth sounder tool (point-and-click depth simulation)
   - Multi-layer map toggle (Topographic Contours, Satellite Ortho, OpenStreetMap)

2. **Verified Species Catch Showcase**:
   - 19 authentic guest catch photographs grouped into 5 biological species:
     - **Muskellunge (Muskie)**: 4 authentic catches, including 45"+ monster on bump board
     - **Walleye (Yellow Pickerel)**: 4 authentic catches, including deep late-season female and 5-fish keeper stringer
     - **Largemouth & Smallmouth Bass**: 5 authentic catches across weedlines, lily pads, and rock reefs
     - **Northern Pike**: 5 authentic catches up to 40"+ class
     - **Black Crappie & Panfish**: Family tradition dock memory
   - Full Ontario FMZ 18 regulations, legal size limits, slot rules, target depths, and tactics
   - Interactive high-resolution modal lightbox with keyboard `Escape` navigation

3. **Cabins 1 through 6 Accommodation Guide**:
   - Complete photo switcher for each housekeeping cabin (Exterior, Interior, Scenic View, Bedrooms)
   - Capacity, rate transparency ($150/nt weekday, $175/nt weekend, 2-night minimum)
   - Direct booking modal with date selector and 50% deposit breakdown

4. **Boat & Gear Rentals Calculator**:
   - 14' aluminum fishing boats + 9.9HP outboards ($85/day)
   - Recreational canoes & kayaks ($35/day)
   - Private dock slips & launch ramp passes ($20/day)
   - Hardwood campfire bundles ($10/bundle)
   - Live interactive trip cost estimator with instant deposit calculations

5. **Historical Facebook Guest Archive (`facebook_gallery.html`)**:
   - 71 verified unique high-resolution guest photos with 0 duplicates
   - Interactive category filtering: Fish Catches (19), Waterfront & Docks (31), Camp Life & Games (21)
   - Fullscreen lightbox viewer

6. **Curated Madoc Local Field Guide**:
   - Downtown Madoc dining and provision recommendations (Hidden Goldmine Bakery, Burnbrae Farms, etc.)
   - Pioneer conservation areas (O'Hara Mill Homestead)
   - Trail systems and bait shops within 5 to 10 minutes of camp

---

## Technical Stack & Standards

- **HTML5 & Semantic Markup**: Structured for fast static delivery
- **Tailwind CSS (v3)**: Custom rustic palette (`pine`, `camp`, `amber`, `stone`)
- **Leaflet.js (v1.9.4)**: Interactive mapping with custom bathymetric canvas layers
- **Lucide Icons**: Crisp vector UI icons
- **Google Fonts**: Cinzel (Heritage Roman serif) + Plus Jakarta Sans (Body typography)
- **Anti-Slop Standards**: Zero em dashes (`—`), strict WCAG AA contrast (6.95:1), visible focus rings, full keyboard accessibility (`Escape` key modal dismiss), and 100% mobile responsiveness (no horizontal scroll overflow at 375px)

---

## Deployment

Hosted on **Cloudflare Pages**:
```bash
npx wrangler pages deploy . --project-name baileys-cottages
```
