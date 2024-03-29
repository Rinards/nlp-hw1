# FST for fragment of Latvian language

**Author**: Rinards Koršaks, RK20099
**Repository**: [Homework 1 Repository](https://github.com/Rinards/nlp-hw1)

---

## latvian.lexc
Lexical structure of the laguage

Includes inflection for nouns, adjectives and verb forms.

### Nouns
Noun cases with declinations and consonant gradation.

### Adjectives
Adjective cases with comparative and superlative.
Formally in Latvian superlative prepends 'vis' but I could not figure out how to implement this.

### Verbs
Verbs in Latvian have many different groups and a lot stem changes depending on tense, person and conjugation. Added only some 2nd and 3rd conjugation for first person singular and plural in past, present and future tense.

For second conjugation it is necessary to insert J in some cases and in third conjustation both J or both J and Ī.

## latvian.foma
Includes latvian.lexc and rules for consonant gradation and inserting J and Ī for Verbs.

Make sure you have FOMA installed.

To run .foma file:
>`foma -l latvian.foma`

## *Issues*
When running the foma file I noticed that rules are not applying correctly. I have spent a lot of time trying to fix this but even simple clean up of asterisk or caret symbol does not work as expected.
