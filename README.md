## Gregory Babior

Engineering leader in Pasadena, CA. I've spent the last several years running global engineering
organizations – most recently a 75-person Development, QA, DevOps, and Production Support org at
TiVo, accountable for delivery, operations, and budget.

The work I care most about is platform modernization and reliability: monolithic services to
containerized microservices, batch pipelines to Kafka-based streaming, and the observability and
change-management discipline that keeps systems running once they ship. At TiVo that meant a 96%
reduction in P1 production incidents and data delivery latency down from 25+ hours to under 30
minutes.

I use Claude Code hands-on nearly every day – building complete applications and setting up
documentation, code-review, and security agents. That practice has raised questions I don't
consider settled: how much of an AI-authored codebase a team can honestly claim to understand, and
where human review is best spent. I'm interested in how other engineering organizations are working
through the same ones.

### What's here

Most of my professional work isn't public. These are personal projects, built to stay close to the
craft:

**[recomps](https://github.com/glbabior/recomps)** — an LLM-orchestrated research pipeline for
pricing a property against its comparable sales. Deterministic passes read what the listing sites
already publish and answer most of the question for free, and parallel agent workers are dispatched
only at the gaps. Built for the lots left after the Eaton Fire burned through Altadena, where a
market-median price per square foot systematically underprices a small parcel.

It reports on screen, and exports a workbook of live formulas when you want one. Either way the run
produces four valuation bases side by side rather than blended, a size/rate table splitting sales
into equal-count bands so the size premium is read off a column instead of assumed, a bracket ladder
showing how far the estimate moves as "similar size" widens from tight to the whole market, a
by-area breakdown of the market's four quadrants with parcel size beside every rate, the
sold-to-ask distribution, and an agent table — who closed what, at what ratio to asking, at what
rate, on what median parcel size — as a shortlist to interview rather than a ranking.

**[pig-purchase-tracking](https://github.com/glbabior/pig-purchase-tracking)** — a local-first
budget tracker in Java and Spring Boot. Point it at folders of bank and credit-card statement PDFs
and it parses, reconciles and categorizes them. Categorization is a learning loop: you write hints
against a category, the app previews what a hint would catch *before* you save it, flags collisions
where two categories claim the same transaction, and folds your manual corrections back into the
rules, so the share that has to go to the Claude API shrinks over time.

Spend is tracked per month and as a rolling average across the months you mark complete, per
category and in total, with spend-over-time charts per category and click-through from any category
to the transactions behind it. Budgets are dated facts: changing one asks whether it changed *going
forward* or was simply wrong, so past months stay measured against the budget they were lived under
and the rolling view averages the budgets actually in force. Dollar amounts never leave the machine.

### Elsewhere

- LinkedIn — [in/gbabior](https://www.linkedin.com/in/gbabior/)
