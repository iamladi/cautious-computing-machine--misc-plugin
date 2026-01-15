# Changelog

All notable changes to this project will be documented in this file.

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
