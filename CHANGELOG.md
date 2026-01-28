# Changelog

All notable changes to this project will be documented in this file.

## [1.4.1] - 2026-01-28

### Added
- GitHub Actions CI workflow for automated plugin validation on push/PR

## [1.4.0] - 2026-01-28

### Added
- **clear-writing skill** - Transform any writing into clear, engaging prose
  - **Strunk's complete 18 rules** organized in two parts:
    - Rules 1-7: Elementary Rules of Usage (grammar, punctuation)
    - Rules 8-18: Elementary Principles of Composition (structure, voice)
  - **Comprehensive AI pattern elimination** based on Wikipedia's AI Cleanup patterns:
    - Regression to the mean detection
    - Puffery words and overused AI vocabulary
    - Empty -ing constructions and superficial analysis
    - Zombie nouns (nominalizations)
    - Rule-of-three abuse, negative parallelisms, elegant variation
    - Hedging language, didactic disclaimers, chatbot artifacts
    - Formatting artifacts (boldface, em dashes, emojis)
  - **Engagement techniques**:
    - BLUF (Bottom Line Up Front)
    - SCR/SCQA patterns for narrative flow
    - Five hook types for openings
    - 1-3-1 rhythm and sentence length audit
    - Scanner's Contract for informative headers
  - **Reference files** in `elements-of-style/` subdirectory:
    - `02-rules-of-usage.md` - Grammar and punctuation fundamentals
    - `03-principles-of-composition.md` - Structure and voice
    - `04-matters-of-form.md` - Formatting conventions
    - `05-words-commonly-misused.md` - Word choice guide (50+ entries)

### Purpose
Fills gap between marketing-focused copywriting skills and general writing needs. Comprehensive clarity and de-slopping tool for technical reports, documentation, emails, and general prose. Based on Strunk's Elements of Style and Wikipedia's Signs of AI Writing.

## [1.3.1] - 2026-01-15

### Fixed
- **conversion-auditor**: Clarified scoring math in audit output template
  - Added Score column to Behavioral Tactics table (6 tactics × 5 points = /30)
  - Changed output format to show RAW TOTAL (/230) before OVERALL SCORE (/100)
  - Added explicit calculation notes for each section
  - Removes ambiguity flagged in code review (sections summed to 230 but template showed /100)

## [1.3.0] - 2026-01-15

### Added
- **SEO/pSEO skill** (`/seo`) - Comprehensive programmatic SEO for auditing and architecting sites at scale (100k+ pages)
- **5 new SEO agents** for specialized tasks:
  - `seo-auditor` - Technical SEO audit of codebases (metadata, schemas, canonicals, OG tags, Core Web Vitals patterns)
  - `seo-architect` - Plan pSEO systems (data models, URL structures, template patterns, build strategies)
  - `schema-advisor` - Structured data specialist (JSON-LD templates for Article, FAQ, Product, LocalBusiness, etc.)
  - `content-strategist` - Content quality guardian (thin content detection, duplication, keyword cannibalization)
  - `internal-linking-planner` - Link architecture (hub-spoke structures, breadcrumbs, related pages, topical clusters)

### Features
- Framework-agnostic (works with Next.js, Astro, Nuxt, or any stack)
- Full lifecycle support (audit existing sites or architect new pSEO systems)
- All levels covered (code implementation to content strategy)
- Optional integrations (Ahrefs, Semrush, GSC when env vars available)
- Quality guardrails for preventing thin content, duplication, and cannibalization at scale

## [1.2.0] - 2026-01-15

### Added
- **3 new persuasion-focused skills** based on 5 foundational marketing books:
  - `product-validator` - Validate product-market positioning using Schwartz's awareness levels and market sophistication stages
  - `conversion-auditor` - Comprehensive landing page audit against 5 persuasion frameworks (Schwartz, Cialdini, Milligan, Warren, behavioral psychology)
  - `persuasion-copywriter` - Write high-converting copy using all 5 frameworks together
- **3 new agents** for specialized tasks:
  - `market-analyst` - Research-based market position analysis
  - `persuasion-auditor` - Score-based persuasion principle audit
  - `copy-enhancer` - Transform bland copy with NEW/EASY/SAFE/BIG + emotional hooks
- Research documentation in `research/` directory

### Frameworks Integrated
- **Breakthrough Advertising** (Eugene Schwartz) - 5 awareness levels, 5 market sophistication stages
- **Influence** (Robert Cialdini) - 7 principles of persuasion
- **Yes! 50 Ways** (Cialdini et al) - Loss framing, specificity, foot-in-door, behavioral tactics
- **Take Their Money** (Kyle Milligan) - NEW, EASY, SAFE, BIG framework
- **One Sentence Persuasion** (Blair Warren) - 5 emotional hooks

## [1.1.0] - 2025-01-09

### Added
- `landing-page-copywriter` skill for SaaS landing page copy using PAS (Problem-Agitate-Solution) framework

## [1.0.0] - 2025-01-07

### Added
- Initial release of misc-plugin
- `terminal-ui-designer` skill for creating distinctive terminal UIs
- `copywriting` skill for direct response copywriting framework
