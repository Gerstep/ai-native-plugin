# AI-Native Transformation Plan — Claude Code Plugin

Interactive 90-day AI transformation plan builder for organizations. Part of the [AI-Native Organizations Playbook](https://github.com/sgershuni/ai-native-playbook).

## What it does

Guides you through a structured 3-week diagnostic sprint:

- **Week 1**: Company assessment, process audit, top-3 initiative selection, AI Champions team
- **Week 2**: 6-layer architecture diagnostic, data mapping, eval strategy, first SKILL.md
- **Week 3**: Initiative roadmap, 90-day plan with ops/R&D split, metrics, Demo Day prep

Outputs:
- `~/aim-sprint/week1.md`, `week2.md`, `week3.md` — structured worksheets
- `~/aim-sprint/dashboard.html` — interactive Stripe-style HTML dashboard with 4 tabs (Overview, Initiatives, 90-Day Plan, Metrics)

## Install

### Add the marketplace

```
/plugin marketplace add sgershuni/ai-native-plugin
```

### Install the plugin

```
/plugin install ai-native@ai-native-marketplace
```

### Reload

```
/reload-plugins
```

## Usage

```
/ai-native:ai-native
```

Or just tell Claude: "start the 90-day transformation plan" / "начни план трансформации"

## Requirements

- Claude Code 1.0.33+
- Works on macOS, Linux, Windows

## Optional

Complete the diagnostic quiz at [codos.ai/quiz](https://codos.ai/quiz) before starting Week 1 for faster, more precise results.

## License

MIT
