---
profileName: Smart Connections
postId: 197
postType: post
categories:
  - 18
url: https://smartconnections.app/creating-a-custom-gpt-with-smart-connect/
sc-app-publish: "true"
---
This guide will help you create a custom GPT assistant that interacts with your Obsidian vault using the Smart Connect plugin.

**Preparation:**
1. **Obsidian & Smart Connect:** Ensure you have Obsidian and the Smart Connect plugin installed and set up.
2. **ChatGPT Account:** Creating custom GPTs requires a ChatGPT Plus subscription.

**Creating Your GPT Assistant:**
1. **Access GPTs:** On ChatGPT, navigate to the \"GPTs\" section.
2. **Create New GPT:** Click \"Create\" and give your GPT a name and description (e.g., \"Obsidian Assistant\").
3. **Optional Conversation Starters:** Add example prompts to guide your GPT's understanding of your needs.

**Connecting to Smart Connect:**
1. **Create Actions:** Click the "Create new action" button.
![[GPT - Create new action.png]]
1. **Open API URL:** In Smart Connect settings, locate and copy the \"Open API\" URL.
![[SC App - OpenAPI URL.png]]
1. **Import Actions:** In the ChatGPT Custom GPT editor, click \"Add Actions\" and paste the URL into \"Enter Schema\". Click \"Import\".
![[GPT Add Actions - Import OpenAPI.png]]
1. **Explore Actions:** Review the list of available Smart Connect actions your GPT can perform (create notes, search, append content, etc.).
![[GPT - Actions - Available actions.png]]
1. **Authentication:** In the ChatGPT editor, go to \"Authentication\" and choose \"API Key\" and \"Bearer\".
![[GPT - Add actions - Authentication.png]]
![[GPT - Authentication API Key.png]]
1. **Get API Key:** Find your unique API key in Smart Connect settings (keep it secure!).
![[SC App - Local API Key.png]]
1. **Connect:** Paste the API key into the designated field within the ChatGPT editor.
2. **Save & Test:** Save your Custom GPT configuration and test its functionality. If issues arise, double-check your API key and connection.

**Start Exploring!**

With your custom GPT connected to Obsidian, you can now:

* **Create and manage notes using natural language commands.**
* **Search your vault effortlessly.**
* **Insert and append content to existing notes.**
* **And much more!**

**Remember, the possibilities are endless. Get creative and discover a new way to interact with your knowledge base!** 
