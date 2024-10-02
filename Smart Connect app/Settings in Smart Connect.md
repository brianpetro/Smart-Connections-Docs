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

- **Purpose**: The **API Key** functions as a password to secure your custom GPTs. It's required when setting up Custom GPTs and ensures that only authorized users can access and modify your GPT configurations.

- **Usage**:
	- Currently set to a default value.
	- In future updates, this setting will become editable and may be relocated for better accessibility.
	- It's important to keep your API Key confidential to maintain security.

### Prevent Sleep

- **Description**: The **Prevent Sleep** toggle keeps your computer awake, preventing it from entering sleep mode while Smart Connect is running.

- **When to Use**:
	- If you need constant access to your notes via ChatGPT from other devices, such as your cell phone.
	- Useful during long-running tasks or continuous data retrieval.

- **How to Enable**:
	- Go to **Global Settings**.
	- Toggle **Prevent Sleep** to **On**.

- **Benefits**:
	- Ensures that Smart Connect remains active and accessible.
	- Prevents interruptions in AI interactions due to the computer sleeping.

### Auto-Launch

- **Description**: Enabling **Auto-Launch** starts the Smart Connect app automatically when your computer boots.

- **How to Enable**:
	- In **Global Settings**, toggle **Auto-Launch** to **On**.

- **Benefits**:
	- The app is always ready for use without manual intervention.
	- Saves time and ensures continuous availability.

- **Trade-offs**:
	- May slightly increase boot time.
	- Consumes system resources upon startup.

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

### Connecting to Smart Connect with Custom Security Settings

- **Scenario**: You are running your own custom tunnel server and need to disable the default security settings to connect.

- **Steps**:
	1. Navigate to **Settings > Security (Advanced)**.
	2. Toggle **Security** to **Off**.
	3. Configure any additional settings that appear after disabling security.
	4. Ensure your custom server is securely set up to mitigate risks.

- **Important**:
	- Disabling security is only recommended for advanced users.
	- Be aware of the potential security implications.

### Monitoring Token Usage for Performance Optimization

- **Scenario**: You want to optimize the performance of your GPT interactions and manage resource usage.

- **Steps**:
	1. Go to **Settings > Stats**.
	2. Review **Input Tokens** and **Output Tokens** to understand your usage patterns.
	3. Use this information to adjust your interactions or configurations to reduce unnecessary token consumption.

- **Benefits**:
	- Helps in managing any costs associated with token usage.
	- Improves efficiency and responsiveness of the AI.

### Debugging System Issues via Logs and Reset Settings

- **Scenario**: You're experiencing issues with the app and need to troubleshoot.

- **Steps**:
	1. Open the **Console Log** via **Settings > Open Console Log**.
	2. Check for any errors or warnings.
	3. If errors are found, take a screenshot and report them to support.
	4. If issues persist, use **Reset Settings** to restore defaults.
	5. Reconfigure your settings after the reset.

- **Tips**:
	- Always backup important settings or configurations before resetting.
	- Use the **Access Log** to check for any unauthorized access that might be causing issues.