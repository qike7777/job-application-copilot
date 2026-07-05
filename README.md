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
