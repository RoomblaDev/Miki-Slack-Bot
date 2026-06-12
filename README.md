# Miki Slack Bot

A very simple Slack slash command bot that replies to several commands such as "/miki-ping", which will tell the current user's exact latency measurement.

## Features

The bot is running 24/7 on the Nest server. Try it in the Slack workspace where it's installed:

- "/miki-help" - Lists available commands for Miki
- "/miki-ping" - Replies with the current user's exact ping (Measure response time between the bot and Slack)
- "/miki-catfact" - Replies with a fact about cats
- "/miki-joke" - Replies with a random joke

## Tech Stack

- Node.js / JavaScript
- Slack Bolt Framework
- Axios (API calls)
- Systemd

- ## Project Structure

- `index.js` - Main bot code with slash commands
- `package.json` - Dependencies
- `.gitignore` - Excludes `node_modules` and `.env`

## Creator

[RoomblaDev](https://github.com/RoomblaDev)
