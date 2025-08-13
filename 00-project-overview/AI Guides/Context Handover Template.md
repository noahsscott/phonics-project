---
title: Updated Project Context Handover Template
type: Template
permalink: 00-project-overview/ai-guides/context-handover-template
entity_type: template
status: ✅ Completed
created: 2025-08-07
modified: 2025-08-13
tags:
  - template
  - handover
  - context
---

> [!abstract] Purpose
> This template provides essential project context for new Claude conversations. Copy and paste the content below (between the dividers) to quickly bring Claude up to speed on the Phonics and Flashcards Project.

---
## 📋 COPY FROM HERE ──────────────────────

# Project Context: Phonics and Flashcards Project

Before anything else, please switch to the "Phonics project" basic memory project, which is located at: /Users/noahscott/Documents/Basic Memory/Phonics-Project. If you cannot find it do let me know and we will locate it prior to anything further.

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
- **Phase**: Research and content development
- **Completed Research**: 
  - RD-001: Teaching methodology guide (synthetic phonics approach chosen)
  - RD-002: Flashcard implementation guide (word lists and progressions)
- **Current Focus**: Refining word lists and generation approaches for flashcards

## Key Project Decisions Made
1. **Methodology**: Synthetic phonics (60%) with analytic support (30%)
2. **Progression**: SATPIN sequence → UK Letters & Sounds phases
3. **Flashcard Specs**: 3"×5" cards, no pictures, black text on white
4. **Sight Words**: Using New Dolch List (875 words) for ESL learners
5. **Decodability Standard**: 80-90% decodable text for practice materials

## Technical Context
- Using Basic Memory for knowledge management
- Documents organised in Obsidian-style markdown
- Project structure:
  - 00-project-overview/ (project briefs, templates, guides)
  - 01-research/ (research documents, resources, templates)
  - materials/ (future: flashcards, guides - not yet created)
- Data should be clean and code-interpretable (JSON preferred)
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
- **Research docs**: External research, preserve original content, use [[memory://01-research/templates/research-doc-template]]
- **Resource docs**: Data/word lists, concise with practical focus, use [[memory://01-research/templates/resource-doc-template]]
- **General docs**: Internal project docs, minimal structure, use [[memory://01-research/templates/general-doc-template]]
- **Quality focus**: Every section must add value - if not, remove it
- **Memory features**: Use sparingly, only for major decisions and direct dependencies

## Current Priorities
1. Develop comprehensive word lists organised by phonics pattern
2. Create sight word progression mapping decodable vs irregular
3. Build Cantonese-specific practice materials for problem sounds
4. Design assessment rubrics and progress tracking

## At the end of the session
I will close the session manually and notify you (alternatively if we get close to context limits please notify me and we will close the session), at which point:
- Please provide any updates to this document that are needed, eg. any changes that would impact the 'Current Project Status' or 'Key Project Decisions Made' areas etc.
- And a commit message that I can use for backing up the project to gh

## Essential References
### Project Documents
- Project Brief: [[memory://00-project-overview/phonics-flashcards-project-brief]]
- Teaching Guide (RD-001): [[memory://01-research/research-docs/eb-teaching-guide-phonics-bilingual-hk]]
- Flashcard Guide (RD-002): [[memory://01-research/research-docs/phonics-flashcard-guide-cantonese-hk]]
- NDL Resource: [[memory://01-research/resources/new-dolch-list-1.1]]

### Templates & Guides
- Style Guide: [[memory://00-project-overview/ai-guides/project-style-guide]]
- Research Template: [[memory://01-research/templates/research-doc-template]]
- Resource Template: [[memory://01-research/templates/resource-doc-template]]
- General Template: [[memory://01-research/templates/general-doc-template]]

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

### Version Control Note
When updating this template:
1. Create a new version with "updated-" prefix
2. Compare changes before replacing the main template
3. Update the modified date
4. Note significant changes in this section

---

*Last updated: 09/08/2025 - Added style guide reference, collaboration principles, and structured request format*