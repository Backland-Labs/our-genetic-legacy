# Source registry

The registry is the source of truth for where evidence can come from and how each source may be used. Agents cite source IDs so a changed URL or access rule is updated here, not in every agent. Last verified: 2026-08-31 (from the OGL Working Plan).

## Access classes

| Class | Definition | Rule |
|---|---|---|
| **DIRECT-PUBLIC** | Public web page or catalog, no participant credentials | The agent may search and read it when web access is available. Record URL, title, and access date. Distinguish an index or guide from the record. |
| **FREE-LOGIN** | Free, but an account may be required | The participant signs in. The agent never asks for the password. If the agent cannot reach the page, the participant supplies the record. |
| **PARTICIPANT-ACCOUNT** | The participant's personal DNA or genealogy account | The participant logs in and provides only selected screenshots, exports, or copied text. |
| **SUBSCRIPTION** | Paid records, newspapers, or DNA tools | Participant access or OGL-licensed access only. Never bypass a paywall. Never pressure the participant to buy access. |
| **REQUEST / ON-SITE** | Archive, courthouse, church, or collection not online | The agent writes a precise request. A human obtains it. |

## Sources

| ID | Source | Address | Class | Agents | Use |
|---|---|---|---|---|---|
| SRC-FS-RECORDS | FamilySearch Historical Records | https://www.familysearch.org/search/ | FREE-LOGIN, some images restricted | Carter, Octavia | Records, indexes, images, catalogs, tree clues. Participant may need to sign in to open images. |
| SRC-FS-WIKI | FamilySearch Research Wiki | https://www.familysearch.org/en/wiki/Main_Page | DIRECT-PUBLIC | Carter, Octavia | Jurisdiction and record-type guidance. Guidance, not proof. |
| SRC-NARA | U.S. National Archives | https://www.archives.gov/research | DIRECT-PUBLIC plus non-digitized holdings | Carter, Octavia | Federal census, military, immigration, pensions, research guides. Some records require ordering or a visit. |
| SRC-NARA-FB | NARA Freedmen's Bureau | https://www.archives.gov/research/african-americans/freedmens-bureau | DIRECT-PUBLIC guide; some records external | Carter; future Sankofa | Freedmen's Bureau (RG 105) research. |
| SRC-LOC | Library of Congress | https://www.loc.gov/ | DIRECT-PUBLIC | Carter, Octavia | Digitized newspapers (Chronicling America), maps, photographs, manuscripts. |
| SRC-ANCESTRY-REC | Ancestry records and trees | https://www.ancestry.com/ | PARTICIPANT-ACCOUNT / SUBSCRIPTION | Carter, Octavia | Participant retrieves records and tree material. |
| SRC-ANCESTRY-DNA | AncestryDNA | https://www.ancestry.com/dna/ | PARTICIPANT-ACCOUNT; some features membership-dependent | Rosalind, Octavia | Matches, cM, Shared Matches, parent-side labels, tree clues. |
| SRC-23ME | 23andMe DNA Relatives | https://www.23andme.com/ | PARTICIPANT-ACCOUNT | Rosalind, Octavia | Relatives, percent shared, predicted relationship, Relatives in Common. |
| SRC-MH-DNA | MyHeritage DNA | https://www.myheritage.com/dna | PARTICIPANT-ACCOUNT; some features paid | Rosalind, Octavia | Matches, cM and percent, segments, AutoClusters, shared matches. |
| SRC-MH-REC | MyHeritage historical records | https://www.myheritage.com/research | PARTICIPANT-ACCOUNT / SUBSCRIPTION | Carter, Octavia | Historical records and trees. |
| SRC-FTDNA | FamilyTreeDNA | https://www.familytreedna.com/ | PARTICIPANT-ACCOUNT | Rosalind, Octavia | Family Finder matches, cM, In Common With, chromosome data. |
| SRC-LIVINGDNA | Living DNA | https://livingdna.com/ | PARTICIPANT-ACCOUNT | Rosalind, Octavia | Family matching, shared matches, shared segments. |
| SRC-GEDMATCH | GEDmatch | https://www.gedmatch.com/ | PARTICIPANT-ACCOUNT; optional paid tools | Rosalind, Octavia | One-to-Many, One-to-One, cross-platform comparison. Only if the participant already uses it. Never request a raw DNA upload. |
| SRC-STATE | State and local archives | Varies | Varies | Carter, Octavia | Vital, probate, land, court, institutional, manuscript records. |
| SRC-CHURCH | Church and diocesan repositories | Varies | REQUEST / ON-SITE or by appointment | Carter, Octavia | Baptism, marriage, burial, congregation records. |
| SRC-COURT | County and court repositories | Varies | Public index, paid copies, or on-site | Carter, Octavia | Probate, guardianship, adoption, deeds, court evidence. |

## Searchable without a login

These are the sources Carter can actually reach from a chat with web access. Reach for them first, in roughly this order, whenever a deceased or historical person is named with a place and an approximate date.

| ID | Source | Address | Class | Use and caution |
|---|---|---|---|---|
| SRC-FINDAGRAVE | Find a Grave | https://www.findagrave.com/ | DIRECT-PUBLIC | Burials, headstone photos, dates, cemetery. A headstone photo is evidence of what the stone says; the linked relatives and biographies are user-authored leads. Sometimes refuses automated fetches; then it is "not reachable," and a search-engine query limited to findagrave.com is the weaker fallback. |
| SRC-CHRONAM | Chronicling America (Library of Congress) | https://chroniclingamerica.loc.gov/ | DIRECT-PUBLIC | Full-text searchable U.S. newspapers, 1770s–1963. Obituaries, marriages, court notices, community news. Original source; OCR errors are common, so try name variants. Sometimes refuses automated fetches; then it is "not reachable." |
| SRC-FS-WIKI | FamilySearch Research Wiki | https://www.familysearch.org/en/wiki/Main_Page | DIRECT-PUBLIC | Which record collections exist for a county and era, and where they are held. Use it to pick the next collection. |
| SRC-NARA-1950 | 1950 U.S. census (National Archives) | https://1950census.archives.gov/ | DIRECT-PUBLIC, name index and images | The most useful login-free record set for anyone alive in 1950. The name index is machine-generated and error-prone (try variants and browse the enumeration district), so an index hit is a lead until the page image is viewed. The image is an original record. |
| SRC-STATE-DIGITAL | State digital archives and online indexes (for example the South Carolina Department of Archives and History online records index, Digital Library of Georgia, Library of Virginia, Missouri Digital Heritage) | Varies by state | DIRECT-PUBLIC index; images vary | Wills, estates, plats, land grants, county court indexes. An index hit is a citation to an index until the image is seen. |
| SRC-ARCHIVE-ORG | Internet Archive, HathiTrust, Google Books | https://archive.org/ · https://www.hathitrust.org/ · https://books.google.com/ | DIRECT-PUBLIC | Digitized county histories, published genealogies, city directories, church histories, yearbooks. Authored sources: leads and context, cited as such. |
| SRC-USGENWEB | USGenWeb county projects | https://usgenweb.org/ | DIRECT-PUBLIC | Volunteer transcriptions of cemeteries, marriages, wills, censuses by county. Derivative; find the original when it matters. |
| SRC-LOWCOUNTRY | Lowcountry Africana | https://lowcountryafricana.com/ | DIRECT-PUBLIC | African American genealogy for South Carolina, Georgia, and Florida: estate inventories, plantation records, Freedmen's Bureau transcriptions. |
| SRC-DISCOVERFREEDMEN | Discover Freedmen (Freedmen's Bureau search) | https://www.discoverfreedmen.org/ | DIRECT-PUBLIC search; images via FamilySearch (FREE-LOGIN) | Indexed Freedmen's Bureau records by name. |
| SRC-WIKITREE | WikiTree and other public collaborative trees | https://www.wikitree.com/ | DIRECT-PUBLIC | Trees with attached sources. Authored; use the sources they cite, not the tree itself. |
| SRC-CONTEXT | Encyclopedias, National Park Service, university, library, and museum pages | Varies | DIRECT-PUBLIC | Authored secondary context for documented historical people and places. Cite and classify as secondary. Never the sole basis for a relationship status above Possible. |

Rules for these: cite the exact page URL, the page title, and the access date. Record a negative search (source, terms tried, date) when a source that should have the person does not. A source that refused the connection or returned a blank page is "not reachable," which is different from "not found": it goes in the task list to retry, never in the negative searches. Never present a remembered fact as a search result; if you know something and cannot find a page for it, say it is unsourced recollection and give it no more than Possible.

## Rules

- A source's existence does not mean the current session can reach it. Check the class before promising a search.
- Direct public research must capture citation metadata at the time of access.
- Participant-account sources never authorize credential collection.
- An index, hint, online tree, or society database can point to evidence. It is not automatically the evidence.
- Never report a source as searched unless its content was actually accessible.

## Access decision

| The source is | Carter does |
|---|---|
| Available on the public web | Searches it, captures the citation, returns evidence or a lead |
| Behind the participant's login | Tells the participant exactly what to retrieve and why; never asks for credentials |
| Behind a subscription | Asks the participant to retrieve it through their account, or uses approved OGL access |
| Physical or request-only | Writes a precise request: repository, collection, record, what to ask for |
| Temporarily unavailable, or refusing automated access (403, bot check, blank page) | Reports it as not reachable, not as not found; logs a retry task; uses a domain-restricted search-engine query as a labeled weaker fallback; chooses another evidence path |

**Example.** Carter needs a 1942 obituary. If Chronicling America has the newspaper, Carter searches it. If it is only on a paid newspaper site, Carter asks the participant to retrieve that specific obituary. If it is only on microfilm at a local library, Carter writes the request. Carter never reports the obituary as searched unless it was actually read.
