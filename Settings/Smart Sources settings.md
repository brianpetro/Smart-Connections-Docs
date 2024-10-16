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

### Loading and Managing Sources

Smart Connect provides several buttons to manage your sources efficiently:

- **Load & Re-load Sources**:
  - **Purpose**: Loads all embeddings manually.
  - **When to use**: 
    - On initial setup or when you want immediate access to all notes.
    - If embeddings are not currently loaded.
  - **Behavior**: 
    - Changes to "Re-load Sources" after initial load.
    - Displays embedding progress and stats after loading.

- **Import**:
  - **Purpose**: Processes new or updated notes for embedding.
  - **When to use**: 
    - After adding significant new content.
    - When metadata of existing items has changed.
  - **Behavior**: 
    - Only queues items with changed metadata for import.
    - Efficient for updating specific changes without reprocessing everything.

- **Prune**:
  - **Purpose**: Removes outdated or invalid items from the collection.
  - **When to use**: 
    - Periodically to clean up the database.
    - If you've deleted files from your vault.
  - **Behavior**: 
    - Deletes items that no longer have a corresponding source file.
    - Helps maintain a clean and efficient database.

- **Clear All & Re-import**:
  - **Purpose**: Performs a complete reset and reimport of all data.
  - **When to use**: 
    - As a troubleshooting step if you're experiencing persistent issues.
    - After making significant changes to your vault structure or settings.
  - **Behavior**: 
    - Clears all existing data.
    - Reinitializes the file system.
    - Queues all items for import and embedding.
    - Use with caution as it's a time-consuming operation.

### Additional Considerations

- **Performance Tips**:

	- **Embed Blocks** increases the number of embeddings; consider disabling if performance is impacted.
	- Adjust **Minimum Embedding Length** to prevent embedding content with less than the minimum length.


- **Troubleshooting**:
  - If embeddings aren't updating properly, try "Import" first.
  - If issues persist, use "Prune" followed by "Import".
  - As a last resort, use "Clear All & Re-import".

- **Feedback and Support**:
  - Report any errors or unexpected behavior when using these functions.
  - Provide detailed information about your setup and the steps that led to the issue.

Remember, these operations can be resource-intensive, especially for large vaults. It's recommended to perform major operations like "Clear All & Re-import" when you have time to let the process complete without interruption.
