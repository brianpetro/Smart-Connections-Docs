---
title: Overview
---
A plugin for the Obsidian note-taking application that leverages the Smart Environment to enhance note management and discovery.
### Key Features
- **Smart Connections View**: Displays relevant connections between notes using AI embeddings, helping you discover relationships within your data.
- **Smart Chat (Upcoming as Separate Plugin)**: allows conversational interaction with your notes directly within Obsidian.
### Usage
- **Visualization**: Helps visualize and navigate relationships between notes.
- **Read-Only Interaction**: Provides a window into the Smart Environment without editing capabilities.
- **Shared Settings**: Uses the same configuration file as the Smart Connect App for seamless integration.
### Development Notes
- The Smart Chat feature will become its own plugin to specialize functionality.
- Both plugins will share underlying components for efficiency.
### Commands
- `Open view`
- `Find connections`
- `Refresh & Make Connections`: updates embedding before finding connections
- `Random Smart Connection`: opens random note based on connections to current note
### Connections View
- Block & source-level connections
- UI
	- hover-preview: hold `CTRL`/`CMD` + hover with mouse
	- drag/drop: for adding links to notes
### Storage & File Management
- `.smart-env/` is the default data folder
- Embeddings and other file specific data is saved in the `multi/` sub-folder
### Search View
- Enables semantic search based on input
- To open the Search View
	- click the search icon in the top-right corner of the Connections View

