# MyToken (Fabian Token) — Bytecode Verification

> **Note:** This repo redirects to the primary verification repo at [cartoonitunes/fabian-token-verification](https://github.com/cartoonitunes/fabian-token-verification).

Source code verification for MyToken (known as "Fabian Token"):

- [`0xe274d18ef7b194a1edebb04cfe297cfe1489ef65`](https://ethereumhistory.com/contract/0xe274d18ef7b194a1edebb04cfe297cfe1489ef65) — deployed Oct 26 2015 (block 788,576)

Deployed by `0x9b22a80d5c7b3374a05b446081f97d0a34079e7f` (Fabian Vogelsteller, creator of ERC-20).

## Contract

An early pre-ERC-20 token contract by Fabian Vogelsteller. Features a public `balanceof` mapping, `Transfer` event, and standard transfer logic. Predates the ERC-20 standard by over a year.

## Compiler

| Field | Value |
|---|---|
| **Image** | `soljson-v0.1.5+commit.23865e39` (JavaScript, via node.js) |
| **Optimization** | OFF |
| **Runtime size** | 625 bytes |

## Verification Result

⚠️ **NEAR MATCH** — 622/625 bytes match (99.5%). The 3-byte difference is in jump targets in the selector dispatch table — a known artifact of early Solidity compiler function ordering. All function bodies are byte-identical.

## Full Verification Details

See the primary repo: [cartoonitunes/fabian-token-verification](https://github.com/cartoonitunes/fabian-token-verification)

EthereumHistory: https://www.ethereumhistory.com/contract/0xe274d18ef7b194a1edebb04cfe297cfe1489ef65
