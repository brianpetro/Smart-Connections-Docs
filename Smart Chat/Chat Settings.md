---
title: Settings in Smart Chat
permalink: smart-chat-settings
---
![[smart chat v2 settings - ollama.png]]
## Chat Settings

### Review Context (toggle)
- When toggled "on," it requires the user to click the "Submit" button in [[Context Review]] before the chat model generates a response. This allows reviewing and approving the retrieved context.

### Lookup Limit (number)
- Specifies the maximum number of context items to retrieve in a single lookup. A higher number may increase the detail of the response.

### Send Tool Output in User Message (toggle)
- When toggled "on," tool outputs are included directly in the user's message instead of being sent as a separate "Tool" message.
- This setting may improve response accuracy in some models, particularly lightweight or locally run ones.

---

## Chat Model Settings

### Platform
- Allows selection of the platform for the chat model. Available options:
  - **Anthropic**
  - **Gemini**
  - **Ollama**
  - **OpenAI**
  - **Custom API**

### Model
- Displays the list of available models for the selected platform.
- Click the "Refresh Models" button to update the list and sync available models.

---

### Model-Dependent Settings

#### API Models
- **API Key**: Requires an API key to authenticate and use the external model.

#### Multi-Modal Models
- **Image Resolution**: Configure the resolution for input images, which is critical for multi-modal interactions like image analysis or integration.
