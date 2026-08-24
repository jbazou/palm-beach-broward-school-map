# Palm Beach & Broward County Schools

Interactive meeting-scheduling map for 69 schools in Palm Beach County and Broward County.

## Features

- Suggests up to three nearby schools using routed driving time.
- Applies meeting duration and arrival/check-in buffers.
- Supports meeting date, start time, and maximum-drive settings.
- Draws the suggested itinerary on the map.
- Opens the final stop order in Google Maps for traffic verification.
- Exports the itinerary as CSV.

Driving-time estimates use the public OSRM service and do not include live traffic. Confirm the final itinerary before booking meetings.

## Security and privacy

- The site is static and does not collect, transmit, or store user-entered meeting details.
- A restrictive Content Security Policy limits scripts, styles, map tiles, and route requests to the services required by the map.
- Leaflet assets are version-pinned and protected with Subresource Integrity hashes.
- External Google Maps links are isolated from the scheduling page and do not receive its referrer URL.
- Route calculations send only the selected schools' public coordinates to the public OSRM routing service.

## GitHub Pages

Publish this repository from the `main` branch and `/ (root)` folder in Settings > Pages.
