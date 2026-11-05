---
tags:
  - starting_guide
---
# The Organic Project Cycle
Most productivity systems assume a constant, grueling uphill climb. That framework inevitably breaks people.

The Organic Project Cycle treats your work like water moving through a biome. Efforts flow through distinct environmental stages—each with its own explicit rules, constraints, and exit criteria. You don't sprint in the Fen, and you don't brainstorm on the Mountain.

This is the **Fen Release** of the vault. The mechanical infrastructure is locked and functional, but the ecosystem is actively evolving.

# Vault Architecture
- **00_Start_Here:** A read-me note explaining the environmental conceit, the continuous loop, and the mechanics of dragging projects through the Kanban board.
- **01_The_Cycle_Board:** The primary `.base` file grouped by the `biome_stage` property, serving as the central visual dashboard. 
- **02_Active_Projects:** The folder where users generate their specific project notes.
- **03_Templates:** A clean markdown template pre-loaded with the `biome_stage` YAML property, alongside tracking fields for daily energy or emotional environment variables.
- **04_Biome_Definitions:** Reference notes defining the core cycle (Ocean to Delta) and the specific rules for the Tundra and Desert set-asides.
- **05_Ocean_Archive**: Once projects have been released in the [[06_Ocean|Ocean]], move the project files and folders here. 
- **Fen_Resource** - The aquifer and the compost heap. Raw stimuli, attached files, reference materials, and abandoned projects live here to feed future iterations.

# How to Operate the Cycle
## 1. Learn the Biomes
Open `01_The_Cycle_Board`. The column headers are clickable links. Click them to read the coaching manuals for each stage located in the `04_Biome_Definitions` folder. Understand the constraints and traps of a biome before you put a project there.

## 2. Spawn a Project
When a new idea enters your ecosystem, create a new note in the `02_Active_Projects` folder and apply the Master Project Template (from `03_Templates`).

- The template includes diagnostic checklists for every stage. Audit your project's structural health before advancing it.
- By default, a new project's `biome_stage` property should be set to `"[[01_Fen|Fen]]"`.

## 3. Move the Flow
Open `01_The_Cycle_Board`. As your project meets its exit criteria, drag the card to the next biome column. The native Bases view will automatically rewrite the `biome_stage` YAML property inside your markdown file to match the new location.

- If a project is lacking upstream resources, drag it to the **Tundra**.
- If it loses downstream traction, place it in the **Desert**.

## 4. Log Your Wins (AMWAP)
The vault includes an automated As Many Wins As Possible (AMWAP) dashboard. Inside your active project notes, log your daily achievements using the `- [ ] #win` syntax.

When you check the box to complete the task, it automatically populates on your `AMWAP Master Log` note. This gives you a read-only, unified dashboard of all your forward momentum across the entire ecosystem._(Requirement: You must turn off Restricted Mode and enable the **Dataview** community plugin for the AMWAP log to function)._

**Next Step:** Navigate to `01_The_Cycle_Board`, click the Fen header, and review the rules of engagement.

## 5. Capture Ideas and Stimuli
As you move about your days and weeks, capture your ideas and thoughts and resources in the `Fen_Resources` folder.

# Ready to Get Started?
If you are ready to get started but might need a better understanding of how a project moves through the process, go to [[00_Project_Lifecycle]].

Otherwise, create a new file in `02_Active_Projects` and press Ctrl/CMD+P and choose "**Templater: Insert open template modal**" then choose the template "**03_Templates/ProjectTemplate**" and start your first project!