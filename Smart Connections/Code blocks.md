---
sync external: ../integration-testing/smart-connections/code_blocks.demo.md
title: "Live Search in Your Notes: Embedded Smart Connections"
draft: true
---
![[assets/screenshots/code_blocks.gif]]
## Purpose
Show how to use a fenced code block (````smart-connections````) inside Obsidian to render the Smart Connections pane dynamically.
### User Goal
Embed a "live" Smart Connections pane inside a note by using a `smart-connections` code block, then provide a query that updates in real time.
### Logline
Create living search blocks right in your documents—see relevant references instantly, no extra tabs needed!
## Workflow

### Step 1: Open a Note in Edit Mode
Open a note in Obsidian and switch to edit mode.
```
![Step 1 Screenshot Placeholder](path/to/codeblock-step1.png "A note in edit mode.")
```

### Step 2: Insert a Code Fence
Insert a code fence using ```` ```smart-connections ````. For example:
``````md
```smart-connections
```
``````
```
![Step 2 Screenshot Placeholder](path/to/codeblock-step2.png "Typing a code fence in the note.")
```

### Step 3: Parse the Code Block
Move the cursor up (ArrowUp) so that Obsidian parses the code block. Observe the resulting connections pane.
```
![Step 3 Screenshot Placeholder](path/to/codeblock-step3.png "Obsidian recognizes the code block and renders a pane.")
```

### Step 4: Type a Query
Type a query into the code block (e.g., `query: "Similar references test"`).
```
![Step 4 Screenshot Placeholder](path/to/codeblock-step4.png "Typing a query within the code block.")
```

### Step 5: Trigger Re-render
Arrow up again (or toggle out of the block) to trigger re-render. Confirm the block re-renders as a specialized "Lookup" pane.
```
![Step 5 Screenshot Placeholder](path/to/codeblock-step5.png "Lookup pane after re-render.")
```

### Step 6: Observe Semantic Search Results
Observe the code block now shows semantic search results based on the `query:` content.
```
![Step 6 Screenshot Placeholder](path/to/codeblock-step6.png "Results displayed in the embedded pane.")
```
