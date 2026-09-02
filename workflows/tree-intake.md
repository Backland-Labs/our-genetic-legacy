# TREE-MAN-01 and TREE-GED-01 — Tree intake

**Owner:** Harriet, with Carter for records attached to the tree.

## Manual baseline (TREE-MAN-01)

Handled inside FOUND-01. The participant states what they know; Harriet reflects it back as a table; the participant corrects; Harriet records it with relationship classes and claim sources.

## Existing tree or GEDCOM (TREE-GED-01)

This beta has no GEDCOM parser. Handle an existing tree this way:

1. **Ask for a summary, not the file.** "Tell me, or paste, the direct ancestors on your tree back to great-grandparents, with dates and places where the tree has them. If it is a GEDCOM file, open it in your genealogy program and read from there, or paste the text if it is small."
2. **If a GEDCOM file is supplied and you have file tools**, you may read it as text. Extract only individuals (`INDI`), families (`FAM`), names, birth and death events, and parent-child links for the direct ancestors and their siblings. Preserve the original file under `dnaversity-case/sources/`. Do not attempt full fidelity.
3. **Every imported link is Imported/Unverified.** A tree is an authored source. It is a lead. Say so once, plainly, without disparaging the participant's work.
4. **Import Review.** Show the imported people and links in a table. For each link, ask what it rests on: a record, a hint, a family statement, or another tree. Record the answer as the claim source.
5. **Conflict handling.** If the imported tree names a parent where the participant says the biological parent is unknown, do not choose. Record both: the tree's claim with source, and the participant's statement. Class: Conflicting. Open a verification task.
6. **Duplicates.** Before creating a `P-` entry, check for the same person by name, dates, places, and spouse or parents. Ask before merging when identity is not certain.
7. **Record the import** in the log with the date and the tree's source (site, program, file name).

## What the tree is for

The tree is the map of what the participant believes. The evidence file is what is established. Keep the two separate in the case file so a changed conclusion never silently rewrites the map.
