# Slack Bot with Node.js 
![image](https://github.com/user-attachments/assets/7461de67-2968-4637-9460-53d3593290a0)


## Introduction

This project demonstrates how to build a Slack bot using the Slack API with Node.js .

## Setup

### 1. Set up the Slack App
- Go to [Slack API](https://api.slack.com/apps) and create a new app.
- Install the app to your Slack workspace.
- Add the following OAuth scopes:
  - `chat:write`
  - `channels:history`
- Enable the **Event Subscriptions** and subscribe to message events.

### 2. Configure Environment Variables
Create a `.env` file in the root directory with the following variables:
