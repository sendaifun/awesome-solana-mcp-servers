*Read this in [English](README.md), [简体中文](README.zh-CN.md)*

<div align="center">

# awesome-solana-mcp-servers

![Awesome Solana MCP Servers](banner.png)

A curated list of awesome Solana Model Context Protocol (MCP) servers and related resources.

</div>

## MCP Servers
- [Solana Agent Kit MCP Server](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - A Solana Agent Kit implementation using MCP for handling protocol operations on the Solana blockchain. Supports all Solana Agent Kit actions with standardized interactions and environment-based configuration.
- [GOAT MCP Server](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol) - A GOAT SDK implementation enabling Claude Desktop to send and receive ETH and ERC-20 tokens on EVM networks. Features Base Sepolia support and easy Claude Desktop integration.
- [Aldrin Labs Solana MCP Server](https://github.com/Aldrin-labs/solana-mcp-server) - A comprehensive MCP server providing 21 essential Solana RPC methods including account operations, token management, system information, and staking functionality. Features natural language interaction with Solana blockchain data.
- [Solana Limit Order MCP Server](https://github.com/dimitrov-d/solana-limit-order-mcp) - An MCP Server providing capabilities to place limit orders on Solana via Jupiter. Using this MCP Server any AI agent is able to set limit buy/sell orders for any token, view open orders and order history, cancel open orders, trade tokens, fetch token balances/prices and more.
- [Solana Forum Summarizer MCP Server](https://github.com/dimitrov-d/solana-forum-summarizer-mcp) - An MCP server providing capabilities to browse and summarize the [Solana Forum](http://forum.solana.com/). Using this MCP Server an AI agent is able to get the latest/most popular posts on the forum, retreive, sort and group posts by category or author, search posts by keyword and summarize post contents.
- [AMOCA MCP Server](https://github.com/manolaz/amoca-solana-mcp-server) - A specialized MCP server focused on Solana wallet analysis. Features include detailed token balance analysis, portfolio valuation, historical transaction review, and natural language querying for wallet metrics. Provides intuitive interaction with wallet data through conversational AI interfaces.
- [SolMCP Solana MCP Server](https://github.com/N-45div/SolMCP---SendAI-MCP-competition) - A MCP server with a set of 7 tools to be a solana degen,validator and node operator which is fully written in python and has utilised Helius and Dexscrenner for latest data and operations with the prime integration of pyth oracle for price feeds.
- [daoCLI MCP Server](https://github.com/DaoCLI/daoCLI-init) - daoCLI is an MCP-compatible DAO server enabling seamless, customizable DAO deployments via CLI. It empowers AI-agent developers to effortlessly embed Solana-based DAOs directly into apps, using proven bonding curves and AMMs to unlock billion-dollar liquidity markets for AI agents.
- [Hubble MCP Server](https://github.com/HubbleVision/hubble-ai-mcp) - Hubble is a solana MCP server that can do data analysis and visualization for transactions on pumpfun and DEXs with natrual language.
- [Solana DeFi Analytics MCP Server](https://github.com/kirtiraj22/solana-mcp) - A MCP Server that offers comprehensive analytics and actionable insights for Solana wallets and DeFi interactions. It enables AI agents and users to deeply analyze wallet behavior, monitor transactions, and optimize DeFi strategies efficiently on the Solana blockchain.
- [Quant72 MCP](https://github.com/Quant72AI/quant72-mcp) - 🚀 An all-in-one on-chain quantitative trading expert with multiple market data sources and advanced analytical tools. Facilitates efficient on-chain trading with AI assistance, seamlessly integrates all Solana Agent Kit operations, and provides traders with a professional-grade on-chain quantitative trading experience.
- [spice MCP Server](https://github.com/getnimbus/spice) - spice is a MCP server that implements a Solana data query system. It allows users to fetch Solana catalog metadata, and provides tools for querying Solana blockchain data via Flipside API.
- [Memecoin Observatory MCP](https://github.com/tony-42069/solana-mcp.git) - A comprehensive Solana MCP server for analyzing memecoins, tracking trends, and providing AI-powered insights using cultural analysis and on-chain data. Features real-time memecoin radar, social signal analysis, whale wallet tracking, and rugpull protection.
- [Solana Wallet Security Scanner](https://github.com/mohitparmar1/Solana-Wallet-Security-Scanner) - A MCP server that implements a Solana security analysis system. It allows users to scan wallets for threats, detect suspicious programs, and provides tools for monitoring blockchain activity via @solana/web3.js.
- [MCP Meme Deployer](https://github.com/kirabuilds/mcp-meme-deployer) - A Model Context Protocol (MCP) server that allows Claude Desktop to deploy instantly tradable tokens on Solana at zero cost with just a simple conversation.
- [Sentinel MCP Server](https://github.com/sentinel-seed/sentinel) - An AI safety validation server implementing the THSP (Truth-Harm-Scope-Purpose) protocol for Solana transactions. Protects AI agents from executing harmful, unauthorized, or suspicious blockchain operations with configurable validation gates and risk assessment.


## Tools and Libraries
- [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) - A toolkit for connecting AI agents to Solana protocols. Features cross-chain operations, token management, Voltr vault interactions, and multi-agent system support with LangGraph.
- [GOAT SDK](https://github.com/goat-sdk/goat) - A framework for building and integrating GenAI features with built-in MCP support. Includes tool management, Dev UI playground, and cross-model compatibility.
- [Sentinel SAK Plugin](https://github.com/sentinel-seed/sentinel/tree/main/integrations/solana-agent-kit/typescript) - A native Solana Agent Kit v2 plugin providing transaction safety validation using the THSP protocol. Validates transfers, swaps, and DeFi operations before execution with configurable risk thresholds.

## Resources
- [Model Context Protocol Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart) - A comprehensive guide covering MCP protocol basics, server implementation, client setup, and early adoption use cases. Includes practical examples and Claude Desktop integration.
- [Add helpful resources here] - Documentation, tutorials, blog posts, videos, debugging guides, and best practices for MCP development.

## Contents

### What is Model Context Protocol (MCP)?

Model Context Protocol (MCP) is a protocol that enables AI models to interact with external tools and resources in a standardized way. It provides a framework for:
- Tool integration and execution
- Resource management and access
- Prompt templates and management
- Sampling capabilities
- Root-level operations

MCP servers can be integrated with various clients including:
- Claude Desktop App
- Cursor
- Continue
- Zed
- Sourcegraph Cody
- And many more

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
