# Source and coverage ledger

This is maintainer documentation, separate from the runtime references. It records provenance, editorial selection, and limits; the host's topic triggers load only the six source references.

## Build decisions

- Requested project title: **Technological Mediation Analyst**. Discoverable skill slug: `technological-mediation-analyst`.
- Destination: the initially empty `ariel-lee-1023/Technological-Mediation-Analyst-` repository. The default Books-to-Skill-Refs project architecture therefore applies.
- Depth: **study**, selected for an analyst that applies concepts and reasons across authors. Every reference has one reconstructed source example and decision rules.
- Inputs: six user-supplied Markdown books. *Moralizing Technology* additionally uses the matching PDF found beside its Markdown conversion, to repair substantial missing prose.
- Reading: table-of-contents and heading probes followed by bounded, cleaned passages. The entire combined corpus was not loaded as one reading. Original extracted text was left intact during analysis.
- Authorial terminology was retained where useful; prose was synthesized. Source instructions, promotional text, rights notices, and document furniture were not adopted as operating instructions.
- Human-facing provenance and evaluation records are kept in `fidelity-ledger/`, separate from the canonical `SKILL.md` and its trigger-loaded `references/`.

## Bibliography and extraction quality

| Source | Edition used | Source coverage and quality |
|---|---|---|
| Don Ihde, *Technology and the Lifeworld: From Garden to Earth* | Indiana University Press, 1990 | Eight top-level units including the epilogue. Markdown has OCR losses, fragmented words, and spurious table markup. Principal concepts are identifiable and corroborated where appropriate by the other supplied books; uncertain historical particulars were excluded from the operational rules. |
| Peter-Paul Verbeek, *What Things Do: Philosophical Reflections on Technology, Agency, and Design* | Pennsylvania State University Press, 2005; translated by Robert P. Crease; Dutch original 2000 | Seven numbered chapters. Readable chapter structure with running headers and conversion artifacts. The work's critical treatment of earlier authors is retained as Verbeek's interpretation. |
| Robert Rosenberger and Peter-Paul Verbeek, eds., *Postphenomenological Investigations: Essays on Human–Technology Relations* | Lexington Books, 2015 | Sixteen chapters across a field guide, theories, cases, and critical interlocutors. All sixteen have attributed structural blocks; secondary citations are not represented as independently consulted books. |
| Peter-Paul Verbeek, *Moralizing Technology: Understanding and Designing the Morality of Things* | University of Chicago Press, 2011 | Eight chapters. Markdown frequently retains only small pieces of each page. Re-extraction of the corresponding 195-page PDF restored extensive prose, including design and assessment procedures. |
| Olya Kudina, *Moral Hermeneutics and Technology: Making Moral Sense through Human-Technology-World Relations* | Lexington Books, 2024 | Five numbered chapters plus introduction and design/governance conclusion. These substantial unnumbered units are included without inflating the top-level budget count. |
| Tiger C. Roholt, *Distracted from Meaning: A Philosophy of Smartphones* | Bloomsbury Academic, 2023 | Seven numbered chapters. Subsection numbers survive better than some chapter headings. Spacing and ligature errors were normalized in synthesis. |

The extractor's script-density estimates were approximately 779,828 tokens for the original six-file batch. Replacing the damaged *Moralizing Technology* text estimate of 27,369 with the PDF estimate of 126,275 yields approximately **878,734 tokens** of source material. These are heuristic corpus-size estimates, not metered model usage or a claim that all those tokens were read. Estimated Markdown page counts were not used as edition pagination.

Source basenames and SHA-256 hashes are recorded in [source-manifest.json](source-manifest.json), without publishing private absolute paths. No book files, extracted corpus, page images, or source attachments are included in the repository.

## Coverage inventory

This inventory records the conceptual and structural items selected through the source probes. The references compress adjacent or related material; a block can preserve several terms. Every listed item below is either retained or explicitly bounded in the final column. “Retained” means a usable conceptual treatment, not exhaustive coverage of the source's arguments.

| Source structure | Retained items | Compression or exclusions and reason |
|---|---|---|
| Ihde 1–4 | Garden thought experiment; material culture; intentionality; lifeworld; non-neutrality; microperception/macroperception; Heidegger's hammer; Husserl's Galileo; Merleau-Ponty's feather; time and space perception; artifacts/technofacts | Foundational chapters grouped. Navigation history and cultural anecdotes compressed; uncertain OCR details and historical quantitative claims excluded. |
| Ihde 5 | Embodiment; hermeneutic relations; alterity; background; transparency; magnification/amplification–reduction; contrast of transformations; horizontal/vertical trajectories; horizonal phenomena; enclosure and totalization | Closely related examples merged. Full diagrams and the extended spaceship scenario omitted; conceptual distinctions retained. |
| Ihde 6 | Transfer; cultural instruments; dependence and failed transfer; control; multistability; variational analysis; varieties of technological experience; technique and culinary practices | Numerous transfer narratives reduced to conditions of use, infrastructure, and cultural embedding. No current country-level conclusions derived. |
| Ihde 7–8 | Pluriculturality; decisional burden; materializing the conceptual; oscillatory phenomena; conservation/stewardship; demythologizing/demasculinizing technoscience; Galileo in the Kitchen | Historical events and science-budget tables omitted as unnecessary and dated. The epilogue's evaluative commitments remain explicit. |
| What Things Do 1–2 and introduction | Jaspers's apparatus/mass existence and neutrality; revealing/enframing/standing-reserve; readiness-to-hand/presence-at-hand; thinging; Orphic temptation | Philosophical genealogy compressed rather than reproducing lengthy exegesis. Jaspers's and Heidegger's views appear through Verbeek's critical reconstruction. |
| What Things Do 3–4 | Empirical turn; postphenomenology; technological intentionality; intermediary/mediator; multistability; experience/praxis; material hermeneutics; co-constitution; amplification/reduction; micro/macroperception; scientific instrumentation | Some overlap with Ihde retained so this reference can be loaded alone. Secondary bibliography and fine-grained historical disputes omitted. |
| What Things Do 5 | Actants; collective; programs/antiprograms; translation; composition; reversible black-boxing; delegation/scripts; actor-network theory/postphenomenology distinction; invitation/inhibition | Full network diagrams omitted. The hotel-key example preserves the practical explanatory sequence. |
| What Things Do 6–7 | Device paradigm; focal practices; effort versus meaning; engaging devices; function/sign/mediation; material aesthetics; Eternally Yours; technical/economic/psychological lifetime; attachment; transparent and engaging artifacts | Numerical possession-survey findings and catalog of product examples omitted. Repair and engagement principles retained without claiming environmental effects are guaranteed. |
| Investigations 1 and 7 | Field guide; relational ontology; four relations and later extensions; field awareness/composition; sedimentation; dominant stability; empirical philosophy; Kiran's four paired dimensions | Full typological diagrams and numerous field-guide case details compressed. Kiran is explicitly attributed; the dimensions are not assigned to Ihde or the entire collection. |
| Investigations 2–6 | Langsdorf's metaphysical challenge; Besmer's re-embodiment/extension critique; Hoel and Carusi's later Merleau-Ponty, measuring body, flesh, Ineinander, and circuit; Nizzi's self-multistability and fiction; Secomandi's technique/body challenge | Long metaphysical arguments, detailed Merleau-Ponty textual exegesis, and individual film plots omitted. Their diagnostic questions and chapter identities remain. |
| Investigations 8–13 | Self-tracking/data double; speed and imaginative/practical multistability; humanoid alterity/robo-etiquettes; clinical automation; body multiplicity/protocols; unveiling and empirical correction | Product catalogs, speculative exoself detail, and clinical statistics omitted. No medical protocol or current capability is inferred. |
| Investigations 14–16 | Feenberg's reification/instrumentalization/dereification; Michelfelder's future-oriented design concerns; Borgmann's critique of homogeneous seeing and the normative sufficiency of variation | Detailed critical exchanges compressed. Disagreement retained rather than synthesized as consensus. |
| Kudina 1–2 | Moral ecosystem; values-in-practices; valuation; ends-in-view; potentiality; thin/thick morality; technomoral change; normative levels; value dynamism | Detailed dictionary and value-theory survey compressed into the distinction between abstract guidance and situated interpretation. Lists of alternative value-change typologies are not presented as a complete operational taxonomy. |
| Kudina 3–4 | Practical/projective appropriation; domestication; Glass/privacy proof of principle; IPA; double hermeneutics; idiography; CA&DP comparison; evidential traceability; SST+ study and its seven-person scope | Verbatim interviews, participant biographies, all subthemes and frequency thresholds, and technical details of sex selection excluded. The worked example uses Glass; SST+ supports the method and its limits. |
| Kudina 5 and conclusion | Hermeneutic circle; material hermeneutics; lemniscate; Body One/Body Two; reciprocal subject formation; temporary stabilization; VSD critique; Collingridge dilemma; social experiments; governance | Voice-assistant capability statistics and exact language-coverage claims omitted as dated. Other design approaches mentioned in passing are not expanded into unsourced methods. |
| Roholt 1–2 | Performance limits; means/ends; strong/weak multitasking; field of awareness; sedimentation; dominant stability; intimate technology | Healthcare and classroom study statistics excluded. Retained as motivation and distinctions, not a clinical or population evidence review. |
| Roholt 3–4 | Doing/undergoing; active experience; recognition/perception; consummation; pervasive quality; developed/undeveloped continuum; fitting fulfillment; happiness/morality/meaning; subjective fulfillment/nonsubjective worth | Dewey's metaphysics is not silently imported; Roholt's deliberate relaxation of consummation is retained. No complete theory of objective value is invented. |
| Roholt 5 | Device paradigm; five focal-thing features; safeguarding practices; traditions/procedures/standards; sociality; paraphernalia; centering; worthwhile practices | Repeated music/craft examples compressed. Terminology “paraphernalia” is attributed to Roholt's adaptation rather than misquoted as Borgmann's original word. |
| Roholt 6–7 | Identity-work; for-the-sake-of-which; plural identity; being-with; group context; effects on others; cautious optimism; on/off-task limit; supportive phone use | Extended seminar narrative reconstructed compactly. Specific writing-app discussion becomes a conditional design example, not a current product recommendation. |

## Boundaries of the shared synthesis

The core's sequence—situated encounter, transformation, moral formation, meaningful participation, and a defensible next step—is an editorial integration, not a named framework found verbatim in a single source. Its institutional questions draw in part on Feenberg's criticism rather than being presented as an exhaustive political theory inherent in all postphenomenology.

Decision rules restate source reasoning for practical use. Some boundaries, such as distinguishing philosophical analysis from current clinical or legal evidence, are editorial safeguards for applying historical examples responsibly. Novel AI cases are applications by analogy and must be labeled and supported accordingly.

The build does not claim exhaustive book coverage or full-page verification. The strongest reconstruction is at the level of the retained concepts and procedures. Exact quotations, close textual disputes, and omitted historical particulars require the underlying source.

## Budget calibration

The six reference files are substantially below the extractor's study/text planning targets while remaining under its hard caps. This is an intentional selection: philosophical frameworks, usable distinctions, a single worked example, and decision rules take priority over chapter recaps, long exegesis, and repeated illustrations. The budget tool flags this as an advisory coverage check; the structural validator reports no errors or warnings.

The framework sections also contain some multi-concept bullets and chapter-attribution scaffolding, particularly in the edited collection. A raw “tokens per bullet” calculation is therefore not equivalent to the skill's “tokens per retained named item” measure. The audit retains this distinction rather than splitting bullets simply to improve the numerical score. Realized per-file token estimates are saved in `validation.json` for future calibration.

## Extending and maintaining the library

1. Inspect the new source's own structure and quality. Record its edition and hash; keep raw material outside this repository.
2. Distill one sibling source reference using the existing layout. Attribute an edited chapter's ideas to its contributor.
3. Record retained and omitted conceptual items in this ledger. Preserve disagreement and explicit evidence limits.
4. Add task-based loading links. Change the core only where the source materially changes reasoning or judgment.
5. Re-run structural validation and the generated-instruction scan, then review the ordinary, uncertain, conflicting, and out-of-scope cases in `evaluation.md`.
6. Recheck current technological or institutional facts for each application. Publication dates are not a freshness guarantee.
