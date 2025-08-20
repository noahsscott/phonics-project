---
title: SATPIN Foundation Words
type: Resource
permalink: 01-research/resources/satpin-foundation-words-1
entity_type: resource-document
status:
  - 🚧 Under review
created: 2025-08-13
modified: 2025-08-13
tags:
  - '["phonics"'
  - '"word-lists"'
  - '"SATPIN"'
  - '"json-data"'
  - '"flashcards"]'
---

> [!resource] Resource Overview
> **Purpose**: Core word list using only SATPIN letters for initial phonics instruction
> **Word Count**: 40 words (10 core + 20 additional + 10 nonsense for assessment)
> **Format**: JSON structure for app integration
> **Usage**: Comprehensive flashcard set with differentiated difficulty levels

## 📋 Resource Description

Foundation word list containing decodable words using only the SATPIN letter sequence. These words enable immediate reading success after teaching just six letters, with students able to blend and segment from day one of word-level instruction.


### Teaching Progression
1. **Start with VC words** (at, it, in) - easiest blending
2. **Add initial continuous sounds** (sat, sit) - /s/ can be held
3. **Introduce stop sounds** (pin, pan, tap) - requires quick blending
4. **Challenge with blends** (ant, pant) - only after CVC mastery

### Cantonese L1 Considerations
- Extra practice with /p/ vs /b/ distinction (pin/bin confusion)
- Emphasise final /n/ sound (often dropped in Cantonese)
- Use mirrors for /s/ tongue position
- Practice /t/ release (often unreleased in Cantonese)

## 📊 Data Structure Benefits

This JSON structure enables:
- **Dynamic difficulty adjustment** based on student progress
- **Filtered card generation** by pattern type or difficulty
- **Progress tracking** through frequency ranks
- **Error analysis** using common_errors data
- **Systematic review** using teaching_sequence

## 💾 JSON Data

```json
{
  "pattern_group": "SATPIN_foundation",
  "pattern_type": "single_letters",
  "sequence_order": 1,
  "prerequisites": ["s", "a", "t", "p", "i", "n"],
  "teaching_notes": "Introduce after all 6 letters are known. Focus on blending continuous sounds (s, n) first.",
  "words": [
    {
      "word": "at",
      "phonemes": ["a", "t"],
      "pattern": "VC",
      "frequency_rank": 1,
      "word_type": "real",
      "decodable_with": ["a", "t"],
      "difficulty": 1,
      "notes": "High-frequency word, good starter"
    },
    {
      "word": "it",
      "phonemes": ["i", "t"],
      "pattern": "VC",
      "frequency_rank": 2,
      "word_type": "real",
      "decodable_with": ["i", "t"],
      "difficulty": 1,
      "notes": "High-frequency pronoun"
    },
    {
      "word": "in",
      "phonemes": ["i", "n"],
      "pattern": "VC",
      "frequency_rank": 3,
      "word_type": "real",
      "decodable_with": ["i", "n"],
      "difficulty": 1,
      "notes": "High-frequency preposition"
    },
    {
      "word": "sat",
      "phonemes": ["s", "a", "t"],
      "pattern": "CVC",
      "frequency_rank": 4,
      "word_type": "real",
      "decodable_with": ["s", "a", "t"],
      "difficulty": 2,
      "notes": "First CVC blend, past tense"
    },
    {
      "word": "sit",
      "phonemes": ["s", "i", "t"],
      "pattern": "CVC",
      "frequency_rank": 5,
      "word_type": "real",
      "decodable_with": ["s", "i", "t"],
      "difficulty": 2,
      "notes": "Common action verb"
    },
    {
      "word": "pin",
      "phonemes": ["p", "i", "n"],
      "pattern": "CVC",
      "frequency_rank": 6,
      "word_type": "real",
      "decodable_with": ["p", "i", "n"],
      "difficulty": 2,
      "notes": "Concrete noun"
    },
    {
      "word": "pan",
      "phonemes": ["p", "a", "n"],
      "pattern": "CVC",
      "frequency_rank": 7,
      "word_type": "real",
      "decodable_with": ["p", "a", "n"],
      "difficulty": 2,
      "notes": "Concrete noun, kitchen item"
    },
    {
      "word": "tin",
      "phonemes": ["t", "i", "n"],
      "pattern": "CVC",
      "frequency_rank": 8,
      "word_type": "real",
      "decodable_with": ["t", "i", "n"],
      "difficulty": 2,
      "notes": "Material/container noun"
    },
    {
      "word": "tap",
      "phonemes": ["t", "a", "p"],
      "pattern": "CVC",
      "frequency_rank": 9,
      "word_type": "real",
      "decodable_with": ["t", "a", "p"],
      "difficulty": 2,
      "notes": "Action verb or noun"
    },
    {
      "word": "nap",
      "phonemes": ["n", "a", "p"],
      "pattern": "CVC",
      "frequency_rank": 10,
      "word_type": "real",
      "decodable_with": ["n", "a", "p"],
      "difficulty": 2,
      "notes": "Common activity for young learners"
    }
  ],
  "additional_words": [
    {
      "word": "tan",
      "phonemes": ["t", "a", "n"],
      "pattern": "CVC",
      "frequency_rank": 11,
      "word_type": "real",
      "decodable_with": ["t", "a", "n"],
      "difficulty": 2,
      "notes": "Colour word"
    },
    {
      "word": "pat",
      "phonemes": ["p", "a", "t"],
      "pattern": "CVC",
      "frequency_rank": 12,
      "word_type": "real",
      "decodable_with": ["p", "a", "t"],
      "difficulty": 2,
      "notes": "Gentle touch action"
    },
    {
      "word": "pit",
      "phonemes": ["p", "i", "t"],
      "pattern": "CVC",
      "frequency_rank": 13,
      "word_type": "real",
      "decodable_with": ["p", "i", "t"],
      "difficulty": 2,
      "notes": "Hole or seed centre"
    },
    {
      "word": "tip",
      "phonemes": ["t", "i", "p"],
      "pattern": "CVC",
      "frequency_rank": 14,
      "word_type": "real",
      "decodable_with": ["t", "i", "p"],
      "difficulty": 2,
      "notes": "End point or gratuity"
    },
    {
      "word": "sap",
      "phonemes": ["s", "a", "p"],
      "pattern": "CVC",
      "frequency_rank": 15,
      "word_type": "real",
      "decodable_with": ["s", "a", "p"],
      "difficulty": 2,
      "notes": "Tree liquid"
    },
    {
      "word": "nit",
      "phonemes": ["n", "i", "t"],
      "pattern": "CVC",
      "frequency_rank": 16,
      "word_type": "real",
      "decodable_with": ["n", "i", "t"],
      "difficulty": 2,
      "notes": "Small insect egg"
    },
    {
      "word": "sin",
      "phonemes": ["s", "i", "n"],
      "pattern": "CVC",
      "frequency_rank": 17,
      "word_type": "real",
      "decodable_with": ["s", "i", "n"],
      "difficulty": 2,
      "notes": "Moral concept"
    },
    {
      "word": "sip",
      "phonemes": ["s", "i", "p"],
      "pattern": "CVC",
      "frequency_rank": 18,
      "word_type": "real",
      "decodable_with": ["s", "i", "p"],
      "difficulty": 2,
      "notes": "Small drink"
    },
    {
      "word": "asp",
      "phonemes": ["a", "s", "p"],
      "pattern": "VCC",
      "frequency_rank": 19,
      "word_type": "real",
      "decodable_with": ["a", "s", "p"],
      "difficulty": 3,
      "notes": "Type of snake, challenging blend"
    },
    {
      "word": "ant",
      "phonemes": ["a", "n", "t"],
      "pattern": "VCC",
      "frequency_rank": 20,
      "word_type": "real",
      "decodable_with": ["a", "n", "t"],
      "difficulty": 3,
      "notes": "Insect, final blend"
    },
    {
      "word": "apt",
      "phonemes": ["a", "p", "t"],
      "pattern": "VCC",
      "frequency_rank": 21,
      "word_type": "real",
      "decodable_with": ["a", "p", "t"],
      "difficulty": 3,
      "notes": "Suitable, challenging final blend"
    },
    {
      "word": "pant",
      "phonemes": ["p", "a", "n", "t"],
      "pattern": "CVCC",
      "frequency_rank": 22,
      "word_type": "real",
      "decodable_with": ["p", "a", "n", "t"],
      "difficulty": 3,
      "notes": "Heavy breathing, 4-letter word"
    },
    {
      "word": "past",
      "phonemes": ["p", "a", "s", "t"],
      "pattern": "CVCC",
      "frequency_rank": 23,
      "word_type": "real",
      "decodable_with": ["p", "a", "s", "t"],
      "difficulty": 3,
      "notes": "Time concept, final blend"
    },
    {
      "word": "pint",
      "phonemes": ["p", "i", "n", "t"],
      "pattern": "CVCC",
      "frequency_rank": 24,
      "word_type": "real",
      "decodable_with": ["p", "i", "n", "t"],
      "difficulty": 3,
      "notes": "Measurement unit"
    },
    {
      "word": "tins",
      "phonemes": ["t", "i", "n", "s"],
      "pattern": "CVCC",
      "frequency_rank": 25,
      "word_type": "real",
      "decodable_with": ["t", "i", "n", "s"],
      "difficulty": 3,
      "notes": "Plural form"
    },
    {
      "word": "pins",
      "phonemes": ["p", "i", "n", "s"],
      "pattern": "CVCC",
      "frequency_rank": 26,
      "word_type": "real",
      "decodable_with": ["p", "i", "n", "s"],
      "difficulty": 3,
      "notes": "Plural form"
    },
    {
      "word": "pans",
      "phonemes": ["p", "a", "n", "s"],
      "pattern": "CVCC",
      "frequency_rank": 27,
      "word_type": "real",
      "decodable_with": ["p", "a", "n", "s"],
      "difficulty": 3,
      "notes": "Plural form"
    },
    {
      "word": "taps",
      "phonemes": ["t", "a", "p", "s"],
      "pattern": "CVCC",
      "frequency_rank": 28,
      "word_type": "real",
      "decodable_with": ["t", "a", "p", "s"],
      "difficulty": 3,
      "notes": "Plural form or verb third person"
    },
    {
      "word": "naps",
      "phonemes": ["n", "a", "p", "s"],
      "pattern": "CVCC",
      "frequency_rank": 29,
      "word_type": "real",
      "decodable_with": ["n", "a", "p", "s"],
      "difficulty": 3,
      "notes": "Plural form"
    },
    {
      "word": "sits",
      "phonemes": ["s", "i", "t", "s"],
      "pattern": "CVCC",
      "frequency_rank": 30,
      "word_type": "real",
      "decodable_with": ["s", "i", "t", "s"],
      "difficulty": 3,
      "notes": "Verb third person"
    }
  ],
  "nonsense_words_for_assessment": [
    {
      "word": "nas",
      "phonemes": ["n", "a", "s"],
      "pattern": "CVC",
      "frequency_rank": 31,
      "word_type": "nonsense",
      "decodable_with": ["n", "a", "s"],
      "difficulty": 2,
      "notes": "Assessment - tests blending without meaning support"
    },
    {
      "word": "pis",
      "phonemes": ["p", "i", "s"],
      "pattern": "CVC",
      "frequency_rank": 32,
      "word_type": "nonsense",
      "decodable_with": ["p", "i", "s"],
      "difficulty": 2,
      "notes": "Assessment - pure decoding"
    },
    {
      "word": "tas",
      "phonemes": ["t", "a", "s"],
      "pattern": "CVC",
      "frequency_rank": 33,
      "word_type": "nonsense",
      "decodable_with": ["t", "a", "s"],
      "difficulty": 2,
      "notes": "Assessment - tests /s/ ending"
    },
    {
      "word": "san",
      "phonemes": ["s", "a", "n"],
      "pattern": "CVC",
      "frequency_rank": 34,
      "word_type": "nonsense",
      "decodable_with": ["s", "a", "n"],
      "difficulty": 2,
      "notes": "Assessment - common pattern"
    },
    {
      "word": "nip",
      "phonemes": ["n", "i", "p"],
      "pattern": "CVC",
      "frequency_rank": 35,
      "word_type": "nonsense",
      "decodable_with": ["n", "i", "p"],
      "difficulty": 2,
      "notes": "Assessment - reverse of 'pin'"
    },
    {
      "word": "nis",
      "phonemes": ["n", "i", "s"],
      "pattern": "CVC",
      "frequency_rank": 36,
      "word_type": "nonsense",
      "decodable_with": ["n", "i", "s"],
      "difficulty": 2,
      "notes": "Assessment - tests initial /n/"
    },
    {
      "word": "stin",
      "phonemes": ["s", "t", "i", "n"],
      "pattern": "CCVC",
      "frequency_rank": 37,
      "word_type": "nonsense",
      "decodable_with": ["s", "t", "i", "n"],
      "difficulty": 4,
      "notes": "Assessment - initial blend"
    },
    {
      "word": "snit",
      "phonemes": ["s", "n", "i", "t"],
      "pattern": "CCVC",
      "frequency_rank": 38,
      "word_type": "nonsense",
      "decodable_with": ["s", "n", "i", "t"],
      "difficulty": 4,
      "notes": "Assessment - /sn/ blend"
    },
    {
      "word": "spat",
      "phonemes": ["s", "p", "a", "t"],
      "pattern": "CCVC",
      "frequency_rank": 39,
      "word_type": "nonsense",
      "decodable_with": ["s", "p", "a", "t"],
      "difficulty": 4,
      "notes": "Assessment - /sp/ blend (actually a real word but less common)"
    },
    {
      "word": "snip",
      "phonemes": ["s", "n", "i", "p"],
      "pattern": "CCVC",
      "frequency_rank": 40,
      "word_type": "nonsense",
      "decodable_with": ["s", "n", "i", "p"],
      "difficulty": 4,
      "notes": "Assessment - blend (actually a real word)"
    }
  ],
  "teaching_sequence": {
    "week_1": ["at", "it", "in"],
    "week_2": ["sat", "sit", "pin", "pan"],
    "week_3": ["tin", "tap", "nap", "tan", "pat"],
    "week_4": ["pit", "tip", "sap", "nit", "sin"],
    "week_5": ["ant", "apt", "asp"],
    "week_6": ["pant", "past", "pint"],
    "plurals_practice": ["tins", "pins", "pans", "taps", "naps", "sits"],
    "assessment": ["nas", "pis", "tas", "san", "nip", "nis"]
  },
  "assessment_notes": {
    "mastery_criteria": "90% accuracy on 7 core words",
    "progression_gate": "Must read 'sat', 'pin', 'sit' fluently before adding new letters",
    "common_errors": [
      "Reversing 'in' to 'ni'",
      "Confusing 'p' and 'b' in 'pan'",
      "Struggling with final 'n' in continuous sound"
    ]
  }
}
```

## 🎯 Implementation Notes

### Flashcard Generation Logic
```javascript
// Pseudocode for app implementation
function generateSATPINCards(studentLevel) {
  if (studentLevel === 'beginner') {
    return words.filter(w => w.difficulty === 1);
  } else if (studentLevel === 'developing') {
    return words.filter(w => w.difficulty <= 2);
  } else {
    return [...words, ...extension_words];
  }
}
```

## 🔗 Related Documents
- **Research basis**: [[memory://01-research/research-docs/systematic-phonics-sequencing-best-practices]] - RD-003
- **Next sequence**: [[memory://01-research/resources/consonant-set-1-words]] - MDGOCK words (planned)
- **Implements**: [[memory://01-research/research-docs/eb-teaching-guide-phonics-bilingual-hk]] - RD-001 methodology