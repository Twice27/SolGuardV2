# SolGuardV2

> Solana smart contract vulnerability scanner

## Overview

SolGuardV2 is a security-focused AI engine with multi-model routing.
Built with MiMo-V2-Pro for fast inference and Claude Opus 4.7 for complex reasoning.

## Architecture

```
   Request -> Router -> Cache -> [MiMo | Claude | GPT] -> Response
```

## Models

- MiMo-V2-Pro (Xiaomi) - cost-efficient
- Claude Opus 4.7 (Anthropic) - deep reasoning
- GPT-4o (OpenAI) - creative
- DeepSeek V3 - code-heavy

## Features

- Smart model routing
- Semantic caching (60% cost reduction)
- Async with timeout protection
- Production-ready

## Install

```bash
pip install -r requirements.txt
python main.py
```

## License

MIT
