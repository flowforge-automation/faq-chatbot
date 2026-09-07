# AI Customer Support Chatbot (FAQ Bot)

## The Problem

Every online store gets the same handful of questions over and over — shipping costs, return policy, payment options, order tracking. Answering them one-by-one by email or live chat eats up support hours that could go toward harder problems, and customers often wait hours for answers that should be instant.

## The Solution

An AI-powered chatbot, built with Zapier's Chatbot builder and powered by Claude, that answers customer questions instantly using a custom knowledge base — with no code required to build or maintain it.

Demonstrated for a fictional e-commerce store ("Ambient Home Goods"), covering:

- Shipping costs and delivery times
- Returns and exchanges policy
- Payment methods
- Order tracking
- Business hours and contact info
- Product care and warranty

## How It Works

1. A knowledge base document (FAQ content) is uploaded to the chatbot
2. The chatbot is given a directive defining its role, tone, and — critically — its boundaries: it only answers questions related to the business, and politely redirects anything off-topic instead of guessing
3. Customers type questions in plain language; the bot always checks the knowledge base before answering, rather than relying on general knowledge
4. If a question falls outside the knowledge base, the bot says so clearly and points the customer to a real contact channel, instead of making something up

## Result

- **Instant answers, 24/7** — no waiting for a human reply to a routine question
- **Accurate by design** — the bot is instructed to always pull from the actual FAQ content, reducing the risk of confidently wrong answers
- **Stays on topic** — off-topic or unrelated questions are declined gracefully, with a clear explanation of what the bot *can* help with, rather than a generic refusal or a made-up answer
- **Fully customizable** — the knowledge base, tone, and escalation message can be updated any time without touching code

## Tech Stack

- Zapier Chatbots (no-code chatbot builder)
- Claude (Anthropic) as the underlying model
- Custom knowledge base (uploaded FAQ document)

## Availability

This same approach adapts to any business with a repeatable set of customer questions — e-commerce stores, service businesses, SaaS products. The knowledge base, personality, and fallback behavior are all tailored to the client's actual policies and tone of voice.

---
*Answering the same five questions all day? Let a bot handle the routine ones so your team can focus on the rest.*
