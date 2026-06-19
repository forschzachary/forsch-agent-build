# Build agent directory note

Purpose: independent ADK repo for the product and engineering lead agent.

Structure:

- `pyproject.toml` - package metadata for `forsch-agent-build`.
- `src/forsch/agent_build/agent.py` - current ADK `Agent` stub and future graph entrypoint.
- `tests/` - build-agent unit tests.
- `evals/` - build-agent evaluation datasets and scenarios.
- `README.md` - setup/run notes for this repo.

Expected scope: GitHub PR review, issue triage, development workflow checks, code quality, and product/engineering execution support.
