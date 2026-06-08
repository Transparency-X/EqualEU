# EqualEU – The European LGBTQ+ Organizations Hub

*Alternative unique names: PrismMap, Rainbow Compass EU, Queer Atlas*

## 📖 GitHub README Overview

**EqualEU 🌈 – A curated, open‑source directory of LGBTQ+ charities, associations, and public bodies across the European Union.**

Finding reliable contact information and understanding the mission of local LGBTQ+ groups can be challenging. EqualEU solves that by collecting, verifying, and presenting data on thousands of organizations in a single, searchable interface.

### Why EqualEU?
- Trustworthy data – sourced from official registries and umbrella networks like ILGA‑Europe.
- Always up‑to‑date – community contributions + automatic validation.
- Free for all – no paywalls, no ads, just a public good.

### Live Demo
[Link to demo / screenshot placeholder]

### Tech Stack
- Frontend: React + Leaflet (interactive map)
- Backend: Node.js + Express
- Database: PostgreSQL with PostGIS
- Data format: JSON / GeoJSON for easy export

## ✅ Features List (Current / v1.0)

| Feature | Description |
|---------|-------------|
| **Country filter** | Browse organizations by any EU member state |
| **Category tags** | Filter by type – e.g., youth, trans rights, families, legal aid, health |
| **Interactive map** | See each organization’s location (or city centroid) on a map |
| **Detailed cards** | Each entry shows: name, website, email, mission, and verified status |
| **Search** | Full‑text search across names, mission statements, and tags |
| **Export** | Download filtered results as CSV or JSON |
| **Open data** | All data is CC‑BY‑4.0 licensed for reuse in research or apps |

## 🗺️ Future Features Roadmap

### Phase 1 – Foundation (completed)
- [x] Scrape and clean data from ILGA‑Europe members & national registries  
- [x] Basic web interface with country filter and list view  

### Phase 2 – Community & Accuracy (Q3 2026)
- [ ] User suggestion form (add/update an organization)  
- [ ] Moderation dashboard for trusted volunteers  
- [ ] “Last verified” timestamp and flag for outdated entries  

### Phase 3 – Advanced Tools (Q4 2026)
- [ ] **API endpoint** – GET `/orgs?country=FR&category=trans`  
- [ ] **Embeddable widget** – websites can show nearby LGBTQ+ resources  
- [ ] **Mobile‑first PWA** (offline access to basic directory)  

### Phase 4 – Impact & Integration (2027)
- [ ] **Report discrimination** – anonymous form linked to local legal aid orgs  
- [ ] **Event calendar** – marches, workshops, support group meetings  
- [ ] **Machine‑learning tagging** – auto‑suggest categories based on mission text  
- [ ] **Donation redirect** – optional link to support each listed organization  
