# DNAversity case file

Copy this structure for every case. Keep every section, even if empty. IDs never change and entries are never deleted; mark superseded ones. Use aliases for living people.

```markdown
# DNAversity case — <case alias>

Package: DNAversity v<version printed at /start>
Created: <date> · Updated: <date>
Tester: P-001 (<alias>)
Records skill: <beginner|intermediate|advanced> · DNA skill: <beginner|intermediate|advanced>
Privacy: notice given <date>; participant said continue. Consent notes: <none | K-002 belongs to <alias>, permission stated <date>>
Readiness: <FOUNDATION READY | READY WITH LIMITATIONS | DNA ORGANIZATION INCOMPLETE | RELATIONSHIP VERIFICATION REQUIRED | UNKNOWN FAMILY RECONSTRUCTION REQUIRED>
Research question: <one question, or "not yet set"> (set <date>)

## People
| ID | Alias | Relationship to tester | Living | Biological or social | Class | Claim source | Status | Notes |
|---|---|---|---|---|---|---|---|---|
| P-001 | Tester | self | yes | — | — | — | — | b. ~1974, SC |
| P-002 | <alias> | mother | yes | biological | Supported/Known | personal knowledge | — | |
| P-003 | Unknown | father | ? | biological | Unknown | — | Unknown | do not fill |

## DNA profiles
| ID | Tester | Platform | Managed by | Features seen | Consent |
|---|---|---|---|---|---|
| K-001 | P-001 | AncestryDNA | participant | matches, shared matches | own kit |

## Matches
| ID | Alias | Platform(s) | cM or % | Predicted | Known? | Tree | Shares with | Group | Membership | Notes |
|---|---|---|---|---|---|---|---|---|---|---|

## Anchors
| M-ID | Documented relationship | cM | Expected range | Fits | Side |
|---|---|---|---|---|---|

## Groups
| ID | Label | Seed | Anchors | Members (status) | Clues | Proposed family (status) |
|---|---|---|---|---|---|---|

## Evidence
| ID | Type | Citation | Source class | Info class | Bears on | Supports / contradicts | Original kept at |
|---|---|---|---|---|---|---|---|

## Hypotheses
| ID | Claim | Status | Evidence for | Evidence against | Exact gap | Ida challenged? | Participant decision |
|---|---|---|---|---|---|---|---|

## Conflicts
| # | Between | Description | Material? | Resolved? | How |
|---|---|---|---|---|---|

## Tasks
| ID | Action | Owner | Priority | Expected evidence value | Status |
|---|---|---|---|---|---|

## Proposed changes awaiting approval
| # | Change | Evidence | Proposed | Decision |
|---|---|---|---|---|

## Specialist reports
<Full-form specialist output from `templates/agent-output.md`, one block per report, newest last. This is the only place the full form appears.>

## Log
- <date> /start · privacy notice · skill levels recorded
- <date> FOUND-01 · P-001..P-00n created
- <date> <command> · <what changed> · <human decision if any>
```

## Rules

- **Status** on a person row is the evaluated status of the parent-child link to that person's parents, once Pauli has assessed it. Until then, leave it blank and rely on Class.
- **Unknown versus not supplied.** Class Unknown means the participant said they do not know who this person is. A relative the participant simply has not mentioned (the other parent of someone in the tree, a spouse, a sibling) gets no row at all until they come up; if a row is needed for structure, class it "Not supplied" so nobody reads silence as a research gap.
- **Superseded** entries get "(superseded <date>: reason)" appended in Notes rather than being removed.
- **Proposed changes** stay in their table until the participant decides. An accepted change is then applied and logged with "approved by participant."
- **The log** is the audit trail: recommendation, evidence, human decision, action.
- **E- ids** go on anything that bears on a claim, including family statements and tree clues, classified by source class. See `reference/evidence-standard.md`.
- **Splitting or replacing a hypothesis** after a challenge: give each new hypothesis a new `H-` id, mark the old one "(superseded <date>: split into H-00x, H-00y)", and keep its row.
- **On reload** of an older or condensed file, re-lay it into this shape, mark rows you derived rather than copied as "derived on reload," and have the participant confirm them.
