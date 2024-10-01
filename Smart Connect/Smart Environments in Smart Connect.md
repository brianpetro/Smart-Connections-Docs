
## Introduction to Smart Environments

Smart Environments are a core component of the Smart Connect app. They define the connection between your notes and the AI, specifying which notes are accessible and how they are processed. By configuring Smart Environments, you enable seamless interaction between your Obsidian vault and AI-powered features.

## Creating a New Smart Environment

### Entering Your Email and Connection Key
To begin using Smart Environments, you need to enter your email and connection key:
1. Open the **Smart Connect** app.
2. Enter your **Email** and **Connection Key** in the respective fields.
3. Restart the application to apply the changes.

### Adding a New Environment
After restarting, you can add a new Smart Environment:
1. Click on the **Smart Environments** section.
2. Since no environments are found initially, click the **New Environment** button.
3. A prompt will highlight the **Folder** setting.
4. Click on the **Folder** field to select your Obsidian vault folder.
	- Navigate to the location of your Obsidian vault and select it.
5. The new environment will appear in the Smart Environments list.

### Renaming the Environment
For compatibility with Obsidian-specific features, rename the environment to match your vault name:
1. Right-click on the new environment and select **Rename**.
2. Enter the exact name of your Obsidian vault.
3. Press **Enter** to save the new name.

## Smart Environment Settings

### Overview of Settings
When you expand your environment, you'll see various settings:
- **Obsidian Vault Name**: Displays the name of your vault.
- **Folder**: Shows the path to your Obsidian vault.
- **Obsidian Vault Toggle**: Indicates whether the vault integration is active.
	- This may be toggled on by default, especially if you have the Smart Connections Obsidian plugin running.
- **Exclusion Settings**:
	- **Untitled File Exclusion**: Excludes untitled files from processing.
	- **Smart Chats File Exclusion**: Excludes Smart Chats files.
	- These settings are synced from your Obsidian settings for Smart Connections.

## Smart Sources

### Understanding Smart Sources
Smart Sources represent your notes in a format that the AI can process. They include settings that determine how your notes are embedded and used by the AI.

### Embedding Settings
- **Embedding Model**: Choose the model for embedding your notes.
- **Other Settings**: Configure additional options similar to those in the Smart Connections plugin.

### Smart Change
The **Smart Change** feature wraps any changes made by the AI, allowing you to see both the original and modified versions.
- In the Obsidian plugin, this translates into a UI where you can accept or reject changes.
- To enable, toggle **Smart Change** to **On**.

### Block Embeddings
Block embeddings split your notes into smaller chunks (blocks), which are embedded individually alongside the entire note.
- **Benefits**:
	- Improves search granularity.
	- Enhances AI's ability to find relevant content.
- **When to Use**:
	- Recommended if your notes are longer or contain headings and bullet points.
	- Not necessary for very short or atomic notes.
- **Enabling Block Embeddings**:
	- Toggle **Block Embeddings** to **On** (should be on by default).

## Managing Sources

### Loading Sources
By default, Smart Connect doesn't load all embeddings to start up faster. If ChatGPT requests content, it will automatically load the necessary sources.
- **Manual Loading**:
	- Click **Load Sources** to manually load all embeddings.
	- Useful if you want all sources available immediately.

### Embedding Progress and Stats
After loading, you can view:
- **Embedding Percentage**: Shows how much of your content is embedded.
- **Number of Sources**: Indicates total and embedded sources.
- **Load Time**: Displays how long loading took.

### Import and Refresh Actions
- **Run Import**:
	- Processes new or updated notes for embedding.
	- Use when you add significant new content.
- **Refresh All**:
	- Reprocesses all notes, applying current settings.
	- Use after changing exclusion settings or other configurations.

#### Updating Exclusion Settings
If you change exclusion settings:
1. The embedding status may show as partially loaded.
2. Click **Refresh All** to reprocess notes based on new exclusions.
3. Wait for the process to complete to see updated stats.

### Troubleshooting
- If embeddings aren't updating or sources aren't loading properly:
	- Try clicking **Refresh All**.
	- Use **Run Import** if embeddings are incomplete.
- **Note**: Some glitches may occur; these are being addressed in future updates.
