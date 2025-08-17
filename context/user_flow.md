# GoSpotter – User Flow

This document outlines the **detailed flow of the GoSpotter app**, describing the main screens, their purpose, and how users move between them.  
The goal: families can start a game in under 60 seconds and play entirely offline with minimal setup.

---

## 1. Launch & Home Screen
**Purpose:** Provide a fast entry point to start a game.  

**Elements:**
- **App logo / title**  
- **Primary button:** "Start New Run"  
- **Secondary options:**  
  - "Continue Run" (if an unfinished run exists)  
  - "Explore Spot Packs" (browse available packs)  
  - "About" (show info about the app and author)

---

## 2. Spot Pack Selection
**Purpose:** Choose what kind of things to look for.  

**Flow:**
- User sees a grid/list of available **Spot Packs** (e.g. "Farm Day", "City Walk", "Zoo Adventure").  
- Each Spot Pack shows:  
  - Cover image (large, visual, kid-friendly)  
  - Title (localized)  
  - Short description (e.g. "Perfect for a walk in the city")  
  - Short list of sample things contained in the pack
- Packs can be **tapped** to select multiple.  
- **Action button:** "Start Run" → moves to game.

---

## 4. Active Run Screen
**Purpose:** Central play screen used during spotting.  

**Elements:**
- **Three active spotting targets** (large cards).  
  - Each card shows an image + name.  
  - Targets have rarity/points (common / rare / epic).  
- **Tap & hold → Found!** triggers:  
  - Animated feedback (stars, visual feedback).  
  - Target marked as found, points added.  
  - New target replaces it from the selected packs.  
- **Top bar:** Run timer / score indicator.  
- **Pause button:** returns to options (resume / end Run).
- **Skip button:** Allows to skip the current selection of things to look out for, disabled at first, available after 60 seconds
- **Take photo button:** Opens Camera to take a photo during the run

---

## 5. Pause / Run Menu
**Purpose:** Provide quick controls without breaking immersion.  

**Elements:**
- Resume Run.  
- End Run (confirmation required).  
- Return to Home.

---

## 6. Run Summary
**Purpose:** Show results at the end of a Run.  

**Elements:**
- **Total points earned**  
- **List of found targets** (with rarity & points).  
- **Streaks / highlights** (e.g. "3 rare finds in a row").  
- **Option:** "Add Photos (optional fun feature)"
  - Select from photos taken during the run
- **Buttons:**  
  - "Start New Run"  
  - "Share Run Report"
  - "Back to Home"

---

## 7. Spot Pack Browser (Optional Flow)
Accessible from Home.  

**Purpose:** Explore, preview, and unlock new content.  

**Elements:**
- Show local packs (downloaded to the device)
- Explore available packs (available online, downloadable from backend)
- **Preview view:** shows example items from the pack.  

---

## 8. Settings
**Purpose:** Small, lightweight controls for adults.  

**Elements:**
- Language switch (EN / DE at launch).  
- Parental info (credits, privacy notice).  

---

## 9. About
**Purpose:** Show info about the app and author

Displays a short text about the app itself and the author. Provides some links to get more info.

---

# Flow Summary

1. **Home** → Start New Run
2. **Spot Pack Selection** → Choose packs  
4. **Active Run** → Play  
5. **Pause Menu** → Resume / End  
6. **Run Summary** → Results  
7. Return to **Home** or restart  

---

This flow ensures:  
- **Fast start:** 2 taps from launch to playing.  
- **Kid-friendly navigation:** Big buttons, minimal reading.  
- **Flexibility:** Optional settings for parents, but defaults work instantly.  
