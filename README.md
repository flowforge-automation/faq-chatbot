# AI Customer Support Chatbot (FAQ Bot)

A no-code AI chatbot that answers customer FAQs instantly, built with Zapier Chatbots and powered by Claude. Demonstrated for a fictional e-commerce store, "Ambient Home Goods."

## What it does

- Answers customer questions about shipping, returns, payments, order tracking, business hours, product care, and warranty
- Always checks its knowledge base before answering — doesn't guess or rely on general knowledge
- Politely declines off-topic questions instead of making something up, and explains what it *can* help with
- Fully configurable tone, knowledge base, and fallback message — no code required

See [`case-study-chatbot.md`](./case-study-chatbot.md) for the full write-up.

## Files in this repo

- `ambient-home-goods-faq.pdf` — the knowledge base document used to train the bot
- `screenshots/` — chatbot in action, AI model configuration, and knowledge source setup

## How it works

1. Upload a knowledge base document (FAQ content) to the chatbot
2. Configure a directive: role, tone, and — importantly — instructions to only answer in-scope questions and always defer to the knowledge base
3. Select the AI model (Claude, via Anthropic)
4. Set the fallback behavior for out-of-scope questions (custom message, rather than a generated guess)

## Tech Stack

- Zapier Chatbots (no-code chatbot builder)
- Claude (Anthropic)

## Notes

- No API keys or credentials are stored in this repository
- The knowledge base, personality, and business details are fully customizable per client

## License

MIT (or update as needed)
