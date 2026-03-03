# Dental Clinic Booking Bot

## Overview
Telegram chatbot designed to automate appointment booking and patient communication for a dental clinic.

## Core Features
- Appointment booking
- Rescheduling and cancellation
- Automated reminders
- FAQ handling
- Objection handling logic

## Tech Stack
- Telegram Bot API
- OpenAI API
- n8n (workflow automation)
- Google Sheets (used as lightweight database)
- Google Calendar

## System Architecture
The bot processes user messages via Telegram API, determines intent and routes the request through conditional logic blocks.

Booking logic includes:
- Availability check
- Conflict prevention
- Data recording in Google Sheets
- Confirmation message generation

## Engineering Challenges
- Handling multiple user intents
- Preventing duplicate bookings
- Designing structured conversation states
- Managing invalid or incomplete user input

## Result
End-to-end working booking automation with structured conversation logic and data storage.
