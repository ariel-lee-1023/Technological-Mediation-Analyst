# Technological Mediation Analyst

An Agent Skills project for analyzing how technologies change perception, action, moral judgment, and meaningful life. Built from six books, it combines a shared reasoning core with one reference per source, loaded when the question needs it.

The analyst starts with a concrete encounter and follows what the technology makes visible, possible, expected, or difficult. It can help review a design, analyze an AI or automation case, study changing values, interpret technology-use interviews, or examine distraction from meaningful activity.

## Use

Open this repository as a project in a compatible host that discovers `.agents/skills/`. The skill name is `technological-mediation-analyst`. To add it to another project, copy the complete `.agents/skills/technological-mediation-analyst/` directory into that project's `.agents/skills/` directory. Keep the references beside `SKILL.md` so its relative links work.

Examples:

- “Use technological-mediation-analyst to review this AI writing assistant. What does it change about writing, learning, and authorship?”
- “Analyze how a workplace productivity score changes what workers and managers treat as good work.”
- “Would automating this task remove a burden or remove meaningful participation? Compare the alternatives.”
- “Help design an interview study about how people interpret privacy when using wearable cameras.”
- “Explain the difference between Ihde's multistability, Verbeek's moral mediation, and Kudina's hermeneutic lemniscate using this case.”

For better analysis, describe the specific feature, affected people, setting, present practice, and decision you need to make. The analyst can also work with incomplete information by identifying assumptions and distinguishing scenarios from observed effects.

## Contents

| File | Contribution |
|---|---|
| [SKILL.md](.agents/skills/technological-mediation-analyst/SKILL.md) | Shared reasoning and task-based loading triggers |
| [Ihde](.agents/skills/technological-mediation-analyst/references/reference-ihde-technology-lifeworld.md) | Human–technology relations, multistability, culture, decisional burden |
| [Verbeek: What Things Do](.agents/skills/technological-mediation-analyst/references/reference-verbeek-what-things-do.md) | Material mediation, scripts, engagement, durable design |
| [Rosenberger and Verbeek, editors](.agents/skills/technological-mediation-analyst/references/reference-rosenberger-verbeek-postphenomenological-investigations.md) | Sixteen chapter-attributed contributions, including critical disagreements |
| [Verbeek: Moralizing Technology](.agents/skills/technological-mediation-analyst/references/reference-verbeek-moralizing-technology.md) | Moral agency, subject formation, design anticipation and assessment |
| [Kudina](.agents/skills/technological-mediation-analyst/references/reference-kudina-moral-hermeneutics.md) | Value dynamism, appropriation, moral hermeneutics, IPA |
| [Roholt](.agents/skills/technological-mediation-analyst/references/reference-roholt-distracted-from-meaning.md) | Developed experience, focal practices, identity-work, smartphone distraction |

Each source reference includes a mental model, chapter-based frameworks, one reconstructed worked example, decision rules, and takeaways. The always-loaded core stays compact; the full books are not included.

## What the synthesis preserves

Material agency is distinguished from consciousness and blameworthiness. Multistability does not become a claim that users can freely reinterpret institutional constraints. Technological acceptance does not become moral justification. Convenience and meaningful engagement are evaluated in concrete practices, including effects on other participants.

The collection's contributors retain their own positions. Feenberg's institutional criticism, Borgmann's normative challenge, and Verbeek's criticism of equating effort with meaning are kept visible. Applications to current AI systems are identified as extensions of these frameworks, with present technical facts requiring separate evidence.

## Sources and validation

Created with [Books-to-Skill-Refs](https://github.com/ariel-lee-1023/Books-to-Skill-Refs) at study depth. The build uses the six supplied Markdown books and repairs substantial extraction loss in *Moralizing Technology* against its matching local PDF.

See [the source and coverage ledger](docs/source-and-coverage-ledger.md) for bibliographic details, extraction limitations, retained and compressed material, and maintenance guidance. See [the evaluation cases](docs/evaluation.md) for editorial checks and their limits. Machine validation results are recorded in [validation.json](docs/validation.json).

The reference texts are original analytical syntheses. Source authors and publishers retain rights in the underlying works; no license to those works is conveyed by this repository.
