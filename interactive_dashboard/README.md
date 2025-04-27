# Interactive Dashboard (Project Two)

This dashboard application allows Grazioso Salvare to filter, map, and visualize animals suitable for rescue operations.

- `ProjectTwoDashboard.ipynb`: JupyterDash app file
- `Grazioso Salvare Logo.png`: Branding logo used in dashboard

## About
An interactive dashboard designed for Grazioso Salvare, a global search-and-rescue dog training organization. Built with Dash and MongoDB.

### Key Technologies:
- Python 3.9+
- Dash (Plotly Dash + Dash Leaflet)
- MongoDB Atlas or Community Edition
- JupyterDash

### Setup
1. Install dependencies:
`pip install jupyter-dash dash dash-leaflet plotly pandas`
2. Ensure MongoDB is populated with the aac database and animals collection.
3. Open ProjectTwoDashboard.ipynb and run all cells to launch the dashboard.

### Dashboard Features
- Interactive filtering by rescue type (Water, Mountain, Disaster/Tracking)
- Live MongoDB querying with real-time updates
- Dynamic Pie Chart of breed distributions
- Geolocation mapping with breed and animal names
- Sortable and selectable DataTable
