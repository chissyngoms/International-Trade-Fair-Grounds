# ZITF Navigator

Interactive web map for navigating the Zambia International Trade Fair (ZITF) grounds.

This project was developed to improve visitor navigation and exhibitor visibility through a clean, interactive digital map built using GIS and web mapping technologies.

---

## Features

- Interactive stand and building map
- Clickable popups with exhibitor information
- Search functionality for stands and companies
- Road and pathway visualization
- Responsive full-screen web map
- Lightweight and fast loading

---

## Built With

- QGIS
- qgis2web
- Leaflet.js
- GeoJSON
- GitHub Pages

---

## Map Layers

The web map currently includes:

- ZITF Buildings
- Exhibition Stands
- Roads and Walkways
- Gates and Entrances
- Grounds Boundary

Additional layers may be added in future updates.

---

## Purpose of the Project

The goal of ZITF Navigator is to create an accessible and user-friendly navigation platform for visitors, exhibitors, and event organizers during the Zambia International Trade Fair.

The project demonstrates how GIS and web mapping can improve movement, accessibility, and information sharing within large event spaces.

---

## Data Workflow

```text
Google Satellite Imagery
        ↓
Digitizing in QGIS
        ↓
Data Cleaning & Attribute Structuring
        ↓
Export via qgis2web
        ↓
Hosted on GitHub Pages
