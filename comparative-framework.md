# Comparative Framework and Record Model

## 1. Do not begin with a universal pantheon

A universal pantheon assumes that every tradition contains comparable gods arranged in comparable hierarchies. That assumption fails for many traditions.

The atlas begins with a neutral record object: **Tradition Record**. Depending on the source community, a record may describe a deity, divine name, sacred presence, ancestor, spirit, saint, bodhisattva, kami, place, ritual, text, cosmological principle, or a community's refusal to classify something in those terms.

The field `record_kind` is descriptive metadata, not a claim about what the being or reality ultimately is.

## 2. Suggested record kinds

- `DEITY_OR_DIVINE_BEING`
- `SACRED_NAME_OR_TITLE`
- `ANCESTOR_OR_HERO`
- `SPIRIT_OR_NONHUMAN_PRESENCE`
- `SAINT_OR_REVERED_PERSON`
- `BODHISATTVA_OR_BUDDHA_FIGURE`
- `SACRED_PLACE_OR_LANDSCAPE`
- `RITUAL_OR_PRACTICE`
- `TEXT_OR_ORAL_TRADITION`
- `COSMOLOGICAL_PRINCIPLE`
- `COMMUNITY_OR_TRADITION`
- `UNCLASSIFIED_BY_SOURCE`

A contributor may use a local category not listed here. Extend the schema rather than forcing a false fit.

## 3. Minimum record fields

| Field | Purpose |
|---|---|
| `record_id` | Stable internal identifier |
| `tradition_name` | Community's own name for the tradition, where appropriate |
| `local_name` | Original-language name, script, pronunciation, and variants |
| `record_kind` | Broad descriptive kind; may remain unclassified |
| `community_description` | How practitioners or source communities describe it |
| `language_and_region` | Relevant language(s), place(s), and historical period |
| `source_type` | Oral testimony, practitioner account, inscription, archival text, scholarship, observation, etc. |
| `source_citation` | Traceable source and access conditions |
| `date_or_period` | Attested date, approximate period, or UNKNOWN |
| `practice_context` | Only what may be shared publicly |
| `relationship_claims` | Separate, typed relations with evidence |
| `confidence` | Evidence assessment, not confidence in a religious belief |
| `consent_and_rights` | Permission, license, attribution, restrictions |
| `review_status` | Draft, community-reviewed, source-verified, disputed, restricted, withdrawn |
| `last_reviewed` | Date of latest review |

## 4. Evidence labels

Evidence labels describe the status of a documentation claim, not the truth or falsity of a faith.

- `DIRECTLY_ATTESTED`: visible in a cited source or directly observed under stated conditions.
- `PRACTITIONER_ACCOUNT`: attributed account from a practitioner or community contributor.
- `SCHOLARLY_INTERPRETATION`: interpretation attributed to a named scholarly source.
- `MULTIPLE_INDEPENDENT_SOURCES`: corroborated by independent sources.
- `CONTESTED`: credible sources or community accounts disagree.
- `HYPOTHESIS`: proposed connection awaiting evidence.
- `UNKNOWN`: not established from available material.
- `RESTRICTED`: not for public disclosure under community or source conditions.

Do not collapse practitioner testimony and archival evidence into one undifferentiated “verified” label.

## 5. Relationship model

Relationships must be directional and typed. Examples:

- `ATTESTED_IN`
- `WORSHIPPED_AT`
- `HONORED_BY`
- `ASSOCIATED_WITH_PLACE`
- `APPEARS_IN_TEXT`
- `NARRATIVE_VARIANT_OF`
- `TRANSMITTED_THROUGH`
- `PRACTICE_CONTINUES_AT`
- `HISTORICAL_CONTACT_WITH`
- `TRANSLATED_AS_BY_SOURCE`
- `COMPARED_BY_SCHOLAR_TO`
- `CLAIMED_EQUIVALENT_BY_COMMUNITY`
- `DISPUTED_EQUIVALENCE_WITH`

Similarity must never be silently upgraded to identity, shared origin, or transmission. If two traditions explicitly identify figures with one another, record who makes that identification, in which period and context, and whether it is accepted by all relevant communities.

## 6. Three distinct transmission histories

1. **Practice / devotional continuity:** who practices, where, and how practices continue or change.
2. **Narrative transmission:** who tells a story, which versions circulate, and how they vary.
3. **Textual transmission:** how texts are written, copied, edited, translated, and cited.

These histories may intersect, but one does not prove the other. A text can survive after a practice ends; a practice can continue without a stable written origin story; multiple texts may derive from one source rather than independent witnesses.

## 7. Comparison without flattening

Comparisons should be made on explicit dimensions: names and translation choices; roles attributed by practitioners; relationships to place, ancestors, nature, or institutions; ritual and devotional contexts; narrative motifs and textual history; historical contact and translation; and changes over time.

Do not use a single “power”, “rank”, “domain”, or “equivalence” score to compare traditions. Such scores import assumptions that many communities do not share.

## 8. Review and correction

Every public record should support source correction, alternate community descriptions, version history, dispute annotations, withdrawal or restriction requests, attribution updates, and correction of mistaken equivalence.

The absence of a record is not evidence that a tradition lacks a concept, practice, or sacred figure.
