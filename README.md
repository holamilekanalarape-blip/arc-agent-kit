1| <div align="center">
2| 
3| <img src="assets/logo.png" alt="Arc Agent Kit" width="128">
4| 
5| # Arc Agent Kit
6| 
7| **All-in-one MCP toolkit for the [Arc](https://arc.exploreme.pro) blockchain, in TypeScript.**
8| 
9| Wallet operations · local-only signing · transfers · contract deploy & verification · staking (delegate / undelegate) · full chain exploration — from **Claude Code**, **Cursor**, **Codex**, [...]
10| 
11| Built for **humans**. Perfect for **AI**.
12| 
13| [![MCP](https://img.shields.io/badge/MCP-server-6E56CF)](https://modelcontextprotocol.io)
14| [![Arc](https://img.shields.io/badge/Arc-mainnet_5042-0a3ab5)](https://arc.exploreme.pro)
15| [![Node](https://img.shields.io/badge/Node-%E2%89%A520-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org)
16| [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org)
17| [![viem](https://img.shields.io/badge/built_with-viem-FFC517)](https://viem.sh)
18| [![License](https://img.shields.io/badge/License-MIT-blue)](#license)
19| 
20| </div>
21| 
22| ---
23| 
24| ## Why Arc Agent Kit
25| 
26| **Your private key never leaves your machine.** MCP only prepares *unsigned* transactions — signing happens locally, and the key is never sent to the AI model or a remote server.
27| 
28| **Two protection levels.**
29| - **Simple** — a guard hook blocks the agent from reading `.env`.
30| - **Secure** — encrypted keystore + a signing daemon in a separate, isolated process; the agent only ever receives the signed hex.
31| 
32| **Two ways to use.**
33| - **Subscription** (free) — connect MCP to Claude Code / Cursor / Codex and use your existing subscription.
34| - **AI SDK** (developers) — programmatic agents via the Vercel AI SDK with Claude or OpenAI.
35| 
36| **Arc-native.** Explore blocks, accounts, tokens, validators, and verify contracts. Native transfers: MCP prepares an unsigned skeleton; you sign locally and broadcast via Arc RPC.
37| 
38| > **Mainnet — real funds.** Default network is **Arc mainnet (chain ID 5042, native USDC)**. There is **no faucet**. Signing a filled transfer and broadcasting it spends **real USDC**. Prefer **[...]
39| 
40| ---
41| 
42| ## Wallet
43| 
| Public wallet address: `0xE90f7075d783a69A0884c6300DAd1658287521Df`
| 
| > Keep this as a public address only. Never share your private key or recovery phrase.
| 
| ---
| 
| ## Architecture
