---
title: Updated Project Context Handover Template v2
type: Template
permalink: 00-project-overview/ai-guides/context-handover-template-1
entity_type: template
status: ✅ Completed
created: 2025-08-07
modified: 2025-08-26
tags:
- template
- handover
---

> [!abstract] Purpose
> This template provides essential project context for new Claude conversations. Copy and paste the content below (between the dividers) to quickly bring Claude up to speed on the Phonics and Flashcards Project.

---
## 📋 COPY FROM HERE ──────────────────────

# Project Context: Phonics and Flashcards Project

Before anything else, please switch to the "phonics-project" basic memory project, which is located at: /Users/noahscott/Documents/Basic Memory/phonics-project. If you cannot find it do let me know and we will locate it prior to anything further.

## ⚡ Quick Reference
- **UK English** | **DD/MM/YYYY dates** | **24-hour time** | **Metric only**
- **Concise > Complete** | **Specific > Vague** | **Simple > Complex**
- **Verify facts** | **Cite sources** | **No imaginary data**

## Collaboration Principles
- **Discuss before editing**: Always review proposed changes together in chat before modifying any documents
- **Version control**: When updating existing documents, keep the original and create a new version for comparison
- **Start simple**: Begin with minimal structure, add complexity only when needed
- **Verify facts**: Flag anything that needs fact-checking rather than guessing
- **Conciseness matters**: Combine related points, avoid redundancy
- **10-second rule**: Document purpose must be clear within 10 seconds

## Project Overview
I'm developing an evidence-based phonics teaching system using flashcards for children aged 3-8 in Hong Kong. The project focuses on one-on-one tutoring in home settings (60-90 minute sessions) for bilingual children (Cantonese-English speakers).

## Current Project Status
- **Phase**: Content development and refinement
- **Completed Research**: 
  - RD-001: Teaching methodology guide (synthetic phonics approach chosen)
  - RD-002: Flashcard implementation guide (word lists and progressions)
  - RD-003: Systematic Phonics Sequencing Best Practices
- **Completed Resources**:
  - SATPIN Foundation Words v2 (WL-001) with 36 real words + 10 nonsense
  - JSON data structure for programmatic word list access
- **Current Focus**: Expanding word lists to next phonics groups and creating teaching materials

## Key Project Decisions Made
1. **Methodology**: Synthetic phonics (60%) with analytic support (30%)
2. **Progression**: SATPIN sequence → UK Letters & Sounds phases
3. **Flashcard Specs**: 3"×5" cards, no pictures, black text on white
4. **Sight Words**: Using New Dolch List (875 words) for ESL learners
5. **Decodability Standard**: 80-90% decodable text for practice materials
6. **Word List Structure**: JSON format with patterns, tiers, and L1 challenges tracked

## Technical Context
- Using Basic Memory for knowledge management
- Documents organised in Obsidian-style markdown
- Project structure:
  - 00-project-overview/ (project briefs, templates, guides)
  - 01-research-foundation/ (research documents, resources, templates)
  - 01-research-foundation/resources/ (word lists and data)
  - 05-phonics/ (SATPIN and phonics materials)
- Data in clean JSON format for future applications
- Planning for future flashcard generator application

## Target Audience Specifics
- **Age**: 3-8 years old
- **Language**: Bilingual (Cantonese-English), no Mandarin focus needed
- **Setting**: Home tutoring, one-on-one
- **Challenges**: L1 interference from Cantonese (missing phonemes: /v/, /z/, /θ/, /ð/, /r/)
- **Special Considerations**: Some learners may have dyslexia

## Documentation Style & Quality Standards
- **Style Guide**: Follow [[memory://00-project-overview/ai-guides/project-style-guide]] for all documentation
- **Core principle**: Clarity beats completeness - be concise and specific
- **UK English**: Use UK spelling (recognise, prioritise, centre) and DD/MM/YYYY date format
- **Evidence-based**: Verify all facts, cite sources properly, no imaginary content
- **Action items**: Must be specific enough to delegate tomorrow

## Document Standards & Templates
- **Research docs**: External research, preserve original content, use [[memory://01-research-foundation/templates/research-doc-template]]
- **Resource docs**: Data/word lists, concise with practical focus, use [[memory://01-research-foundation/templates/resource-doc-template]]
- **General docs**: Internal project docs, minimal structure, use [[memory://01-research-foundation/templates/general-doc-template]]
- **Quality focus**: Every section must add value - if not, remove it
- **Memory features**: Use sparingly, only for major decisions and direct dependencies

## Current Priorities
1. Develop Group 1.2 word lists (c/k, e, h, r, m, d)
2. Create teaching sequence for blending SATPIN + Group 1.2
3. Design assessment rubrics for progress tracking
4. Build Cantonese-specific error correction materials
5. Create decodable reading passages using completed word lists

## At the end of the session
I will close the session manually and notify you (alternatively if we get close to context limits please notify me and we will close the session), at which point:
- Please provide any updates to this document that are needed, eg. any changes that would impact the 'Current Project Status' or 'Key Project Decisions Made' areas etc.
- And a commit message that I can use for backing up the project to gh

## Essential References
### Project Documents
- Project Brief: [[00-project-overview/project-brief]]
- Teaching Guide (RD-001): [[01-research-foundation/research-docs/RD-001-teaching-guide-phonics-bilingual-hk]]
- Flashcard Guide (RD-002): [[01-research-foundation/research-docs/RD-002-flashcard-guide-cantonese-hk]]
- Systematic Phonics Sequencing Best Practices (RD-003): [[01-research-foundation/research-docs/RD-003-systematic-phonics-sequencing]]
- NDL Resource: [[01-research-foundation/resources/new-dolch-list-1.1]]

### Word Lists & Data
- SATPIN Foundation Words v2: [[05-phonics/05.1-satpin-mastery/resources/satpin-foundation-words-v2]]
- SATPIN JSON Data: [[05-phonics/05.1-satpin-mastery/data/satpin-words-data]]

### Templates & Guides
- Style Guide: [[00-project-overview/ai-guides/project-style-guide]]
- Research Template: [[01-research-foundation/templates/research-doc-template]]
- Resource Template: [[01-research-foundation/templates/resource-doc-template]]
- General Template: [[01-research-foundation/templates/general-doc-template]]

## What I Need Help With
<!-- Be specific using this format: -->
**Task**: [What needs to be done]
**Document(s)**: [Which documents to work with]
**Constraints**: [Any specific requirements or limitations]
**Expected outcome**: [What success looks like]
**Style notes**: [Any departures from standard style guide]

## ──────────────────── COPY TO HERE 📋

---

## 📝 Usage Instructions

1. **Copy the content** between the dividers above
2. **Paste at the start** of your new Claude conversation
3. **Fill in the "What I Need Help With"** section with specifics for your session
4. **Add any additional context** specific to current work not captured in template
5. **Reference specific documents** if the task requires them

## 💡 Tips for Effective Handovers

### DO:
- **Be specific** about what you need in the current session
- **State if you want comparison versions** when updating documents
- **Reference exact document paths** when working on specific files
- **Mention recent changes** not captured in the template
- **Include examples** of the output format you want

### DON'T:
- **Don't be vague** - "improve this" vs "make this more concise by combining related points"
- **Don't skip context** - Claude needs to know what stage you're at
- **Don't forget constraints** - mention deadlines, length limits, specific requirements

## 🔄 Maintaining This Template

Update this template when:
- Major project decisions are made
- New research documents are completed
- Project phase changes
- Technical approach evolves
- New document types or templates are added
- Style guide receives significant updates
- New word lists or resources are completed

### Version Control Note
When updating this template:
1. Create a new version with updated suffix (e.g., -v2, -v3)
2. Compare changes before replacing the main template
3. Update the modified date
4. Note significant changes below

### Change Log
- **26/08/2025 (v2)**: Added RD-003, SATPIN Foundation Words v2, JSON data structure, updated priorities, added Word Lists & Data section
- **09/08/2025 (v1)**: Added style guide reference, collaboration principles, and structured request format
- **07/08/2025**: Initial template creation

---

*Last updated: 26/08/2025 - Added completed SATPIN resources, RD-003, JSON data structure, and updated project priorities*