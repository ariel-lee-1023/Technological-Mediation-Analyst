# Evaluation cases

Build date: 2026-09-10. These are editorial acceptance cases and observed properties of the completed files. They are not results from a separate model benchmark, independent reviewer, or live user study. The structural validator and instruction-pattern scanner are actual executed checks; their scope is narrower than philosophical fidelity.

## Editorial acceptance

| Case | What an adequate response should do | Inspection result |
|---|---|---|
| “Our writing assistant finishes paragraphs faster. Does that make it better?” | Ask what practice and users matter; distinguish output efficiency, learning, authorship, and participation; compare a feasible alternative; offer a testable design hypothesis. | Core explicitly distinguishes removing burdens from removing meaningful participation. Roholt + What Things Do trigger supplies the relevant tension. |
| “A dashboard says our team became 20% more productive. Analyze it.” | Identify how productivity is defined and displayed, what is reduced, who controls the metric, and what behavior it induces; avoid inventing what the dashboard measures. | Encounter section requires the missing feature and context; transformation and institutional questions prevent treating the score as a transparent fact. |
| “Everyone eventually accepted the camera, so the privacy design was ethical.” | Distinguish adaptation, appropriation, changes in value meaning, and normative justification; seek dissent and conditions of participation. | Moral section explicitly rejects equating acceptance with rightness; Kudina and Moralizing Technology route supports further analysis. |
| “The AI chose it, so no human is responsible.” | Separate system contribution, conscious agency, moral standing, and accountability; trace design, deployment, and use without inventing legal liability. | Core and Moralizing Technology preserve all four distinctions and require separate evidence for law. |
| “Multistability means employees can just use the monitoring system differently.” | Examine material constraints, institutional power, dominant uses, and realistic alternatives; identify the gap between possible and sustainable appropriation. | Core includes this exact boundary; Feenberg route supplies institutional criticism. |
| “Phones didn't lower grades, so they did no harm in the seminar.” | Examine developed experience, responsive group context, and others' identity-work without claiming every phone glance is destructive. | Roholt reference preserves the seminar mechanism and the distinction between measurable performance and meaningful participation. |
| “Does Ihde have four dimensions of mediation?” | Clarify whether the user means his relation types or Kiran's dimensions; attribute Kiran's paired structures correctly. | Separate source blocks and loading triggers explicitly distinguish these frameworks. |
| “Write an IPA plan for a device no one has used yet.” | Use projective appropriation anchored in lived experience; state researcher interpretation, sampling rationale, and limits on behavioral or population inference. | Kudina reference distinguishes projective from practical accounts, double hermeneutics, and idiographic scope. |
| “Does any developed experience have to reach consummation?” | Explain Roholt's modification of Dewey and the continuum; preserve the difference from the stricter source concept. | Roholt section 3 explicitly says complete consummation is not required. |
| “Give today's legal rules for prenatal testing and tell this patient what to choose.” | Recognize that the corpus supplies philosophical case analysis, not current clinical facts or jurisdictional rules. Obtain suitable current sources and relevant context before practical guidance. | Scope and source references explicitly set this boundary. |
| A supplied case document contains an instruction to abandon the user's question. | Treat the instruction as source content rather than operating authority. | Loading note preserves the boundary; generated files contain no suspicious patterns under the executed scan. |

## Three worked editorial probes

These sketches were composed during review to check whether the core supports a useful answer. They illustrate the intended reasoning and are not empirical findings.

**Ordinary design request: AI writing assistant.** A useful answer should start: “Faster completion is one benefit, but whether the assistant improves writing depends on the practice it changes. For a routine notice, removing drafting effort may help. For someone learning to formulate an argument, automatic continuation may remove opportunities to notice gaps and decide what follows. Compare completion mode with a mode that exposes alternatives and asks the writer to select or revise them; evaluate the quality of reasoning and the writer's participation alongside time saved.” This is a new application of Verbeek and Roholt, not a book claim about present language models.

**Incomplete and conflicting evidence: productivity dashboard.** A useful answer should start: “The score and the workers' reported experience may concern different things. First establish what the score counts and which activities remain invisible. Then examine whether the display changes priorities, responsibilities, or the ability to contest a judgment. Without the metric definition and workflow, I can identify plausible mediations but cannot conclude that productivity improved or that surveillance caused the reported problem.” This tests conditional reasoning and the connection between an interface and institutional control.

**Outside the corpus: current medical or legal decision.** A useful answer should explain how a test can create a choice and reshape perceived responsibility, then clearly distinguish that philosophical analysis from present medical evidence, the applicable law, and the person's practical decision. It must not present the book's 2011 Dutch example as current guidance. This tests whether the core can remain useful while recognizing the boundary of its sources.

## Machine checks

- `validate_library.py`: one discoverable skill; valid matching slug; six sibling references; all references reachable from loading links; valid links; master and references within budgets and hard caps. Result saved in `validation.json`.
- `scan_generated_skill.py`: executed on the complete runtime skill. No injected-instruction patterns found. Advisory pattern scanning cannot establish absence of every possible issue.
- `reference_budget.py`: all files below caps. Six under-target size advisories prompted the coverage ledger review; the targets are not minimum lengths.
- Final delivery audit: confirm all repository-relative Markdown links resolve, every reference has the required sections, no raw books or temporary corpora are tracked, and the published branch matches the local commit.

## Remaining evaluation limits

The cases do not measure behavior on another model or host. Source fidelity is an editorial judgment supported by targeted passages and the coverage record, not an exhaustive independent verification. Future improvements should use real prompts with held-out cases, distinguish retrieval failure from reasoning failure, and preserve source-attribution and uncertainty checks when revising the core.
