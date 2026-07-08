<p align="center">
  <img src="brand/readme-header.png" alt="You write code. We cover it. — Covallaby generates beautiful coverage reports for your pull requests." width="820">
</p>

## 🦘 Beautiful coverage reports for your pull requests

No account. No upload token. No dashboard you didn't ask for. One workflow
step, and every PR answers the only question that matters: **can I merge this?**

```yaml
- uses: covallaby/action@v0.1.1
  with:
    files: coverage/lcov.info
    min-patch: 85
```

Every pull request gets one sticky comment (updated in place, never spam),
named checks, warning annotations on untested lines in the diff, and a CI
gate whose failures tell you where to start — never just "coverage failed."

**See it live:** [a passing PR](https://github.com/covallaby/action/pull/1) ·
[a failing PR](https://github.com/covallaby/action/pull/2) ·
[a docs-only PR](https://github.com/covallaby/action/pull/3)

### The pieces

| | |
|---|---|
| [**covallaby/action**](https://github.com/covallaby/action) | The GitHub Action, CLI, parsers (LCOV · JaCoCo · Cobertura · xccov), and single-file HTML report |
| **covallaby/covallaby** | The optional self-hosted dashboard: history, PR comparisons, hotspots, live badges — one tiny process |

### Install with AI

Paste this into your coding agent (Claude Code, Cursor, Copilot…):

```text
Read https://raw.githubusercontent.com/covallaby/action/main/llms-install.md and set up Covallaby in this repository.
```

---

<sub>Friendly, never shaming. Open source, MIT. 🌿 You're covered.</sub>
