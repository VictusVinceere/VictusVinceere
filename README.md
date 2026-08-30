# Aziz Riskulov

**Full Stack AI Engineer** · Voice agents · Retrieval · Evals and guardrails

Most AI demos never survive contact with real users. I build the ones that do:
systems wired into the CRM, ERP and document stores a business already runs,
deployed and measured rather than demonstrated once and abandoned.

Six years full stack, three of them building with language models.

## Projects

**[ai-voice-agents-crm-erp](https://github.com/VictusVinceere/ai-voice-agents-crm-erp)** — [demo](https://youtu.be/obWUc-foFNU)
A phone agent that identifies the caller, answers stock and order questions
from live ERP data, books appointments, and writes contacts, deals and call
summaries back into HubSpot. LiveKit, Python, pgvector.

I built the specialists-behind-a-router architecture that gets recommended for
multi-skill agents, measured it against a single agent, and deleted it: same
10/10 eval score, first response 4993ms versus 3217ms, plus two failure modes
the split introduced. Twelve eval cases name the tool the agent must call and
the ones it must not.

**[whatsapp-ea](https://github.com/VictusVinceere/whatsapp-ea)** — [demo](https://youtu.be/kKBwOS1lApY)
A WhatsApp assistant answering from a company's own documents, with Gmail,
Calendar and Drive access. Running in production. LangGraph, FastAPI, Claude,
pgvector, Deepgram.

Reads run immediately, writes wait for confirmation, and that gate is a
conditional database update rather than a prompt instruction — so two people
approving at the same moment produce exactly one action. There is a test for
that race.

## Stack

**AI:** Claude · Gemini · OpenAI · LangGraph · LiveKit · RAG · pgvector · fastembed · Deepgram · evaluation suites
**Languages:** Python · TypeScript · JavaScript · PHP · SQL
**Backend:** FastAPI · Node · Nest.js · Laravel · REST · GraphQL
**Frontend:** React · Next.js · Redux · Vue
**Data:** PostgreSQL · MySQL · DynamoDB · Redis
**Cloud:** AWS Lambda · SQS · S3 · Docker · GitHub Actions · Caddy · Linux
**Integrations:** HubSpot · Slack · WhatsApp Cloud API · Google Workspace

## Writing

Notes on what actually breaks when these systems meet real users:

- [The obvious voice agent architecture was the slower one](https://blog.azizriskulov.com/posts/the-obvious-voice-agent-architecture-was-the-slower-one)
- [An assistant with write access has to ask first](https://blog.azizriskulov.com/posts/an-assistant-with-write-access-has-to-ask-first)
- [Two coaches, one interview, and a race nobody could see](https://blog.azizriskulov.com/posts/two-coaches-one-interview-and-a-race-nobody-could-see)

## Elsewhere

- **Portfolio:** [azizriskulov.com](https://azizriskulov.com)
- **Notes:** [blog.azizriskulov.com](https://blog.azizriskulov.com)
- **LinkedIn:** [in/aziz-riskulov](https://www.linkedin.com/in/aziz-riskulov/)
- **Email:** vinceere@gmail.com

Currently learning Go.
