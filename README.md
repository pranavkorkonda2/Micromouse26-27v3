# Micromouse 2026-27: Prototype V3 (Pranav's Design)

This repository contains the V3 hardware prototype for the 2026-27 IEEE Micromouse competition. This revision deviates from earlier templates to solve specific physical clearance and weight distribution challenges identified in previous iterations.

## Key Hardware Improvements

* **Top-Mounted Battery for Optimal CoG:** After evaluating underside and motor-top mounting strategies, the battery is mounted top-center. This prevents chassis scraping, protects delicate components, and centralizes the Center of Gravity (CoG) for better high-speed cornering stability.
* **Accommodates 32mm Wheels:** The board layout and component placement are explicitly routed to provide full clearance for 32mm wheels, ensuring zero friction or wheel-bite during tight maze maneuvers.
* **J5 Connector Integration:** Features the updated J5 connector placement for clean, interference-free peripheral routing.

## File Structure & Review Notes

To maintain compatibility with the team's automated review scripts and existing templates, the core KiCad project files retain the standard `bloo` prefix. 

**To review the PCB layout:**
1. Open `bloo.kicad_pro` in KiCad.
2. Launch the PCB Editor (`bloo.kicad_pcb`) to view the top-mounted battery routing and wheel clearances.
