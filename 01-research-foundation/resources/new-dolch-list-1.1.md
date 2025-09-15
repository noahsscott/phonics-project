---
type: Resource Data
permalink: 01-research/resources/new-dolch-list-1.1-1
entity_type: resource-data
status: 🚧 Under review
created: 2025-08-07
modified: 2025-08-09
tags:
- resource
- sight-words
- high-frequency-words
---

> [!doc-resource] Resource Overview
> | **Source**        | New General Service List Project          |
> |-------------------|-------------------------------------------|
> | **Published**     | 15/02/2023                               |
> | **Version**        | 1.1                                       |
> | **Licence**        | Creative Commons                                      |
> | **Source URL**       | https://www.newgeneralservicelist.com/new-dolch-list                            |


## 🔍 What is this resource?
The New Dolch List (NDL) is a collection of high-frequency English vocabulary commonly used to teach children to read. It's an updated, evidence-based revision of the original Dolch sight words list (1936-1948), specifically designed for modern English usage and ESL learners. These words appear most frequently in children's books, educational materials, and media. Learning to recognise them automatically facilitates reading fluency and comprehension.


## 🎨 How can I use it?
Use the NDL to:
1. **Create flashcard sets** - Group sight words by frequency bands (1-100, 101-300, etc.) for systematic teaching
2. **Complement phonics** - Effective instruction requires a mix of decodable phonics words AND sight words
3. **Assess competency** - Track mastery of high-frequency words using rank numbers and coverage milestones


## 🎯 Why was it selected?
- **Modern coverage**: Provides 90% coverage of current children's texts and media (vs 70% for outdated 1936 Dolch list)
- **ESL/Hong Kong context**: Designed for ESL learners; addresses irregular words that Cantonese L1 speakers cannot decode phonetically
- **Data-driven**: Includes frequency data (SFI scores and per-million counts) enabling prioritised teaching
- **Alignment**: Supports dual approach of phonics instruction + sight word recognition for reading fluency


## 📚 Research Basis
- **Why frequency matters**: Children need to know at least 95% of words in a text to successfully guess meaning of unknown words from context (Nation & Waring, 1997)
- **Why sight words work**: When children connect letters to sounds, words become stored in memory with their pronunciations and meanings, enabling instant recognition (Ehri, 2020)
- **Why ESL learners benefit**: The same systematic phonics and sight word instruction that works for native speakers also helps English language learners develop literacy skills (August & Shanahan, 2006)
- **Why automaticity is crucial**: Fast, accurate word recognition frees up mental resources for understanding what the text means rather than decoding individual words (Perfetti, 1985)


## 📈 Quick Stats & Summary
- **Total entries**: 874 words (NDL 1.1)
- **Frequency range**: 58,062 per million ("the") to 111 per million ("peek")
- **Coverage statistics** (verified from official sources):
  - **315 words = 78% coverage**: Children recognise roughly 8 out of 10 words in the corpus materials surveyed by the NDL
  - **875 words = 90% coverage**: Children recognise 9 out of 10 words in children's texts (threshold needed for comprehension)
  - **Higher coverage for media**: Even greater than 90% for children's TV and YouTube videos
- **Notable inclusion**: "flashcard" appears at rank 555, reflecting modern educational contexts
- **Comparison**: Original Dolch list (315 words) claimed 70% coverage without empirical verification



## Data

#### 📋 Data Structure
| Field            | Type    | Description                    | Notes                                                   |
| ---------------- | ------- | ------------------------------ | ------------------------------------------------------- |
| Rank             | Integer | Word frequency ranking (1-874) |                              |
| Word             | String  | The sight word                 | Some entries are lemmas (e.g., "be" includes am/is/are) |
| SFI              | Float   | Standard Frequency Index       | Higher SFI = more frequent (logarithmic scale)          |
| U (Freq/million) | Integer | Occurrences per million words  |                   |

![[New Dolch List 1.1.csv]]

---

## 🔍 Implementation Notes

### Integration with Teaching Method:
- **SATPIN alignment**: Identify NDL words that are decodable using current phonics progression
- **Tricky words**: Introduce high-frequency irregular words as sight words requiring memorisation
- **Dual coding**: Teach decodable parts of irregular words (e.g., in "the", /th/ is decodable)
- **Contextual learning**: Always present sight words within meaningful sentences initially
- **Progress tracking**: Maintain separate records for phonics decoding vs sight word recognition

## ❗Limitations & Considerations
- **Irregular spellings**: Many high-frequency words (the, of, was, said) cannot be fully decoded using phonics rules
- **Corpus variation**: Frequency data based on general corpus; specific books/materials may vary significantly
- **L1 interference for Cantonese speakers**: Common pronunciation challenges include /v/ (very, have), /z/ (is, was), th sounds /θ/ /ð/ (the, this, that), and /r/ (for, from). Children with more English exposure at home may have fewer challenges
- **Contextual considerations**: Not all 874 words are developmentally appropriate for youngest learners (e.g., "adjective" at rank 711), and some require cultural adaptation for Hong Kong students (e.g., "cookie" vs "biscuit")


---

## 📝 Appendices

### About this resource:
- **Methodology**: NDL is based on a carefully selected, 2.5-million-word corpus of children’s reading and listening materials across:
	- 991,104 Children's books,
	- 575,976 EFL Textbooks,
	- 548,172 Top kids YouTube videos,
	- 322,169 Middle-school textbooks,
	- 13,347 L1 Picture-books, and
	- 4,623 Elementary EFL textbooks (MEXT)
- **Updates**: Version 1.1 includes refinements based on educator feedback and ESL learner data

### References:
- (August, D. & Shanahan, T. (Eds.), 2006, Developing Literacy in Second-Language Learners: Report of the National Literacy Panel on Language-Minority Children and Youth, Lawrence Erlbaum Associates)
- (Ehri, L.C., 2020, "The Science of Learning to Read Words: A Case for Systematic Phonics Instruction" in Reading Research Quarterly, 55(S1), pp. S45-S60)
- (Nation, P. & Waring, R., 1997, "Vocabulary Size, Text Coverage and Word Lists" in Vocabulary: Description, Acquisition and Pedagogy, Cambridge University Press, pp. 6-19)
- (Perfetti, C.A., 1985, Reading Ability, Oxford University Press)