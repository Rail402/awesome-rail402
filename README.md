# Awesome Rail402 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of SDKs, tools, APIs, agents, and resources for
> [Rail402](https://rail402.app) — the agent-native paid-API marketplace on
> Base, powered by [x402](https://github.com/rail402/agent-services-spec) and USDC.

Rail402 lets AI agents **discover, pay for, and call** APIs autonomously: no API
keys, no accounts — just per-call USDC settlement over the x402 protocol on Base.

## Contents

- [Official Tools](#official-tools)
- [Community SDKs](#community-sdks)
- [Published APIs](#published-apis)
- [Agent Projects Using Rail402](#agent-projects-using-rail402)
- [x402 Resources](#x402-resources)
- [Base Network Resources](#base-network-resources)
- [Related Standards](#related-standards)
- [Powered by Rail402 badge](#powered-by-rail402-badge)
- [Contributing](#contributing)

## Official Tools

Maintained by the Rail402 team.

- [x402-sdk](https://github.com/rail402/x402-sdk) — Make any REST endpoint x402-payable. Express, Next.js, and FastAPI adapters (`@rail402/x402`, `rail402-x402`).
- [provider-starter](https://github.com/rail402/provider-starter) — Deploy-ready Express / Next.js / FastAPI paid-API templates with Dockerfiles and deploy guides.
- [agent-services-spec](https://github.com/rail402/agent-services-spec) — The Agent Services Discovery standard + `@rail402/validate-spec` CLI.
- [rail402-mcp](https://github.com/rail402/rail402-mcp) — MCP server exposing the marketplace to Claude, Cursor, and Base MCP.
- [examples](https://github.com/rail402/examples) — LangChain, Claude, OpenAI, and Base MCP agents that pay for Rail402 APIs.

## Community SDKs

SDKs and integrations built by the community. _Open a PR to add yours._

- _Your library here — see [CONTRIBUTING.md](./CONTRIBUTING.md)._

## Published APIs

Live services in the [Rail402 marketplace](https://rail402.app/marketplace).

- [Token Analytics](https://rail402.app/marketplace/token-analytics) — Holder stats, liquidity, price/volume, social mentions, and candlestick signals for a Base token. `0.05 USDC` · Analytics.
- [Wallet Risk Score](https://rail402.app/marketplace/wallet-risk-score) — 0–1 risk score for an EVM wallet from on-chain behavior. `0.05 USDC` · Security.
- [Sentiment Summary](https://rail402.app/marketplace/sentiment-summary) — Recent social sentiment for a ticker. `0.02 USDC` · Data.
- [The Stall](https://the-stall.intuitek.ai) — 178 pay-per-call financial market data capabilities: US stocks, ETFs, equity fundamentals, analyst ratings, insider trades, hedge fund holdings, options chains, treasury yields, DeFi yields, crypto, prediction markets, and macro indicators. `$0.005 USDC/call` · Finance & Market Data.

## Agent Projects Using Rail402

Agents and apps that consume Rail402 APIs. _Open a PR to add yours._

- [rail402/examples](https://github.com/rail402/examples) — Reference agents (LangChain, Claude, OpenAI, MCP) that discover and pay for marketplace APIs.

## x402 Resources

- [Agent Services Spec — x402 flow](https://github.com/rail402/agent-services-spec/blob/main/spec/x402-flow.md) — Normative description of the HTTP 402 payment handshake.
- [HTTP 402 Payment Required (MDN)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/402) — The status code x402 revives.
- [`llms.txt` for paid APIs](https://github.com/rail402/agent-services-spec/blob/main/spec/llms-txt-format.md) — Discovery breadcrumb format.

## Base Network Resources

- [Base](https://base.org) — Ethereum L2 by Coinbase; the settlement layer for Rail402.
- [Base MCP](https://github.com/base/base-mcp) — MCP server for Base wallets and chain actions; pairs with `rail402-mcp`.
- [USDC on Base](https://www.circle.com/usdc) — The settlement currency (`0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`).
- [Base Docs](https://docs.base.org) — Network docs, RPC endpoints, and faucets.

## Related Standards

- [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) — Agent identity standard used to attest agent identities interacting with Rail402.
- [ERC-8021](https://eips.ethereum.org/EIPS/eip-8021) — Builder attribution standard for crediting tooling builders.
- [Model Context Protocol](https://modelcontextprotocol.io) — The protocol behind `rail402-mcp` and Base MCP.

## Powered by Rail402 badge

If your API or agent uses Rail402, show it. Add this to your README:

```markdown
[![Powered by Rail402](https://img.shields.io/badge/powered%20by-Rail402-0052FF.svg)](https://rail402.app)
```

Renders as: [![Powered by Rail402](https://img.shields.io/badge/powered%20by-Rail402-0052FF.svg)](https://rail402.app)

HTML version:

```html
<a href="https://rail402.app"><img src="https://img.shields.io/badge/powered%20by-Rail402-0052FF.svg" alt="Powered by Rail402"></a>
```

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for the
guidelines, then open a pull request. Every entry must be relevant to Rail402,
x402, or the Base agent-payments ecosystem.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](./LICENSE)

To the extent possible under law, the contributors have waived all copyright and
related rights to this work. See [LICENSE](./LICENSE).
