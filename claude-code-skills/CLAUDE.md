# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a knowledge base of software development lifecycle skills for non-technical founders building SaaS applications with AI tools (Lovable, Replit, Claude Code, Cursor). It contains markdown guides, not executable code.

## Structure

Eight numbered skill directories following the development lifecycle:

1. **scope** - Turn ideas into AI-ready specs (Quick Feature Specs, Full Project Scopes)
2. **design** - UX/UI patterns for SaaS (Laws of UX, component patterns)
3. **build** - AI-assisted development workflows and tool selection
4. **secure** - Security checklists and OWASP vulnerability guidance
5. **performance** - Speed optimization prompts and checks
6. **test** - Testing scenarios, edge cases, intentional bug hunting
7. **debug** - Systematic debugging workflows and error interpretation
8. **monitor** - Production health monitoring and incident response

Each directory contains:
- `SKILL.md` - Main overview and workflow (always under 500 lines)
- Supporting `[TOPIC].md` files - Detailed patterns and examples

## File Conventions

- All files use ALL CAPS with hyphens: `DEBUG-PROMPTS.md`, not `debug_prompts.md`
- SKILL.md files use YAML frontmatter with `name` and `description` fields
- Skills are designed for progressive disclosure: SKILL.md first, then supporting files

## Design Philosophy

These skills assume Claude's intelligence - they focus on:
- Non-technical founder perspective and common mistakes
- Tool selection criteria (when to use Lovable vs Claude Code vs Replit)
- Actionable checklists and "Tell AI:" copy-paste prompts
- What's out of scope (preventing premature optimization)

Content should be concise, actionable, and avoid explaining concepts Claude already knows.
