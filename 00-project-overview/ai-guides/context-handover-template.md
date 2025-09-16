---
title: AI Context Handover Template
type: Template
permalink: 00-project-overview/ai-guides/context-handover-template
entity_type: template
status: ✅ Completed
created: 2025-08-07
modified: 2025-09-16
tags:
  - handover
  - ai-guide
---

> [!abstract] Purpose
> Quick-start guide for new Claude sessions. Points to authoritative sources rather than duplicating content.

---
## 📋 COPY FROM HERE ──────────────────────

# Phonics Project - Session Start

## ⚡ First Steps
1. Switch to Basic Memory project: `/Users/noahscott/Documents/Basic Memory/phonics-project`
   - If not found, we'll locate it before proceeding
2. Read these in order:
   - [[00-project-overview/project-brief]] - Current status, goals, evolution
   - [[00-project-overview/ai-guides/project-style-guide]] - Documentation standards
   - [[00-project-overview/ai-guides/project-commit-log]] - Recent changes and decisions

## 🗂️ Quick Navigation

00-project-overview/ → Brief, guides, templates
01-research-foundation/ → Research (RD-XXX), resources, word lists
02-pre-literacy/ → Pre-phonics activities (no letters)
03-alphabet/ → Letter introduction  
04-transition/ → Letter-sound bridge activities
05-phonics/ → SATPIN onwards
06-crosswalk-tools/ → Navigation aids between stages

## 🎯 Common Task Locations
- **Add research**: Create RD-XXX in `01-research-foundation/research-docs/`
- **Create materials**: Use MAT-XXX in relevant stage folder
- **Update word lists**: `01-research-foundation/resources/`
- **Cantonese L1 support**: `03-alphabet/03.5-cantonese-support/`
- **Assessment tools**: `[stage]/[stage.1]-assessment/`
- **Progress tracking**: Check templates in assessment folders

## ⚡ Quick Reminders
- **UK English** | **DD/MM/YYYY** | **24-hour time** | **Metric only**
- **Evidence-based** > Everything else
- **Exposures not weeks** for tracking
- **Discuss before editing** any documents

## 💬 What I Need Help With
**Task**: [Specific task]
**Documents**: [Which files to work with]
**Constraints**: [Requirements/limitations]
**Success looks like**: [Expected outcome]

## 🏁 Session End Protocol
When closing session, provide:
1. **In chat**: Commit message for GitHub (I'll copy this for manual commit)
2. **Update**: [[00-project-overview/ai-guides/project-commit-log]] with same message + key changes
3. **Flag**: Any decisions needing project brief update

Example commit message format:
"Refactor(links): update all memory links and permalinks after project restructure

- Updated all memory:// links to reflect new folder structure
	- Changed 01-research/ → 01-research-foundation/
	- Updated research doc naming to RD-XXX-kebab-case format
	- Moved SATPIN resources to 05-phonics/05.1-satpin-mastery/
	- Fixed AI Guides → ai-guides folder references 
- Fixed YAML frontmatter permalinks in all documents 
	- Templates: corrected 3 permalink references 
	- Resources: updated new-dolch-list permalink 
	- All permalinks now use new folder structure - 
- Updated cross-references in key documents 
	- 00-project-overview/ai-guides/context-handover-template 
	- 00-project-overview/project-brief 
	- 00-project-overview/SATPIN Materials Development Brief 
	- 01-research-foundation/planning/pre-phonics-research-plan-completed 
	- 01-research-foundation/templates/* (all templates) 
- Aligned all internal links with sequential learning journey (00-06) 
	- Pre-literacy (02) 
	- Alphabet (03) 
	- Transition (04) 
	- Phonics (05) 
	- Crosswalk tools (06) 
- BREAKING CHANGE: Old memory:// links to 01-research/ will no longer resolve. All links now point to 01-research-foundation/ and new structure. 
- Note: Some stale database entries from old structure remain in Basic Memory but will clear on next full re-index. Physical files are correctly organised.
"
## ──────────── COPY TO HERE 📋

## 💡 Usage Instructions

1. **Copy** everything between the dividers
2. **Paste** at start of new Claude conversation
3. **Fill** "What I Need Help With" section
4. **Begin** work after Claude confirms project access

## 🎯 Template Philosophy

This template is intentionally minimal. It:
- **Points to** authoritative documents rather than duplicating them
- **Requires zero maintenance** (except commit log updates by Claude)
- **Provides navigation** without overwhelming detail
- **Stays under 300 words** to respect context limits

## 🚫 What This Template Doesn't Do

- **Doesn't duplicate** project brief content
- **Doesn't repeat** style guide principles  
- **Doesn't maintain** outdated information
- **Doesn't explain** the project (that's what the brief is for)

## 🔧 Maintenance

This template should rarely need updates. Only modify if:
- Basic Memory project location changes
- Folder structure fundamentally changes
- Session protocols change

Do NOT update for:
- Project status changes (update project brief instead)
- New research documents (they'll be in the folders)
- Style guide updates (read the guide directly)

---

*Simplified 16/09/2025: Removed all content duplication, now a pure navigation document pointing to authoritative sources*