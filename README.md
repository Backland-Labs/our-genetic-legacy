# DNAversity

DNAversity is an AI-assisted genealogy research team for Our Genetic Legacy (OGL), packaged as an agent skill. This release is the September 2026 beta. It is intended to run in [Claude Cowork](https://claude.com/product/cowork), [ChatGPT Work](https://openai.com/chatgpt-work/), or [OpenWorker](https://github.com/andrewyng/openworker). It helps a participant organize what they know about their family, work through DNA matches, search public records, weigh the evidence, and leave with a concrete next step. It does not prove ancestry on its own, log into anyone's accounts, or contact anyone.

The participant talks to one voice, Harriet. Behind Harriet is a team of specialists brought in as the work calls for them. Every relationship claim carries an evidence status, "Unknown" is treated as valid data, and the participant approves any change to their tree.

## Agents

| Agent | Role | Brought in for |
|---|---|---|
| **Harriet** | Research Director / Orchestrator | Always present. Establishes the Family & DNA Foundation, defines the research question, routes work to specialists, and reports back to the participant. |
| **Rosalind** | Genetic Genealogy Analyst | DNA matches from Ancestry, 23andMe, MyHeritage, FamilyTreeDNA, Living DNA, and GEDmatch. Organizes matches into family networks. Never declares parentage. |
| **Carter** | Records Researcher | Historical records: census, probate, deeds, church registers, Freedmen's Bureau, obituaries. Finds and evaluates documentary evidence and cites it. |
| **Pauli** | Evidence Evaluator | Weighs documentary and DNA evidence together and assigns a defensible status to a claim before it moves above "Possible." |
| **Ida** | Skeptic / Red Team | Tries to disprove the leading hypothesis using only a sealed packet, with no tools or case access. Runs before any consequential conclusion. |
| **Octavia** | Kinship Reconstruction Specialist | Unknown parents or grandparents, adoptee cases, and trees that conflict with DNA. Keeps the relationship Unknown until the evidence earns a name. |

## Layout

- `SKILL.md` — Harriet's identity, the non-negotiable rules, and the research loop.
- `agents/` — one file per specialist with triggers, inputs, allowed sources, and handoff rules.
- `workflows/` — step-by-step intake procedures (Foundation, tree intake, record upload, DNA platforms).
- `reference/` — evidence standard, DNA method, shared cM ranges, source registry, privacy rules, glossary, commands.
- `templates/` — case file, agent output, and Ida packet formats.
- `sample-case/` — a synthetic practice case ("Renee") for testing and facilitator training.

## Getting started

Install the skill in Claude Cowork, ChatGPT Work, or OpenWorker and type `/start`. To try it without real data, follow `sample-case/README.md`.
