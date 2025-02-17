### What are Custom Actions?
Custom Actions empower you to execute local functions with unparalleled ease, bypassing the complexities of server hosting. They allow you to define specific operations that the AI can perform on your local system, enhancing your productivity and enabling customized workflows.

- **Simplified Development:** Execute local functions without the need for server infrastructure.
- **Tailored Functionality:** Create actions that suit your specific needs and workflows.
- **Enhanced Productivity:** Automate tasks and streamline your development process.

### What are Community Actions?
Community Actions are user-contributed actions that can be installed and used within Smart Connect. They are shared through a public repository, allowing users to expand their Smart Connect capabilities by leveraging actions developed by the community.

- **Shared Resources:** Access a variety of actions created by other users.
- **Easy Installation:** Install Community Actions directly from the Smart Connect app.
- **Collaborative Development:** Contribute your own actions for others to use.

### Differences between Custom Actions and Community Actions
- **Custom Actions:** Created by you for your personal use, tailored to your specific needs.
- **Community Actions:** Created by other users and shared publicly, available for anyone to install and use.

### Installing Community Actions
![[sc-app community actions screenshot.png]]
#### Finding Community Actions
1. **Access Community Actions:**
    - In the Smart Connect app, navigate to **Smart Actions**.
    - Expand the **Community Actions** section.
2. **Browse Available Actions:**
    - Review the list of available Community Actions.
    - Each action includes a brief description.

#### Installing a Community Action
1. **Select an Action:**
    - Choose the action you wish to install (e.g., **List Tweets**).
2. **Install the Action:**
    - Click the **Install** button next to the action.
    - A notification may prompt you to restart Smart Connect to activate the action.
3. **Restart Smart Connect:**
    - Click **Restart** when prompted, or manually restart the app.
4. **Verify Installation:**
    - The action will now appear under **Custom Actions** in the Smart Connect app.

#### Example: Installing the "List Tweets" Action
1. **Navigate to Community Actions:**
    - Go to **Smart Actions** > **Community Actions**.
2. **Find "List Tweets":**
    - Locate the **List Tweets** action in the list.
3. **Install:**
    - Click **Install** next to **List Tweets**.
    - Restart the app when prompted.
4. **Action Ready:**
    - The **List Tweets** action is now available for use in your Custom GPTs.

### Using Community Actions in Custom GPTs
1. **Add Action to Custom GPT:**
    - In your Custom GPT settings, under **Available Actions**, add the newly installed action (e.g., **List Tweets**).
2. **Update OpenAPI Schema:**
    - Copy the updated **OpenAPI URL** from your Custom GPT settings.
    - In ChatGPT, import the new schema to include the new action.
3. **Set Up Authentication (if required):**
    - For actions interacting with external platforms (e.g., Twitter), authentication may be needed.
    - In ChatGPT's GPT editor, configure the **Authentication** settings as required.
4. **Use the Action:**
    - In ChatGPT, issue commands that utilize the new action.
    - Example: "List the latest tweets from my Twitter feed."

### Browser Automation with Custom and Community Actions
Custom and Community Actions can interact with web platforms using browser automation. Smart Connect opens a Chromium browser on your desktop to perform these actions.

- **Benefits:**
    - Interact with websites as if you were using a regular browser.
    - Bypass limitations of traditional APIs or when APIs are restricted.
- **Considerations:**
    - **Login Requirements:** You may need to be logged into the platform for the action to work (e.g., Twitter).
    - **Pop-up Windows:** The browser window may appear during the action execution.
    - **Privacy and Security:** Be cautious when automating interactions with personal accounts.

### Managing Community Actions
#### Updating Actions
- Community Actions may receive updates from their creators.
- To update an action, reinstall it from the **Community Actions** section.
#### Removing Actions
- To remove an installed Community Action:
    - Go to **Custom Actions** in the Smart Connect app.
    - Find the action you wish to remove.
    - Click the **Delete** icon next to it.

### Contributing to Community Actions
- **Share Your Actions:**
    - You can contribute your own actions to the community repository.
- **Public Repository:**
    - Visit the [Smart Connect Community Actions Repository](https://github.com/brianpetro/community-actions) to browse, contribute, or download actions.
- **Guidelines:**
    - Follow the contribution guidelines provided in the repository.