Smart Environments are a core component of the Smart Connect app. They define the connection between your computer and the AI, specifying which files are accessible (sources) and how they are processed (actions).

### Creating and Managing Environments

**New Environment**

- **Creating a New Environment**:

	- Open the **Smart Connect** app.
	- If no environments are found, click the **New Environment** button.
	- Click on the **Folder** field to select your Obsidian vault folder.
	- The new environment will appear in the Smart Environments list.

- **Renaming the Environment**:

	- It's recommended to rename the environment to match your vault name for compatibility with Obsidian-specific features.
		- Right-click on the new environment and select **Rename**.
		- Enter the exact name of your Obsidian vault.
		- Press **Enter** to save the new name.

**Delete Environment**

- **Deleting an Environment**:

	- In the **Smart Environments** section, locate the environment you wish to delete.
	- Right-click on the environment and select **Delete** (or click the delete icon if available).
	- **Considerations**:
		- Deleting an environment will remove its configuration and associated settings.
		- Embedded data and settings specific to that environment will be lost.
		- This action cannot be undone, so proceed with caution.

### Environment Configuration Settings

**Name**

- The **Name** field specifies the name of your Smart Environment.
	- **Recommendation**: Set the environment name to match your Obsidian vault name.
		- Ensures compatibility with Obsidian-specific features.
		- Facilitates synchronization between the app and the Obsidian plugin.

**Folder**

- The **Folder** setting defines the directory where your notes are stored.
	- **Selecting a Folder**:
		- Click on the **Folder** field.
		- Navigate to your Obsidian vault directory.
		- Select the folder containing your notes.
	- **Purpose**:
		- Specifies the source of notes for embedding and AI interaction.

**Obsidian Vault Toggle**

- The **Obsidian Vault Toggle** indicates whether the environment is linked with an Obsidian vault.
	- **Activating the Toggle**:
		- Toggle it **On** if you're using Obsidian.
		- May be toggled on by default if the Smart Connections Obsidian plugin is running.
	- **Benefits**:
		- Synchronizes settings between Smart Connect and Obsidian.
		- Shares the same Smart Environment configuration file.
		- Ensures compatibility with Obsidian-specific features.

**File Exclusions**

- **Purpose**: Exclude specific files from being embedded and processed by the AI.
- **How to Set File Exclusions**:
	- In the environment settings, find the **File Exclusions** field.
	- Enter the names or patterns of files to exclude (e.g., `Untitled.md`, `Smart Chats.md`).
- **Usage**:
	- Prevents certain files from being included in embeddings.
	- Useful for excluding temporary files or notes not relevant to AI interactions.

**Folder Exclusions**

- **Purpose**: Exclude entire folders from embedding and AI processing.
- **How to Set Folder Exclusions**:
	- Locate the **Folder Exclusions** field in the environment settings.
	- Enter the names or paths of folders to exclude (e.g., `Templates/`, `Archive/`).
- **Usage**:
	- Excludes all notes within specified folders.
	- Helps manage large vaults by omitting irrelevant sections.

**Excluded Headings**

- **Purpose**: Exclude specific headings or sections within notes from being embedded.
- **How to Set Excluded Headings**:
	- In the environment settings, find the **Excluded Headings** option.
	- Enter the headings or patterns to exclude (e.g., `# Drafts`, `## Personal`).
- **Usage**:
	- Prevents sensitive or irrelevant sections from being processed.
	- Enhances privacy and relevance of AI interactions.

### Smart Sources

**Embedding Model**

- **Description**: The **Embedding Model** determines how your notes are converted into vector representations for AI processing.
- **Selecting a Model**:
	- Choose from available models (e.g., `"TaylorAI/bge-micro-v2"`).
	- Consider factors like model size and performance.
- **Purpose**:
	- Influences the quality and efficiency of AI understanding of your notes.

**Minimum Embedding Length**

- **Description**: Sets the minimum length for a note to be considered for embedding.
- **Setting the Length**:
	- Specify the minimum number of characters or words (e.g., 100 characters).
- **Implications**:
	- Shorter notes below this threshold are excluded from embedding.
	- Optimizes performance by reducing unnecessary processing.

**GPU Batch Size**

- **Description**: Determines the number of embeddings processed simultaneously when using a GPU.
- **Setting the Batch Size**:
	- Enter a numerical value based on your GPU capabilities.
	- Set to `0` to disable GPU processing.
- **Guidance**:
	- Larger batch sizes can improve speed but require more memory.
	- Adjust according to your hardware specifications.

**Legacy Transformers**

- **Description**: Option to use older v2 transformer models instead of the default v3 models.
- **When to Use**:
	- If you experience issues with v3 models.
	- For compatibility with previous setups.
- **How to Enable**:
	- Toggle **Legacy Transformers** to **On**.

**Smart Change (Change Safety)**

- **Description**: The **Smart Change** feature wraps AI-made changes, showing both original and modified versions.
- **Benefits**:
	- Protects against accidental deletions or overwrites.
	- Allows you to review and accept or reject changes.
- **In Obsidian**:
	- Converts into a UI for managing changes within the plugin.
- **How to Enable**:
	- Toggle **Smart Change** to **On**.
- **Recommendation**:
	- Keep enabled to maintain control over AI interactions with your notes.

### Smart Blocks

**Embed Blocks**

- **Description**: Embedding blocks splits notes into smaller chunks (blocks), embedding them individually along with the whole note.
- **How to Activate**:
	- In the **Smart Sources** section, toggle **Embed Blocks** to **On** (default is **On**).
- **Impact on Data Processing**:
	- Enhances AI's ability to retrieve specific content.
	- Increases the number of embeddings, potentially affecting performance.
- **Use Cases**:
	- Recommended for longer notes with headings and bullet points.
	- Not necessary for very short or atomic notes.

### Loading Sources

- **Default Behavior**:
	- Smart Connect does not load all embeddings by default to improve startup speed.
	- Automatically loads sources when ChatGPT requests content.

- **Manual Loading**:

	- **Load Sources**:
		- Click the **Load Sources** button to manually load all embeddings.
		- Useful if you want immediate access to all notes.
	- **Embedding Progress and Stats**:
		- View embedding percentage, number of sources, and load time after loading.

- **Import and Refresh Actions**:

	- **Run Import**:
		- Processes new or updated notes for embedding.
		- Use when you've added significant new content.
	- **Refresh All**:
		- Reprocesses all notes, applying current settings.
		- Use after changing exclusion settings or other configurations.

- **Updating Exclusion Settings**:

	- After changing exclusions, embeddings may show as partially loaded.
	- Click **Refresh All** to reprocess notes with new settings.
	- Monitor the embedding status to ensure completeness.

- **Troubleshooting**:

	- If embeddings aren't updating or sources aren't loading properly:
		- Click **Refresh All**.
		- Use **Run Import** if issues persist.
	- Be aware of potential glitches; updates are ongoing to resolve them.

### Additional Considerations

- **Performance Tips**:

	- **Embed Blocks** increases the number of embeddings; consider disabling if performance is impacted.
	- Adjust **Minimum Embedding Length** to prevent embedding content with less than the minimum length.

- **Synchronization with Obsidian**:

	- Matching the environment name with your vault name ensures seamless integration.
	- Shared configurations enhance functionality between the app and plugin.

- **Feedback and Support**:

	- Report errors or issues to support channels or the GitHub repository.
	- Provide screenshots to assist in troubleshooting.