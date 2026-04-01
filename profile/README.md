## Veil Protocol

Decentralized AI inference. Rules, not process.

```
CONSUMER ──> RELAY ──> PROVIDER ──> AI MODEL
   |            |          |
   └────── SOLANA CHAIN ───┘

Relay sees who, not what. Provider sees what, not who.
```

### Status: Testnet Live

```
[x] E2E verified: Consumer → Relay → Provider → Claude
[x] Streaming + envelope encryption (tweetnacl)
[x] 36/36 tests passing
[x] 12 module design specs (4385 lines)
[x] 10 desired-state tasks for AI agents
[ ] Multi-provider support
[ ] On-chain settlement (Solana)
[ ] RBOB scoring system
```

### Repositories

| Repo | Description | Status |
|------|-------------|--------|
| [core](https://github.com/runveil-io/core) | Protocol core — consumer, relay, provider, crypto | ✅ Testnet |
| [website](https://github.com/runveil-io/website) | [runveil.io](https://runveil.io) | ✅ Live |
| [whitepaper](https://github.com/runveil-io/whitepaper) | Protocol whitepaper (15 chapters) | ✅ Published |
| [contracts](https://github.com/runveil-io/contracts) | Solana programs — Registry, Escrow, Staking | ⏳ Stage 2 |
| [docs](https://github.com/runveil-io/docs) | Documentation and specifications | ✅ Published |

### Build with Your Agent

```bash
git clone https://github.com/runveil-io/core.git && cd core
npm install && npm test              # 36/36 passing
ls desired/                          # 10 tasks, pick one
```

Merged code earns RBOB points. Early builders get 5x Genesis Bonus.
Points convert to TOKEN at TGE.

[Design docs →](https://github.com/runveil-io/core/tree/main/docs/design)

### RBOB — Four Rules

```
R1: Code that passes verification can be merged.
R2: Merge requires K independent stake signatures.
R3: Protected modules require higher threshold.
R4: Surviving code earns points. Points = future revenue share.
```

---

**[runveil.io](https://runveil.io)** · [Twitter](https://x.com/runveil_io) · [Telegram](https://t.me/+XJ-ogZ9hBy44ZmFl)
