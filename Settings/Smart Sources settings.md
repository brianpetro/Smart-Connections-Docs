
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



- **Feedback and Support**:

	- Report errors or issues to support channels or the GitHub repository.
	- Provide screenshots to assist in troubleshooting.