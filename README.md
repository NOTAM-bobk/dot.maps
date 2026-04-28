# 🗺️ Route Planner On-The-Go

A powerful, mobile-friendly web application for creating, visualizing, and managing multi-point routes. It combines interactive mapping, local search, route optimization, and elevation data in a sleek, glass-morphism UI. Perfect for planning walks, bike rides, drives, or exploring new areas.

🔗 **[Live Demo]**(https://dot-maps.edgeone.app/) 

## ✨ Key Features

-   **Interactive Multi-Point Routing**: Click on the map to add waypoints. Drag them to reorder, or double-click to remove.
-   **Multiple Travel Profiles**: Switch between Walking, Cycling, Driving, and a "Straight Line" view with a single click.
-   **Real-time Route Info**: Displays total distance, estimated time (with Naismith’s rule elevation adjustment), and turn-by-turn directions.
-   **Elevation Profile**: Fetches and displays an elevation chart for your route, showing total gain, loss, and max altitude.
-   **Local Explorer**: Search for nearby restaurants, parks, groceries, and public spaces within the current map view and add them as waypoints.
-   **Search Along Route**: Find points of interest (e.g., coffee shops, gas stations) within the corridor of your planned route.
-   **Auto-Generate Routes**: Create a circular "Loop" or an "Out & Back" course from the map center based on a target distance (e.g., "Generate a 5k running loop").
-   **Save & Load Routes**: Save your favorite routes and locations to your browser's local storage and load them later.
-   **GPX Import/Export**: Import `.gpx` files from your GPS device or export your created routes for use in other apps.
-   **Strava Heatmap Integration**: *(Feature)* View your own Strava activities as a heatmap on the route planner (requires authentication).
    - *Note: The client ID and secret in the code are for demonstration. For a production app, you must secure these on a backend.*
-   **Shareable Routes**: Generate a shareable URL link that contains all your waypoints and the selected travel profile.
-   **Multiple Map Styles**: Cycle through Clean, Standard, Topographical, and Satellite map layers.
-   **Persistent Sessions**: Your last edited route and profile are automatically saved and restored on page reload.

## 🛠️ Built With

-   **[Leaflet.js](https://leafletjs.com/)** - The core interactive mapping library.
-   **[OpenStreetMap](https://www.openstreetmap.org/) (Nominatim)** - For geocoding (searching for places) and reverse geocoding (getting addresses from coordinates).
-   **[OSRM](https://project-osrm.org/) (Open Source Routing Machine)** - The backend routing engine for driving, cycling, and walking routes.
-   **[Open-Meteo](https://open-meteo.com/)** - For fetching elevation data along the route.
-   **[Chart.js](https://www.chart.js/)** - For rendering the elevation profile chart.
-   **[TailwindCSS](https://tailwindcss.com/)** - For the UI styling and the "glass-morphism" panels.
-   **[Strava API v3](https://developers.strava.com/)** - Used to fetch and display user activities as a heatmap.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

-   A modern web browser (Chrome, Firefox, Safari, Edge).
-   An internet connection to load the required libraries and fetch map data.

### Installation & Setup

1.  **Clone or Download the Repository**
    ```bash
    git clone https://github.com/your-username/route-planner-otg.git
