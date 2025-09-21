# Intelligence-Driven Digging System & The Emerald Tablets Arc

## Overview
This document outlines the core gameplay loop of **Project Chimera**, which shifts the focus from mindless digging to a strategic, intelligence-driven excavation process, all in service of the ultimate goal: discovering the lost **Emerald Tablets of Thoth** (`[ARC-THOTH]`).

## Core Philosophy: Dig Smart, Not Hard
The player is a **Field Director**, not a laborer. Every dig is a calculated risk based on data and expert interpretation, pushing towards a profound narrative goal.

---

## Part 1: The Three Pillars of Intelligent Excavation

### 1. Scanning (The "Sensor Sweep")
The player actively uses the drill's systems to gather raw data.

**Mechanics:**
- **Action:** Activate a scan from the drill's UI.
- **Cost:** Significant fuel (e.g., 15% of tank).
- **Output:** A "Sensor Readout" – a messy image of the surrounding area.
- **Upgrades:** Improve clarity, range, and reduce cost.
    - **Sonar:** Identifies large cavities (chambers, tunnels).
    - **GPR (Ground-Penetrating Radar):** Distinguishes material densities (ore vs. rock).
    - **LIDAR:** (Late Game) Creates precise 3D maps.

**Example Sensor Readout (Tier 1 Sonar):**
`[Image: A fuzzy, monochrome image with indistinct blobs.]`

### 2. Interpretation (The "Expert Analysis")
Raw data is useless without an expert. Specialists analyze it.

**The Archaeologist's Role:**
- Provides a hypothesis and a **Confidence Percentage**.
- Skill level affects accuracy and detail.

**Analysis Tiers:**

| Specialist Tier | Analysis Output Example | Confidence |
| :--- | :--- | :--- |
| **1 (Novice)** | "I see a dense object. It could be valuable." | 50% |
| **3 (Competent)** | "The shape suggests a pre-dynastic burial urn." | 75% |
| **5 (Expert)** | "GPR density matches gold funerary masks. Probability: 85%." | 85% |

### 3. Excavation (The "Strategic Dig")
The player makes the final call.

**The Decision Matrix:**
| Intel | Player's Choice | Potential Outcome |
| :--- | :--- | :--- |
| High-Value, High Confidence | **Dig towards it.** | High chance of major reward. |
| High-Value, Low Confidence | **Gamble resources?** | Windfall or waste ("false lead"). |
| Unidentified Hazard | **Avoid or plan.** | Prevents damage; requires upgrades. |

**Risk vs. Reward:**
- **Failed Dig (False Lead):** Lose fuel, gain "Experience Data" for Specialist proficiency.
- **Successful Dig:** Gain resources, artifacts, and story clues (`[CLUE-XXXX]`).

---

## Part 2: Narrative Integration - The Path to the Tablets

The core loop is the **only way** to uncover the story. The Emerald Tablets will not be found by random digging.

### The Ultimate Goal: `[ARC-THOTH]`
- **The Lore:** The tablets are hidden in a **deep, subterranean aquifer**, sealed by geological shifts and protected by ancient mechanisms.
- **The Challenge:** Finding them requires piecing together clues from artifacts, star charts, and hieroglyphs found only through intelligent excavation.

### How the Loop Serves the Narrative:

1.  **Scanning for Clues:** The player must scan specific zones mentioned in decoded hieroglyphs.
2.  **Interpreting History:** The Archaeologist analyzes data to find hidden chambers linked to Thoth.
3.  **Excavating Secrets:** Digging strategically reveals clues (`[CLUE-STAR-CHART]`, `[CLUE-CELESTIAL-KEY]`).

### Specialist Dialogue for the Arc (`[ARC-THOTH]`)

**Archaeologist Pop-Ups:**
- On finding `[CLUE-STAR-CHART-ALPHA]`: *"Driller, this chart maps the constellation of Thoth's Ibis as it was 10,000 years ago. It's a celestial lock for the aquifer's entrance."*
- On scanning a protective mechanism: *"The energy signature is unlike anything natural. This is a warning system... or a test."*

**Engineer Pop-Ups:**
- On encountering the aquifer's defenses: *"Hull integrity failing! The water pressure isn't natural; it's mechanized. We need the Diamond Drill Head to proceed."*

### New Mechanics for the Arc:
- **Environmental Hazard:** `[HAZARD-PRESSURED-WATER-JET]` - Mechanized water jets that damage the drill.
- **New Resource:** `Ancient Alloy Fragments` - Needed to reinforce the drill against the aquifer's defenses.
- **Ultimate Upgrade:** `Sonar Hydrophone` - Navigate the pitch-black, flooded tunnels by sound.

---

## UI/UX Flow Mockup

1.  **Player** hits "Scan". Fuel bar depletes.
2.  **UI** displays a "Sensor Readout" screen with a fuzzy image.
3.  **Pop-up:** "Archaeologist is analyzing the data..."
4.  **Archaeologist's portrait** appears with dialogue and a confidence %.
5.  **UI** highlights the anomaly on the dig map with a pulsing icon.
6.  **Player** decides to dig or ignore.
