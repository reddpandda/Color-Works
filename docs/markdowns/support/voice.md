# Voice

The writing rules for every page in the standard.

The file has parts. Markdown voice applies to every system. Each later part applies to one system and only adds to Markdown voice. A system part never restates or changes a general rule.

Each system's syntax document defines which entries are valid. This document defines how the system is described. Mechanical checks belong to the lint script and its own documentation, not here.

## Parts

- [Markdown voice](#markdown-voice): every system
- [Color voice](#color-voice): the color system only
- Font voice: added when the font system is documented

# Markdown voice

These rules apply to every page of every system.

## Normative words

- `MUST`, `MUST NOT` and `MAY` are the only normative words. They are written in capitals.
- `MUST` marks a requirement. `MUST NOT` marks a prohibition. `MAY` marks a permission.
- There is no recommendation tier. A statement is mandatory, prohibited or permitted. Anything else is description and carries no force.
- Each word is defined once, in the general pages of each system, and used the same way everywhere.
- `MAY` means permission. The word "can" means ability or possibility. Prose does not use "can" to grant permission.

## Controlled terms

- Each term has one meaning. A term is never swapped for a synonym for variety.
- The glossary of each system holds the authoritative definitions. Until a glossary is written, that system's part of this file is the source.
- Words banned by a system are kept out of its prose, except on the page that bans them. Mentioning one to identify it as banned is allowed there. Using one as a descriptor is not.
- A system that uses ordinal names always writes each name with its position, and its glossary says once that position is not importance.

## Sentences

- Sentences are short, present tense and active.
- Invariants are stated directly: "A page has one title." Not: "Titles are assigned to pages."
- A length limit on a kind of line, such as a row field, belongs to the system part. It applies to that line only, not to every explanatory sentence.

## Person

- The prose describes "the system" and its parts, not the reader.
- "You" appears only in the places a system part names, and on the adoption page.
- No other page uses "you".

## Tone

- The tone is plain and slightly dry, on every page. The Introduction states purpose in the same voice.
- No marketing language, no hedging filler, no "simply" or "just", and no apologies for rules.

## Numbers

Two rules apply, in this order. The first takes precedence.

1. Numbers in rules, limits, ratios, sizes, versions and page numbers are always digits: `6 words`, `40px`, `v0.1`, page 7.
2. Numbers in other running prose are words from one to nine and digits from 10 up: "three pages at a time", "14 entries".

A number that is both in a rule and within one to nine follows rule 1. "At most 6 words" is correct.

## Examples

- Every valid example uses a real, legal entry from the system being described.
- An illegal example is labeled as illegal and is taken from that system's bad-construction list.
- Examples are checked against the same grammar the lint script uses.

## Page openings

- The first sentence says what the page defines or establishes.
- A second sentence states the page's scope or boundary, only when it adds information.
- The aim is consistent navigation, not repetition.

## Cross-references

- A page is referred to by its name, not its number. The number can change when pages are split or added.
- A page number appears only where the number itself is the subject.

## Formatting and spelling

- Every name that is written literally, such as an entry, folder or file name, is in backticks.
- A full path is one backtick span, extension included: `docs/markdowns/` and `README.md`. Components are not separately wrapped.
- Headings use sentence case.
- Spelling is American.

# Color voice

These rules apply to the color system. They add to Markdown voice.

## Controlled terms

The glossary holds the authoritative definitions. Until it is written, this list is the source.

- **Role**: a named job a color does, such as `text-base`.
- **Id**: the written name of a role.
- **Kind**: the first word of an id. It says what is colored: `fill`, `text`, `icon`, `line`, `ring` or `shadow`.
- **Type**: the word after the kind. It says what the role is for. An on-form has no type slot, because the target takes its place.
- **Form**: plain or on-form.
- **Emphasis**: an optional strength word (`subtle`, `strong`) that makes a different role from the same kind and type. Leaving it out means normal emphasis.
- **State**: a condition of use: `hover`, `active`, `selected`, `disabled` or `visited`. An id with a state is its own role.
- **Target**: the fill whose id an on-form id contains.

Emphasis and state can appear in one id. Emphasis comes first, then state, as in `text-base-subtle-disabled`.

## Words kept out of the prose

- The banned id words are listed on the bad-construction page. They appear only on that page.
- Identity words always appear with their position: `primum` (first), `secundum` (second), `tertium` (third), `quartum` (fourth).
- The glossary says once that position is not importance.

## Rows

- A job line is 12 words or fewer and has no final period.
- "You" appears in the `Use:`, `Don't use:` and `Override:` lines of a row, and on the adoption page.

## Examples

- Valid examples use real legal ids, such as `text-on-fill-primum` or `line-input-strong`.
- Illegal examples come from the bad-construction page.

## Numbers

- Contrast ratios are digits: `4.5:1`.
