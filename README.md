# misc-plugin

Miscellaneous skills for Claude Code - terminal UI design, copywriting & persuasion frameworks.

## Installation

```bash
/plugin install misc
```

Or add the marketplace first:
```bash
/plugins marketplace add iamladi/cautious-computing-machine
/plugin install misc
```

## Skills

### Persuasion Framework Skills

Based on 5 foundational books on selling and persuasion:
- **Breakthrough Advertising** (Eugene Schwartz)
- **Influence** (Robert Cialdini)
- **Yes! 50 Scientifically Proven Ways** (Cialdini et al)
- **Take Their Money** (Kyle Milligan)
- **One Sentence Persuasion** (Blair Warren)

#### product-validator

Validate product-market positioning using Schwartz's framework.

**Use when**: Launching a product, pivoting positioning, or unsure how to communicate value.

**What it does**:
1. Diagnoses audience awareness level (Unaware → Most Aware)
2. Diagnoses market sophistication stage (Direct Claims → Identity)
3. Recommends positioning strategy based on the matrix
4. Generates example headlines and copy approach

#### conversion-auditor

Comprehensive landing page audit against all 5 persuasion frameworks.

**Use when**: Landing page isn't converting or you want to optimize.

**Audit sections**:
- Schwartz alignment (awareness/sophistication match)
- Cialdini's 7 principles scorecard
- NEW/EASY/SAFE/BIG presence check
- Warren's emotional hooks analysis
- Behavioral tactics (loss framing, specificity, etc.)

**Output**: Scorecard with priority fixes and rewrites.

#### persuasion-copywriter

Write high-converting copy using all 5 frameworks together.

**Use when**: Writing landing pages, marketing copy, or sales content.

**Process**:
1. Position on Schwartz matrix
2. Select Cialdini principles to weave in
3. Trigger NEW/EASY/SAFE/BIG
4. Connect with emotional hooks
5. Apply behavioral tactics

### Classic Copywriting Skills

#### landing-page-copywriter

SaaS landing page copy using PAS (Problem-Agitate-Solution) framework.

#### copywriting

Direct response copywriting framework.

**THE SLIDE** (7-step formula):
1. Headline (80% of work)
2. Problem (quantify it)
3. Agitate (make vivid)
4. Credibility
5. Solution (transform)
6. Proof (specific)
7. CTA (benefit)

**SO WHAT? CHAIN**: Feature → Functional → Financial → Emotional

### Design Skills

#### terminal-ui-designer

Create distinctive, production-grade terminal user interfaces.

Covers: Box drawing, colors, typography, layout, animation, data display.

## Agents

### market-analyst

Research-based market position analysis using web search.

**Tools**: Read, WebFetch, WebSearch

### persuasion-auditor

Score-based audit against Cialdini's 7 principles, NEW/EASY/SAFE/BIG, and emotional hooks.

**Tools**: Read, WebFetch

### copy-enhancer

Transform bland copy with psychological triggers.

**Tools**: Read

## Framework Quick Reference

### Schwartz: Awareness Levels

| Level | Name | Copy Approach |
|-------|------|---------------|
| 1 | Unaware | Educate, long copy, no product |
| 2 | Problem Aware | Amplify pain, hint at solutions |
| 3 | Solution Aware | Present clearly, differentiate |
| 4 | Product Aware | Overcome objections, show proof |
| 5 | Most Aware | Minimal copy, urgency, CTA |

### Cialdini: 7 Principles

1. **Reciprocity** - Give value before asking
2. **Commitment** - Small yes before big yes
3. **Social Proof** - Specific, from similar users
4. **Authority** - Third-party validation
5. **Liking** - Be conversational, relatable
6. **Scarcity** - Authentic limits only
7. **Unity** - Shared identity language

### Milligan: NEW, EASY, SAFE, BIG

- **NEW**: First, revolutionary, finally
- **EASY**: 3 minutes, no-config, one-click
- **SAFE**: Guaranteed, trusted by, cancel anytime
- **BIG**: 74% improvement, 10x faster, $50k saved

### Warren: 5 Emotional Hooks

1. **Encourage dreams** - "Finally achieve..."
2. **Justify failures** - "Not your fault..."
3. **Allay fears** - "No risk, cancel anytime"
4. **Confirm suspicions** - "You were right..."
5. **Throw rocks** - "Unlike [enemy]..."

## License

MIT
