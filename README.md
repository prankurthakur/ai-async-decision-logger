AI Async Decision Logger
Overview

AI Async Decision Logger is an automation system that captures decisions from team discussions and converts them into structured documentation automatically.
It is designed for remote teams that work asynchronously and need clear, searchable records of decisions without manual note-taking.
The system uses AI to extract decisions from conversations and logs them into a structured Notion database.

Problem:
Remote teams make decisions across multiple tools such as Slack, email, and meetings. Important decisions often become difficult to locate later.
This creates problems such as:

• Decisions get lost in long conversations
• Context is difficult to reconstruct
• Documentation becomes inconsistent
• Team members in different time zones miss updates

Solution

This system automatically:

Receives discussion text via webhook or manual input
Uses AI to extract structured decision data
Formats the information into a consistent schema
Logs the decision into a Notion database
This creates a searchable decision history for asynchronous teams.

Workflow Overview
Input (Webhook or Manual Text)
        ↓
AI Decision Extraction
        ↓
Structured JSON Output
        ↓
Notion Database Entry
Decision Structure

Demo Video Link: https://drive.google.com/file/d/1o7b3edgkwnr8NT1v0MHVF475_g6ZEaUU/view?usp=sharing

Each decision is stored with:

• Decision Summary
• Context
• Alternatives Considered
• Final Choice and Rationale
• Owner
• Deadline
• Risks
• Related Discussion

Key Features

• Automatic decision extraction
• Structured decision records
• Searchable decision history
• Async team friendly
• Minimal manual work
• Scalable automation workflow

Tools Used

• n8n – Workflow automation
• OpenAI API – Decision extraction
• Notion API – Structured storage
• Webhooks – Input automation
• JSON – Structured data exchange

Example Input

Example Discussion:
The team debated whether to launch Feature A or Feature B. After discussion the team decided to launch Feature B. Alex will own the implementation and the deadline is March 30.

Example Output

Decision Summary: Feature B selected
Context: Discussion about Feature A vs Feature B
Owner: Alex
Deadline: March 30
Risks: Not fully identified


Ideal Use Cases

This system is useful for:

• Remote startups
• Async teams
• Distributed product teams
• Operations teams
• Documentation-focused companies

Future Improvements

• Slack integration
• Gmail integration
• Discord integration
• Automatic triggering
• Multi-language support for global teams

Screenshots:
Screenshots are included in the repository.

Author:
Prankur Thakur
Remote professional building human-centered AI workflows for asynchronous teams.
Background in communication, teaching, and AI automation.
