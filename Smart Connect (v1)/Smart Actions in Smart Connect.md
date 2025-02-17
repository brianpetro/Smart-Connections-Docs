Smart Actions allow you to define how the AI interacts with your notes by specifying the operations it can perform. They are crucial for managing workflows and customizing AI behavior to suit your specific needs. With Smart Actions, you can leverage both Official GPTs provided by the app and create your own Custom GPTs and utilize Community Actions. This flexibility enables you to integrate with official tools and community-created actions, tailoring the AI's capabilities to enhance your productivity.
## Smart Actions
### Official GPTs
#### Notes GPT
The **Notes** Official GPT is designed for standard note interaction within your Smart Environments. It allows the AI to read, create, and modify notes according to your instructions. This GPT utilizes your configured Smart Environment to access and process your notes, enabling seamless integration between your note-taking workflow and AI assistance.
#### Notes v2 (Experimental) GPT
The **Notes v2 (Experimental)** GPT introduces new features and improvements over the standard Notes GPT. It includes experimental capabilities such as enhanced note retrieval, better integration with Smart Environments, and advanced actions that can be tested and refined.
- **Features:**
    - Improved note editing and creation functionalities.
    - Enhanced understanding of note structures and relationships.
    - Optimized for more complex interactions with your notes.
- **Known Limitations:**
    - As an experimental GPT, it may have bugs or unstable behaviors.
    - Some features may not be fully implemented.
##### Smart Environment Selection
To use the Notes v2 GPT effectively, you need to select the appropriate Smart Environment:
1. Navigate to the **Smart Actions** section in the Smart Connect app.
2. Under **Official GPTs**, find **Notes v2 (Experimental)**.
3. In the GPT settings, locate the **Smart Environment** dropdown.
4. Select the Smart Environment that corresponds to your Obsidian vault or the environment you wish to use for testing.
##### Run Tests for Notes v2
To test the experimental GPT and interpret the results:
1. Open ChatGPT and select the **Notes v2 (Experimental)** GPT.
2. Start by issuing simple commands, such as "Read my open notes" or "Find more notes about [topic]".
3. Observe how the AI interacts with your notes:
    - Check if it retrieves the correct notes.
    - Verify if it opens notes in Obsidian when prompted.
4. Monitor the **Console Log** in the Smart Connect app for any errors or issues.
5. Provide feedback or report any glitches to improve the GPT's performance.
#### Transcribe GPT
The **Transcribe** GPT action is optimized for converting spoken words or audio content into written notes within your Obsidian vault. It focuses on creating and appending content to notes, making it ideal for transcribing lectures, meetings, or voice memos.
To enable or run the Transcribe GPT:
1. In the Smart Connect app, go to **Smart Actions**.
2. Under **Official GPTs**, find **Transcribe GPT**.
3. Configure the **Folder** setting to specify where transcribed notes should be saved (e.g., your **Inbox** folder).
4. Ensure that only the **Create** and **Append** actions are enabled to streamline the transcription process.
5. Use ChatGPT with the Transcribe GPT to begin transcribing audio content into your notes.
## Custom GPTs
### Default GPT Action Group (Deprecated)
**Important Notice**: The **Default** GPT action group is being deprecated and will be removed in future updates. This group previously served as a catch-all for custom GPTs that had not been updated to the new system. It is critical to replace any GPTs relying on the default action group with newly created custom GPTs to ensure continued functionality.
### Custom GPT Creation
Creating and managing Custom GPTs allows you to tailor the AI's capabilities to your specific workflows. Here's how to create a new Custom GPT:
1. In the Smart Connect app, navigate to **Smart Actions**.
2. Click the **New Custom GPT** button.
3. A new entry (e.g., **Custom 1**) will appear in the **Custom GPTs** section.
4. Rename the custom GPT for clarity by clicking on its name and typing a new one (e.g., **Notes Management GPT**).
### **Configuring Custom GPTs**:
#### Alignment File
- **Purpose**: The **Alignment File** provides custom instructions and context to guide the AI's behavior.
- **How to Upload**:
    1. In your custom GPT settings, find the **Alignment File** field.
    2. Click on it and navigate to the file containing your custom instructions.
    3. Select the file to upload it to the GPT configuration.
#### Alignment Text
- **Purpose**: Allows you to input direct alignment text as custom instructions without using a file.
- **How to Input**:
    1. Locate the **Alignment Text** field in your custom GPT settings.
    2. Type or paste your custom instructions directly into the text area.
#### Smart Environment Selection
- **Purpose**: Specifies which Smart Environment the custom GPT will use to access notes.
- **How to Select**:
    1. In the custom GPT settings, find the **Smart Environment** dropdown menu.
    2. Select the appropriate environment that contains the notes you want the GPT to interact with.
#### Show Custom GPT Setup Details
The **Setup Details** section provides necessary information for integrating your custom GPT with ChatGPT.
- **OpenAPI URL**:
    - **Purpose**: Supplies ChatGPT with the definitions of available actions.
    - **How to Use**:
        1. Copy the **OpenAPI URL** provided in the **Setup Details**.
        2. In ChatGPT, access the GPT editor and look for an option to import from a URL.
        3. Paste the OpenAPI URL to import the action definitions.
- **GPT URL Input**:
    - **Purpose**: Enhances the OpenAPI by reducing the amount of text ChatGPT needs to process, minimizing confusion.
    - **How to Use**:
        1. Copy the **GPT URL** from the **Setup Details**.
        2. Paste it into the corresponding field in ChatGPT's GPT editor.
#### Advanced Configuration Options
- **Available Actions**:
    - **Purpose**: Customize which actions the AI can perform, reducing unnecessary options and focusing the AI's capabilities.
    - **How to Add Actions to the Group**:
        1. In the **Advanced Configuration** section, locate the **Available Actions** dropdown.
        2. Click on it and select the specific actions you want to include (e.g., **Create**, **Append**, **Alignment**).
        3. The settings in the upper area will update based on the selected actions.
- **Dependency of Settings on Selected Actions**:
    - Certain settings, such as **Alignment File/Text**, will only appear if the corresponding action (e.g., **Alignment** action) is included.
    - **Tip**: Add all the necessary actions first to ensure all required settings are available for configuration.
### Managing Actions
Managing actions within your custom GPT is crucial for tailoring the AI's behavior.
#### Add Action to Group
- **How to Add Specific Actions**:
    1. In your custom GPT settings, go to the **Advanced Configuration** section.
    2. Under **Available Actions**, click the dropdown menu.
    3. Select the actions you wish to add to the GPT (e.g., **Notes V1 Create**, **Notes V1 Append**).
    4. The GPT will now have access only to these specified actions.
#### Delete Custom GPT
- **How to Delete an Existing Custom GPT**:
    1. In the **Custom GPTs** list, find the GPT you wish to delete.
    2. Click on the **Delete** or **Trash** icon next to it.
    3. Confirm the deletion when prompted.
- **Note**: Deleting a custom GPT will remove its configuration and could disable any workflows or tasks linked to it. Ensure you have migrated or no longer need the GPT before deleting.
#### Run Tests for Custom GPT
- **How to Run Tests**:
    1. After configuring your custom GPT, open ChatGPT.
    2. Select your custom GPT from the list.
    3. Issue commands or prompts that utilize the actions you've configured.
    4. Observe the AI's responses to ensure it behaves as expected.
- **Interpreting the Output**:
    - Verify that the AI is performing the correct actions on the intended notes.
    - Check for any errors or unexpected behavior.
    - Adjust your GPT's configuration as necessary based on the test results.
### Community Actions
- **Finding and Integrating Community Actions**:
    - Community actions are pre-built actions created by other users that you can incorporate into your custom GPTs.
    - **How to Access**:
        1. Visit the community repository or platform where actions are shared.
        2. Browse through the available actions and select ones that suit your needs.
        3. Download or copy the action definitions.
    - **Integrating into Your GPT**:
        1. In your custom GPT's **Advanced Configuration**, use the **Available Actions** dropdown to add the community actions.
        2. Ensure you have any necessary alignment files or settings required by the action.
        3. Test the GPT to confirm the community action works correctly.
## Example Use Cases
### Creating a Custom GPT for Notes Management
**Objective**: Set up a custom GPT that can summarize and categorize notes.
**Steps**:
1. **Create a New Custom GPT**:
    - Navigate to **Smart Actions** and click **New Custom GPT**.
    - Rename it to **Notes Management GPT**.
2. **Configure Alignment Instructions**:
    - In **Alignment Text**, input instructions guiding the AI to summarize and categorize notes.
3. **Select Smart Environment**:
    - Choose the Smart Environment containing the notes you wish to manage.
4. **Add Relevant Actions**:
    - In **Advanced Configuration**, add actions such as **Summarize Note**, **Categorize Note**, **List Categories**.
5. **Set Up OpenAPI and GPT URLs**:
    - Copy the **OpenAPI URL** and **GPT URL** from **Setup Details**.
    - Import them into ChatGPT's GPT editor.
6. **Test the GPT**:
    - Use ChatGPT to issue commands like "Summarize the note titled 'Project Plan'" or "Categorize notes related to 'Marketing'".
    - Verify the AI performs the tasks accurately.
### Adding and Testing Transcription GPT
**Objective**: Set up a transcription GPT for converting audio content into notes.
**Steps**:
1. **Create a New Custom GPT**:
    - Click **New Custom GPT** and rename it to **Transcription GPT**.
2. **Configure Actions**:
    - In **Advanced Configuration**, add **Notes V1 Create** and **Notes V1 Append** actions.
3. **Set Target Folder**:
    - In the GPT settings, specify the **Folder** where transcribed notes will be saved (e.g., **Inbox**).
4. **Input Alignment Instructions**:
    - Use **Alignment Text** to instruct the AI on formatting transcriptions and handling specific scenarios.
5. **Set Up Integration**:
    - Copy the **OpenAPI URL** and **GPT URL** from **Setup Details**.
    - Import them into ChatGPT.
6. **Test the Transcription GPT**:
    - In ChatGPT, input or upload audio content (if supported).
    - Command the AI to transcribe the content into a note.
    - Check Obsidian to ensure the note is created in the specified folder with the correct content.