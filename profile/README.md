# Cassis

Cassis is the data context layer that improves with use. Claude, ChatGPT or whatever agent you use
reads fresh, governed metrics, definitions and business rules from it over one MCP.

Every question tests that context. When an answer needs a correction, an eval fails or a dbt model
changes, Cassis flags the gap and, once it has enough evidence, drafts the fix. Your data team
reviews it as a tested pull request in a Git repository you own, and merging it publishes the new
version to every agent.

[getcassis.com](https://getcassis.com) · [docs](https://docs.getcassis.com) · [blog](https://blog.getcassis.com) · [reading list](https://github.com/GetCassis/analytics-agent-articles)

## Start here

| What you want to do | Where to start |
|---|---|
| **Try the maintenance loop** | **[cassis-demo-stallora](https://github.com/GetCassis/cassis-demo-stallora)**: ask a question on sample marketplace data, resolve a missing definition, and ship the fix through a tested pull request. Uses your own agent, with no connection to your data. Requires GitHub and Cassis accounts, Python and an MCP client. Use the GitHub template to create your repository. |
| **Audit your dbt project** | **[dbt-agent-readiness](https://github.com/GetCassis/dbt-agent-readiness)**: find what an analytics agent will get wrong if you point it at your data today. Requires your dbt project, Python and a coding agent. No Cassis account or warehouse connection needed. |
| **Build your first context** | **[ontology-bootstrap](https://github.com/GetCassis/ontology-bootstrap)**: assemble a reviewable ontology from your existing assets. Evidence stays attached and unknowns become questions. Requires a dbt project, schema export, Python and a coding agent. No Cassis account needed; runs use model tokens and include human review checkpoints. [See run requirements](https://github.com/GetCassis/ontology-bootstrap#run-it), or [read the measured write-up](https://blog.getcassis.com/a-blank-beats-a-guess/). |

## Connect your own project

[Talk to us](https://getcassis.com/contact/) to connect your own warehouse and get a Cassis project.
If you used the bootstrap kit, [connect the ontology you just generated](https://github.com/GetCassis/ontology-bootstrap#keeping-it-current).
For the CI and MCP setup, use the demo template and replace its `cassis/` tree with your own ontology.

| Repository | What it does |
|---|---|
| **[cassis-cli](https://github.com/GetCassis/cassis-cli)** | Validate, test and eval an ontology from your terminal, then publish it. The same commands run in CI to gate pull requests. `pip install cassis-cli` |
| **[skills](https://github.com/GetCassis/skills)** | Agent skills for authoring an ontology and for querying through MCP. In Claude Code, add the marketplace with `/plugin marketplace add GetCassis/skills`, then [install the skills you need](https://github.com/GetCassis/skills#install). |
| **[cassis-ontology-examples](https://github.com/GetCassis/cassis-ontology-examples)** | Two complete ontology trees to copy from: a minimal skeleton and a fully authored one. |

## Reading

| Repository | What you will find |
|---|---|
| **[analytics-agent-articles](https://github.com/GetCassis/analytics-agent-articles)** | A curated list of write-ups from data teams building analytics agents: Anthropic, OpenAI, Ramp, GitHub, Gorgias and more, with reading notes organized by problem. Suggestions and corrections welcome. |

## Research

| Repository | What you will find |
|---|---|
| **[research](https://github.com/GetCassis/research)** | Benchmarks, harnesses and the run data behind our write-ups. |
