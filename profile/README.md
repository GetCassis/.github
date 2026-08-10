# Cassis

The context layer between your data and the agents that query it. Your business definitions live in a
git repository you own; Cassis grounds every question in them, detects where the context is wrong or
missing from real use, and keeps it true through pull requests you review.

[getcassis.com](https://www.getcassis.com) · [docs](https://docs.getcassis.com) · [blog](https://www.getcassis.com/blog)

## Start here

Two ways in, depending on whether you want to see it or use it.

| | |
|---|---|
| **[cassis-demo-stallora](https://github.com/GetCassis/cassis-demo-stallora)** | See the whole loop on a sample marketplace warehouse. Fifteen minutes, from your own terminal and your own agent, nothing of yours involved. |
| **[cassis-ontology-starter](https://github.com/GetCassis/cassis-ontology-starter)** | Start an ontology on your own schema. The CI gates, the MCP config and the modeling guide, with none of the content — that part is yours. |

Both are GitHub templates: use the template, don't fork.

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
