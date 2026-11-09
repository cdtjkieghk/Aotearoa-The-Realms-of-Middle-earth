[README.md](https://github.com/user-attachments/files/34577854/README.md)
# Aotearoa-The-Realms-of-Middle-earth# Aotearoa — The Realms of Middle-earth

An interactive, Middle-earth-inspired web map of New Zealand. It uses Leaflet for the map interface and Esri World Topographic Map tiles as the default basemap.

## Run locally

Open `index.html` in a modern browser while connected to the internet. The page loads Leaflet from unpkg and map tiles from Esri.

## Publish with GitHub Pages

1. Create or open a GitHub repository.
2. Upload `index.html` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. Open the Pages URL shown by GitHub after deployment.

## Features

- Esri World Topographic and World Imagery basemaps.
- Filterable markers: film locations, natural places and cities.
- Place pop-ups with short descriptions and coordinates.
- Random quest destination.
- Illustrative Fellowship trail, including a stylised Cook Strait crossing.
- Straight-line distance measurement between two markers.
- Adventurer's notebook to save and revisit places.
- Responsive layout for desktop and mobile.

## Notes

- The Fellowship trail is illustrative, not a road or ferry route.
- Distance measurements are geodesic/straight-line approximations, not driving distances.
- Some map pins are approximate location references. Check local access, weather and conservation guidance before visiting.
- Keep the Esri and data-provider attribution visible if you modify the map.
- The fantasy references are fan-made and unofficial.

## Basemap and attribution

The default layer is Esri's World Topographic Map tile service:
`https://services.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer`

Esri attribution is shown in the map itself. See [Esri's basemap attribution guidance](https://support.esri.com/en-us/knowledge-base/what-is-the-correct-way-to-cite-an-arcgis-online-basema-000012040) and [World Topographic Map item details](https://www.arcgis.com/home/item.html?id=6e850093c837475e8c23d905ac43b7d0).
