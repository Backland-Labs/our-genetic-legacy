# ANC-MATCH-01 and ANC-SHARED-02 — AncestryDNA intake

**Owner:** Rosalind. **Source:** SRC-ANCESTRY-DNA (PARTICIPANT-ACCOUNT). Last verified against Ancestry's help documentation: 2026-08-31.

Ancestry's feature availability depends on the participant's membership. Shared Matches, Matches by Parent, and Pro Tools features (Enhanced Shared Matches, Matches by Cluster) may or may not be present. Ask what the participant sees; never assume, and never suggest buying access.

## ANC-MATCH-01 — closest matches

**Goal.** Capture the strongest useful matches so Rosalind can find anchors and seed groups.

**Instruction to the participant.**
1. Sign in to Ancestry and open **DNA → DNA Matches**. Confirm the correct test is selected at the top if you manage more than one.
2. Take a screenshot of the first screen of matches, making sure the page shows the match names, the shared cM (or percentage) and the predicted relationship, and any "Mother's side / Father's side" labels if you have them.
3. If you would rather type than screenshot, list each match as: name or initials, cM, predicted relationship, side label if shown, and whether they have a tree.

**Required fields.** Tester context (which test), match display name, sharing amount, predicted relationship.
**Optional fields.** Side label, tree indicator, "unviewed" flag, notes.

**Screen validation.** The screenshot should show the DNA Matches page heading or the match list layout, and at least one match with a cM value visible. If the participant has cropped the header away but the rows are clear, accept it and note the tester was confirmed verbally.

**Extraction.** One `M-` entry per match. Check for an existing `M-` by name and cM before creating. Record the platform's predicted relationship as a platform observation, not a conclusion.

**Fallback.** If cM values are cut off, ask for one screenshot of the same rows with the sharing column visible. If the participant sees only percentages, record percent and note it.

**Privacy.** Match names are other people's names. Use initials or first names in the case file. Remind the participant.

**Next action.** Rosalind checks known relatives against their expected cM ranges, promotes anchors, and identifies the strongest unexplained match as a seed.

## ANC-SHARED-02 — Shared Matches for a target match

**Goal.** Determine whether the target match belongs to an existing group or should seed a new neutral group.

**Instruction to the participant.**
1. Open the target match from your DNA Matches list.
2. Choose **Shared Matches** (on some accounts this tab may be labeled differently or be part of Pro Tools; if you do not see it, tell me what tabs you do see).
3. Screenshot the top of the shared-matches list so that the target match's name is visible along with the first several shared matches and their cM if shown.
4. If Enhanced Shared Matches is available, the screen may also show how much DNA the shared match shares with the target match. Include it if it is there; do not go looking for a way to get it if it is not.

**Required fields.** Target match identity; shared-match names; enough page context to confirm this is the Shared Matches view.
**Optional fields.** Shared cM to the tester, shared cM between target and shared match, side labels, tree indicators.

**Screen validation.** Target match name visible; list layout visible. If the header is cropped, ask for one screenshot of only the header.

**Extraction.** One match-edge per shared match: tester ↔ target, target ↔ shared match, with observed values. New `M-` entries for shared matches not yet in the case.

**Fallback.** If the feature is unavailable on the participant's plan, switch to manual: "Open the target match and tell me the names of the first few people listed under shared matches, if you can see any." If nothing is available, record "shared matches unavailable on this account" and choose another seed or another platform.

**Evidence class.** Platform observation. Not proof of a specific common ancestor.

**Next action.** Compare shared matches to anchors and existing groups. Strengthen, keep provisional, or create a new neutral group. Return the reasoning to Harriet.
