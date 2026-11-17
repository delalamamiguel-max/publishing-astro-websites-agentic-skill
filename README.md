# Publishing Astro Websites - Claude Code Agentic Skill

A comprehensive Claude Code skill for building and deploying static websites with the Astro framework.

## Overview

This skill provides guidance for Astro static site generation (SSG), covering:

- **Content Collections** - Legacy patterns, Content Layer API (Astro 5.0), Custom Loaders
- **Syntax Highlighting** - Shiki configuration, Transformers, Expressive Code
- **Diagram Integration** - Mermaid, PlantUML, dark mode theming strategies
- **Client-Side Search** - Pagefind (granular controls, weighting), Fuse.js comparison
- **Versioned Documentation** - Starlight framework, multi-version patterns
- **Internationalization** - i18n routing, fallback logic for missing translations
- **Common Patterns** - Pagination, tag archives, RSS feeds, forms, JSON-LD, dark mode
- **Performance** - Prefetching, Critical CSS (astro-critters), partial hydration
- **Testing** - Vitest component testing, Playwright E2E, link checking
- **Deployment** - Firebase, Netlify, Vercel, GitHub Pages, GCS + Cloud CDN

## Installation

Clone this repository into your Claude Code skills directory:

```bash
cd ~/.claude/skills
git clone https://github.com/SpillwaveSolutions/publishing-astro-websites-agentic-skill.git
```

Or add as a Git submodule to your existing skills:

```bash
git submodule add https://github.com/SpillwaveSolutions/publishing-astro-websites-agentic-skill.git
```

## Usage

Once installed, Claude Code will automatically use this skill when you ask about:

- "Create an Astro site"
- "Deploy Astro to Firebase"
- "Set up content collections"
- "Add Mermaid diagrams to Astro"
- "Configure Astro i18n"
- "Build a static blog"
- "Astro markdown setup"

## Structure

```
publishing-astro-websites-agentic-skill/
├── .claude-plugin/
│   └── marketplace.json
├── publishing-astro-websites/
│   ├── SKILL.md
│   └── references/
│       ├── deployment-platforms.md
│       └── markdown-deep-dive.md
├── .gitignore
└── README.md
```

## Requirements

- Claude Code CLI
- Node.js 18+ (for Astro projects)

## License

MIT

## Author

Richard Hightower - [SpillwaveSolutions](https://github.com/SpillwaveSolutions)


---

# Owned checkout guide

## Purpose and status

This is the owned reference fork of [SpillwaveSolutions/publishing-astro-websites-agentic-skill](https://github.com/SpillwaveSolutions/publishing-astro-websites-agentic-skill), authored by Richard Hightower. It supplies Astro website guidance rather than a deployable website. The upstream README, examples, author credit and MIT statement above are preserved unchanged.

## Repository map

- `publishing-astro-websites/SKILL.md`: the main Astro workflow and examples.
- `publishing-astro-websites/references/deployment-platforms.md`: provider-specific publishing reference.
- `publishing-astro-websites/references/markdown-deep-dive.md`: Markdown/content guidance.
- `.claude-plugin/marketplace.json`: local marketplace metadata and skill registration.

## Architecture and integrations

The package consists of instructions and reference documents, with no root application manifest, backend or database. It describes content collections, islands, search, diagrams, i18n, testing and several hosting providers. Those examples become operations in a separate target website only when deliberately implemented and invoked.

## Setup and environments

Installation copies/clones the skill into an agent's directory or adds a submodule; either modifies that environment/repository. The upstream Node 18+ note is historical guidance, not a universal requirement for current Astro versions. Determine the target project's actual package engine and framework version before using an example. Host credentials belong to the target's approved environment, not this public reference fork.

## Safe commands

For this documentation review use `git status --short`, `git diff -- README.md` and `git diff --check`. Upstream install, update, build, test and deployment examples above are retained reference material, not commands executed or authorized by this README rollout.

Do not execute scaffold, install, Firebase/GCP, Vercel, Netlify or other publishing commands during documentation review. No agent skill was installed or invoked here.

## Testing and validation

There is no runnable test suite or package test command in this checkout. Vitest, Playwright and link-check examples describe target-site validation, not checks that this library has passed. Review examples against the target's locked framework/tool versions before implementation.

## Deployment and rollback

The library has no website artifact to deploy. Updating an installed copy and deploying a target website are separate actions. Retain the previous approved skill revision and target-project state before any update. A rollback of skill files does not undo a site deployment, cloud resource creation or billing change.

## Risks and guardrails

Preserve upstream attribution and examples. The README states MIT, but no standalone LICENSE file is tracked at this root; this guide does not invent additional license terms or third-party asset permissions. Provider recipes may incur cost or change accounts. Keep credentials and client material out of the fork, and never treat an installation recipe as authorization to deploy.

## Related documentation

- [Main skill reference](publishing-astro-websites/SKILL.md)
- [Deployment reference](publishing-astro-websites/references/deployment-platforms.md)
- [Markdown reference](publishing-astro-websites/references/markdown-deep-dive.md)
- [Marketplace metadata](.claude-plugin/marketplace.json)

This owned-checkout guide was checked statically only. No installation, application build/test, agent invocation, provider call, target acquisition, database operation or deployment was performed. Installed state, upstream freshness, external URLs and runtime behavior remain unverified.
