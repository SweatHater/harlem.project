# Harlem Hub: AI-Powered Transit & Vendor Manager
### Lead Designer: Taha Ilyas**An AI Platform for Organizing Community Vendor Markets in Urban Transit Hubs**

## 1. Project Overview
Harlem Hub is a prototype AI-supported platform designed to help city planners and community groups manage the flow of pedestrians and local vendors at major Harlem transit intersections (e.g., 125th St & Lexington).

### The Core Problem
Current transit hubs in Harlem suffer from:
* **Pedestrian Bottlenecks:** Unorganized street vending blocks subway entrances.
* **Barriers to Entry:** Local Harlem entrepreneurs struggle with slow permitting.
* **Lack of Diversity:** High-traffic areas are often dominated by non-local corporate entities.

## 2. System Workflow
1. **Registration:** Vendors/Performers upload permits via the Harlem Hub portal.
2. **AI Verification:** The system checks mock documents for validity.
3. **AI Placement Engine:** Using real-time data, the AI assigns a GPS-specific "stall" to the vendor.
4. **Public Interface:** Commuters use a live web-map to find local food, art, and music in the hub.

## 3. AI Placement Logic
To ensure fairness and safety, the AI follows these programmed "Harlem Rules":

* **Safety Buffer:** No placement within 15ft of subway stairs.
* **Congestion Score ($C$):** Calculated as $C = P/W$ (Pedestrians / Sidewalk Width). AI prevents placement if $C > 0.8$.
* **Equity Weighting:** Vendors from Harlem ZIP codes (10027, 10030, etc.) receive a +25% priority boost for "Prime Spots."
* **Acoustic Zoning:** "Loud" performers must be at least 50ft away from "Quiet" vendors (like bookstores).

## 4. Simulation Results (Mock Data)
* **Total Vendors:** 15 (10 Harlem-Local, 5 External)
* **Locations Managed:** 125th St Metro-North & 125th St Subway (A/B/C/D)
* **Efficiency Gain:** 30% reduction in sidewalk "clump" incidents compared to unmanaged layouts.

## 5. Evaluation & Reflection
**Benefits:** Improves pedestrian safety while guaranteeing economic space for the Harlem community. 
**Limitations:** Requires vendors to have active mobile data; cannot predict emergency street closures perfectly.
**AI Reflection:** AI serves as an "Impartial Referee," removing human bias from space allocation and ensuring that local residents aren't priced out of their own neighborhood's foot traffic.

---
*Created for the Harlem Pedestrian Project - 2026*
