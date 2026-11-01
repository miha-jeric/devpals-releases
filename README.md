# DevPals

DevPals is a Windows desktop workspace for building software with a small AI team. You describe what you want, and a team of agents built on the **Claude Code** and **Codex** CLIs you already have installed and signed in plans the work, implements it, reviews it and verifies it in your project folder.

## Features

- **Chat-centric workflow.** Describe a feature, agree on a plan, and follow the team's progress, tool activity and handoffs in one timeline.
- **Roles.** Planner, Developer and Tester. Each role can use Claude or Codex.
- **Independent review and testing.** Work is reviewed and verified before a feature is marked complete.
- **Parallel mode.** Several features are developed in separate Git worktrees and integrated back into your branch.
- **Changes view.** Shows a diff of everything the team changed, and you can attach files to a request.
- **Project rules and permissions.** You control what agents are allowed to run.
- **Usage overview, export and import** of projects between computers.
- **Languages and themes.** Slovenian and English interface; dark, light and system themes.
- **Automatic updates** from this repository.

## Requirements

- Windows 10/11 x64
- The Claude Code and/or Codex CLI, installed and signed in with your own subscription. DevPals does not use API keys and sends no project data anywhere other than the CLIs you use.

## Install

Download the latest `DevPals-x.y.z-Setup.exe` from [Releases](../../releases) and run it.

The installer is not code-signed yet (beta). If Windows SmartScreen shows a warning, choose **More info → Run anyway**.

Installed copies check this repository for updates and install them when the app is closed.

## Status and license

DevPals is a free beta and is provided without warranty. Terms may change in future versions; see the license agreement shown during installation.

Copyright © Miha Jerič. All rights reserved. The source code is private; this repository only hosts the installers and update metadata.
