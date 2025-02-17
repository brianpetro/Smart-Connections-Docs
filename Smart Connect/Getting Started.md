---
sync external: ../integration-testing/smart-connect/getting_started.demo.md
image: assets/screenshots/getting_started.gif
---
# Getting Started with Smart Connect
![[assets/screenshots/smart-connect-getting_started.gif]]

## Purpose / Objective

### Real-World Use Case
You have a local environment and a cloud-based environment, both storing related notes or references, and you want to see them side by side with minimal friction.

---

## Workflows

### Demo 1: Install/Enable Smart Connect

#### Step 1: Check Setup
Make sure your system can run Smart Connect (a valid connection key, or supporter key, is required). If you're already a Smart Connections supporter, the same supporter key can be used during the sign-in process (expires 90 days after joining the supporter program).

#### Step 2: Launch
Open the Smart Connect desktop app. The main screen should indicate that no environments exist yet and prompt you to sign in.

#### Step 3: Connection Key
Enter your email and connection key in the login prompt. Press 'Login' to proceed.

Below is a screenshot showing the login prompt with the email and connection key fields:

![[assets/screenshots/smart-connect-getting_started/1.png]]

#### Step 4: Wait for Status
Look for the main dashboard. A 'Connected' or 'Ready' status indicates the environment is active.

Here is a screenshot of the main dashboard after you have successfully logged in:

![[assets/screenshots/smart-connect-getting_started/2.png]]

### Demo 2: Create a New Environment

#### Step 1: Click "New Environment"
On the Smart Connect main screen, click 'New Environment.' Provide a nickname (for example, 'Local Env').

The screenshot below displays the 'New Environment' dialog and the nickname field:

![[assets/screenshots/smart-connect-getting_started/3.png]]

#### Step 2: Select Folder or Path
Point to the location of your local notes or a shared network folder. Once set, confirm.

Below is a screenshot showing the folder selection step:

![[assets/screenshots/smart-connect-getting_started/4.png]]

#### Step 3: Refresh & Observe
Smart Connect processes the new environment. A short notice 'Embedding complete' or 'Sync complete' may appear.

### Demo 3: Connect Another Environment

#### Step 1: Add Another Environment
Repeat the steps to add a second environment (for example, 'Cloud Env').

#### Step 2: Verify Multi-Env Connections
Confirm that both 'Local Env' and 'Cloud Env' appear under the 'Environments' list, each with its own connection key or status.

This screenshot shows multiple environments in the list:

![[assets/screenshots/smart-connect-getting_started/5.png]]

### Demo 4: Open a Note

#### Step 1: Select an Environment
Click on 'Local Env' from the environment list.

#### Step 2: Open Any Note
Choose any note to open. Confirm that a new window or pane launches. The note's content should be fully editable.

The following screenshots show the environment details and note-opening sequence:

![[assets/screenshots/smart-connect-getting_started/6.png]]

Below, the next screen indicates the location of the connection key:

![[assets/screenshots/smart-connect-getting_started/7.png]]

Here, you can see the note's folder and the option to 'Browse':

![[assets/screenshots/smart-connect-getting_started/8.png]]

Finally, the environment can start and show a connected status:

![[assets/screenshots/smart-connect-getting_started/9.png]]

#### Step 3: Observe Real-Time Sync
Any changes made in that note can appear in the other environment's note listing if relevant.

### Demo 5: Troubleshooting

#### Step 1: Check Logs
If something isn't syncing, open the 'Logs' tab or console. Look for error messages like 'Key invalid' or 'Permission denied.'

#### Step 2: Re-Auth or Reconnect
Re-enter your license key, or click 'Refresh' to re-scan your environment.

---

## Expected Results
- You have Smart Connect installed, licensed, and showing at least one environment connected.
- Opening and editing notes in one environment can reflect in the consolidated environment listing.
- Additional environments can be added quickly, with 'Embedding complete' notifications confirming readiness.
