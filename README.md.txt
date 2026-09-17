# 🤖 SafeX AI Meeting Scheduler Assistant

## Overview

The SafeX AI Meeting Scheduler Assistant is an AI-powered meeting scheduling prototype developed as part of Week 2.

The assistant uses a real Hugging Face Large Language Model (LLM) together with calendar-style availability logic to understand natural-language meeting requests and suggest available meeting times.

## Features

- Real Hugging Face LLM integration
- Natural-language meeting requests
- Meeting day and time extraction
- Exact time availability checking
- Morning, afternoon, and evening availability
- Alternative time suggestions
- Conversation memory using the last 5 messages
- Mock calendar integration
- Gradio chat interface
- SafeX-branded interface
- Testing with varied scheduling prompts

## Technologies Used

- Python
- Pandas
- Hugging Face Inference API
- Hugging Face Qwen/Qwen2.5-7B-Instruct
- Gradio
- Jupyter Notebook

## Project Structure

```text
AI_Meeting_Scheduler_Assistant/
│
├── data/
│   └── mock_calendar.csv
│
├── notebook/
│   └── Week_2_AI_Meeting_Scheduler.ipynb
│
├── week2_test_results.csv
│
├── README.md
└── requirements.txt