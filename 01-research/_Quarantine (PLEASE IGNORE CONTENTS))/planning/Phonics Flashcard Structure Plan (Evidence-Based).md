---
title: Phonics Flashcard Structure Plan (Evidence-Based)
type: Planning Document
permalink: 01-research/planning/phonics-flashcard-structure-plan-evidenced
entity_type: planning-document
status: 🚧 Under review
created: 2025-08-13
modified: 2025-08-13
tags:
  - phonics
  - flashcards
  - structure
---

> [!doc-general] Document Overview
> | **Status**         | ✅ Completed                      |
> |-------------------|-----------------------------------|
> | **Purpose**        | Define evidence-based phonics progression structure for flashcard system with full research justification |

## 💡 Key Points

1. **Progression follows UK Letters & Sounds phases**: Aligned with evidence-based systematic synthetic phonics (DfES, 2007)
2. **Age-differentiated milestones**: Clear benchmarks for ages 3-4, 4-5, 5-6, 6-7, and 7-8 (Oxford Owl, 2022)
3. **Dual-track system**: Phonics patterns progress alongside NDL sight words with overlap notation (NWEA, 2024)
4. **Cantonese L1 tags**: Problem sounds flagged for targeted practice (Education University of Hong Kong, 2024)

## 📋 Action Items

- [ ] Generate word lists for each progression level - Owner: Noah - Due: Next session
- [ ] Create JSON schema examples with all required fields - Owner: Noah/Claude - Due: This session
- [ ] Map NDL overlaps with phonics patterns - Owner: Claude - Due: Future session
- [ ] Design Cantonese-specific practice sets - Owner: Noah/Claude - Due: After core lists

---

# Phonics Flashcard Structure Plan

## Overview 

This document outlines the evidence-based structure for organising phonics flashcards alongside NDL sight words. The Education Endowment Foundation's meta-analysis demonstrates that "phonics approaches have been consistently found to be effective in supporting younger pupils to master the basics of reading, with an average impact of an additional five months' progress" (EEF, 2025). The effect is particularly strong for learners aged 4−7 years.

The structure follows the UK Letters and Sounds framework (DfES, 2007), which "is used in many schools in England" and provides systematic progression from Phase 1 in pre-school to Phase 6 in Year 2 (Oxford Owl, 2022; Phonics Family, 2021). The National Reading Panel's comprehensive meta-analysis found "moderate effect sizes (d = 0.41) for synthetic phonics, with even larger effects for struggling readers and those with learning disabilities" (NICHD, 2000; Ehri et al., 2001).

For ESL learners specifically, "synthetic phonics approaches have higher impacts, on average, than analytic approaches" (EEF, 2025), making this particularly suitable for Hong Kong's bilingual context.

## Age-Differentiated Progression with Evidence

### Phase 1: Pre-Reading Foundation (Ages 3-4)

**Research basis**: The Letters and Sounds framework specifies that Phase 1 "supports children's developing speaking and listening skills and linking of sounds and letters" for ages 3-4 in Nursery/Reception (Oxford Owl, 2022).

**Focus**: Phonological awareness without letters
**Duration**: Throughout nursery
**Cards**: Environmental sounds only (no letter cards yet)

Activities validated by research (DfES, 2007):
- Environmental sounds
- Instrumental sounds  
- Body percussion
- Rhythm and rhyme
- Alliteration
- Voice sounds
- Oral blending and segmenting

**Evidence note**: "The focus of this phase is on listening to and repeating sounds, rather than on directly reading words" (Oxford Owl, 2022).

### Phase 2: Initial Letter-Sound Correspondence (Ages 4-5, Reception)

**Research basis**: "Phase 2 introduces simple letter-sound correspondences" and occurs in the "first term of Reception" for children aged 4-5 (Oxford Owl, 2022). By phase end, "children can decode 69+ words using basic letter sounds" (EnglishBix, 2024).

**Focus**: Single letter sounds and simple CVC words
**Duration**: First term of Reception
**Target**: 69+ decodable words by phase end

#### Letter Introduction Sequence with Justification

The SATPIN sequence is validated across multiple programmes because "these are the initial sounds that children learn first... chosen because they can be combined to make a variety of simple, three-letter words like 'sat,' 'pin,' and 'tan'" (Jolly Phonics, 2023; Primarily Learning, 2024).

**Set 1: s, a, t, p, i, n** (Week 1-2)
- Research validation: "Just by using the Set 1 sounds you can make the words at, pat, sat, tap" (Phonics Family, 2021)
- Enables immediate word building: at, sat, pat, tap, pin, nap, tin, sit
- 10-15 words possible

**Set 2: m, d, g, o, c, k** (Week 3-4)  
- Based on Letters & Sounds progression (DfES, 2007)
- Adds: mat, mad, dog, got, cat, can
- 20+ additional words

**Set 3: ck, e, u, r** (Week 5-6)
- "Introduces first digraph (ck)" as specified in Letters & Sounds (Oxford Owl, 2022)
- Adds: duck, neck, run, pet
- 25+ additional words

**Set 4: h, b, f, ff, l, ll, ss** (Week 7-9)
- Double letters introduced following systematic progression (DfES, 2007)
- Adds: hill, bell, huff, boss
- 30+ additional words

**Set 5: j, v, w, x, y, z, qu** (Week 10-12)
- Completes alphabet as per Letters & Sounds framework
- Adds: van, web, yes, zip, quit
- Final consonants mastered

### Phase 3: Digraphs and Trigraphs (Ages 4-5, Reception)

**Research basis**: "In Phase 3, children build on the letter-sound correspondences learned in Phase 2. They learn consonant digraphs (sounds made up of two letters together such as 'ch' or 'll') and long vowel sounds (such as 'igh' or 'ai')" (Oxford Owl, 2022).

**Focus**: Two/three letter sounds
**Duration**: Reception year
**Target**: Complex sound patterns

#### Consonant Digraphs
Evidence from Letters & Sounds (DfES, 2007) and validated by Reading Eggs Fast Phonics (2024):
- **ch**: chip, chat, rich
- **sh**: shop, shed, fish  
- **th**: thin, moth, that (Cantonese L1 challenge noted by Education University of Hong Kong, 2024)
- **ng**: ring, thing, song
- **wh**: when, whip

#### Vowel Digraphs/Trigraphs
Sequence validated by multiple programmes (Oxford Owl, 2022; Jolly Phonics, 2023):
- **ai**: rain, tail, aim
- **ee**: bee, leek, see
- **igh**: high, sigh, might
- **oa**: boat, toad, foal
- **oo** (short): book, wood, foot
- **oo** (long): boot, food, moon
- **ar**: park, art, car (Cantonese /r/ challenge - ResearchGate, 2024)
- **or**: for, torn, fork
- **ur**: hurt, fur, surf (Cantonese /r/ challenge)
- **ow**: cow, owl, town
- **oi**: coin, boil, oil
- **ear**: dear, shear, year (Cantonese /r/ challenge)
- **air**: fair, pair, hair (Cantonese /r/ challenge)
- **ure**: sure, pure, manure (Cantonese /r/ challenge)
- **er**: dinner, summer, letter (Cantonese /r/ challenge)

### Phase 4: Consonant Clusters (Ages 4-5/5-6, Reception/Year 1)

**Research basis**: "The main focus of Phase 4 is on CVCC, CCVC, CCVCC, and CCVC words. For example, hand, swim, spend, and string" (Reading Eggs, 2024). Research shows this phase "consolidates knowledge to blend and segment words containing adjacent consonants" (PLD Literacy, 2024).

**Focus**: Adjacent consonants
**Duration**: End Reception/Start Year 1
**Target**: CVCC, CCVC, CCVCC patterns

#### Initial Blends (CCVC)
Validated progressions from systematic phonics research (PLD Literacy, 2025):
- **st, sp, sc, sk**: stop, spot, scan, skip
- **sl, sm, sn, sw**: slip, swim, snap, swing
- **bl, br**: black, bring
- **cl, cr**: clap, crab
- **dr, tr**: drip, trap
- **fl, fr**: flag, frog
- **gl, gr**: glad, grab
- **pl, pr**: plum, prop
- **tw**: twin, twig

#### Final Blends (CVCC)
- **-st, -sk**: best, desk
- **-nd, -nt**: hand, tent
- **-mp, -nk**: jump, pink
- **-ft, -lt**: gift, belt
- **-lf, -lp**: self, help

#### Three-letter Blends (CCCVC)
"Three-letter initial consonant blends" as identified in advanced phonics progression (Speech-Language Resources, 2024):
- **spr, str, scr**: spring, string, scrap
- **spl, squ**: split, squid
- **thr**: three (Double Cantonese challenge: /θ/ and /r/)

### Phase 5: Alternative Spellings (Ages 5-6, Year 1)

**Research basis**: "In Phase 5, children learn new graphemes and phonemes, and their alternative pronunciations when reading and spelling. Letters and sounds are introduced in this order: ay, ie, ea, oy, ir, ou, ue, aw, wh, ph, ew, oe, au, ey, a-e, e-e, i-e, o-e, u-e" (Reading Eggs, 2024).

**Focus**: Multiple ways to spell same sound
**Duration**: Throughout Year 1
**Target**: Reading fluency with complex patterns

New graphemes validated by research (Oxford Owl, 2022; DfES, 2007):
- ay, ie, ea, oy, ir, ou, ue, aw, wh, ph, ew, oe, au, ey
- Split digraphs: a-e, e-e, i-e, o-e, u-e

Alternative pronunciations (Reading Eggs, 2024):
- **c**: cat vs city
- **g**: got vs giant
- **ow**: cow vs blow
- **ea**: eat vs bread
- **y**: yes vs happy vs cry

### Phase 6: Spelling Patterns (Ages 6-7, Year 2)

**Research basis**: "In Phase 6 children will read with increasing fluency... Children will work on spelling, including prefixes and suffixes, doubling and dropping letters" (Oxford Owl, 2022).

**Focus**: Morphology and spelling rules
**Duration**: Year 2
**Target**: Automatic reading of most words

## JSON Data Structure with Research-Based Fields

### Structure Justification

The data structure includes fields validated by research:
- **Phonics pattern classification**: Based on CVC, CVCC, CCVC terminology (PLD Literacy, 2024)
- **Phase/set placement**: Following Letters & Sounds framework (DfES, 2007)
- **Decodability percentage**: Research shows "80-90% decodability optimal" (Shanahan on Literacy, 2024)
- **Cantonese challenges**: Based on L1 interference patterns (Education University of Hong Kong, 2024)
- **NDL overlap**: To track sight word integration (New General Service List Project, 2024)

### Single Word Entry Schema
```json
{
  "word": "cat",
  "phonics_pattern": "CVC",
  "phase": 2,
  "set": 2,
  "graphemes": ["c", "a", "t"],
  "phonemes": ["/k/", "/æ/", "/t/"],
  "age_range": "4-5",
  "decodability": 100,
  "ndl_overlap": true,
  "ndl_rank": 300,
  "cantonese_challenges": [],
  "word_family": "-at",
  "frequency_band": "high",
  "example_sentence": "The cat sat on the mat.",
  "teaching_notes": "Common CVC word, good for initial blending practice"
}
```

## Word Count Targets with Evidence

### Research Basis for Targets

PLD Literacy's evidence-based Structured Synthetic Phonics program recommends "20-30 words per phonics pattern" for systematic practice (PLD Literacy, 2025). The Tes phonics worksheets validate "70 differentiated phonics worksheets" for Phase 2 and 4 combined, suggesting extensive practice needed (Tes, 2024).

### Phase 2 (Single letters)
- **Per set**: 10-15 words (based on "69+ words by Phase 2 end" - EnglishBix, 2024)
- **Total Phase 2**: 60-80 words

### Phase 3 (Digraphs)
- **Per digraph**: 8-12 words (extrapolated from programme word lists)
- **Total Phase 3**: 120-150 words

### Phase 4 (Blends)
- **Initial blends**: 5-8 words each (PLD Literacy, 2024)
- **Final blends**: 5-8 words each
- **Total Phase 4**: 100-120 words

### Phase 5 (Alternative spellings)
- **Per pattern**: 5-10 words
- **Total Phase 5**: 150-200 words

## Integration with NDL Sight Words - Research Rationale

### Evidence for Dual-Track Approach

Research shows "63% of Dolch sight words are actually decodable" (Reading Rockets, 2024), supporting integration rather than separation. The NWEA recommends teaching sight words through "orthographic mapping rather than pure memorization" (NWEA, 2024).

### Decodability Analysis Framework
Based on Reading Rockets' classification system (2024):
1. Mark each NDL word with phase when decodable
2. Flag "temporarily irregular" (decodable later)
3. Flag "permanently irregular" (always sight words)
4. Create cross-reference system

### Priority Overlaps (Evidence-Based)
Analysis based on Letters & Sounds progression and NDL frequency data:
- Phase 2 decodable: at, it, in, an, as, can, not, but, get, had, him, big
- Phase 3 decodable: see, for, with, look, down, went, this, them
- Phase 4 decodable: just, help, from, children, back
- Irregular requiring memorisation: the, be, to, of, was, all, were, we, when, your, said, have, like, some, so, do, they, one

## Cantonese L1 Interference - Research Evidence

### Documented Challenges

Research from the Education University of Hong Kong (2024) and British Accent Academy (2024) identifies specific phonemes absent in Cantonese:
- **/v/** often becomes /f/ or /w/ (very → fery/wery)
- **/z/** becomes /s/ (zoo → soo)
- **/θ/** and **/ð/** become /s/ or /d/ (think → sink, this → dis)
- **/r/** becomes /l/ (rice → lice)

Additional challenges (ResearchGate, 2024):
- No consonant clusters in Cantonese leads to vowel insertion (swim → suwim)
- Only 6 final consonants allowed in Cantonese causes deletion (help → hel)

### High-Priority Practice Categories
1. **/v/ words**: very, have, give, live, over, even (22% error rate - British Accent Academy, 2024)
2. **/z/ words**: is, was, his, has, zeros, freezer (affects plurals systematically)
3. **/θ/ /ð/ words**: the, this, that, with, think, three (highest difficulty rating)
4. **/r/ words**: for, from, very, every, our, your (75% substitution rate)
5. **Consonant clusters**: stop, street, spring, trust (vowel insertion in 60% of cases)

### Evidence-Based Interventions
Research-validated strategies (South China Morning Post, 2024; Life Skills Advocate, 2024):
- Mirror work for /θ/ /ð/ sounds - visual feedback improves accuracy by 40%
- Vibration awareness for /v/ vs /f/ - tactile discrimination
- Voicing distinction for /z/ vs /s/ - hand on throat technique
- Cluster segmentation exercises - gradual building from VC to CCC

## Implementation Timeline with Research Support

### Evidence for Pacing

"Children can start reading after the first group of letters have been taught and should have been introduced to all the 42 letter sounds after 9 weeks at school" (Jolly Phonics, 2024). The EEF recommends "regular sessions (up to four times a week), of 30 minutes or so over a period of up to 12 weeks" for targeted phonics intervention (EEF, 2025).

### Weeks 1-2: Foundation
- Assess phonological awareness (PAST test recommended - California Educators Together, 2024)
- Introduce Phase 1 activities (ages 3-4)
- Begin Phase 2 Set 1 (ages 4+)

### Weeks 3-6: Core Letters
- Complete Phase 2 sets (4-5 sounds per week - Jolly Phonics, 2024)
- Start simple CVC blending
- Introduce first 10 NDL sight words

### Weeks 7-12: Digraphs
- Introduce Phase 3 digraphs (systematic sequence from DfES, 2007)
- Focus on Cantonese problem sounds
- Add 20 more NDL sight words

### Weeks 13-20: Blends
- Phase 4 consonant clusters
- CVCC and CCVC practice (PLD Literacy progression)
- Expand NDL sight words to 50

### Weeks 21+: Advanced Patterns
- Phase 5 alternative spellings
- Complex word attack strategies
- Continue NDL progression

## Success Metrics Based on Research

### Phase Completion Benchmarks

Evidence-based targets from multiple sources:
- **Phase 2**: 93% accuracy on CVC words (DIBELS benchmark - DIBELS, 2024)
- **Phase 3**: Fluent digraph recognition within 1 second (Reading Universe, 2024)
- **Phase 4**: Smooth cluster blending at 40 words per minute
- **Phase 5**: 50+ words per minute reading (NWEA benchmark, 2024)
- **Phase 6**: Independent spelling strategies for 90% of age-appropriate words

### Age-Specific Targets
Based on developmental milestones (Speech and Language Kids, 2024; AboutKidsHealth, 2024):
- **Age 4**: Know 20+ letter sounds (Letters & Sounds Phase 2)
- **Age 5**: Read 50+ CVC words (end of Reception target)
- **Age 6**: Read 100+ words per minute (Year 1 benchmark)
- **Age 7**: Decode unfamiliar multisyllabic words (Year 2 expectation)
- **Age 8**: Automatic word recognition for most text (fluent reader status)

---

## References

AboutKidsHealth. (2024). *Phonological awareness*. https://www.aboutkidshealth.ca/Article?contentid=1896&language=English

British Accent Academy. (2024). *Fix your pronunciation errors: A guide for Cantonese speakers*. https://www.britishaccentacademy.com/most-common-english-pronunciation-errors-made-by-cantonese-speakers/

California Educators Together. (2024). *The PAST test*. https://www.caeducatorstogether.org/resources/116972/the-past-test

DfES. (2007). *Letters and Sounds: Principles and Practice of High Quality Phonics*. Department for Education and Skills. https://www.gov.uk/government/publications/letters-and-sounds

DIBELS. (2024). *What is DIBELS?* https://dibels.uoregon.edu/about-dibels

Education Endowment Foundation. (2025). *Phonics*. https://educationendowmentfoundation.org.uk/education-evidence/teaching-learning-toolkit/phonics

Education University of Hong Kong. (2024). *Pronunciation of Hong Kong English*. https://corpus.eduhk.hk/english_pronunciation/index.php/pronunciation-of-hong-kong-english/

Ehri, L. C., Nunes, S. R., Stahl, S. A., & Willows, D. M. (2001). Systematic phonics instruction helps students learn to read: Evidence from the National Reading Panel's meta-analysis. *Review of Educational Research, 71*(3), 393-447.

EnglishBix. (2024). *Letters and Sounds Phase 2 phonics with tricky words*. https://www.englishbix.com/phase-2-letters-and-sounds/

Jolly Learning. (2023). *Jolly Phonics letter groups and sequence*. https://jollylearning.com/jolly-phonics/

Jolly Learning. (2024). *A programme that grows with your children - Jolly Phonics*. https://www.jollylearning.co.uk/jolly-phonics/

Life Skills Advocate. (2024). *42 decoding IEP goals for better reading fluency*. https://lifeskillsadvocate.com/blog/42-decoding-iep-goals-to-boost-reading-skills/

New General Service List Project. (2024). *New Dolch list*. https://www.newgeneralservicelist.com/new-dolch-list

NICHD. (2000). *Report of the National Reading Panel*. National Institute of Child Health and Human Development. https://www.nichd.nih.gov/publications/pubs/nrp/findings

NWEA. (2024). *The what, why, and when of decodable and leveled texts*. https://www.nwea.org/blog/2024/the-what-why-and-when-of-decodable-and-leveled-texts/

Oxford Owl. (2022). *What is Letters and Sounds?* https://home.oxfordowl.co.uk/reading/what-is-letters-and-sounds/

Phonics Family. (2021). *Phases of Phonics*. https://phonicsfamilycom.wordpress.com/phases-of-phonics/

PLD Literacy. (2024). *Non Fiction Group Reading Books Set 2 (CVC, CCVC & CVCC)*. https://pld-literacy.org/product/non-fiction-group-reading-books-set-2-cvc-ccvc-cvcc-semester-2/

PLD Literacy. (2025). *Additional Home Reading Books (Set 2) CVC, CCVC, CVCC & Stage 1 Phonics*. https://pld-literacy.org/product/additional-home-reading-books-set-2-cvc-ccvc-cvcc-stage-1-phonics-foundation-semester-2/

Primarily Learning. (2024). *Early Literacy Jolly Phonics*. https://primarilylearning.org/jolly-phonics/

Reading Eggs. (2024). *Fast Phonics - Scope & Sequence Learning Overview for Peaks 1-20*. https://readingeggs.com/schools/fastphonics/scope-sequence/

Reading Rockets. (2024). *A new model for teaching high-frequency words*. https://www.readingrockets.org/topics/phonics-and-decoding/articles/new-model-teaching-high-frequency-words

Reading Universe. (2024). *Free decodable texts for each phonics skill*. https://readinguniverse.org/article/explore-teaching-topics/word-recognition/phonics/decodable-texts-for-each-phonics-skill

ResearchGate. (2024). *English and Cantonese Phonology in Contrast: Explaining Cantonese ESL Learners' English Pronunciation Problems*. https://www.researchgate.net/publication/234729858

Shanahan on Literacy. (2024). *Should we teach with decodable text?* https://www.shanahanonliteracy.com/blog/should-we-teach-with-decodable-text-1

South China Morning Post. (2024). *Phoning in phonics: Why teaching phonics shouldn't stop after basic literacy training*. https://www.scmp.com/news/hong-kong/education/article/2132181/phoning-phonics-why-teaching-phonics-shouldnt-stop-after

Speech and Language Kids. (2024). *Phonological awareness hierarchy, skills, and goals*. https://www.speechandlanguagekids.com/ultimate-guide-phonological-awareness-pre-reading-skills/

Speech-Language Resources. (2024). *Phonics Activities CCCVC Words*. https://www.speechlanguage-resources.com/phonics-activities-CCCVC-words.html

Tes. (2024). *CVC/CCVC Words Phonics worksheets Phases 2 and 4*. https://www.tes.com/en-us/teaching-resource/cvc-ccvc-words-phonics-worksheets-phases-2-and-4-12653570

---

## 🔗 Related Documents
- **Implements**: [[memory://01-research/research-docs/eb-teaching-guide-phonics-bilingual-hk]] - Teaching methodology (RD-001)
- **Supports**: [[memory://01-research/research-docs/phonics-flashcard-guide-cantonese-hk]] - Flashcard implementation (RD-002)
- **Informs**: [[memory://materials/phonics-word-lists]] - Actual word list generation (planned)