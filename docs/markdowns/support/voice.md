# Voice

The writing rules for every page in the standard.

The syntax document defines which ids are valid. This document defines how the system is described. Mechanical checks belong to the lint script and its own documentation, not here.

## Normative words

- `MUST`, `MUST NOT` and `MAY` are the only normative words. They are written in capitals.
- `MUST` marks a requirement. `MUST NOT` marks a prohibition. `MAY` marks a permission.
- There is no recommendation tier. A statement is mandatory, prohibited or permitted. Anything else is description and carries no force.
- Each word is defined once, on page 03, and used the same way everywhere.
- `MAY` means permission. The word "can" means ability or possibility. Prose does not use "can" to grant permission.

## Controlled terms

Each term has one meaning. A term is never swapped for a synonym for variety.

The glossary (page 02) holds the authoritative definitions. Until it is written, this list is the source.

- **Role**: a named job a color does, such as `text-base`.
- **Id**: the written name of a role.
- **Kind**: the first word of an id. It says what is colored: `fill`, `text`, `icon`, `line`, `ring` or `shadow`.
- **Type**: the word after the kind. It says what the role is for. An on-form has no type slot, because the target takes its place.
- **Form**: plain or on-form.
- **Emphasis**: an optional strength word (`subtle`, `strong`) that makes a different role from the same type. Leaving it out means default strength.
- **State**: a temporary condition of use: `hover`, `active`, `selected`, `disabled` or `visited`. A state never makes a new role.
- **Target**: the fill whose id an on-form id contains.

Emphasis and state can appear in one id. Emphasis comes first, then state, as in `text-base-subtle-disabled`.

## Words kept out of the prose

- The banned id words, listed on page 05, appear only on the page that bans them. Mentioning one to identify it as banned is allowed there. Using one as a descriptor or role name is not.
- Identity words always appear with their position: `primum` (first), `secundum` (second), `tertium` (third), `quartum` (fourth).
- The glossary says once that position is not importance.

## Sentences

- Sentences are short, present tense and active.
- Invariants are stated directly: "A role has one id." Not: "Ids are assigned to roles."
- A job line is 12 words or fewer and has no final period. This limit applies to job lines only, not to every explanatory sentence.

## Person

- The prose describes "the system" and "an id".
- "You" appears only in two places: the `Use:`, `Don't use:` and `Override:` lines of a row, and the adoption page (page 06).
- No other page uses "you".

## Tone

- The tone is plain and slightly dry, on every page. The Introduction states purpose in the same voice.
- No marketing language, no hedging filler, no "simply" or "just", and no apologies for rules.

## Numbers

Two rules apply, in this order. The first takes precedence.

1. Numbers in rules, limits, ratios, sizes, versions and page numbers are always digits: `6 words`, `4.5:1`, `40px`, `v0.1`, page 7.
2. Numbers in other running prose are words from one to nine and digits from 10 up: "three pages at a time", "14 fill types".

A number that is both in a rule and within one to nine follows rule 1. "At most 6 words" is correct.

## Examples

- Every valid example uses a real, legal id, such as `text-on-fill-primum` or `line-input-strong`.
- An illegal example is labeled as illegal and is taken from the bad-construction list (page 05).
- Examples are checked against the same grammar the lint script uses.

## Page openings

- The first sentence says what the page defines or establishes.
- A second sentence states the page's scope or boundary, only when it adds information.
- The aim is consistent navigation, not repetition.

## Formatting and spelling

- Every id, folder name and file name is in backticks.
- A full path is one backtick span, extension included: `docs/markdowns/colors/` and `README.md`. Components are not separately wrapped.
- Headings use sentence case.
- Spelling is American.
