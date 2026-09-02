# REC-UPLOAD-01 and OBIT-UPLOAD-01 — Historical record intake

**Owner:** Carter. **Input:** an image, PDF, or pasted text of a record. **Output:** an `E-` evidence item with citation, extracted facts, and an assessment.

## Process

1. **Identify the record type and repository first.** Death certificate, census page, marriage register, deed, probate file, Freedmen's Bureau register, church register, obituary, Bible page, photograph with inscription. Where did it come from: which site, which collection, which image or page? If the participant does not know, ask what site they downloaded it from and note "source per participant."
2. **Preserve the original.** In Claude Code, save the file under `dnaversity-case/sources/` with a descriptive name and reference it from the `E-` item. In claude.ai, record the participant's file name and the site.
3. **Transcribe what is relevant**, keeping it separate from the original. Mark uncertain readings with `[?]`. Never guess at a name; ask for a clearer image or record the uncertainty.
4. **Extract every genealogical statement:** names as written (with variants), relationships as stated, dates, places, ages, occupation, residence, birthplace, parents' names, witnesses, informant, neighbors on the same page.
5. **Record the informant** and their likely knowledge. This decides whether the information is primary or secondary.
6. **Compare with the case.** Which `P-` entries does this bear on? Does it agree, add, or conflict?
7. **Decide whether it is the right person.** Same name is not same person. Check age, place, spouse, and associates before linking the record to a `P-` entry.
8. **Classify** the source (original, derivative, authored), the information (primary, secondary, undetermined), and the evidence (direct, indirect, negative) for each claim it bears on.
9. **Write the citation** in a form a genealogist could follow: record type, jurisdiction, date, subject, repository or site, collection, image or certificate number, date accessed or date supplied.
10. **Return** the `E-` item to Harriet, and flag any conflict for Pauli.

## Obituaries and newspaper items (OBIT-UPLOAD-01)

- Capture subject, publication, date, and page.
- Separate what the newspaper states as fact from what a family member told the newspaper. An obituary's list of relatives is family-supplied information: valuable, secondary, sometimes wrong.
- Record every named relative and stated relationship as a lead for `P-` entries and for Rosalind's match-tree work.

## Household records

Two people in one household is not proof of a biological relationship. The census relationship column is what the enumerator was told. Record it as stated and evaluate it.

## Participant transcriptions

When the participant types out a record they hold rather than supplying the image, treat the text as a **derivative** source (a participant transcription of an original), save it verbatim as a text file under `sources/` in Claude Code, cite it as "transcribed and supplied by the participant, image not examined," and open a task to see the image. Ask only for the fields the transcription left out (surnames, certificate number, exact dates).

## Indexes

If the participant supplies an index entry rather than an image, record it as an index citation and add a task to obtain the image.

## Unreadable material

Show the participant the fields you could not read and ask for a clearer image, a zoomed crop, or their reading of it (recorded as "reading per participant").

## Privacy

A record can name living people. Use aliases for them in the case file. If a record exposes unrelated sensitive information (medical cause of death for a living person's parent, for example), record only what the research needs.
