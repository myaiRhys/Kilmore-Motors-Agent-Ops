# Dealer Agent Ops

Console for running dealer voice agents across many dealers. Static HTML, no build step.

- `v2.html` is the current console (v2.1).
- `index.html` is v1, kept on purpose as the "before".

## Versions

Each version is saved as its own branch: `version/v1.0`, `version/v2.0`, `version/v2.1`. Switch to one on GitHub to see it as it was.

| Version | What changed | Why |
|---|---|---|
| v1.0 | One dealer. Stock, slots and facts typed into the prompt. Generated prompt and 8 tests. | Get a working agent and test suite fast. |
| v2.0 | Multi-dealer list. Prompt holds behaviour only; stock, facts and slots come from tools and the knowledge base. Stale-stock test added. | Stock in the prompt meant every stock change needed a new prompt version, and sold cars still got offered. |
| v2.1 | Proper light/dark theme, dealer cards, add/edit/delete dealers. | v2.0 was hard to read and adding a dealer gave no feedback. |

## Next
- Go-live readiness per dealer, scored against the ElevenLabs Architect deployment checklist.
- Read agents, versions and test results live from the ElevenLabs API.
