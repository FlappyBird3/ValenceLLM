![tests](https://github.com/FlappyBird3/ValenceLLM/actions/workflows/tests.yml/badge.svg)

# ValenceLLM

Does fine-tuning for generating compound formulas improve an LLM's chemical reasoning, or just its answers?

**Live demo:** https://chemcheck-lovat.vercel.app
**API documentation:** https://chemcheck-api-crwd.onrender.com/docs

| Folder | What it contains |
|---|---|
| [`research/`](research/) | DPO + LoRA fine-tuning, held-out evaluation, token-level analysis |
| [`src/chemcheck/`](src/chemcheck/) | ChemCheck verifier library and FastAPI service |
| [`web/`](web/) | React website |
| [`tests/`](tests/) | Automated tests, run by GitHub Actions on every push |
