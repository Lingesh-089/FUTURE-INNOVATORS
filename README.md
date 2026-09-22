# FUTURE-INNOVATORS

## Adaptive Variable-Resolution 2.5D LiDAR Mapping for Dynamic Environment Perception

Interactive browser simulation demonstrating:

- Raw-style multi-beam LiDAR point-cloud visualization
- North-up sensor-return display
- Variable-resolution 2.5D mapping by distance
- Partial building observation limited by simulated LiDAR vertical FOV
- Realistic-shaped buildings, trees, vehicles, and pedestrians in the scene
- Hard building boundaries for the platform
- Defined traffic lanes with vehicles entering, moving through, turning, following, and leaving the map
- Defined pedestrian routes with continuous inflow/outflow
- Dynamic scene perception and live map updates

### Resolution model

| Distance | Map resolution |
|---|---:|
| 0–5 m | 5 cm |
| 5–10 m | 10 cm |
| 10–15 m | 25 cm |
| 15–18 m | 50 cm |

The browser simulation is a visual prototype. Its LiDAR returns, traffic flow, and environment are simulated rather than recorded from a physical sensor or replayed from a measured traffic dataset.

## Run locally

Open `index.html` directly in a modern browser, or serve the repository with a local static server.

