# Akaishi Dashboard

![Akaishi Logo](./assets/logo.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [How to Use Akaishi Dashboard](#how-to-use-akaishi-dashboard)
  - [1. Connect Your Wallet](#1-connect-your-wallet)
  - [2. Configure Akaishi Settings](#2-configure-akaishi-settings)
  - [3. View Agent Transactions](#3-view-agent-transactions)
  - [4. Interact with Agent Terminal](#4-interact-with-agent-terminal)
- [Behind the Scenes](#behind-the-scenes)
  - [AI16z Integration](#ai16z-integration)
  - [Trusted Execution Environment (TEE)](#trusted-execution-environment-tee)
- [Security](#security)
- [Support](#support)

## Introduction

Welcome to the **Akaishi Dashboard**—a sophisticated web application that seamlessly integrates blockchain technology with advanced AI capabilities. Designed for users who seek to manage their digital assets, configure AI-driven settings, and interact through a secure terminal, Akaishi provides a unified and secure platform to enhance your blockchain experience.

## Features

- **Wallet Integration:** Easily connect and manage your Solana-based Phantom wallet.
- **Akaishi Settings:** Customize your AI agent with essential parameters.
- **Agent Transactions:** Monitor all transactions related to your agent in real-time.
- **Agent Terminal:** Interact with your AI agent through a secure command-line interface.
- **Real-Time Notifications:** Receive instant feedback with on-screen toast messages.
- **Secure Operations:** Leveraging Trusted Execution Environments (TEE) for data integrity.
- **AI-Powered Insights:** Enhanced functionalities through AI16z technology.

## How to Use Akaishi Dashboard

Follow these steps to get the most out of your Akaishi Dashboard experience.

### 1. Connect Your Wallet

Before accessing the dashboard's features, you need to connect your Phantom wallet.

1. **Open the Dashboard**

   Navigate to [https://akaishi.xyz](https://akaishi.xyz) in your web browser.

2. **Connect Phantom Wallet**

   - Click on the **Connect Wallet** button located in the top-right corner of the navigation bar.
   - A Phantom popup will appear. Approve the connection request.
   - Once connected, the button will display your wallet's short address (e.g., `abcd...wxyz`).
   - To disconnect, simply click the **Connect Wallet** button again.

### 2. Configure Akaishi Settings

Customize your AI agent to align with your preferences and requirements.

1. **Navigate to Settings**

   Click on the **Akaishi Settings** tab in the navigation bar.

2. **Fill Out the Settings Form**

   - **Agent Name:** Enter a unique name for your AI agent.
   - **LLM Model:** Select your preferred Large Language Model (e.g., GPTo1, Claude 3.5 Sonnet, llama-3-1-70b).
   - **API Key:** Input your AI service API key.
   - **Twitter (X) Handle:** (Optional) Provide your Twitter handle for enhanced integrations.

3. **View Connected Wallet Address**

   Below the Twitter handle, your full connected wallet address will be displayed for reference.

4. **Save Settings**

   - Click the **Save Settings** button.
   - A confirmation toast will appear in the lower-right corner stating "Settings saved successfully!".
   - Your settings will also be displayed in the terminal with the API key masked for security.

### 3. View Agent Transactions

Monitor all blockchain transactions associated with your AI agent.

1. **Navigate to Transactions**

   Click on the **Agent Transactions** tab in the navigation bar.

2. **View Transactions**

   - The section will display a list of all transactions, including details like transaction ID, status, amount, and timestamp.
   - If no transactions have been made yet, a message stating "Your Agent has not made any transactions yet." will appear.

### 4. Interact with Agent Terminal

Use the terminal to issue commands and interact with your AI agent.

1. **Access the Terminal**

   Click on the **Agent Terminal** tab in the navigation bar.

   - Upon accessing, a toast notification will appear in the lower-right corner: `"For a list of commands, type 'help'"`.

2. **Use Terminal Commands**

   - **Help Command:** Type `help` and press Enter to view available commands.
   - **Show Settings:** Type `show settings` and press Enter to display your current agent settings (with the API key masked).
   - **Agent Progress:** Type `agent -m` and press Enter to display the agent performing tasks.
   - **Agent Status:** Type `agent status` and press Enter to view the current status of the agent.

   **Example Interaction:**

 @Akaishi2.4~$ help
@Akaishi2.4~ Available Commands:
help => List available commands
show settings => Display current agent settings
agent -m => Show progress of the agent’s current tasks
agent status => Show current status of the agent
@Akaishi2.4~$

- ** Agent Progress:** When typing `agent -m`, the terminal will display a series of progress messages with delays to display real-time operations.

@Akaishi2.4~$ agent -m
@Akaishi2.4~ Agent is processing your request…
@Akaishi2.4~ Step 1: Data Collection - Completed.
@Akaishi2.4~ Step 2: Data Analysis - Completed.
@Akaishi2.4~ Step 3: Generating Insights - Completed.
@Akaishi2.4~ Agent has successfully completed the tasks.
@Akaishi2.4~$

- **Agent Status:** Displays the current status of the agent.

  @Akaishi2.4~$ agent status
@Akaishi2.4~ Agent Status: Active and running smoothly.
@Akaishi2.4~$

- **Unrecognized Commands:** If a user enters a command that isn't recognized, the terminal will respond accordingly.
  
  @Akaishi2.4~$ unknown
@Akaishi2.4~ Command not recognized: unknown
@Akaishi2.4~$

## Behind the Scenes

Discover how Akaishi Dashboard leverages cutting-edge technologies to deliver a secure and intelligent user experience.

### AI16z Integration

Akaishi utilizes **AI16z**, a state-of-the-art AI technology, to power its intelligent agent functionalities. This integration allows Akaishi to:

- **Provide Intelligent Responses:** Generate context-aware and personalized replies based on user inputs.
- **Automate Tasks:** Streamline repetitive tasks and enhance productivity through automation.
- **Enhance User Interactions:** Deliver a more engaging and interactive user experience with advanced AI capabilities.

The AI models process inputs from the terminal and settings to deliver insightful and relevant outputs, ensuring that your AI agent remains both effective and adaptable to your needs.

### Trusted Execution Environment (TEE)

To ensure the highest level of security and data integrity, Akaishi Dashboard employs **Trusted Execution Environments (TEE)**. Here's how TEE enhances Akaishi:

- **Secure Data Processing:** Sensitive information, such as API keys and user settings, is processed within a secure enclave, isolated from the main application environment.
- **Data Privacy:** TEE ensures that your critical data remains confidential and protected against unauthorized access.
- **Integrity Assurance:** By leveraging TEE, Akaishi guarantees that the data processed is untampered and maintains its integrity throughout operations.

This robust security framework ensures that all your interactions and data within Akaishi Dashboard are safeguarded against potential vulnerabilities and threats.

## Security

Akaishi Dashboard is built with security as a top priority. Key security features include:

- **Secure Wallet Connections:** Utilizes Phantom Wallet's secure protocols to manage user authentication and wallet interactions.
- **Data Encryption:** All sensitive data, including API keys and user settings, are encrypted and processed within the TEE to maintain confidentiality and integrity.
- **Input Validation:** Forms and terminal inputs are rigorously validated to prevent injection attacks and ensure data consistency.
- **Regular Security Audits:** The application undergoes continuous security assessments to identify and mitigate potential vulnerabilities.

## Support

If you encounter any issues or have questions about using Akaishi Dashboard, feel free to reach out:

- **Email:** support@akaishi.xyz
- **GitHub Issues:** [Open an Issue](https://github.com/your-username/akaishi-dashboard/issues)


---
© 2025 [Akaishi](https://akaishi.xyz) | All Rights Reserved
