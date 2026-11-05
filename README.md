# Obsidian-NatureFlowProject (Fen Release 0.1)

A cyclical, hydrology-inspired project management framework built natively for Obsidian. 

This is a **Fen Release** of the vault. In the methodology of this framework, the Fen is a nutrient-rich wetland where ideas ferment, prototype, and take shape. As a "Fen" release, this vault's mechanical infrastructure is functional and ready for use, but the aesthetic styling and documentation are actively evolving. 

## The Core Concept

Linear productivity assumes a constant uphill climb. The Organic Project Cycle treats projects like water moving through a biome. Efforts flow through distinct, environmentally-themed stages with explicit entry and exit criteria:

*   **Fen:** Prototyping, brainstorming, and resource gathering.
*   **Forest:** Structuring, constraint-setting, and preparing for deep work.
*   **Mountain:** The sprint. Pure execution. No external inputs.
*   **Field:** Early feedback, soft refinement, and legibility testing.
*   **Delta:** Soft launch and controlled public exposure.
*   **Ocean:** Completion, integration, and release.

**Set-Aside Biomes:**
*   **Tundra:** Upstream holding zone for projects missing resources to scale the Mountain.
*   **Desert:** Downstream parking lot for stalled momentum or burnout.

## Features

*   **Native Kanban Integration:** Uses Obsidian's native Bases (v1.14+) to drive the cycle board. Moving a project card visually updates the file's underlying YAML `biome_stage` property automatically.
*   **Master Project Template:** Includes built-in diagnostic checklists to audit a project's readiness before moving it to the next biome.
*   **Automated AMWAP Tracking:** Uses Dataview to aggregate an "As Many Wins As Possible" log, pulling completed `#win` tags from all active projects into a single, real-time dashboard.

## Externalities in Vault

This vault utilizes these Community Plugins:

* Dataview
* Templater

This vault utilizes this Theme (not a requirement):

* Blue Topaz

## Installation

1. Download the latest release `.zip` from the [Releases](link-to-releases) page, or clone this repository.
2. Open Obsidian and select **Open folder as vault**. Choose the extracted folder.
3. **Crucial Step:** Open Obsidian Settings > Community Plugins. Turn off "Restricted mode" and enable the **Dataview** plugin. 
   *(Note: Dataview is the only third-party dependency required. It powers the AMWAP master log).*

## Vault Structure

*   `00_Start_Here` - The internal introduction and methodology guide.
*   `01_The_Cycle_Board` - The dynamic Kanban interface for active projects.
*   `02_Active_Projects` - The holding folder for in-flight project markdown files.
*   `03_Templates` - Contains the Master Project Template with stage diagnostics.
*   `04_Biome_Definitions` - The asynchronous coaching manual defining the rules and traps of each stage.

## Contributing to the Fen

Because this is a Fen release, feedback on friction points, Dataview query optimization, and native Obsidian CSS styling (specifically for targeting native Bases columns) is highly welcome.
