# JD Screening Reverse Engineering

Use this reference to infer what recruiters, hiring managers, and ATS-like filters may look for.

## Parse The JD

Extract these layers:

1. **Role mission**: what business/product problem this hire exists to solve.
2. **Work objects**: products, platforms, workflows, modules, users, markets, or systems named in the JD.
3. **Responsibilities**: planning, discovery, design, delivery, measurement, community, ops, platform governance.
4. **Hard requirements**: years, education, domain experience, language, tools, technical literacy.
5. **Bonus requirements**: open source, research collaboration, engineering background, design ability, AI tool depth.
6. **Hidden evaluation criteria**: taste, judgment, autonomy, ambiguity tolerance, detail sensitivity, communication.

## Build The Screening Matrix

Return a table with:

- `criterion`: what they are likely screening for
- `signal`: words/phrases that trigger the criterion
- `resume evidence`: what proof should appear in the resume
- `candidate fit`: strong / medium / weak / missing
- `rewrite guidance`: where and how to show it

## Keyword Library

Group keywords by recruiter intent, not alphabetically.

Common groups:

- **Role identity**: AI PM, Agent PM, Platform PM, Growth PM, Product Owner, Module Owner.
- **AI / Agent**: Agentic AI, Agent Harness, Agent Template, Agent Loop, Tool Use, Skills, MCP, Memory, Planning, Reasoning, Context Engineering, Prompt Engineering.
- **Product surface**: Chat, App, Web, API, Open Platform, Workflow, Knowledge Base, Skill Market, Developer Console, Admin Console.
- **Product work**: 0-1, Roadmap, PRD, user research, competitor analysis, prioritization, launch, iteration, project management.
- **Data / evaluation**: metrics, funnel, retention, conversion, A/B test, gray release, instrumentation, model evaluation, quality metrics.
- **Experience / taste**: UI/UX, prototype, usability, edge cases, failure states, developer experience, user experience.
- **Collaboration**: model team, algorithm team, research, engineering, operations, community, open source users.

## Reverse-Engineer Questions

For every role, answer:

- What would make a recruiter stop scanning and keep reading?
- What would make a hiring manager believe this person can own the work on day one?
- What proof is missing if the resume only uses generic PM language?
- Which two or three experiences should dominate the first half of the resume?
- Which keywords must appear naturally in titles, summaries, or first bullets?

## Red Flags To Catch

- Too many responsibilities without product objects.
- AI vocabulary without first-hand usage or implementation evidence.
- Metrics without decision context.
- Design claims without artifacts, prototypes, or product outcomes.
- "Participated in" language for work the candidate actually owned.
- Dense keyword lists that do not map to resume bullets.
