---
title: Overview
---
A plugin for the Obsidian note-taking application that leverages the Smart Environment to enhance note management and discovery.

**Purpose**: The Smart Connections project aims to develop a system that enhances users' ability to manage and navigate their personal knowledge bases. By leveraging AI, it suggests relevant connections between notes, enabling users to create smart, meaningful links within their information.

**Vision**: To empower individuals by providing tools that improve communication, productivity, and personal development. The Smart Connections project seeks to make knowledge management more efficient and accessible, unlocking hidden capabilities and helping users achieve their full potential.

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


The Smart Connections project is dedicated to creating an AI-enhanced tool that empowers users by improving how they manage and connect their knowledge. By upholding values like empowerment and accessibility, the project seeks to eliminate communication barriers, reduce inequality, and help individuals realize their full potential through smarter, more connected personal knowledge management.
