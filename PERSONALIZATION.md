# PersonalStudio customization notes

This fork adapts Microsoft's ResearchStudio-Idea workflows for personal
projects rather than scientific research.

## Adapted skills

- `project-research`: find evidence about tools, models, workflows, products,
  documentation, and existing approaches.
- `differentiation-check`: compare a proposed project against existing work and
  produce a practical positioning delta. This is not legal IP advice.
- `project-brief`: turn a rough direction into one scoped, testable project
  brief with risks, resources, and a smallest useful experiment.

## Design rule

The fork preserves the upstream evidence-first and validation-oriented behavior.
Only the domain language and expected deliverables are changed in this first
pass. Connector and rendering changes should be made separately and tested
against real personal-project inputs.

## Installation policy

This repository is the editable source of truth. Do not install globally until
the adapted skills have been tested locally. When ready, install or link the
skill directories into both `~/.claude/skills/` and `~/.codex/skills/`.
