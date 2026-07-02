# 🥎 College Softball Programs Map

An interactive map of **every college softball program** in the continental United States — all divisions, all levels.

## Live Site

👉 **[View the Map](https://tinagabriele.github.io/college-softball-map/)**

## Data Sources

| Association | Source | Programs |
|---|---|---|
| NCAA D1, D2, D3 | [NCAA Directory API](https://web3.ncaa.org/directory/api/directory/memberList) | 968 |
| NAIA | [NAIA Prestosports Data Feed](https://naiastats.prestosports.com) | 191 |
| NJCAA D1, D2, D3 | [NJCAA Prestosports Data Feeds](https://njcaastats.prestosports.com) | 392 |
| NWAC | [NWAC Stats](https://nwacsports.com) | 26 |
| CCCAA/3C2A | [3C2A Stats](https://3c2astats.prestosports.com) | 79 |
| USCAA | [USCAA Stats](https://uscaastats.prestosports.com) | 31 |

**Total: 1,687 programs**

## Geocoding

Coordinates sourced from:
1. **IPEDS** (US Dept of Education Integrated Postsecondary Education Data System) — primary source
2. **Nominatim/OpenStreetMap** — fallback for schools not in IPEDS
3. **Manual verification** — for remaining edge cases

## Features

- 🗺️ Interactive Leaflet.js map
- 🎨 Color-coded by association/division
- 🔍 Search by school name, state, city, or conference
- 👆 Click any dot for school details
- 🎛️ Toggle associations on/off via legend

## Tech Stack

- Leaflet.js (mapping)
- GeoJSON (data format)
- GitHub Pages (hosting)
- CartoDB Positron tiles (basemap)

## Data Last Updated

July 2, 2025

---

Built as a personal project to visualize college softball opportunity across the US.
