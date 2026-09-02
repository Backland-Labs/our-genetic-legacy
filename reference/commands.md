# Commands

Every action has a stable command and a natural-language equivalent. Both resolve to the same workflow and are logged the same way in the case file. Commands are case-insensitive. A missing argument prompts for that argument only.

| Command | Owner | Behavior | Natural-language examples |
|---|---|---|---|
| `/start` | Harriet | Create or open a case, print version, privacy notice, capture skill levels, begin Foundation | "let's get started", "I want to research my family", "new case" |
| `/foundation` | Harriet | Run or resume the Family & DNA Foundation (FOUND-01) | "let's go over what I know", "back to the foundation" |
| `/status` | Harriet | Readiness, active question, known/suspected/unknown/conflicts, open tasks, next step | "where are we", "summarize the case" |
| `/question` | Harriet | Set or revise the research question once readiness allows | "I want to find out who my grandfather was" |
| `/next` | Harriet | One highest-value next action with the reason | "what should I do next" |
| `/agents` | Harriet | Which specialists are active and why | "who is working on this" |
| `/tree` | Harriet, Carter | Tree status and intake options | "show me the tree" |
| `/tree import` | Harriet, Carter | GEDCOM or pasted tree intake (TREE-GED-01) | "I have a GEDCOM", "here's my tree from Ancestry" |
| `/tree add` | Harriet, Carter | Propose a person or relationship addition or correction | "add my grandmother", "that date is wrong" |
| `/dna` | Rosalind | DNA platform and profile inventory (DNA-PROFILE-01) | "I tested at Ancestry and 23andMe" |
| `/dna add` | Rosalind | Add a platform or profile | "I also have my mom's kit" |
| `/matches` | Rosalind | Match table, anchors, groups, ungrouped, missing data | "here are my top matches", "show my matches" |
| `/groups` | Rosalind | Neutral groups with evidence | "show me the groups", "which cluster is my dad's side" |
| `/shared [match]` | Rosalind | Shared Matches capture for one match (ANC-SHARED-02 or platform equivalent) | "here's who I share with J.W." |
| `/upload` | Harriet | Identify the upload type and route | "here's a screenshot", "I have a document" |
| `/upload dna` | Rosalind | DNA screenshot, CSV, or match-list intake | "here's my match list" |
| `/upload record` | Carter | Record, image, or PDF intake (REC-UPLOAD-01) | "here's her death certificate" |
| `/research` | Harriet, Carter | Show, add, or complete research tasks; research log | "what's on the to-do list", "log that search" |
| `/sources` | Carter, Pauli | Sources, source quality, missing citations | "what sources do we have", "how good is that record" |
| `/verify [claim]` | Pauli | Evidence evaluation of one claim (REL-VERIFY-01) | "is it proven that she was his daughter", "how sure are we" |
| `/challenge` | Ida | Independent red-team of the leading hypothesis (REDTEAM-01) | "poke holes in this", "what else could explain it" |
| `/unknown [relationship]` | Octavia | Unknown parent, grandparent, or relative reconstruction (KIN-UNKNOWN-01) | "I don't know who my father is", "I'm adopted" |
| `/privacy` | Harriet | What is local, what is sent, current consent notes | "what happens to my data" |
| `/export` | Harriet | Emit the full case file | "save my work", "give me the file" |
| `/help` | Harriet | Commands, supported inputs, examples | "what can you do" |

## Mapping rules

- Match on intent, not on keywords. "I'm adopted and want to find my birth mother" is `/unknown mother`, not `/tree add`.
- When a message contains several intents, handle them in Foundation order: intake before analysis, analysis before verification.
- When the participant supplies material without saying what it is, identify it, name the workflow you are using, and proceed.
- Commands never bypass the rules. `/question` before the Foundation allows it returns the readiness state and what is needed first.
- Log the canonical command and workflow ID in the case file each time one runs.
