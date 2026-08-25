# Cassis

Cassis does context maintenance for analytics agents. Your business definitions live in a Git
repository you own, changes run against evals, and merging an approved pull request publishes the
context your agents read over MCP.

[getcassis.com](https://getcassis.com) · [docs](https://docs.getcassis.com) · [blog](https://blog.getcassis.com)

## Start here

Three ways in, depending on whether you want to bootstrap context, see the full loop, or start from a clean ontology.

| | |
|---|---|
| **[ontology-bootstrap](https://github.com/GetCassis/ontology-bootstrap)** | Assemble a reviewable first ontology from the dbt project, schema, dashboards and docs you already have. Evidence stays attached and unknowns become questions. No account or Cassis key required. [Read the measured write-up](https://blog.getcassis.com/a-blank-beats-a-guess/). |
| **[cassis-demo-stallora](https://github.com/GetCassis/cassis-demo-stallora)** | See the whole loop on a sample marketplace warehouse. Fifteen minutes, from your own terminal and your own agent, nothing of yours involved. |
| **[cassis-ontology-starter](https://github.com/GetCassis/cassis-ontology-starter)** | Start an ontology on your own schema. The CI gates, the MCP config and the modeling guide, with none of the content — that part is yours. |

The demo and starter are GitHub templates: use the template, don't fork.

## Build with it

| | |
|---|---|
| **[cassis-cli](https://github.com/GetCassis/cassis-cli)** | Validate, test and eval an ontology from your terminal, then publish it. The same commands run in CI to gate pull requests. `pip install cassis-cli` |
| **[skills](https://github.com/GetCassis/skills)** | Agent skills for authoring an ontology and for querying through MCP. `/plugin marketplace add GetCassis/skills` |
| **[cassis-ontology-examples](https://github.com/GetCassis/cassis-ontology-examples)** | Two complete ontology trees to copy from: a minimal skeleton and a fully authored one. |

## Tools

| | |
|---|---|
| **[dbt-agent-readiness](https://github.com/GetCassis/dbt-agent-readiness)** | Audit a dbt project for what an AI agent will get wrong if you point it at the data today. Runs on your own repository; no Cassis account needed. |

## Research

| | |
|---|---|
| **[research](https://github.com/GetCassis/research)** | Benchmarks, harnesses and the run data behind our write-ups. |
