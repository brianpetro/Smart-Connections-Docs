**Securely Enhance Your AI Coding Workflow in VS Code**

![](https://github.com/brianpetro/smart-context-vscode/raw/main/assets/smart-context-vscode-menu.png)

In today’s rapidly evolving development world, integrating AI tools like ChatGPT into your workflow is becoming more common. But while these tools offer powerful capabilities, developers often face a major concern: **How do you share your code context without sacrificing privacy and security?**

Enter **Smart Context**, a **100% open-source** VS Code extension designed to make it easier and safer to manage code snippets and project context for use in AI tools—all while keeping your sensitive code **local and secure**.

### The Challenge Developers Face

When working with AI tools, developers often need to share snippets or entire project files as context for better responses. However, there’s a problem: using cloud-based services to copy and share code can expose sensitive information to external servers, especially in large or proprietary projects. Moreover, manual processes of gathering relevant text files across a project are time-consuming and prone to error.

### What is Smart Context?

**Smart Context** solves these issues by providing a **secure, local-first solution** for copying and managing code snippets. This VS Code extension respects your `.gitignore` file, ensuring only the necessary files are copied—without ever sending your code to the cloud.

Whether you’re working on proprietary software, personal projects, or contributing to open-source, Smart Context allows you to safely and easily gather relevant text files into a single, easily sharable format, all while staying completely within your local development environment.

### Key Features of Smart Context

#### **1. 100% Open-Source**

Smart Context is fully open-source under the MIT License, meaning you can **inspect, modify, and contribute** to the codebase. No hidden features, no limitations—just a tool built for the community.

#### **2. Privacy and Security**

Unlike cloud-based alternatives, **Smart Context never uploads your code anywhere**. It works entirely on your machine, so your private or proprietary code stays safe. No external APIs are involved.

#### **3. Respects `.gitignore`**

Smart Context automatically reads and respects your `.gitignore` file, so it will only copy the files you want. This ensures that unnecessary or sensitive files—such as configuration or environment variables—are never included.

#### **4. Supports Multiple File Types**

The extension recognizes a wide range of text-based file formats—everything from `.js`, `.json`, and `.md` to `.py`, `.java`, `.xml`, and more. Whether you’re working in front-end, back-end, or even data science, Smart Context has you covered.

#### **5. Simple and Efficient Workflow**

With Smart Context, there’s **no complex setup**. You can quickly copy folder contents with a simple right-click or a command from the Command Palette, making it a **seamless addition** to your existing workflow.

### How It Works

**Using Smart Context is simple:**

1. **Right-Click Method:**
    - In VS Code’s file explorer, right-click on a folder and select **"Smart Context: Copy Folder Contents to Clipboard"**.
    - Paste the copied contents wherever needed—whether it’s in a ChatGPT window, another code editor, or any document.
    
2. **Command Palette Method:**
    - Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
    - Type **"Smart Context: Copy Folder Contents to Clipboard"**.
    - Select the folder and your contents are instantly copied.

The extension scans the folder for relevant text files (based on a wide range of file extensions), excludes files listed in `.gitignore`, and organizes the content for easy pasting.

### Why Choose Smart Context?

There are many tools out there for sharing code snippets, but **Smart Context** stands out because it offers something critical that many alternatives don’t: **complete privacy**. Unlike cloud-based services that upload your code to external servers, Smart Context ensures your code never leaves your machine.

Here’s why Smart Context is the best choice:

- **Privacy-First Approach**: Your code stays on your local machine. There’s no risk of exposing proprietary or sensitive information to the cloud.
- **Git-Friendly**: The extension respects your `.gitignore` file, ensuring only the files you need are copied.
- **Simple, Seamless Workflow**: No need to install extra tools or services—Smart Context integrates directly into VS Code.
- **Open-Source and Customizable**: You have full control over how it works. Modify and extend the tool to fit your unique workflow.

### Getting Started with Smart Context

#### **Install the Extension from GitHub:**

1. **Download the latest `.vsix` file** from the [Smart Context GitHub Releases](https://github.com/brianpetro/smart-context-vscode/releases).
2. **Install in VS Code** by either dragging the `.vsix` file into the Extensions view or using the **"Install from VSIX..."** option.

#### **Compatibility:**

Smart Context requires VS Code version **1.60.0 or higher**. Once installed, it’s ready to use—no extra configuration needed.

### Join the Community

As an open-source project, Smart Context thrives on community involvement. If you have ideas for improvements or spot issues, feel free to contribute to the project on GitHub. Together, we can make Smart Context even better.

- **Contribute on GitHub**: [Smart Context GitHub Repository](https://github.com/brianpetro/smart-context-vscode)
- **Report Issues or Suggestions**: Submit feedback via the GitHub Issues page.
- **Stay Updated**: Follow the project for upcoming updates, features, and discussions.


### Conclusion

**Smart Context** is a fast, secure, and privacy-focused way to copy code context for AI tools like ChatGPT, all without leaving VS Code. Whether you’re concerned about keeping your proprietary code private or just looking for a smoother way to share project context, Smart Context has you covered.

**Download the extension today**, and experience a better way to manage your code context with complete peace of mind.

---

#### **About the Author**

**🌴 Brian** is the creator of Smart Context for VS Code. He’s passionate about building tools that empower individuals while keeping privacy at the forefront. Follow his updates on Twitter at [@wfhbrian](https://x.com/wfhbrian).

---

Ready to give Smart Context a try? [Download it now from GitHub](https://github.com/brianpetro/smart-context-vscode) and start simplifying your code context management today!