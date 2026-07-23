# QA Skill for Claude Code

The complete QA skill for Claude Code — turns Claude into an expert QA engineer
that picks the right test type, writes reliable Playwright, Cypress, and pytest
tests, eliminates flaky tests, enforces coverage, and wires up CI.

## Install

Copy `SKILL.md` into your project's `.claude/skills/claude-code-qa/` directory,
or install it as a Claude Code skill package.

## What it covers

- Detecting and respecting the existing test framework in a repo
- Reliable, deterministic Playwright/Cypress/pytest tests (stable locators, no
  fixed sleeps, no shared state between tests)
- Eliminating flaky tests at the source
- Meaningful coverage (behavior-focused assertions, not just line counts)
- API testing (status codes, schema, auth, validation, pagination)
- Wiring tests into CI

See [SKILL.md](./SKILL.md) for the full skill definition.

## Attribution

Originally authored by **qaskills**, distributed under the MIT license (see
[LICENSE](./LICENSE)). Mirrored here for personal use and sharing.
