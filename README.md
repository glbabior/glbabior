## Gregory Babior

Engineering leader in Pasadena, CA. I've spent the last several years running global engineering
organizations – most recently a 75-person Development, QA, DevOps, and Production Support org at
TiVo, accountable for delivery, operations, and budget.

The work I care most about is platform modernization and reliability: monolithic services to
containerized microservices, batch pipelines to Kafka-based streaming, and the observability and
change-management discipline that keeps systems running once they ship. At TiVo that meant a 96%
reduction in P1 production incidents and data delivery latency down from 25+ hours to under 30
minutes.

I use Claude Code hands-on nearly every day - building complete applications and setting up 
documentation, code-review, and security agents. The velocity gains are real and dramatic - working 
software in days that would once have taken weeks. That same velocity is what sharpens the harder 
questions, though - how much of an AI-authored codebase a team can honestly claim to understand, 
and where human review is best spent. I'm actively interested in how other engineering organizations
are working through the same questions.

### What's here

Most of my professional work isn't public. These are personal projects, built to stay close to the
craft:

**[recomps](https://github.com/glbabior/recomps)** — works out what a property is worth by comparing
it to nearby sales. It starts with the sales data the listing sites already publish, which is free
and covers most of what it needs, and only sends AI workers out to research a property when
something is missing. I built it for the lots left after the Eaton Fire burned through Altadena,
where using the market's median price per square foot makes a small lot look cheaper than it is.

Results show on screen, and you can export a spreadsheet. A run gives you the value figured four
different ways, side by side instead of averaged together. Three suggested list prices and a price
to walk away at. A table grouping sales by lot size, so you can see for yourself whether smaller
lots really do sell for more per square foot. How much the estimate moves depending on how loosely
you define "a similar size lot". A breakdown by area of town. And a list of the agents who actually
sold these lots — how many each sold, how close to asking they got, at what price per square foot,
and on what size lot — meant as people to interview, not a ranking.

**[pig-purchase-tracking](https://github.com/glbabior/pig-purchase-tracking)** — a budget tracker
that runs on your own machine. Point it at folders of bank and credit-card statement PDFs and it
pulls out the transactions and sorts them into your budget categories. It learns as it goes: you
write rules for a category, it shows you what a rule would catch before you save it, warns you when
two categories both claim the same purchase, and remembers the corrections you make by hand.
Anything it still can't place goes to the Claude API, and that gets rarer over time.

It tracks each month against your budget, and averages across the months you have marked finished,
so you see a typical month rather than one odd one. Charts show spending per category over time, and
you can click any category to read the transactions behind the number. Budgets have dates: when you
change one it asks whether the amount changed going forward or was simply wrong, so old months stay
measured against what you were budgeting at the time. Dollar amounts never leave your machine.

### Elsewhere

- LinkedIn — [in/gbabior](https://www.linkedin.com/in/gbabior/)
