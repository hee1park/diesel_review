# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **literature review workspace** for diesel degradation research. It is not a software project — there are no build, test, or lint commands.

## Directory Structure

- `literature-pdfs/` — Store PDF papers related to diesel degradation here before analysis.
- `summary/` — Output directory for generated summaries and reports.

## Available Skill

A custom PubMed skill is installed at `.claude/skills/topic-explorer-pubmed/`. Invoke it with:

```
/topic-explorer-pubmed <research topic>
/paper-summary <file path>
```

## Workflow

For a systematic review on a diesel degradation topic:
1. Optionally place relevant PDFs in `literature-pdfs/` for local analysis.
2. Run `/topic-explorer-pubmed <topic>` to search PubMed and generate an HTML report.
3. Review the report in `summary/`.
