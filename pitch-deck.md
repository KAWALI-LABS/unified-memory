# UnifiedMemory — Pitch Deck
**Hackathon Demo Day | June 21, 2026**

---

## Slide 1: Title
# UnifiedMemory
### Your Digital Life. One Unified Memory. Agent-Ready.

> Speaker note: Open with the URL — https://unified-memory.kawai-labs.com — and let the landing page animate for 5 seconds before speaking.

---

## Slide 2: The Problem
# AI Has No Memory of YOU

- Every ChatGPT conversation starts from zero
- Claude doesn't know your Spotify playlist
- AI agents have zero context about your actual life

**The result?** Repetitive, shallow, forgetful AI interactions.

> Speaker note: "Imagine if every time you met your best friend, they had no memory of you. That's AI today."

---

## Slide 3: The Solution
# UnifiedMemory

**One platform. 20+ data sources. One unified knowledge graph.**

- **Connect** Gmail, GitHub, Spotify, Slack, Notion, and 15 more
- **Store** memories as vector embeddings in Pinecone
- **Control** access via NEAR ConsentNFT — mint, define limits, revoke
- **Pay** per query via Circle x402 micropayments ($0.001/query)

> Speaker note: "We don't just aggregate data — we turn your digital life into a queryable memory graph that AI agents can access with your explicit consent."

---

## Slide 4: Live Demo (90 seconds)
### Walkthrough: Onboard → Mint → Query → Revoke

**Step 1 — Onboard**
- Show platform grid: Gmail, GitHub, Spotify, Slack, Notion connected

**Step 2 — Mint Consent NFT**
- Agent ID: demo-agent.testnet
- Platforms: All 6 active platforms
- Budget: 100 queries, $1 USDC, expires in 1 day
- Click "Mint Consent" → tx hash appears instantly

**Step 3 — Agent Query**
- Query: "What did Sarah email me about the hackathon?"
- Result: Real memory from Gmail — "Sarah sent an email reminding that the hackathon deadline is Sunday noon..."

**Step 4 → Dashboard**
- Stats: 30 memories indexed, 100 queries remaining, $1 budget

**Step 5 — Revoke**
- Click "Revoke Consent" → NFT burned on NEAR
- Access cut off. Agent can no longer query.

> Speaker note: "This is real. The memory came from our Pinecone index. The NFT is on NEAR testnet. The payment gate is Circle x402."

---

## Slide 5: Tech Stack
# Built for Scale

- **Blockchain / Consent:** NEAR Protocol (ConsentNFT smart contract)
- **Vector Memory:** Pinecone (90+ demo vectors, scales to millions)
- **Payments:** Circle x402 ($0.001 USDC per query)
- **Edge Compute:** Cloudflare Workers (global, <100ms cold start)
- **Frontend:** Next.js 14 + Tailwind CSS
- **Embeddings:** OpenRouter / OpenAI text-embedding-3-small

> Speaker note: "Every piece is production-grade. NEAR for on-chain consent, Pinecone for sub-100ms vector search, Cloudflare Workers for edge deployment, Circle for micropayments."

---

## Slide 6: Business Model
# How We Make Money

**Freemium**
- 3 queries/day free
- Then $0.001 per query via x402

**Enterprise**
- Flat monthly rate for teams
- Custom connectors, SLA, dedicated support

**Target: $50K MRR in 12 months**

> Speaker note: "We're not selling data — we're selling access. Users own their data. Agents pay to query it. We take a small fee per transaction."

---

## Slide 7: Team & Ask
# Join Us

**Team:** [Your names and roles]

**What we need:**
- AI agent platforms to integrate UnifiedMemory as their memory layer
- Seed funding to build out the remaining 17 connectors
- Partnerships with data platforms (Gmail, Spotify, etc.)

**Contact:**
- Demo: https://unified-memory.kawai-labs.com
- Repo: https://github.com/KAWALI-LABS/unified-memory

> Speaker note: "We built this in 48 hours. Imagine what we can do in 48 weeks. Let's give AI a memory."

---

## Appendix: Demo Credentials & URLs

| Service | URL / Details |
|---------|--------------|
| Frontend | https://unified-memory.kawai-labs.com |
| MCP Worker | https://unified-memory-mcp.rapid-king-4a64.workers.dev |
| NEAR Contract | aihackathon.testnet |
| Token ID | 0 |
| Pinecone Index | unified-memory (90 vectors) |

---

## Appendix: 3-Minute Timing Script

| Time | Action |
|------|--------|
| 0:00 | Open URL, let landing page animate |
| 0:15 | Slide 2: Problem statement |
| 0:45 | Slide 3: Solution overview |
| 1:15 | Slide 4: Start demo — Onboard page |
| 1:30 | Slide 4: Mint Consent NFT |
| 1:50 | Slide 4: Agent query — show real result |
| 2:20 | Slide 4: Dashboard stats |
| 2:40 | Slide 4: Revoke consent |
| 2:55 | Slide 5-6: Tech stack + business model (fast) |
| 3:10 | Slide 7: Ask + close |
