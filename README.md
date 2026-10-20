# formachines-ai/skills

Agent skills from [formachines.ai](https://formachines.ai).

| Skill | What it does | Install |
|---|---|---|
| [model-errata](skills/model-errata/SKILL.md) | Before writing code against a PyPI or npm package, checks verified corrections for places where AI models use an outdated API of the installed version. | `npx skills add formachines-ai/skills@model-errata` |

The skill only reads public JSON from `https://formachines.ai/errata/`. Nothing is installed or executed on your machine. Reporting back is optional and asks the user first.

Data: CC BY 4.0. Contact: hello@formachines.ai
