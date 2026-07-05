# Job Application Copilot

Turn any job description into a targeted resume, ATS keyword map, Figma-ready layout plan, and final application QA checklist.

一个用于求职投递的 Codex Skill：把 JD 反推出筛选机制、关键词库、简历改写方向、Figma 排版建议和最终 PDF/ATS 检查清单。

## Why This Exists

Most resume edits stop at "make it sound better." This skill goes one layer deeper:

1. What is this company really screening for?
2. Which keywords matter, and what evidence must support them?
3. Which resume modules should be rewritten first?
4. Does the final PDF actually scan well for recruiters and ATS?

## Best For

- AI Product Manager candidates
- Agent / Agent Harness / AI Workflow roles
- Platform PM and developer ecosystem roles
- PMs rewriting a resume for one specific JD
- Figma-designed one-page resumes
- Portfolio / GitHub proof planning

## What You Give It

```text
- Target JD or recruiter notes
- Current resume or rough experience notes
- Optional: portfolio, GitHub, Figma file, PDF resume
```

## What It Produces

```text
- JD screening matrix
- ATS / recruiter keyword library
- Evidence gap analysis
- Role-specific resume rewrite
- Figma layout and spacing guidance
- PDF / ATS / link QA checklist
```

## Example Prompt

```text
Use $job-application-copilot to analyze this AI Agent PM JD, reverse-engineer the screening criteria, and rewrite my resume into a targeted one-page version.
```

## Example Outputs

- [Sample JD screening matrix](examples/sample-jd-screening-matrix.md)
- [Sample resume rewrite](examples/sample-resume-rewrite.md)
- [AI Agent PM keyword map](examples/ai-agent-pm-keyword-map.md)

## Install

Copy this folder into your Codex skills directory:

```bash
cp -R job-application-copilot ~/.codex/skills/
```

Then start a new Codex session and invoke:

```text
$job-application-copilot
```

## Skill Structure

```text
job-application-copilot/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── examples/
│   ├── ai-agent-pm-keyword-map.md
│   ├── sample-jd-screening-matrix.md
│   └── sample-resume-rewrite.md
└── references/
    ├── figma-layout.md
    ├── jd-screening.md
    ├── qa-checklist.md
    └── resume-writing.md
```

## Design Principles

- Make the candidate look specific, not inflated.
- Use the target role's language without keyword stuffing.
- Tie every AI/Agent keyword to real product evidence.
- Preserve truthfulness: do not invent metrics, ownership, tools, or scope.
- Treat the final resume as both content and interface: it must scan well.

## Good Use Cases

```text
Use $job-application-copilot to:
- infer what this JD is really screening for
- build a resume keyword library
- rewrite my work experience for an AI Agent PM role
- check whether my Figma resume layout is recruiter-friendly
- QA my exported PDF before I submit it
```
# Job Application Copilot

An end-to-end Codex skill for role-specific job applications: reverse-engineer a JD, infer screening logic, build an ATS keyword library, rewrite resume content, guide Figma/PDF layout polish, and run final application QA.

## What It Does

- Reverse-engineers job descriptions into screening criteria
- Builds keyword libraries grouped by recruiter intent
- Maps candidate evidence to role requirements
- Rewrites resume summaries, experience bullets, project sections, and skill modules
- Gives Figma layout guidance for resume hierarchy, spacing, links, and PDF export
- Checks final resumes for ATS text extraction, visual layout, links, and role fit

## Best For

- AI Product Manager applications
- Agent / Agent Harness / AI Workflow roles
- Platform PM and developer ecosystem roles
- Role-specific resume rewrites
- Figma-designed one-page resumes

## Example Prompt

```text
Use $job-application-copilot to analyze this JD, reverse-engineer the screening criteria, and rewrite my resume into a role-specific one-page version.
```

## Install

Copy this folder into your Codex skills directory:

```bash
cp -R job-application-copilot ~/.codex/skills/
```

Then start a new Codex session and invoke:

```text
$job-application-copilot
```

## Structure

```text
job-application-copilot/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── figma-layout.md
    ├── jd-screening.md
    ├── qa-checklist.md
    └── resume-writing.md
```

## Notes

This skill is designed to preserve truthfulness: it should strengthen positioning and evidence, but should not invent metrics, ownership, tools, or work scope.
