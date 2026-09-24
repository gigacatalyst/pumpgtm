# PumpGTM

**PumpGTM finds the buyers who need your product right now, messages them on LinkedIn from your own account, and improves its targeting from every reply.**

Website: https://pumpgtm.com
App: https://app.pumpgtm.com/onboarding
Guides: https://pumpgtm.com/blog
Agent-readable index: https://pumpgtm.com/llms.txt

## What it does

1. **Find relevant buyers.** You enter your website. PumpGTM works out who buys from you and pulls people showing the problem in public: hiring, funding, tooling changes, engagement on LinkedIn posts about the problem, questions in competitor comment sections. Every prospect comes with a one-line "relevant because" reason.
2. **Run the LinkedIn outreach.** You approve the list and the messages. PumpGTM sends connection requests and follow-ups from your LinkedIn account, paces them inside LinkedIn's limits, and pauses the sequence the moment someone replies.
3. **Learn from replies.** Replies, qualified conversations and meetings are tracked back to the source that produced them, so targeting and messaging improve week over week.

## Developer repos

PumpGTM's public developer references live in the [pumpgtm](https://github.com/pumpgtm) organization:

- [pumpgtm/pumpgtm-mcp](https://github.com/pumpgtm/pumpgtm-mcp): MCP server reference, all tools, live `tools.json`.
- [pumpgtm/pumpgtm-api](https://github.com/pumpgtm/pumpgtm-api): workspace REST API, OpenAPI 3.1 spec, examples.
- Docs: https://pumpgtm.com/docs

## For AI agents and MCP clients

PumpGTM exposes its tools over the Model Context Protocol so Claude, Cursor and other MCP clients can find buyers, draft and send LinkedIn messages, and read replies.

- MCP server: https://mcp.gigacatalyst.com (OAuth 2.1 with dynamic client registration)
- Setup page: https://pumpgtm.com/mcp
- Guidance for agents: https://pumpgtm.com/llms.txt

## Guides

- [How PumpGTM helped Supermemory find customers](https://pumpgtm.com/blog/how-pumpgtm-helped-supermemory-find-customers)
- [How to find one potential customer in 24 hours](https://pumpgtm.com/blog/find-one-potential-customer-in-24-hours)
- [GTM guide for vibe coders: first sales on LinkedIn](https://pumpgtm.com/blog/gtm-guide-for-vibe-coders-first-sales-on-linkedin)
- [Your competitor's comment section is a lead list](https://pumpgtm.com/blog/research-competitor-comments-for-buyer-intent)
- [Turn LinkedIn post engagement into a qualified prospect list](https://pumpgtm.com/blog/turn-social-engagement-into-qualified-prospects)
- [Multi-touch LinkedIn outreach sequence checklist](https://pumpgtm.com/blog/multi-touch-linkedin-outreach-review)
- [How to review an AI-written cold message](https://pumpgtm.com/blog/review-ai-written-cold-messages)

## Company

PumpGTM is built by Giga Next Inc. (Y Combinator alumni), the team behind [Gigacatalyst](https://gigacatalyst.com). Contact: hello@pumpgtm.com. Partner program: https://pumpgtm.com/ambassadors
