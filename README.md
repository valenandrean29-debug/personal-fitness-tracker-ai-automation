# Personal Gym Tracker Bot

An AI-powered Telegram bot that helps track, retrieve, and update personal gym workout data using Google Sheets as the main database.

---

## Features

- Retrieve workout data by:
  - Body type
  - Exercise name
- Automatically update reps & weight
- Add new exercises to the database
- Understand natural language commands
- Integrations:
  - Telegram Bot
  - OpenAI & Google Gemini
  - Google Sheets
  - n8n Automation

---

## How It Works

1. User sends a message to Telegram bot  
2. AI Agent analyzes the command  
3. System determines:
   - Fetch data
   - Update data
   - Add new exercise  
4. Data is processed in Google Sheets  
5. Bot sends a professional response

---

## Tech Stack

- n8n Workflow Automation
- Telegram Bot API
- OpenAI GPT
- Google Gemini
- Google Sheets API

---

## Database Structure (Google Sheets)

| Column Name     | Description              |
|-----------------|--------------------------|
| body type       | Target muscle group      |
| exercise name   | Name of the exercise     |
| reps pertama    | Number of repetitions   |
| weight          | Weight used             |

---

##  Example Commands
"give me a weight and repetition data of incline dumnbell press"
"update a weight of incline dumbell press to 50 kg and 8 repetition"
"add new exercise called jm press"

## How to use the .json
-log in to n8n, or any workflow automation platform
-import the json file into n8n
-setting the credential and api key
