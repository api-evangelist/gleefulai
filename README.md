# Gleeful AI — Visibility AI Audit API

Audits how visible and understandable a website is to AI assistants and agents: visibility
scoring, AI-crawler access audits (GPTBot, ClaudeBot), `llms.txt` and schema.org generation,
brand citation checks, and competitor gap analysis.

- **API:** https://visibility.gleefulai.com
- **Docs:** https://visibility.gleefulai.com/docs
- **OpenAPI:** https://visibility.gleefulai.com/openapi.json
- **Pricing (machine-readable):** https://visibility.gleefulai.com/api/pricing
- **llms.txt:** https://visibility.gleefulai.com/llms.txt

Part of the [API Evangelist](https://apievangelist.com) network. Profiled 2026-08-03 from a
listing request; every surface was fetched first — see `X-Discovery` in `apis.yml`.

## Why this one is worth attention

**No API keys.** Access is priced per call and settled with **x402** micropayments. An
unauthenticated request to a priced endpoint returns a live `HTTP 402` with a
`Payment-Required` header carrying a base64 x402 v2 challenge:

```json
{ "x402Version": 2,
  "accepts": [{ "scheme": "exact", "network": "eip155:8453",
                "amount": "60000", "asset": "0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913",
                "maxTimeoutSeconds": 300 }] }
```

USDC on Base, $0.06–$0.55 a call across 14 priced endpoints. Discovery, pricing, capabilities
and two preview endpoints are free and unauthenticated.

That makes it **agent-native in both directions** — built to be discovered, priced and paid for
by an agent with no human account creation, and built to measure whether agents can read you.
A useful reference implementation for the 402 commercialization thread.
