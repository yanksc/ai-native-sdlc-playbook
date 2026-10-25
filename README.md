# AI-Native SDLC Playbook

A one-page playbook for making a 50–100 person SaaS engineering org AI-native: which capabilities to build, which to buy or adopt, seven workstreams with outcomes and key results, a model for prioritizing MCP servers and agents, and a 12-month roadmap with measured gates.

**Read it:** https://yanksc.github.io/ai-native-sdlc-playbook/

## What's inside

- **Maturity ladder** from ad hoc AI use (L0) to an AI-native operating model (L4), with proposed exit gates.
- **Capability map** of five SDLC stages on six shared capabilities, and the two you should build yourself.
- **Seven workstreams** (guardrails, context, intent to spec, spec to PR, agentic quality, release to recovery, people and measurement), each with an outcome and key results.
- **Build, buy or adopt** defaults for each capability.
- **MCP and agent prioritization**: a scoring formula, an in-page priority calculator, and a tiered list of MCP servers to connect first.
- **Roadmap**: four phases over 12 months, each closed by a measured gate.
- **Measurement and risks**: metrics paired with quality guardrails, and the failure modes to plan for.

## Run it locally

The site is a single static `index.html` with no build step.

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Contributing

Corrections, new evidence and field reports are welcome. Open an issue, or send a pull request that edits `index.html`. Please cite a public source for any new figure.

## Sources

All figures come from public sources, listed at the bottom of the page: the 2025 DORA report and AI Capabilities Model, METR's 2025 and 2026 developer productivity studies, Faros telemetry reports (vendor), and the OWASP MCP Top 10 (via a vendor summary). Key-result targets and gates are proposals, not benchmarks.

## License

Text and diagrams are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE).

This is a personal project, not affiliated with or endorsed by any employer.
