# Elfa API Skill for Claude

Real-time crypto social data in Claude. Track trending tokens, surface narratives, search mentions, and run market analysis through Elfa's API without leaving the chat.

## What it does

This skill lets Claude tap into [Elfa's](https://elfa.ai) social intelligence platform to:

- Pull trending tokens and contract addresses from Twitter/X and Telegram
- Search social mentions by ticker or keyword
- Get smart follower and engagement stats for any Twitter/X account
- Surface trending narratives and event summaries
- Run AI-powered market analysis, token breakdowns, and account reviews
- Generate ready-to-use integration code (TypeScript, Python, curl)

If you have an API key, Claude makes live calls and returns real data. Without one, it generates correct code snippets you can use in your own app.

## Install

1. Download `elfa-api.skill` from [Releases](../../releases)
2. Open Claude and drag the file into your conversation, or add it via **Settings → Skills**

## Get an API key

Grab a free key (1,000 credits) at **https://go.elfa.ai/claude-skills**

Free tier works with most endpoints. Trending narratives and AI chat require a paid plan — see the link above for details.

## Example prompts

```
Show me the top trending tokens in the last 24 hours
```

```
What are the top mentions for $SOL this week?
```

```
Get smart stats for @elaborateelf on Twitter
```

```
Give me a curl example for the keyword mentions endpoint
```

```
Help me integrate the Elfa trending tokens endpoint in TypeScript
```

## What's inside

```
elfa-api/
├── SKILL.md                        # Main skill instructions
├── scripts/
│   └── elfa_call.sh                # Helper script for live API calls
└── references/
    ├── api-reference.md            # Full endpoint docs
    └── swagger.json                # OpenAPI spec
```

## Links

- [Elfa API docs](https://docs.elfa.ai)
- [Get an API key](https://go.elfa.ai/claude-skills)
