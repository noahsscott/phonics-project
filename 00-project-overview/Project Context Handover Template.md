---
title: Project Context Handover Template
type: Template
permalink: 00-project-overview/project-context-handover-template
entity_type: template
status: ✅ Completed
created: 2025-08-07
modified: 2025-08-07
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

Ways of working: I want to discuss changes before they are made, so please do not edit documents without having us both discussed changes thoroughly and agreed upon them first. 

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
  - 00-project-overview/ (project briefs and templates)
  - 01-research/ (research documents and findings)
  - materials/ (future: flashcards, guides - not yet created)
- Data should be clean and code-interpretable (JSON preferred)
- Planning for future flashcard generator application

## Target Audience Specifics
- **Age**: 3-8 years old
- **Language**: Bilingual (Cantonese-English), no Mandarin focus needed
- **Setting**: Home tutoring, one-on-one
- **Challenges**: L1 interference from Cantonese (missing phonemes: /v/, /z/, /θ/, /ð/, /r/)
- **Special Considerations**: Some learners may have dyslexia

## Document Standards
- Research docs: Use research template, main content unmodified
- General docs: Use general template, main content uses Basic Memory features
- Status indicators: ✅ Completed / ⚠️ Needs Review / 🔄 In Progress / ❌ Deprecated
- Memory URLs: [[memory://path/to/doc]] format for linking
- Keep documents lean, maintainable, and readable

## Current Priorities
1. Develop comprehensive word lists organised by phonics pattern
2. Create sight word progression mapping decodable vs irregular
3. Build Cantonese-specific practice materials for problem sounds
4. Design assessment rubrics and progress tracking

## Key Documents to Reference
- Project Brief: [[Project Brief]]
- Teaching Guide: [[EB Teaching Guide for Phonics and Reading to Bilingual Children in HK]]
- Flashcard Guide: [[Phonics Flashcard Guide for Cantonese-Speaking Children in HK]]
- Research Template: [[Research Doc Template]]
- General Template: [[General Doc Template]]

## What I Need Help With
Now I have a CSV with the New Dolch List (NDL) v1.1 of words are a list of high frequency English sight words commonly used to teach children to read. I need a template that would be suitable for resources like this as it does not fit neatly within the general doc template or research doc template. The key is keeping it lean, maintainable and readable while also leveraging basic memory features. You can see my rough start of the NDL resource doc here "01-research/resources/new-dolch-list-1.1" with some questions marked for consideration. Let me know if you can find this first and lets discuss some ideas before we modify anything.
- [Specific task or question]
- [Area needing development]
- [Problem to solve]

## ──────────────────── COPY TO HERE 📋

---

## 📝 Usage Instructions

1. **Copy the content** between the dividers above
2. **Paste at the start** of your new Claude conversation
3. **Customise the last section** ("What I Need Help With") for your specific session
4. **Add any additional context** specific to what you're working on
5. **Reference specific documents** if the task requires them

## 💡 Tips for Effective Handovers

- **Be specific** about what you need in the current session
- **Reference document permalinks** if working on specific files
- **Mention any recent changes** not captured in the template
- **Include error messages or problems** you're trying to solve
- **State desired output format** if you need something specific

## 🔄 Maintaining This Template

Update this template when:
- Major project decisions are made
- New research documents are completed
- Project phase changes
- Technical approach evolves
- New document types are added

---

*Last updated: 2025-08-07 - Remember to check if this template needs updates before use*