# AP2 Mandate Studio

A tiny static tool for drafting machine-readable purchase mandates and guardrail policies for autonomous agents.

## Pitch

AP2 Mandate Studio helps agent operators define:
- intent mandates
- cart approval rules
- domain allowlists
- sandbox / firewall requirements
- audit-ready receipt chains

It is inspired by:
- Google Cloud's Agent Payments Protocol (AP2)
- OpenAI's updated Agents SDK with sandbox execution
- GitHub's org-level firewall controls for Copilot cloud agent
- Reuters reporting on Google making enterprise AI agents a monetization priority
- xAI's Grok Voice Agent API

## Live URL

Pending GitHub Pages deployment.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000`.

## Files

- `index.html` — single-page app with inline CSS/JS
- `LICENSE` — MIT
- `.gitignore`

## Sources

- https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol
- https://openai.com/index/the-next-evolution-of-the-agents-sdk/
- https://github.blog/changelog/2026-04-03-organization-firewall-settings-for-copilot-cloud-agent/
- https://uk.finance.yahoo.com/news/google-puts-ai-agents-heart-120308146.html
- https://x.ai/news/grok-voice-agent-api

## License

MIT
