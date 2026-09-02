# Changelog

## 0.1.5 — Small clarifications from the third live test

An identified-but-unnamed person at `/start` gets an acknowledgment, not a search promise. Skill levels given in the continue message are not re-asked. The case file has a Specialist reports section, the only place the full-form output appears. A sensitive finding that arrives inside Carter's same-turn search is presented in that reply with its status, its does-and-does-not-establish sentence, and the pause offer. A person of unknown living status is treated as living. `/status` is the one fenced-block output.

## 0.1.4 — Names are search terms

From Mitch's second live test. The blanket ban on searching a living person by name is replaced by a purpose rule: any name the participant gives, living or not, may be a search term for records about deceased people (a grandfather's obituary naming the living father as a survivor is exactly how grandfathers are found), while searching to identify, locate, or profile a living person stays prohibited and a web hit never names a living person as a parent. Harriet no longer announces limits that have not come up. `/start` now opens with a plain overview of what DNAversity does and does not do. Specialist output has two forms: a short prose form with key citations inside the reply, and the full template in the case file only, never as a code block and never twice. Checklist scenarios 1, 19, and 20.

## 0.1.3 — Honest about what was reached

Fixes found by the two historical-figure tests (Robert Smalls of Beaufort, and an invented control ancestor). "Not reachable" is now a distinct result from "not found": a source that returns 403, a bot check, a maintenance page, or a blank page is logged as a retry task, never as a negative search, with a domain-restricted search-engine query as the labeled weaker fallback. The 1950 census name index joins the login-free sources, with its machine-index caution. Consent comes before any search on a first message, and the length cap yields to citations: the reply carries Carter's summary and the one action, the case file carries his full template output. The Foundation reflect-back table is named as the one table that belongs in the reply. The case file distinguishes Unknown from Not supplied. Also: one ask for a load-bearing fact the participant never mentioned is not re-asking; a historical person's relationship drawn from public sources is class Reported and capped at Possible until an original record is seen; a material conflict beyond the grandparent level sets READY WITH LIMITATIONS with the link marked Conflicting and research stopped at it; a specialist's ranked next-actions list is case-file content; Pauli may ask for one more targeted search before assigning a status; and a new enslaver-paternity rule in the privacy file. Checklist scenarios reordered, scenario 17 tightened, and scenario 18 now checks the not-reachable distinction.

## 0.1.2 — Search first

Carter now searches the login-free public sources (Find a Grave, Chronicling America, FamilySearch wiki, state digital archives, digitized county histories, Lowcountry Africana, Discover Freedmen, public trees, encyclopedias) in the same turn a deceased or historical person is named, and reports found, not found, and behind-a-login with citations. Ancestor questions no longer wait for the Foundation: the ancestor is searched now and the participant's line of descent is verified in parallel. Recall is never presented as research.

## 0.1.1 — Work with what you have

Fixes rigidity found in Mitch's first live test: Harriet re-asked for things the participant had said they did not have, ended every reply with several questions plus a task list, spent two turns on "is this you," and took five turns to say that DNA was the only path. Added the "Work with what you have" rules to SKILL.md (take the dump, do something before asking, one question or action per reply, say early which doors are open, match the participant's length), a triage table in Harriet's file, a fast path in the Foundation workflow, Carter's initiative on public sources, a one-question consent rule for proxy cases, and an explicit ban on searching the web for a living person by name.

## 0.1.0 — September 2026 workshop beta

First release. Harriet plus five specialists (Rosalind, Carter, Pauli, Ida, Octavia), Constance privacy rules, the evidence standard, DNA method, source registry, Ancestry intake workflows, record upload workflow, case-file template, one synthetic sample case, and the manual test checklist.

Validated Sept 2, 2026 with three simulated smoke tests (foundation and unknown father, weak evidence and password refusal, Ida challenge). Instruction gaps they surfaced were fixed before release: consent pause at /start, resuming a saved case, first-name clues versus Alleged persons, E- ids for family statements, Probable cap before Ida on consequential identities, volunteered credentials, participant transcriptions, seed and small-group membership, non-managed kits, display names, isolated Ida inputs with no tools, and hypothesis splitting.
