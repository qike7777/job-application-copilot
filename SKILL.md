---
name: job-application-copilot
description: End-to-end job application workflow for reverse-engineering job descriptions, inferring resume screening logic, building ATS keyword libraries, rewriting role-specific resume content, planning portfolio/GitHub proof, and preparing Figma/PDF resume layouts. Use when the user provides a JD, recruiter notes, job screenshots, resume drafts, PDF resumes, Figma resume designs, portfolio links, or asks how to optimize a resume/application for a target company or role.
---

# Job Application Copilot

## Core Workflow

Run the work as an application package, not as isolated resume polishing.

1. Intake the target role, company, JD, recruiter notes, screenshots, current resume, portfolio/GitHub links, and any non-negotiable facts.
2. Reverse-engineer the screening model: role mission, must-have evidence, bonus signals, likely ATS keywords, interview concerns, and missing proof.
3. Map candidate evidence to the screening model: work experience, projects, metrics, technical/tool fluency, product taste, collaboration scope, and leadership ownership.
4. Rewrite only what can be credibly supported. Prefer concise, high-signal bullets with ownership, product object, mechanism, metric, and relevance.
5. Design the resume structure for scanning: one-line positioning, keyword strip if useful, work modules by evidence type, education, links, and proof artifacts.
6. If Figma or visual design is involved, refine layout, hierarchy, spacing, and link behavior before export.
7. QA the final artifact: ATS text extraction, PDF rendering, link checks, typo scan, consistency, and role-fit against the JD.

## Reference Routing

- Read `references/jd-screening.md` when analyzing a JD, screenshots of job requirements, or recruiter notes.
- Read `references/resume-writing.md` when rewriting resume bullets, summary, modules, keywords, or project descriptions.
- Read `references/figma-layout.md` when the user wants Figma editing, resume layout, visual hierarchy, PDF export polish, clickable links, or portfolio presentation.
- Read `references/qa-checklist.md` before final delivery or when reviewing a PDF/Figma/exported resume.

## Output Modes

Choose the output form based on what the user asks for:

- **Diagnosis**: concise issues and priority fixes.
- **Keyword library**: grouped ATS/recruiter keywords with evidence requirements.
- **Resume rewrite**: ready-to-paste sections in Markdown.
- **Figma guidance**: concrete layout/spacing/link instructions.
- **Application package**: resume, cover note, GitHub/portfolio proof plan, and interview talking points.

## Style Rules

- Make the candidate look specific, not inflated.
- Use the target role's language without keyword stuffing.
- Prefer "owned/built/defined/measured/iterated" evidence over generic "participated/responsible for" phrasing.
- Compress repeated concepts into one strong phrase: e.g. "intelligent workflow" instead of listing every example.
- Preserve truthfulness. If a metric or scope is unknown, suggest a placeholder or ask for confirmation instead of inventing.
- Keep Chinese resumes dense but readable: strong headings, short bullets, visible ownership tags, and minimal filler.

## Tool Notes

- Use browser/web only when current market/JD/company facts must be verified or the user explicitly asks for online research.
- Use Figma tools when available for direct design work. If Figma MCP is unavailable or rate-limited, provide exact manual instructions and continue with content/layout guidance.
- Use PDF rendering/text extraction tools for final exported resumes when visual or ATS quality matters.
