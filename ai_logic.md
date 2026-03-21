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
