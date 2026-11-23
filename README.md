# AdaNext engineering guides

AdaNext is Cristian Gîrlea’s personal project for running and reviewing work across AI agents. Ada handles the conversation, AdaNext OS coordinates the task, and Harness runs the chosen agent and records what happened. These guides follow a request through that workflow and show what a fresh reviewer can recover from the record.

| Guide | Where to start |
| --- | --- |
| [Technical brief · 13 pages](./AdaNext-technical-brief.pdf) | Start here for the architecture, how agents exchange context, and a walkthrough you can reproduce. |
| [Engineering dossier · 30 pages](./AdaNext-engineering-dossier.pdf) | Pages 4–10 trace a handoff through review and recovery. Pages 14–18 examine retrieval, the 60-run pilot, and where supplying extra context made the agent do more work. |

The November 2026 edition links to the source revisions used in each guide. The cloud-credit workflow on dossier pages 24–26 is a worked design example.

[Harness source](https://github.com/cristiangirlea/harness) · [AdaNext OS](https://github.com/cristiangirlea/adanext-os) · [Retrieval pilot and per-question results](https://github.com/cristiangirlea/harness/blob/3615d4a257660ec201fa7aa0167fcaf50ba3a8ae/docs/retrieval-pilot-report.md)
