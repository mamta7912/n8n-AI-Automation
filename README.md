# n8n-AI-Automation

Demo 1: 
This first AI agent is intentionally simple to understand the logic:
Input from chat → AI thinks → AI rewrites email → Gmail sends email

The workflow:
Chat Trigger
↓
AI Agent
↓
OpenAI Chat Model
↓
Simple Memory
↓
Gmail Tool

The idea: User types rough email instruction in chat. AI Agent understands and rewrites it professionally. Gmail sends the email.

Demo 2: 
Build a Telegram-based AI personal assistant using n8n.
The main goal: Connect Telegram with n8n and build a personal assistant AI agent.
The agent would work from Telegram. Users would type a message in Telegram, and the workflow would run in n8n. The assistant would be able to:
1. Understand the user’s Telegram message
2. Decide whether it is an email task or calendar task
3. Use Gmail tool to send emails
4. Use Google Calendar tool to create meetings/events
5. Reply back to Telegram with a short confirmation
   
The practical use case: A personal assistant bot on Telegram that can send emails and schedule calendar meetings.

User message → Telegram Trigger → AI Agent → LLM + Memory → Tools → Final Telegram Reply

Demo 3: Customer Feedback Agent

The use case:
A customer fills a feedback form for a business. AI analyzes whether the feedback is Positive or Negative. AI prepares a suitable response email.
Gmail sends the response to the customer.

The workflow structure:
Customer submits feedback form
↓
LLM classifies sentiment as Positive/Negative
↓
Merge combines form data + sentiment output
↓
Second LLM creates HTML reply email
↓
Gmail sends reply to customer






