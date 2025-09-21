# Drill Vehicle: Design Specifications

## Overview
The drill is the player's primary tool and avatar in the world. Its design must communicate power, progression, and functionality.

## 1. Core Identity
- **In-Game Name:** The "Sand Worm" Mk I
- **Overall Vibe:** Rugged, industrial, but with a touch of advanced tech. Think NASA rover meets construction equipment.

## 2. Visual Design by Tier
Define how the drill looks and changes at each upgrade level.

| Tier | Name | Visual Description | Key Differentiating Feature |
| :--- | :--- | :--- | :--- |
| **1** | Rustbucket | Faded paint, rust spots, small drill bit, exposed wiring. | Basic, barely functional. |
| **2** | Workhorse | Cleaner paint, reinforced chassis, medium drill bit. | Looks reliable. |
| **3** | Depth Runner | Sleek alloy body, larger bit, glowing engine vents. | Looks fast and efficient. |
| **4** | Pharaoh's Bore | Gold and cobalt accents, massive laser-tipped drill, particle effects. | Looks legendary and powerful. |

## 3. Functional Attributes
How each tier affects gameplay.

| Tier | Dig Speed | Fuel Efficiency | Max Depth | Special Ability |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 1x | 1x | 500m | None |
| 2 | 1.5x | 1.2x | 1000m | +5% gold chance |
| 3 | 2.5x | 1.5x | 2000m | Small sonar pulse |
| 4 | 4x | 2x | Unlimited | Immune to lava damage |

## 4. Animation & Feedback
How the drill communicates its state to the player.

- **Idle:** Low hum, slight engine vibration.
- **Drilling:** Intense shaking, shower of rock particles, deep grinding sound.
- **Overheating:** Red glow from vents, warning alarm sound, smoke particles.
- **Upgrade Complete:** Brilliant light flash and a satisfying "CHUNK" sound effect.

## 5. Sound Design
- **Engine:** A low, diesel-like chugging.
- **Drill:** A high-pitched, metallic grinding.
- **Impact:** A deep, crunchy sound when breaking through a hard rock layer.

## 6. Concept Art References
*(Here, you would link to or describe your AI-generated images or mood board for the drill. Since you're using KLING, you can generate these based on your specs above.)*

// Example prompt for AI:
"Concept art for a rugged mining drill vehicle called the 'Sand Worm'. Industrial yellow and steel grey color scheme. Large central rotary drill bit, heavy treads, exposed hydraulic pistons. Should look functional and powerful, sitting in a desert environment near a pyramid."

## 7. Subsystems & Integration

The drill is a complex machine where each component can be independently challenged, damaged, and upgraded. Its functionality is directly supported by the base camp's staff.

### Subsystem Challenges & Upgrades

| Subsystem | Challenge | Upgrade Path | Base Camp Integration |
| :--- | :--- | :--- | :--- |
| **Drill Head** | Wears down on hard rock; can break. | **Material:** Iron → Titanium → Diamond → Plasma | **Engineer** can repair it. **Lab** researches new materials. |
| **Fuel Efficiency** | Consumes more fuel at deeper depths. | **Tank Size:** Small → Large. **Engine:** Standard → Fusion | **Engineer** upgrades efficiency. Fuel must be managed at base. |
| **Hull Integrity** | Damaged by cave-ins, lava, pressure. | **Reinforcement:** Basic → Reinforced → Adamantium | **Engineer** repairs hull. **Lab** researches stronger alloys. |
| **Sonar/Scanner** | Limited range; can be obscured. | **Range:** Short → Long. **Clarity:** Fuzzy → Clear | **Archaeologist** interprets sonar data for clues and secrets. |
| **Depth Rating** | Crushing pressure at extreme depths. | **Pressure Comp:** None → Basic → Advanced | **Lab** researches depth upgrades. Reaching new depths unlocks new story logs. |

### Pop-Up Support System (UI Flow)

The drill's connection to the camp is realized through pop-up events and UI panels.

-   **Archaeologist Pop-up:** "Driller, my analysis of the sonar ping suggests a hidden chamber 10 meters to your left. Suggest diverting course."
    - **Options:** `[Ignore]` or `[Divert Course - 15 Fuel]`

-   **Engineer Pop-up:** "Warning! Hull integrity at 20%. Recommend returning to surface immediately."
    - **Options:** `[Acknowledge]` or `[Ignore - Risk Breakdown]`

-   **Lab Pop-up:** "New research complete. The Diamond Drill Head upgrade is now available for purchase."
    - **Action:** Opens the Upgrade Shop UI directly.