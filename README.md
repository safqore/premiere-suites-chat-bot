# Premiere Suites Chat Bot

This repository contains the n8n workflow for the Premiere Suites Chat Bot.

## Workflow Description

- **Name**: My workflow 3
- **Type**: AI Chat Bot with OpenAI integration
- **Features**:
  - Chat trigger for receiving messages
  - AI Agent with system message constraints
  - OpenAI GPT-5 Nano integration
  - Memory management for conversation context
  - Knowledge base integration

## Files

- `premiere_suites_chat_bot.json` - The main n8n workflow export

## Setup Instructions

1. Import this workflow into your n8n instance
2. Configure the OpenAI API credentials
3. Set up the knowledge base workflow referenced in the execute workflow node

## Backup Information

This repository serves as a backup for the n8n workflow configuration.

## Workflow Components

- **Chat Trigger**: Receives incoming chat messages
- **AI Agent**: Processes messages with system constraints
- **OpenAI Model**: GPT-5 Nano for language processing
- **Memory Buffer**: Maintains conversation context
- **Memory Manager**: Handles chat memory operations
- **Workflow Executor**: Calls knowledge base insertion workflow

## Version Control

This repository tracks changes to the workflow configuration, allowing for:

- Version history and rollback capabilities
- Collaboration with team members
- Backup and recovery of workflow configurations
