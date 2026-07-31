# PulseMap-API-Fusion
Hey, This is my submission for the API fusion contest. Hope you find it interesting.
# 🌍 PulseMap — See the World's News, Where It Happens

PulseMap is an interactive hyper-local news visualizer built for the API Fusion Ideathon. It dynamically combines **OpenStreetMap** and **NewsAPI** to map breaking news stories onto an interactive geographic canvas.

## 👥 Team
* **Team Name:** Eurekaa
* **Assigned APIs:** OpenStreetMap + NewsAPI

## 🛠️ Tech Stack & Architecture
* **Frontend:** React.js / Leaflet.js
* **Map Service:** OpenStreetMap (OSM) Tiles
* **Data Feed:** NewsAPI JSON Endpoints

## 🔄 API Integration Workflow
1. User interacts with or zooms into a region on the OpenStreetMap interface.
2. Coordinates/bounds are captured, translating the viewport into a geographic location name.
3. A query request is dispatched to `NewsAPI /v2/everything?q={location}`.
4. Returned news articles are rendered as interactive, clickable story pins on the map.

## 🚀 Future Scope
* ML sentiment analysis to color-code news markers (Red/Yellow/Green).
* Personalized location notifications and saved travel route updates.
