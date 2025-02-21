# VSCode Profile

[![Visual Studio Code Version](https://img.shields.io/badge/VSCode-1.97%2B-brightgreen.svg)](https://code.visualstudio.com/)

Welcome to the VSCode Profile! This repository provides a streamlined Visual Studio Code configuration with custom settings, keybindings, and snippets to enhance your coding experience.

---

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)

---

## Overview

This profile is designed for developers who want a quick and efficient setup of their VSCode environment. It works seamlessly on Windows, macOS, and Linux, providing optimized settings for a smooth development experience.

---

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/vscode-profile.git
   cd vscode-profile
   ```

2. **Backup Your Current Settings (Optional):**

   ```bash
   # Linux/macOS
   cp -r ~/.config/Code/User ~/vscode-settings-backup

   # Windows (PowerShell)
   Copy-Item "$env:APPDATA\Code\User" -Destination "$env:USERPROFILE\vscode-settings-backup" -Recurse
   ```

3. **Copy the Configuration Files:**

   ```bash
   # Linux/macOS
   cp settings.json keybindings.json -r snippets/ ~/.config/Code/User/

   # Windows (Command Prompt)
   copy settings.json keybindings.json %APPDATA%\Code\User\
   xcopy snippets %APPDATA%\Code\User\snippets\ /E /I
   ```

4. **Install Recommended Extensions:**

   Use the VSCode Extensions sidebar to install the recommended extensions for an optimal experience.

5. **Restart VSCode:**

   Restart VSCode to load the new settings and configurations.

---

## Usage

Once installed, launch VSCode and enjoy your updated environment featuring custom settings, keybindings, and snippets. Customize further as needed to fit your workflow.

---

## Troubleshooting

- **Settings Not Loading:** Ensure that the configuration files are in the correct VSCode directory.
- **Missing Keybindings or Snippets:** Verify that the `keybindings.json` file and `snippets/` folder are correctly placed.
- **Extension Conflicts:** Disable any conflicting extensions if necessary.

For additional help, refer to the [VSCode Documentation](https://code.visualstudio.com/docs).

---

Enjoy your optimized VSCode setup!
