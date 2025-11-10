author: Arie M. Prasetyo
summary: GitHub Copilot Workshop for Github Universe Recap 2025 Jakarta Indonesia
id: github-copilot-workshop-id
categories: AI, Development
environments: Web
status: Published
feedback link: https://example.com/feedback

# GitHub Copilot Workshop


## About the Workshop
Duration: 5

Welcome to the GitHub Copilot Workshop! In this workshop, you will learn how to use GitHub Copilot to explain and improve code.
GitHub Copilot Chat enables interactive dialogue with AI through a chat experience. Let's learn how to use GitHub Copilot through this workshop!

![GitHub Copilot Logo](github-copilot-workshop-id/img/__octocat_copilot.png)

### Today's Goals

- Understand the various features of GitHub Copilot
- Develop a new application using agent mode

### Prerequisites

- Visual Studio Code is installed
- GitHub Copilot license is available
- GitHub account is available



## Project Setup
Duration: 15

This workshop uses the following GitHub repository:

**Project URL**: [https://github.com/arisetyo/2025-github-ur-copilot-workshop](https://github.com/arisetyo/2025-github-ur-copilot-workshop)

### Step 1: Fork the Repository

First, open the project URL above in your browser and fork the repository:

1. Open the project URL in your browser
2. Click the **Fork** button in the top right

![Click Fork button](github-copilot-workshop-id/img/__fork-step1.png)

3. Click the `Create fork button` on the fork creation screen. Once the fork is complete, a copy of the repository will be created in your GitHub account.

### Step 2: Development Environment Setup

Using your forked repository, you can start the project using one of the following methods:

#### Method A: Use "GitHub Codespaces"

1. On your forked repository page from the previous step, click the green **Code** button
3. Select the **Codespaces** tab
4. Click **Create codespace on main**

![Codespaces Setup](github-copilot-workshop-id/img/__github-codespaces.png)

> aside positive
>
> **Tip**: Using Codespaces launches a VS Code-like environment in your browser, allowing you to start development immediately.

#### Method B: Clone to Local Environment

If you have VSCode installed locally:

1. Open Terminal or Command Prompt
2. Clone your forked repository with the following command:

```bash
git clone https://github.com/[your-username]/2025-github-ur-copilot-workshop.git
```

3. Navigate to the cloned directory:

```bash
cd 2025-github-ur-copilot-workshop
```

4. Open the project in VSCode

### Step 3: Workspace Setup

After opening the project, please install the following extensions:

1. Install **GitHub Copilot** extension
2. Install **GitHub Copilot Chat** extension
3. Install **Python** extension



## Configuration Check
Duration: 10

### Branch Preparation

Create and switch to the `feature/pomodoro` branch:

```bash
git checkout -b feature/pomodoro
```

1. Confirm that you are signed in to your GitHub account in VSCode
2. Confirm that Copilot functionality is enabled
3. Confirm that the Python interpreter is set up correctly

### Next Edit Suggestions Setup

⚙️ [`github.copilot.nextEditSuggestions.enabled`](vscode://settings/github.copilot.nextEditSuggestions.enabled) is a setting that enables GitHub Copilot's next-generation edit suggestion feature. This feature allows you to receive more advanced code editing suggestions.

### 1. Open VS Code

### 2. Access Settings
Open the settings screen using one of the following methods:

#### Method A: From Menu
- **Windows/Linux**: `File` → `Preferences` → `Settings`
- **macOS**: `Code` → `Settings...` → `Settings`

#### Method B: Keyboard Shortcut
- **Windows/Linux**: `Ctrl + ,`
- **macOS**: `Cmd + ,`

#### Method C: Command Palette
- `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (macOS)
- Select `Preferences: Open Settings (UI)`

### 3. Search Settings
Enter the following in the settings search box:
```
github.copilot.nextEditSuggestions.enabled
```

### 4. Enable Setting
- Check the checkbox for the setting item shown in search results
- Or change `false` to `true`

### 5. Confirm Setting
Verify the setting is correctly applied:
- Restart VSCode (recommended)
- Edit code in the editor and confirm the new suggestion feature works

### Alternative Method: Direct Edit in settings.json

#### 1. Open settings.json file
- `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (macOS)
- Select `Preferences: Open User Settings (JSON)`

#### 2. Add Setting
```json
{
    "github.copilot.nextEditSuggestions.enabled": true
}
```

#### 3. Save File
- `Ctrl + S` (Windows/Linux) or `Cmd + S` (macOS)

### Important Notes

- Make sure VSCode's GitHub Copilot extension is updated to the latest version
- Restarting VSCode is recommended after setting changes

### Troubleshooting

#### If Settings Are Not Found
1. Confirm GitHub Copilot extension is installed
2. Confirm extension is updated to the latest version
3. Restart VSCode and try again

#### If Functionality Doesn't Work
1. Confirm you are logged in to GitHub Copilot
2. Check internet connection
3. Check VSCode console for error messages


## Creating the Pomodoro app

```
Create a step-by-step implementation plan for the Pomodoro web application and save it to plan.md
```



## [WIP] Documentation

### Create User Flow

```
Create a documentation about how to use this web application. Draw a user flow chart and sequence diagram, use Mermaid format.
```
