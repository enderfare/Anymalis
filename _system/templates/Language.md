---
title: "{{title}}"
subtitle: "*{{subtitle}}*"
image: "{{image}}"
tags: [Language, '{{type}}', "{{status}}"]

# Overview
Type: "{{type}}"               # e.g., Spoken, Written, Signed, Ancient
Status: "{{status}}"            # e.g., Living, Dead, Sacred, Constructed
Script: "{{script}}"            # e.g., Alphabet, Logographic, Abjad
AssociatedCultures: "{{cultures}}"  # e.g., [[Felinnari]], [[Drifters]]
Region: "{{region}}"            # Geographical area where spoken
Speakers: "{{speakers}}"        # Approximate number or communities
Classification: "{{classification}}"  # Language family or isolate

# Characteristics
WritingSystem: "{{writing_system}}"   # Description of script
Direction: "{{direction}}"             # e.g., Left-to-right, Right-to-left, Boustrophedon
Tonal: "{{tonal}}"                     # Yes/No/Partially
GenderedNouns: "{{gendered}}"          # Yes/No
GrammaticalCases: "{{cases}}"          # e.g., Nominative, Accusative, etc.
VerbAspect: "{{aspect}}"               # e.g., Perfective, Imperfective
NotableFeatures: "{{features}}"        # e.g., Agglutinative, Polysynthetic

# Dialects
Dialects:
  - "{{dialect1}}"
  - "{{dialect2}}"

# Usage
CommonPhrases:
  - Phrase: "{{phrase1}}"
    Meaning: "{{meaning1}}"
  - Phrase: "{{phrase2}}"
    Meaning: "{{meaning2}}"

VocabularyInfluence: "{{influence}}"   # Other languages that influenced it
Loanwords: "{{loanwords}}"              # Examples

layout:
  # Overview Group
  - type: header
    text: "Overview"
    above: Type
  - type: group
    keys: [Type, Status, Script]
  - type: group
    keys: [AssociatedCultures, Region, Speakers]
  - type: group
    keys: [Classification]

  # Characteristics Group
  - type: header
    text: "Characteristics"
    above: WritingSystem
  - type: group
    keys: [WritingSystem, Direction, Tonal, GenderedNouns]
  - type: group
    keys: [GrammaticalCases, VerbAspect, NotableFeatures]

  # Dialects Group
  - type: header
    text: "Dialects"
    above: Dialects
  - type: group
    keys: [Dialects]

  # Usage Group
  - type: header
    text: "Usage"
    above: CommonPhrases
  - type: group
    keys: [CommonPhrases, VocabularyInfluence, Loanwords]
---
# Description
[General introduction to the language, its beauty, complexity, and role in the world.]

# History
[Origin, evolution, historical events that shaped it. Mention if it descended from an ancient tongue or was artificially constructed.]

# Script
[Detailed description of the writing system. Include samples, how it's written (tools, surfaces), and any calligraphic traditions. May include images of script samples.]

# Phonology
[Sound system: consonants, vowels, syllable structure, stress patterns. Can be as detailed as needed, possibly with IPA.]

## Consonants
|            | Bilabial | Dental | Alveolar | Palatal | Velar | Glottal |
|------------|----------|--------|----------|---------|-------|---------|
| Plosive    | p b      |        | t d      |         | k g   |         |
| ...        |          |        |          |         |       |         |

## Vowels
|         | Front | Central | Back |
|---------|-------|---------|------|
| Close   | i     |         | u    |
| Mid     | e     |         | o    |
| Open    |       | a       |      |

# Grammar
[Overview of grammar: word order, noun declensions, verb conjugations, tense, aspect, mood, etc. Provide examples.]

## Nouns
[How nouns are inflected for number, case, gender.]

## Verbs
[Verb paradigms, tense markers, agreement.]

## Syntax
[Typical sentence structure (SOV, SVO, etc.), clause formation.]

# Vocabulary
[Lexicon highlights, word formation processes, semantic fields. Include a few example words with translations.]

| Word | Translation | Notes |
|------|-------------|-------|
| ...  | ...         | ...   |

# Dialects
[Describe major dialects, their differences in pronunciation, vocabulary, and grammar. Mention which groups speak them.]

# Cultural Significance
[Role in rituals, literature, magic (glyph incantations?), social status. Are there sacred or secret variants?]

# Learning & Usage
[How do outsiders learn it? Are there academies? Common phrases used in trade or diplomacy.]

# Example Text
[Provide a sample sentence or short text with gloss and translation.]

# Notes
[Any additional information, trivia, or author's notes.]