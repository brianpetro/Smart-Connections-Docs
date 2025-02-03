---
sync external: ../integration-testing/smart-connections/connections_pane_filters.demo.md
image: assets/screenshots/connections_pane_filters.gif
---
# Refine Your View: Pinpoint Precision: Filtering Inbound & Outbound Links
![[assets/screenshots/connections_pane_filters.gif]]
## Purpose / Objective
Feeling overwhelmed by too many cross-links? Hone in on the exact notes you need. Used to better manage massive vaults—gain laser-focused clarity in seconds.

### User Goal
Learn how toggling outlink/inlink filters affects which notes appear, giving you total control over your vault's relationships.

### Logline
Advanced usage for power-users: Filter out entire categories of links and see only your most relevant connections.

### Real-World Use Case
Researchers organizing large vaults might hide outbound links (outlinks) or inbound links (inlinks) to see only notes which may be otherwise overlooked.

## Workflows
### Demo 1: Create 'SimilarIdea.md' Referencing 'SecondNote'

#### Step 1: Create/Open 'SimilarIdea.md'
Open or create a new note named "SimilarIdea.md."
#### Step 2: Reference 'SecondNote'
Add text referencing "SecondNote," e.g., "This is a note about my identity referencing SecondNote."
![[assets/screenshots/connections_pane_filters/4.png]]
#### Step 3: Refresh Connections
Click the "Refresh" button in the Connections pane to force link regeneration.

#### Step 4: Verify 'SecondNote'
Check that "SecondNote" now appears as a relevant connection.
![[assets/screenshots/connections_pane_filters/5.png]]

### Demo 2: Exclude Outlinks

#### Step 1: Confirm Newly Linked Note is Visible
Confirm that the note you just linked to is present in the Connections list.
![[assets/screenshots/connections_pane_filters/6.png]]
#### Step 2: Open Filter Menu
Click the "Filter" button in the Connections pane top bar.
![[assets/screenshots/connections_pane_filters/7.png]]

#### Step 3: Toggle 'Exclude Outlinks'
Check the "Exclude Outlinks" option.
![[assets/screenshots/connections_pane_filters/8.png]]
#### Step 4: Refresh
Click "Refresh" to apply the updated filter.
![[assets/screenshots/connections_pane_filters/9.png]]

#### Step 5: Confirm Note Disappears
Verify that the newly-linked note no longer appears in the list.
![[assets/screenshots/connections_pane_filters/10.png]]

#### Step 6: Open the Newly Linked Note Manually
Open that newly-linked note (e.g., "SecondNote.md"), and observe that its own Connections pane still shows the original note as an inlink.
![[assets/screenshots/connections_pane_filters/12.png]]

### Demo 3: Toggle Exclude Inlinks

#### Step 1: Reopen the Filter Menu
From the newly-linked note, reopen the filter menu.
![[assets/screenshots/connections_pane_filters/13.png]]
![[assets/screenshots/connections_pane_filters/14.png]]


#### Step 2: Toggle 'Exclude Inlinks'
Enable or check the "Exclude Inlinks" option.
![[assets/screenshots/connections_pane_filters/15.png]]
#### Step 3: Refresh
Click "Refresh" again to apply the changes.
![[assets/screenshots/connections_pane_filters/16.png]]

#### Step 4: Confirm Original Note is Excluded
Verify that the original note (e.g., "SimilarIdea.md") is now absent from the connections list.
![[assets/screenshots/connections_pane_filters/17.png]]
