# Cassis

Cassis does context maintenance for analytics agents. Your business definitions live in a Git
repository you own, changes run against evals, and merging an approved pull request publishes the
context your agents read over MCP.

[getcassis.com](https://getcassis.com) · [docs](https://docs.getcassis.com) · [blog](https://blog.getcassis.com) · [reading list](https://github.com/GetCassis/analytics-agent-articles)

## Start here

Three things you can run today with no account, in order of effort.

| | |
|---|---|
| **[cassis-demo-stallora](https://github.com/GetCassis/cassis-demo-stallora)** | See the whole loop on a sample marketplace warehouse. Fifteen minutes, from your own terminal and your own agent, nothing of yours involved. A GitHub template: use the template, don't fork. |
| **[dbt-agent-readiness](https://github.com/GetCassis/dbt-agent-readiness)** | Audit your dbt project for what an AI agent will get wrong if you point it at the data today. Runs on your own repository. |
| **[ontology-bootstrap](https://github.com/GetCassis/ontology-bootstrap)** | Assemble a reviewable first ontology from the dbt project, schema, dashboards and docs you already have. Evidence stays attached and unknowns become questions. [Read the measured write-up](https://blog.getcassis.com/a-blank-beats-a-guess/). |

## Reading

| | |
|---|---|
| **[analytics-agent-articles](https://github.com/GetCassis/analytics-agent-articles)** | A curated list of write-ups from data teams building analytics agents: Anthropic, OpenAI, Ramp, GitHub, Gorgias and more, with reading notes organized by problem. Suggestions and corrections welcome. |

## Connect your own project

Once you have a Cassis project and a key ([talk to us](https://getcassis.com/contact/)). Start from the demo template and replace the `cassis/` tree with your own.

| | |
|---|---|
| **[cassis-cli](https://github.com/GetCassis/cassis-cli)** | Validate, test and eval an ontology from your terminal, then publish it. The same commands run in CI to gate pull requests. `pip install cassis-cli` |
| **[skills](https://github.com/GetCassis/skills)** | Agent skills for authoring an ontology and for querying through MCP. `/plugin marketplace add GetCassis/skills` |
| **[cassis-ontology-examples](https://github.com/GetCassis/cassis-ontology-examples)** | Two complete ontology trees to copy from: a minimal skeleton and a fully authored one. |

## Research

| | |
|---|---|
| **[research](https://github.com/GetCassis/research)** | Benchmarks, harnesses and the run data behind our write-ups. |
