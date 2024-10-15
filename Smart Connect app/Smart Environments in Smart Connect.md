Smart Environments are a core component of the Smart Connect app, designed to provide seamless integration between your local notes and AI-powered processing. By defining which files are accessible and how they are processed, Smart Environments empower users to interact with their data in a more intelligent and personalized manner. Whether you’re managing your knowledge base, syncing content from Obsidian, or excluding specific sections from processing, Smart Environments offer flexible configuration options tailored to your needs.

The goal is to put users in control—enabling personal alignment with AI tools while keeping data secure and local. With features like selective embedding, Obsidian compatibility, and advanced customization options, Smart Environments make it easy to integrate your personal workflows with the power of AI while maintaining privacy and relevance.

##### New Environment

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

##### Delete Environment
- Right-click on the environment and select **Delete** (or click the delete icon if available).
- **Considerations**:
	- Deleting an environment will remove its configuration and associated settings.
	- Embedded data and settings specific to that environment will be lost.
	- This action cannot be undone, so proceed with caution.


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

## Smart Sources settings
See [[Smart Sources settings]] to learn more about settings for sources and blocks.