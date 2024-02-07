# SalusAI

## Overview
SalusAI is a business-focused AI wellness platform, offering personalized health management by integrating with devices like Apple Health and Garmin. It features stress and cardio tracking with an AI-guided interactive experience.

- Meeting Notes: https://docs.google.com/document/d/1-pp4yXU-DZxLriyV4eG1oHoitcX_rbXrLYKWKClIofg/edit?usp=sharing

- Member Info (email and contact): https://docs.google.com/spreadsheets/d/1Shu7XimfcrSg2G1KbBRC5W_Lg_PSZ9bOsMth_4S5MI8/edit#gid=0

- Discord Channel for Communication: https://discord.gg/hr4PczbX

- Trello for Planning: https://trello.com/invite/b/KRh8MCHG/ATTIdb4477de0e01d0ab11ae4e0d0869b227547FE4EE/salus

**Regular Meeting time: Saturday 10 am - 11 am**

## Features
- Integration with popular health data platforms like Apple Health and Garmin.
- Personalized fitness and dietary plans based on individual health metrics.
- Advanced analytics for stress and cardio health tracking.
- AI-driven chatbot for interactive user guidance and support.

## Getting Started

To set up your development environment for this project, you will need to have Node.js installed. We recommend using the Long Term Support (LTS) version for better stability and compatibility with our application.

### Step 1: Download Node.js

1. Visit the official Node.js website: [https://nodejs.org/en/](https://nodejs.org/en/)
2. We recommend downloading **Node.js 20.11.0 LTS**, which is labeled as "Recommended For Most Users".
3. Click on the download link for your operating system (Windows, macOS, or Linux) to begin the download.

### Step 2: Install Node.js

After downloading, run the installer and follow the prompts to complete the installation. The installer will guide you through the process, which includes accepting the license agreement, choosing the installation location, and selecting which components to install.

### Step 3: Verify Installation

To ensure Node.js and npm (Node.js package manager) were installed correctly, open a terminal or command prompt and run the following commands:

```bash
node -v
```

### Step 4: Install Yarn

Yarn is a powerful package manager that facilitates the installation of packages and management of project dependencies. To install Yarn globally on your system, open a terminal and run the following command:

```bash
npm install --global yarn
```

Verify the installation by checking the version of Yarn:

```bash
yarn --version
```

This command should return the version of Yarn that was installed.


### Step 5: Setting Up a React Native Project

1. **Initialize a New React Native Project**

To create a new React Native app, run the following command in your terminal:

```bash
npx react-native init YourProjectName
```
Replace YourProjectName with the desired name of your project. This command creates a new directory with all the initial files and configurations needed for a React Native app.

## Code Contribution and Conflict Resolution

Before committing code, ensure there are no conflicts or potential issues. Follow these steps:

1. **Check for Conflicts**: Always pull the latest changes from the base branch and check for conflicts.

2. **Collaboration**: If you encounter problems, reach out to the team in the group chat for a review.

3. **Unresolved Issues**: For problems that remain unsolved, prepare a concise description and bring it up in the next meeting.

**Branch Naming Criteria**: Adhere to the specified branch naming criteria (`feature/`, `bugfix/`, `hotfix/`, etc.) for clarity and consistency in our workflow.

## Branch Management

In SalusAI, we adhere to specific branch management rules to ensure a smooth and efficient workflow:

1. **Feature Branches (`feature/<feature-name>`):** Used for developing new features. Branched from and merged back into `develop`.

2. **Bugfix Branches (`bugfix/<bugfix-description>`):** For bug fixes, usually branched from and merged back into `develop`.

3. **Hotfix Branches (`hotfix/<hotfix-description>`):** For urgent fixes to production, branched from `main` and merged back into both `main` and `develop`.

4. **Release Branches (`release/<release-version>`):** For preparing releases, branched from `develop` and merged into `main` and back into `develop`.

5. **Experiment Branches (`experiment/<experiment-name>`):** For experimental work, not necessarily merged back.

These rules help maintain order and clarity in our version control system.
