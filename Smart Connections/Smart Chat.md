---
sync external: ../integration-testing/smart-connections/smart_chat.demo.md
image: assets/screenshots/smart_chat.gif
---
# Smart Chat: Chat Smarter: AI-Powered Conversations in Obsidian
![[assets/screenshots/smart_chat.gif]]
## Purpose / Objective
Ready to chat with your notes? The Smart Chat feature makes interactive, AI-backed conversations a breeze. Trusted by busy researchers who want on-the-fly Q&A without leaving Obsidian.
### User Goal
Learn how to open the Smart Chat pane, configure the chat model, clear chats for fresh conversations, and pull in note links with a single keystroke."
### Logline
Ask your vault anything. Start a new conversation in seconds, refine chat settings, and insert note links directly from an in-chat context selection modal.
### Real-World Use Case
Smart Chat provides an Obsidian interface for AI chat with your notes. Use '@' to insert references to existing notes or include "based on my notes" to trigger AI to find relevant notes before answering your question.

## Workflows
### Demo 1: Configuring the Chat Model
#### Step 1: Open Smart Chat Pane
Run the 'Smart Chat view' command from the Command Palette or use the ribbon icon.
![[assets/screenshots/smart_chat/3.png]]
#### Step 2: Open Settings
Click the "Settings" button (title="Settings") in the top-right of the chat pane.
![[assets/screenshots/smart_chat/4.png]]
#### Step 3: Choose a Model
Select a local or API-based language model, then close the settings overlay.
![[assets/screenshots/smart_chat/5.png]]
![[assets/screenshots/smart_chat/6.png]]

### Demo 2: Basic Response to "Hello."
#### Step 1: Type "Hello."
Type "Hello." into the Smart Chat input field.
![[assets/screenshots/smart_chat/8.png]]

#### Step 2: Submit
Press Ctrl/Cmd+Enter to submit.
![[assets/screenshots/smart_chat/9.png]]

#### Step 3: Observe Response
The AI responds with a greeting or sample text.
![[assets/screenshots/smart_chat/10.png]]

### Demo 3: "New Chat" Button Clears Chat
#### Step 1: Click "New Chat"
In the Smart Chat header, click the "New Chat" button.
![[assets/screenshots/smart_chat/12.png]]

#### Step 2: Confirm Empty History
Observe that the conversation history is cleared.

### Demo 4: '@' Input Triggers Context Selection Modal
#### Step 1: Type '@'
In the chat input, type '@' to open a context selection modal.
![[assets/screenshots/smart_chat/13.png]]
#### Step 2: Observe Context Modal
A modal or dropdown with note suggestions appears.
![[assets/screenshots/smart_chat/14.png]]

### Demo 5: Select Note in Context Modal
#### Step 1: Choose Note
Click on one of the suggested notes in the modal.
![[assets/screenshots/smart_chat/15.png]]

#### Step 2: Confirm Link Inserted
Observe that a link (e.g., `[[NoteTitle]]`) is inserted into the chat input.
![[assets/screenshots/smart_chat/16.png]]


## Expected Results
- Users can configure the chat model quickly.
- 'Hello.' receives a response.
- "New Chat" button resets the conversation.
- Typing '@' triggers a modal; note selection inserts a link in the input.