
## Context selection
- Typing `@` in the chat input opens context selection interface

### File selection
- `enter` inserts selected content as link
	- Includes linked item prior to user message, wrapped as 'context'
	- Keeps link in user input
- `ctrl + enter` / `⌘ + enter` inserts selection as a system prompt
	- Best used like "custom instructions"
- `shift + enter` inserts as embedded link
	- example: `![[path to note.md]]`
	- Replaces link in user input with full text of the linked content

### Images
- requires multi-modal chat model


## Triggering "Lookup" (RAG)
- Self-referential pronouns trigger lookup
- Folder references trigger lookup within the specified folder