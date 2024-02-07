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

## Development Environment Setup Guide

Welcome to our React Native project! This guide will walk you through setting up your development environment to ensure you have all the necessary tools and dependencies installed. Our project uses Expo for a seamless cross-platform development experience and Yarn as our package manager for its speed and reliability.

### Prerequisites

Before you begin, ensure you have Node.js installed on your machine. Node.js is essential for running the Expo CLI and Yarn.

- **Node.js**: Download and install Node.js from [Node.js official website](https://nodejs.org/).

### Step 1: Install Yarn

After installing Node.js, the next step is to install Yarn. Yarn is a powerful package manager that facilitates efficient management of project dependencies.

- **Windows and macOS**:

  Open a terminal or command prompt and run the following command to install Yarn globally:

  ```bash
  npm install --global yarn
  ```

### Step 2: Install Expo CLI
Expo CLI is a command-line tool that enables you to work with Expo, a framework and platform for universal React applications.

In your terminal or command prompt, run:

  ```bash
  yarn global add expo-cli
  ```

  or if does not works use 
  
  ```bash
  npm install -g expo-cli
  ```

### Step 3: Initialize Your React Native Project
Now, let's start a new React Native project using Expo.

Run the following command and follow the prompts to create a new Expo project:

  ```bash
  expo init YourProjectName
  ```
Replace YourProjectName with the desired name of your project.

###Step 4: Navigate to Your Project Directory

Change into your project directory:

  ```bash
  cd YourProjectName
  ```

### Step 5: Start the Development Server
Launch the Expo development server:

  ```bash
  yarn start
  ```
Or, you can use:
  ```bash
  expo start
  ```

This command will open a new tab in your web browser with the Expo developer tools.

### Step 6: Running Your App

- **On Your Mobile Device**: Download the Expo Go app from the iOS App Store or Google Play Store. Use the Expo Go app to scan the QR code displayed in the Expo developer tools to open your project on your device.

- **iOS Simulator (macOS Only)**: To run your app on an iOS simulator, ensure you have Xcode installed on your macOS device. From the Expo developer tools in the browser, click on "Run on iOS simulator".

- **Android Emulator**: To run your app on an Android emulator, ensure you have Android Studio installed and an emulator set up. From the Expo developer tools in the browser, click on "Run on Android device/emulator".

### Collaborating and Version Control
We use Git for version control. Make sure to regularly commit your changes and push them to our shared repository. Collaborate effectively by using branches for new features and pull requests for merging changes.

### Conclusion
You're now set up to develop with React Native, Expo, and Yarn. This setup ensures a smooth and efficient development process across different operating systems. Happy coding!


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
