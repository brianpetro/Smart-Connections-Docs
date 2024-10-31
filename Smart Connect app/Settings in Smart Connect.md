The **Settings** section allows you to configure global preferences, security options, and other important aspects of the Smart Connect app. This includes managing your connection to the Smart Connect Official Service, adjusting security settings, monitoring performance and token usage, and utilizing debugging tools to maintain optimal functionality.
## Security (Advanced)
- **Description**: The **Security** toggle enables or disables HTTPS security features within the Smart Connect app. By default, this setting should be **On** to ensure secure communication when connecting via the Smart Connect Official Service.
- **When to Disable**:
    - If you're running your own tunnel server instead of using the Smart Connect Official Service, you need to turn off the **Security** setting.
    - Disabling security allows the app to connect through your custom server, but it also disables certain security features provided by the official service.
- **Potential Risks and Mitigation**:
    - Disabling HTTPS security can expose your data to potential security risks.
    - Ensure that your custom server is securely configured.
    - Be cautious of unauthorized access when security is disabled.
## Global Settings
### API Key
- **Purpose**: The **API Key** functions as a password to secure your Custom GPTs and Custom Actions. It's required when setting up Custom GPTs and ensures that only authorized users can access and modify your GPT configurations.
- **Usage**:
    - Access your **API Key** in the Smart Connect app under **Settings** > **Global Settings**.
    - Keep your API Key confidential to maintain security.
- **Setting up Authentication**:
    - When configuring Custom GPTs or integrating with external platforms, you may need to provide your API Key in the **Authentication** settings.
    - In the ChatGPT editor, under **Actions** > **Authentication**, select **API Key** and enter your **Bearer** token.
- **Security Considerations**:
    - Do not share your API Key with others.
    - If you suspect your API Key has been compromised, regenerate it if possible.
### Prevent Sleep
- **Description**: The **Prevent Sleep** toggle keeps your computer awake, preventing it from entering sleep mode while Smart Connect is running.
- **When to Use**:
    - If you need constant access to your notes via ChatGPT from other devices, such as your cell phone.
    - Useful during long-running tasks or continuous data retrieval.
- **How to Enable**:
    - Go to **Global Settings**.
    - Toggle **Prevent Sleep** to **On**.
### Auto-Launch
- **Description**: Enabling **Auto-Launch** starts the Smart Connect app automatically when your computer boots.
- **How to Enable**:
    - In **Global Settings**, toggle **Auto-Launch** to **On**.
## Official Service
### Email
- **Purpose**: Enter the email address associated with your Smart Connect account. This email is linked to your official service credentials and is necessary for authentication.
- **How to Enter**:
    - In the **Official Service** section, input your registered email address.
### Connection Key
- **Purpose**: The **Connection Key** links the app to your Smart Connect account, allowing secure communication with the official service.
- **How to Obtain**:
    - Click the **Get Connection Key** button within the app.
    - Follow the instructions sent to your email to retrieve the key.
- **How to Enter**:
    - Enter the **Connection Key** in the designated field in the **Official Service** settings.
- **When to Refresh**:
    - If you experience connection issues.
    - After resetting settings or reinstalling the app.
## Stats
### Input Tokens
- **Definition**: Input tokens represent the amount of data (in tokens) sent to ChatGPT based on requests from your conversations.
- **Usage**:
    - Helps monitor how much information you're sending to the AI.
    - Useful for understanding and managing usage limits or costs.
### Output Tokens
- **Definition**: Output tokens are the tokens representing the context retrieved by ChatGPT from your notes.
- **Usage**:
    - Indicates how much of your note content is being accessed by the AI.
    - Helps track data retrieval and potential exposure of sensitive information.
### Total Tokens
- **Calculation**: Total tokens are the sum of input and output tokens.
- **Purpose**:
    - Provides an overall view of your token usage.
    - Important for tracking resource consumption and optimizing performance.
    - Can help in managing any associated costs with token usage.
## Logs
### Open Access Log
- **Purpose**: The **Access Log** records incoming requests to the Smart Connect app, providing transparency and security oversight.
- **Usage**:
    - Monitor for unauthorized access attempts.
    - Review the origins of requests to ensure they are legitimate.
- **How to View**:
    - Navigate to the **Access Log** section at the bottom of the **Settings** page.
### Open Console Log
- **Purpose**: The **Console Log** is a diagnostic tool that provides detailed technical information for troubleshooting.
- **How to Open**:
    - Click **Open Console Log** within the **Settings** section.
    - A new window will appear displaying log information.
- **Interpreting the Console Log**:
    - Focus on the **Console** tab for relevant information.
    - Look for errors or warnings highlighted in the log.
- **When to Use**:
    - If you encounter issues or unexpected behavior in the app.
    - For reporting errors to support channels.
- **Reporting Errors**:
    - Take a screenshot of any errors found.
    - Report them via GitHub or through the support channels provided.
## Debug
- **Refreshing the App**:
    - After making significant changes (e.g., updating Custom GPTs, installing new actions), it's recommended to refresh the app.
    - **How to Refresh**:
        - Use **Ctrl + R** (Windows/Linux) or **Cmd + R** (Mac) to refresh the Smart Connect app.
        - This ensures that all settings and changes are properly loaded.
### Reset Settings
- **Purpose**: The **Reset Settings** function restores all app settings to their default configurations.
- **When to Use**:
    - If you're experiencing issues due to incompatible or corrupt settings.
    - After significant updates or when troubleshooting major problems.
- **How to Reset**:
    1. Click **Reset Settings** in the **Debug** section.
    2. Confirm the action when prompted.
- **Warning**:
    - All custom configurations will be lost.
    - You will need to reconfigure your settings after the reset.
- **Note**:
    - The **Reset Settings** button is designed to be accessible even if other parts of the app are not functioning properly.
### Show GPU Details
- **Note**: This feature is generally not important for most users and may be removed in future versions.
- **Purpose**: Displays details about your system's GPU.
- **When to Use**:
    - Only if instructed by support staff for troubleshooting performance issues.
- **Recommendation**:
    - Ignore this setting unless specifically advised to use it.
## Example Scenarios and Use Cases
### Setting Up Authentication for Custom Actions
- **Scenario**: You are using Custom Actions that require authentication, such as interacting with external platforms (e.g., Twitter).
- **Steps**:
    1. Obtain your **API Key** from **Settings** > **Global Settings** in the Smart Connect app.
    2. In your Custom GPT configuration, under **Authentication**, select **API Key**.
    3. Enter **Bearer** as the header prefix.
    4. Paste your **API Key** into the designated field.
    5. Save your GPT configuration.
- **Security Reminder**:
    - Keep your API Key secure and do not share it.
### Monitoring Token Usage for Performance Optimization
- **Scenario**: You want to optimize the performance of your GPT interactions and manage resource usage.
- **Steps**:
    1. Go to **Settings > Stats**.
    2. Review **Input Tokens** and **Output Tokens** to understand your usage patterns.
    3. Use this information to adjust your interactions or configurations to reduce unnecessary token consumption.
- **Benefits**:
    - Helps in managing any costs associated with token usage.
    - Improves efficiency and responsiveness of the AI.
### Using the Console Log and Refreshing the App
- **Scenario**: After installing new actions or updating Custom GPTs, you want to ensure all changes are properly loaded.
- **Steps**:
    1. **Open Console Log** to monitor for any errors during operation.
        - Go to **Settings > Open Console Log**.
    2. **Refresh the App** to load changes.
        - Press **Ctrl + R** (Windows/Linux) or **Cmd + R** (Mac) in the Smart Connect app.
    3. **Verify Functionality**:
        - Test your Custom GPTs and actions to confirm they are working as expected.
    4. **Troubleshoot Issues**:
        - If errors occur, refer to the **Console Log** for details.
        - Report issues with relevant screenshots or log excerpts.