# DNA method

DNAversity uses one methodology across every DNA platform: request the smallest useful evidence, extract it, structure it, compare it with the documented family, group it, evaluate it, and request the next piece. The platform is an adapter, not a different method.

## Vocabulary

- **Tester**: the person whose DNA results are being organized.
- **Match**: another tester who shares DNA with the tester. Each is one `M-` identity even if seen on several platforms.
- **Shared cM**: centimorgans of DNA shared. Larger usually means closer, with wide overlap between relationships. See `shared-cm-ranges.md`.
- **Shared match** (Ancestry), **Relatives in Common** (23andMe), **In Common With** (FamilyTreeDNA), **Shared DNA Matches** (MyHeritage): a third tester who matches both the tester and the match.
- **Anchor**: a known relative among the matches whose documented relationship has been checked against the shared DNA.
- **Group**: a set of matches who share DNA with each other, labeled neutrally (Group A, B, C, D) until evidence says which family they descend from.

## Anchors

An anchor orients everything else, so it must be earned.

1. The participant identifies the match as a known relative and states the documented relationship.
2. Rosalind checks the shared cM against the range for that relationship. It must fit.
3. Where possible, the relationship has documentary support in the case file.

Only then is the match an Anchor. A known relative whose cM does not fit the documented relationship is not an anchor; it is a foundational conflict and goes to Harriet.

## Neutral groups

1. **Seed** a group from the strongest match that is not explained by an anchor.
2. **Add members provisionally**: matches who appear in the seed's shared-match list.
3. **Strengthen** a member's status when it co-occurs with several meaningful members of the group, not just the seed.
4. **Do not name the group** after a family until independently reconstructed pedigrees converge on that family. "Group A" becomes "Group A (Simmons of Beaufort, Probable)" only with evidence.

Membership statuses: **seed** (the match the group was built from), **provisional** (shares with one other group member), and **strengthened** (shares with two or more other members, or is placed by a reconstructed pedigree). In a group of three, "strengthened" is easy to reach and means little; say so, and treat the group as provisional as a whole until it has four or more members or a record-based pedigree.

## Sharing with an anchor

Sharing with a maternal anchor means the match is a candidate for the maternal side. It does not confirm it, because:

- The match may be related to the anchor through the anchor's other parent.
- Endogamy or multiple relationships can create sharing on both sides.
- Small segments can be false matches.

Candidate is the word until the pattern repeats.

## Cluster first, then investigate, identify, and label

Group the matches before trying to explain them. Explaining one match at a time leads to fitting each into the story you already have.

## Cautions before concluding a branch is missing or wrong

The absence of an expected surname among matches does not disprove a documented line. Before treating it as a problem, check:

- Platform coverage: few descendants of that line may have tested here.
- Alternate surnames: married names, name changes, post-emancipation surnames, transliterations.
- Random inheritance: distant cousins may share no DNA at all.
- Grouping error: the group may be mislabeled.
- Endogamy: repeated ancestry inflates sharing and blurs groups.
- Pedigree collapse: cousins who married make one family look like two.
- Multiple relationships: two families intermarried more than once.

## Known relatives who tested

A tested relative whose kit the participant does not manage is a match, not a DNA profile. Record them in the Matches table with Known = yes and the documented relationship, and evaluate them as an anchor candidate. Only kits the participant manages, or has stated permission to use, go in the DNA profiles table.

## Cross-platform identity

The same person on two platforms is one `M-` record with two platform entries. Record both sharing amounts, but count the person once when weighing evidence. Ask the participant whether a similarly named match on another site is the same person; do not assume it.

## Interpreting shared cM

1. Look up the value in `shared-cm-ranges.md`.
2. List every relationship whose range includes the value. Usually there are several.
3. Use the documented tree, ages, and shared matches to narrow, never the platform's single prediction alone.
4. Remember that averages are not expectations. A value near the average of one relationship may sit comfortably inside the range of three others.
5. For values under about 20 cM, the match may be too distant to place or may be a false match; do not build a group on them.

## What Rosalind does not do

- Name a biological parent.
- Request raw genotype files or a GEDmatch upload.
- Treat a predicted relationship as a conclusion.
- Count a duplicate match twice.
- Ask for the full match list when the top matches will do.
