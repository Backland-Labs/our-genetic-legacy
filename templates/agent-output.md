# Specialist output

A specialist's work appears in two places, and they look different on purpose. The reply is for the participant and reads as prose. The case file is for the record and holds the full structure. Never put the full structure in a reply, never render either as a code block, and never state the same finding twice.

## In the reply (short form)

Under a plain heading, in the participant's own register, and inside Harriet's reply:

```markdown
### Carter — <what was searched>

<Two to five sentences: what was found, not found, not reachable, or behind a login, and what it does and does not establish. Statuses in plain words ("a lead, not proof"; "Possible"). The one tension or conflict, if there is one.>

- <Key citation: title, site, URL, accessed date. One line each; only the items that carry the finding.>
- <...>
```

Then Harriet speaks again: what changed in the case file, the readiness state if it changed, and the one action. Beginners get a sentence explaining any term the first time it is used.

## In the case file (full form)

Every specialist section in the case file uses this shape so Harriet, Pauli, and the participant can read any result the same way. Omit a heading only if it is truly empty, and say "none" rather than leaving it out silently. The ranked Next actions list is case-file content that feeds `/status` and `/next`; it does not replace Harriet's rule that the reply itself ends with one action or one question.

```markdown
### <Specialist> — <task> · <date>

**Finding summary.** Two to four sentences.

**Claims**
| Claim | Status | Confidence note |
|---|---|---|

**Evidence for**
- E-xxx: <what it shows> (source class / info class / evidence class)

**Evidence against**
- E-xxx: <what it shows>

**Sources used**
- Found / consulted: <citation, with URL, title, and access date for web sources>
- Not found: <source, terms and variants tried, date>
- Not reachable: <source, URL, what happened (403, bot check, blank, timeout); to retry>
- Behind a login: <collection, what to search, what to bring back>

**Proposed changes** (nothing is committed until the participant approves)
- <change> — evidence: E-xxx

**Next actions** (ranked by expected evidence value)
1. <action> — would let us decide <what>

**Handoffs**
- <specialist>: <what they need>

**Privacy flags**
- <living person named; other person's DNA; sensitive finding; none>

**Human review required:** yes / no — <reason>

**Audit explanation.** One paragraph: what was done, what was assumed, what was not checked.
```
