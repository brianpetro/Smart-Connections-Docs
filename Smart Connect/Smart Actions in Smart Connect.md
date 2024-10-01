## Introduction to Smart Actions
Smart Actions define how the AI interacts with your notes, specifying the operations it can perform. They are essential for customizing the AI's behavior to suit your workflow.
There are two types of Smart Actions:
- **Official GPTs**: Pre-configured actions provided by the app.
- **Custom GPTs**: User-defined actions that you can tailor to your needs.

## Official GPTs

### Overview of Available Official GPTs
1. **Note GPT**: Standard GPT for note interaction.
2. **Experimental Notes to GPT**: A version with experimental features.
3. **Transcribed GPT**: Optimized for transcribing content into notes.

### Configuring Official GPTs

#### Alignment File Setting
- **Alignment File**: A file that guides the AI's responses.
	- To set:
		1. Click on **Alignment File**.
		2. Select the file from your system.
- **Alignment Text**: Directly input alignment instructions.
	- Useful if you prefer not to use a file.

#### Folder Settings
For actions like transcribing:
- **Target Folder**: Specify where new notes are saved (e.g., your **Inbox**).
- To update:
	1. Locate the **Folder** setting within the GPT configuration.
	2. Select the desired folder.

## Custom GPTs

### Creating Custom GPTs
To build your own GPT:
1. Click **New Custom GPT**.
2. A new entry (e.g., **Custom 1**) appears.
3. Rename it for clarity if desired.

### Configuring Custom GPTs

#### Alignment File and Text Settings
- Set an **Alignment File** or input **Alignment Text** to guide the AI.

#### Selecting Smart Environment
- Choose which Smart Environment the GPT uses:
	1. Find the **Smart Environment** dropdown.
	2. Select the appropriate environment.

#### Setup Details

##### OpenAPI URL
- **Purpose**: Needed for integrating with ChatGPT.
- **Usage**:
	- Provides ChatGPT with the available actions.
	- Copy the URL and paste it into the GPT editor in ChatGPT.

##### GPT URL Input
- **Purpose**: Enhances the OpenAPI efficiency by reducing unnecessary text.
- **Benefits**:
	- Minimizes AI confusion.
	- Streamlines action definitions.
- **Adding GPT URL**:
	1. Copy the **GPT URL** from **Setup Details**.
	2. Paste it into the appropriate field in ChatGPT.

### Advanced Configuration

#### Available Actions
Limit actions to focus the AI:
- **Default**: All actions are available.
- **Customizing Actions**:
	1. In **Advanced Configuration**, find **Available Actions**.
	2. Use the dropdown to select specific actions.
		- Example: For a transcribing GPT, select only **Create** and **Append** actions.

#### Dependency of Settings on Selected Actions
- Some settings appear only when certain actions are selected.
- **Example**:
	- **Alignment File/Text** options appear when the **Alignment** action is included.
- **Tip**:
	- Adjust actions first to ensure all necessary settings are visible.

## Managing Custom GPTs

### Updating Old Custom GPTs
- Older custom GPTs may default to a generic action.
- It's recommended to recreate them using the new **Custom GPT** feature.

### Removing Default Actions
- The **Default Action** will be deprecated.
- Update your GPTs to use specific actions to maintain functionality.

## Best Practices
- **Limit Available Actions**:
	- Reduces AI confusion.
	- Focuses the AI on intended tasks.
- **Use Alignment Notes**:
	- Provides the AI with context and guidelines.
- **Test Custom GPTs**:
	- Verify that they perform as expected.
	- Adjust configurations as necessary.
