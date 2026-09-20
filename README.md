# minor-_project_1
# GroupDNA — WhatsApp Group Analytics

> **Your WhatsApp Group, Decoded.** 📊

GroupDNA is a Python-based WhatsApp group analytics project that converts a WhatsApp chat export into meaningful insights about group activity, communication patterns, and participant behavior.

The project was developed as a minor project to apply core Python programming and data analysis concepts to a real-world, unstructured dataset.

---

## 🚀 Project Overview

WhatsApp conversations contain a lot of information about how a group communicates, but the raw exported chat is difficult to analyze directly.

GroupDNA processes the exported chat and extracts structured information such as:

- Group activity and participation
- Most active days and hours
- Activity patterns using a NumPy-based heatmap
- Frequently used words
- Response-time patterns
- Silent streaks
- Participant activity patterns
- Personality-based communication archetypes
- A consolidated final report

The project also handles common WhatsApp export edge cases such as media messages, deleted messages, system messages, and multiline messages.

---

## ✨ Features

### 1. Chat Parser
Parses the exported WhatsApp `.txt` file and extracts:

- Timestamp
- Sender
- Message content
- Media messages
- Deleted messages

It also supports multiline messages and separates system messages from user messages.

### 2. Group Overview

Provides an overview of the conversation including:

- Total messages
- Number of active participants
- First and last message
- Number of active days
- Messages per participant
- Media and deleted-message statistics

### 3. Most Active Day & Hour

Identifies the days and hours when the group was most active.

### 4. Activity Heatmap

Uses **NumPy** to construct an activity matrix showing message frequency across hours of the day for participants.

### 5. Top Words

Analyzes message text and identifies frequently used words while filtering common stop words and irrelevant tokens.

### 6. Response Speed & Silent Streaks

Analyzes communication patterns by calculating:

- Response-time patterns
- Fastest and slowest average responses
- Periods of inactivity
- Longest silent streaks

### 7. Personality Archetypes

Participants are assigned communication archetypes based on observable chat behavior.

The project includes archetypes such as:

- **Spammer**
- **Group Mom**
- **Night Owl**
- **Storyteller**
- **Drama Queen**
- **Ghost**

These classifications are based on activity patterns within the dataset and are intended as an analytical feature rather than psychological profiling.

### 8. Final Report

Generates a consolidated report containing the major insights extracted from the chat.

---

## 🛠️ Technologies & Concepts Used

### Programming
- Python

### Libraries
- NumPy

### Core Concepts
- Lists
- Dictionaries
- Sets
- Tuples
- Loops
- Conditional statements
- Functions
- String manipulation
- File handling
- Date and time processing
- Basic data analysis


