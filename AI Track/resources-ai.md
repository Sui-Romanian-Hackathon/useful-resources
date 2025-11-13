##AI Track Guide – Sui Hackathon Edition

#⚡ Recommended Dev Tools
IDE (Integrated Development Environment)
Cursor
Windsurf
Terminal / CLI Tools
Claude Code
Gemini CLI

Only for teams who choose the AI track.
##🚀 Recommended APIs & Frameworks
If your team chooses AI, we recommend using one of ****these three APIs:
Gemini API → Generous freemium tier and very fast models (flash/flash-lite).
Docs: https://ai.google.dev/gemini-api/docs/quickstart
OpenRouter.ai → Access any LLM (GPT, Claude, Llama, etc.) through a single, unified API.
Docs: https://openrouter.ai/docs/quickstart
Fal.ai → The best choice for non-LLM tasks. An "OpenRouter" equivalent for image, audio, and video generation.
Docs: https://docs.fal.ai
Langchain/Langgraph → The most popular framework (Python/JS) for building context-aware, reasoning agents that can chain multiple AI calls and actions together.
Docs: https://docs.langchain.com

##💡 Use Cases
1. ART: AI-Generated NFT Collections
Generation: Use generative AI models to create unique collections of images, music, 3D models, or other digital media.
Storage: Store the generated media files and their corresponding metadata on decentralized storage solutions like IPFS (InterPlanetary File System) or Arweave.
Minting: Programmatically mint the assets as NFTs on Sui, with each token's URI pointing to its unique metadata and media files on decentralized storage.

2. DeFi: Intent-Based AI Agents
Intent: A user states a complex financial goal in natural language, such as "Find the best yield for my 1,000 USDC" or "Swap my ETH for Token X with minimal slippage."
Strategy: The AI agent analyzes the user's intent, scans multiple protocols, chains, and liquidity pools, and then proposes an optimized, multi-step transaction strategy to achieve the goal.
Approval: The user reviews this human-readable strategy and approves it.
Execution: The agent autonomously executes the entire approved sequence of actions.

3. GameFi: AI Agents for games
Pre-Game Bid (Optional): A player initiates a match by placing a "bid" or "stake" (e.g., in crypto tokens or game-specific NFTs) into a smart contract, defining the terms of the game against the AI agent.
Player Move: A human player makes a move in a blockchain-based game (e.g., playing a card, moving a character). This action is sent as a transaction to the game's smart contract, updating the on-chain game state.
Agent Response: An AI agent, acting as an autonomous opponent with its own wallet address, detects this state change. It analyzes the new game state, determines its optimal counter-move, and sends its own transaction to the smart contract.
Win & Payout (Optional): After the game's concluding move, the smart contract automatically determines the winner based on the game rules. It immediately distributes the staked assets (the "bid") to the winner's wallet.
Post-Game Analysis (Optional): After the game ends, a separate AI can analyze the complete, immutable transaction history of the match. It can then provide both the human and AI player with a detailed strategic analysis, insights, or even mint a summary of the game as an "analysis NFT."

