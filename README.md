# doug-plugins

A custom Claude Code plugins marketplace featuring productivity and development tools.

## Installation

Add this marketplace to Claude Code:

```bash
claude plugin marketplace add https://github.com/sofrono44/doug-plugins
```

Then install any plugin:

```bash
claude plugin install <plugin-name>@doug-plugins
```

## Plugins

### spec-to-ralph

Bridge GitHub Spec Kit to Ralph Wiggum autonomous loops. Convert your spec-driven development artifacts (constitution, spec, plan, tasks) into optimized prompts for overnight autonomous coding.

```bash
claude plugin install spec-to-ralph@doug-plugins
```

**Commands:**
- `/status` - Check project readiness for Ralph conversion
- `/generate` - Generate optimized PROMPT.md from Spec Kit artifacts
- `/start` - Generate prompt AND start Ralph loop in one command

---

### question-storm

Generate rapid bursts of questions to reframe problems, uncover assumptions, and find new angles using the Question Storming framework.

```bash
claude plugin install question-storm@doug-plugins
```

**Skills:**
- `question-storming-brainstorm` - Quick question generation across multiple question types
- `question-storming-workshop` - Guided workshop format for deeper exploration

---

### scamper

Generate divergent ideas using the SCAMPER framework (Substitute, Combine, Adapt, Modify, Put to other uses, Eliminate, Reverse). Ideal for brainstorming product variations, features, and strategies.

```bash
claude plugin install scamper@doug-plugins
```

**Skills:**
- `scamper-brainstorm` - Rapid idea generation across all SCAMPER dimensions
- `scamper-workshop` - Structured workshop for thorough ideation

## License

MIT
