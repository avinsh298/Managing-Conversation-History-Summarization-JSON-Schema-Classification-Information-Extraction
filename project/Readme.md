# Conversation Management & Classification using Groq API

## Overview
This project implements two core tasks using Groq APIs:
1. **Conversation History Management** with intelligent summarization
2. **JSON Schema Classification** for structured information extraction

## Features

### Task 1: Conversation Management
- Maintains conversation history with timestamps
- Periodic summarization (every k-th message)
- Flexible truncation options (by turns/characters)
- Customizable summarization prompts

### Task 2: Information Extraction
- JSON schema definition for 5 fields (name, email, phone, location, age)
- Function calling with Groq API
- Batch processing capability
- Data validation and cleaning

## Installation

```bash
pip install groq python-dotenv