<p align="center">
  <img src="https://img.shields.io/github/license/LeoLin990405/claude-lenny-skills?style=flat-square" alt="License">
  <img src="https://img.shields.io/github/stars/LeoLin990405/claude-lenny-skills?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/issues/LeoLin990405/claude-lenny-skills?style=flat-square" alt="Issues">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-8A2BE2?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code Skill">
</p>

<h1 align="center">Claude Lenny Skills</h1>

<p align="center">
  <strong>Complete Product Management Toolkit for Claude Code</strong>
  <br>
  <em>88 actionable PM skills distilled from Lenny's Podcast, organized into workflow modules with executable templates</em>
</p>

<p align="center">
  <a href="#features">Features</a> &middot;
  <a href="#quick-start">Quick Start</a> &middot;
  <a href="#modules">Modules</a> &middot;
  <a href="#templates">Templates</a> &middot;
  <a href="#playbooks">Playbooks</a> &middot;
  <a href="#contributing">Contributing</a>
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| **88 PM Skills** | Actionable frameworks covering the full product management lifecycle |
| **8 Workflow Modules** | Organized by phase: discovery, strategy, execution, growth, analytics, communication, team, leadership |
| **10 Executable Templates** | Ready-to-use PRDs, OKRs, interview scripts, launch checklists, and more |
| **9 Role-Based Playbooks** | Guided workflow sequences for founders, PMs, managers, growth leaders, and executives |
| **Auto-Routing** | Claude Code automatically selects the right module based on your request |
| **Lenny's Podcast Wisdom** | Distilled from 86+ episodes with top product leaders |

---

## Quick Start

### Installation

```bash
cd ~/.claude/skills
git clone https://github.com/LeoLin990405/claude-lenny-skills.git
```

### Usage

```bash
# The toolkit auto-routes based on your request:
"Help me write a PRD"              # -> pm-strategy + prd-template
"Prepare user interviews"          # -> pm-discovery + interview-script
"Set OKRs for Q2"                  # -> pm-strategy + okr-template
"Run a retro"                      # -> pm-execution + retro-template
"Build a financial model"          # -> pm-analytics + financial-model-spec

# Or access modules directly:
"Use the PM growth module"         # -> pm-growth
"Show me the founder playbook"     # -> pm-playbooks
```

---

## Modules

| # | Module | Skills | What It Covers |
|---|--------|--------|----------------|
| 1 | [pm-discovery](skills/pm-discovery/SKILL.md) | 7 | Problem definition, user research, competitive analysis, JTBD |
| 2 | [pm-strategy](skills/pm-strategy/SKILL.md) | 8 | Vision, north star, OKRs, roadmap, PRD, prioritization |
| 3 | [pm-execution](skills/pm-execution/SKILL.md) | 10 | Shipping, timelines, decisions, meetings, retros |
| 4 | [pm-growth](skills/pm-growth/SKILL.md) | 8 | PMF, growth loops, pricing, retention, experiments |
| 5 | [pm-analytics](skills/pm-analytics/SKILL.md) | 8 | Metrics, financial modeling, data-driven decisions, platform |
| 6 | [pm-communication](skills/pm-communication/SKILL.md) | 9 | Presentations, writing, stakeholders, brand, content |
| 7 | [pm-team](skills/pm-team/SKILL.md) | 22 | Hiring, 1:1s, culture, delegation, sales team |
| 8 | [pm-leadership](skills/pm-leadership/SKILL.md) | 16 | Coaching, product taste, AI strategy, org design, career |

---

## Templates

Ready-to-use templates for common PM tasks:

| Template | Use Case |
|----------|----------|
| [prd-template](templates/prd-template.md) | Write a product requirements document |
| [okr-template](templates/okr-template.md) | Set quarterly OKRs |
| [user-interview-script](templates/user-interview-script.md) | Conduct user research interviews |
| [competitive-analysis](templates/competitive-analysis.md) | Analyze competitive landscape |
| [launch-checklist](templates/launch-checklist.md) | Plan and execute a product launch |
| [retro-template](templates/retro-template.md) | Run retrospectives and post-mortems |
| [metrics-dashboard](templates/metrics-dashboard.md) | Design a metrics dashboard |
| [one-on-one-template](templates/one-on-one-template.md) | Run effective 1:1 meetings |
| [decision-doc-template](templates/decision-doc-template.md) | Make and document decisions |
| [financial-model-spec](templates/financial-model-spec.md) | Build financial models and unit economics |

---

## Playbooks

Role-based workflow sequences -- see [pm-playbooks](skills/pm-playbooks/SKILL.md):

| Playbook | Workflow Sequence |
|----------|-------------------|
| **Startup Founder** | discovery -> strategy -> execution -> growth -> team -> leadership |
| **Product Manager** | discovery -> strategy -> execution -> communication -> leadership |
| **First-Time Manager** | team -> communication -> execution -> leadership |
| **Growth Leader** | growth -> discovery -> analytics -> communication -> leadership |
| **Engineering Manager** | execution -> analytics -> team -> communication |
| **Sales Leader** | team -> communication -> strategy -> growth |
| **AI Builder** | leadership -> strategy -> discovery -> growth -> execution |
| **Executive** | communication -> leadership -> strategy -> execution |
| **Career Growth** | leadership -> communication -> team |

---

## Project Structure

```
claude-lenny-skills/
├── SKILL.md                          # Root skill index for Claude Code
├── README.md                         # This file
├── LICENSE                           # MIT License
├── CONTRIBUTING.md                   # Contribution guidelines
├── CHANGELOG.md                      # Release history
├── .github/
│   ├── workflows/
│   │   └── claude-review.yml         # Claude Code PR review action
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml            # Bug report template
│   │   ├── feature_request.yml       # Feature request template
│   │   └── config.yml                # Issue template chooser config
│   └── PULL_REQUEST_TEMPLATE.md      # PR template
└── skills/
    ├── lenny-advanced/SKILL.md       # Product taste, systems thinking
    ├── lenny-career/SKILL.md         # Ideation, productivity
    ├── lenny-communication/SKILL.md  # Presentations, writing
    ├── lenny-decision/SKILL.md       # Decision processes, trade-offs
    ├── lenny-design/SKILL.md         # Design systems, reviews
    ├── lenny-execution/SKILL.md      # Delivery, timelines
    ├── lenny-growth/SKILL.md         # PMF, growth loops, pricing
    ├── lenny-hiring/SKILL.md         # JDs, interviews, onboarding
    ├── lenny-marketing/SKILL.md      # Positioning, storytelling
    ├── lenny-playbooks/SKILL.md      # Role-based combinations
    ├── lenny-research/SKILL.md       # User research, interviews
    ├── lenny-sales/SKILL.md          # Founder sales, enterprise
    ├── lenny-skills/SKILL.md         # Master index of 86 PM skills
    ├── lenny-startup/SKILL.md        # Team rituals, fundraising
    ├── lenny-strategy/SKILL.md       # Vision, roadmaps, OKRs
    └── lenny-technology/SKILL.md     # AI strategy, LLMs, tech debt
```

---

## Contributing

Contributions are welcome! Please read the [Contributing Guide](CONTRIBUTING.md) for details on how to submit skills, templates, and improvements.

---

## Acknowledgements

- **[Lenny Rachitsky](https://www.lennyspodcast.com/)** -- For the incredible podcast and PM wisdom that forms the foundation of this toolkit.

## Contributors

- **Leo** ([@LeoLin990405](https://github.com/LeoLin990405)) -- Project Lead
- **Claude** (Anthropic Claude) -- Content Generation

## License

This project is licensed under the MIT License -- see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <sub>Built with collaboration between human and AI</sub>
</p>
