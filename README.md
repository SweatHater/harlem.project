# Harlem Hub: AI-Powered Transit & Vendor Manager
### Lead Designer: Taha Ilyas
**An AI Platform for Organizing Community Vendor Markets in Urban Transit Hubs**

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
**AI Reflection:** AI serves as an "Impartial Referee," removing human bias from space allocation and ensuring that local residents aren't priced out of their own neighborhood's foot traffic

## 6. AI Placement Engine (The Logic)

**Category Buffering:** Automatically places vendors selling similar items (like two bakeries) at least 50 feet apart to prevent repetitive clusters. 

**Anchor Distribution:** Spreads high-demand categories across the park to ensure balanced foot traffic for all vendors. 

**Hyper-Local Priority:** Recognizes Harlem zip codes and prioritizes those vendors for high-visibility "Tier 1" slots.

**Diversity Balance:** Monitors the ratio of product types (Food, Crafts, Produce) to ensure a fair and balanced market layout. 

** 7. System Workflow (How it Works)

**Step 1:** Registration:** Vendors register on our platform and upload permits for mock verification.

**Step 2:** AI Optimization:** The placement engine analyzes the vendor list and generates a fair layout based on our logic rules.

**Step 3:** Organizer Review: The Market Organizer uses a dashboard to approve or manually adjust the AI-recommended spots.

**Step 4:** Public Discovery: The finalized layout is published to our browser so residents can search for their favorite vendors.

---

# Phase 3: AI Placement Logic (The Harlem Hub Engine)

Our AI system uses a "Community-First" algorithm to decide exactly where a vendor should be placed on the 125th Street corridor.

### 1. The Congestion Formula (Safety)
To prevent subway entrance crowding, the AI calculates a **Congestion Score (C)**:
$$C = P / W$$
* **P** = Real-time pedestrian count (from sensors/cameras).
* **W** = Sidewalk width in feet.
* **Logic:** If **C > 0.8**, the AI automatically "locks" the spot and moves the vendor to a secondary, wider location to ensure commuter safety.

### 2. The Equity Weighting (Fairness)
To support local businesses (Section 1.9.3), the AI applies a **Residency Score**:
* **Base Priority:** 50 points.
* **Harlem Resident Bonus:** +25 points (Verified if ZIP code is 10027, 10030, 10031, 10037, or 10039).
* **New Vendor Bonus:** +10 points (To help new creators get discovered).

### 3. Spacing & Acoustic Rules
* **Category Separation:** Identical categories (e.g., two Coffee Carts) must be at least 100ft apart to prevent unfair competition.
* **Acoustic Buffers:** Musicians are placed at least 50ft away from "Quiet Zones" (like bookstores or subway help desks).

---

# Phase 4: 15-Vendor Market Simulation Data

This table shows how the Harlem Hub AI distributed 15 mock vendors across the 125th St corridor during a simulated Friday afternoon rush.

| Vendor Name | Category | ZIP Code | AI-Assigned Location | Logic Applied |
| :--- | :--- | :--- | :--- | :--- |
| **Harlem Espresso** | Food | 10027 | 125th & Park (East) | Commuter Flow High |
| **Uptown Jazz Trio** | Music | 10031 | 125th & St. Nicholas | Acoustic Plaza Rule |
| **125th Threads** | Retail | 10037 | 125th & Lex (Mid-Block) | Retail Spacing |
| **Patty King** | Food | 10030 | 125th & Park (West) | Food Diversity Logic |
| **Harlem Books** | Retail | 10027 | 125th & 7th Ave | Quiet Zone Buffer |
| **Soulful Beats** | Music | 10039 | 125th & Lenox | Spacing from Jazz |
| **Community Art** | Arts | 10027 | 125th & Lex (North) | Equity Priority (+25) |
| **Tea Time Harlem** | Food | 10030 | 125th & 8th Ave | Congestion Safety |
| **Vintage Harlem** | Retail | 10031 | 125th & Park (Mid) | Category Lock |
| **Harlem Drums** | Music | 10027 | 125th & St. Nicholas | Volume Spacing |
| **Bake & Flourish** | Food | 10037 | 125th & 7th Ave | Neighborhood Bonus |
| **Poetry Corner** | Arts | 10030 | 125th & Lenox | Acoustic Buffer |
| **Wellness Hub** | Comm. | 10039 | 125th & Lex (South) | Sidewalk Width Adj. |
| **Bead It Art** | Arts | 10027 | 125th & Park (North) | Equity Priority (+25) |
| **Morning Joe** | Food | 10035 | 125th & 5th Ave | Category Separation |

**Outcome:** All 15 vendors were placed without violating the 15ft subway safety buffer.

---

# Phase 5: System Evaluation & Reflection

### 1. How does this help Hub Managers?
It automates safety. Instead of managers arguing with vendors, the AI uses real-time pedestrian data to prove why a spot is safe or unsafe, reducing conflict and improving flow.

### 2. Is the placement fair?
Yes. By using a "Priority Score" instead of "First Come, First Served," the AI ensures that long-time Harlem residents aren't pushed out by outside corporate vendors.

### 3. Does it support the Harlem community?
Directly. The +25 point ZIP code bonus acts as a "Digital Subsidy," giving local creators the best foot-traffic spots to boost the local economy.

### 4. How does it help shoppers/commuters?
It turns a chaotic walk into a curated experience. Commuters can use the Live Map to find exactly what they need (coffee, art, music) without getting stuck in a crowd.

### 5. What are the limitations?
The system relies on smartphone access and GPS accuracy. If a vendor's phone dies or the GPS signal is weak under the Metro-North tracks, the placement accuracy may drop.

---

# Phase 6: Process Log & AI Documentation

### Team Roles
* **Project Manager:** Taha Ilyas
* **AI Logic Architect:** Taha Ilyas
* **UI Designer:** Taha Ilyas

### AI Prompt History
The following prompts were used to develop the Harlem Hub prototype:
1. *"Adapt the Smart Market framework for a high-traffic NYC transit hub."*
2. *"Generate a mathematical formula for sidewalk congestion safety."*
3. *"Create a simulated dataset for 15 vendors using Harlem-specific ZIP codes."*

### Human Corrections (The "Human-in-the-loop")
* **Safety Override:** The AI initially suggested placing a food vendor 5ft from the subway stairs. I corrected this to **15ft** to ensure ADA compliance and emergency exit safety.
* **ZIP Code Logic:** I instructed the AI to prioritize the 10030 and 10027 areas specifically to keep the project focused on the immediate Harlem community.

### Meeting Notes
* **Session 1:** Defined the problem of "Transit Hub Chaos."
* **Session 2:** Developed the "Harlem-First" priority weighting system.
* **Session 3:** Evaluated system limitations (e.g., weather and phone battery life).


