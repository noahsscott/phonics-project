---
title: Project Commit Log
permalink: 00-project-overview/ai-guides/project-commit-log
entity_type: log
status: 🔄 Ongoing
created: 2025-09-16
modified: 2025-09-16
tags:
- commit-log
- project-history
- ai-maintained
- ai-guide
---

### 16/09/2025 - Navigation README and WIP Licensing
**Commit Message:**
```
Docs(root): add navigation README and establish WIP licensing

- Created navigational README for GitHub landing page
  - Added project structure overview (folders 00-06)
  - Added quick-start links to key documents
  - Added current status indicator
  - No content duplication, only wayfinding
- Established "All Rights Reserved" license for WIP phase
  - Protects work-in-progress materials
  - Notes future intent for educational CC licensing
  - Maintains flexibility for future phonics generator
- Deleted outdated git-collaboration-guide.md
  - No longer needed with new project structure
- Verified entity_type consistency across all documents
  - Confirmed only entity_type needed (not entity property)
  - All documents follow consistent pattern

BREAKING CHANGE: None
Note: License can be relaxed to CC BY-NC-SA once materials validated
```

**Key Decisions:**
- Use "All Rights Reserved" during WIP phase, transition to CC BY-NC-SA when ready
- Keep root README purely navigational (no content duplication)
- entity_type is sufficient for properties (no entity field needed)
- Future phonics generator may have separate proprietary licensing

**Documents Modified:**
- `README.md` (created with navigation structure)
- `00-project-overview/ai-guides/git-collaboration-guide.md` (deleted)
- `00-project-overview/ai-guides/project-commit-log.md` (updated)

---

### 16/09/2025 - Project Documentation System Overhaul
**Commit Message:**
```
Docs(project-overview): major overhaul of project documentation system

- Updated project brief to reflect pre-phonics pivot
  - Reduced word count 850→685 (19% reduction)
  - Added 6-stage learning journey overview
  - Added differentiated pathways section
  - Made exposure-based tracking explicit
  - Updated status to "Materials Development (Pre-Phonics Focus)"
- Enhanced style guide with project learnings
  - Added document types & numbering (RD-XXX, MAT-XXX)
  - Added file naming conventions (kebab-case)
  - Added exposure-based tracking principle
  - Added status indicators
  - Removed version control (too much maintenance)
- Redesigned context handover template
  - Removed ALL content duplication
  - Now points to authoritative sources only
  - Reduced 1000→280 words (72% reduction)
  - Added pointer to new commit log
- Created project commit log for AI session continuity
  - AI-maintained for automatic context preservation
  - Latest-first structure
  - Captures key decisions and changes

Key principle: Single source of truth, zero duplication, evidence-based
```

**Key Decisions:**
- Eliminate all documentation duplication - point to authoritative sources
- Track exposures not weeks (flexible for varied attendance patterns)
- Student placement guide planned but not yet created
- JSON structure designed for future flashcard generator compatibility
- Context handover now pure navigation, not content repository

**Documents Modified:**
- `00-project-overview/project-brief`
- `00-project-overview/ai-guides/project-style-guide`
- `00-project-overview/ai-guides/context-handover-template`
- `00-project-overview/ai-guides/project-commit-log` (created)

---

> [!important] About This Log
> AI-maintained record of project changes. Updated at each session end with commit messages and key changes. Latest entries appear first.

---

## 📊 Session Log

### 16/09/2025 - Refactor(links)
**Commit Message:**
```
Refactor(links): update all memory links and permalinks after project restructure

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
```

**Key Decisions:**
- Updated all memory links
- Updated all internal links
- Identified ghost entries and where they arose from

**Documents Modified:**
- (!Details missing)

---

### 15/09/2025 - Created new github repo
**Commit Message:**
```
New project and folder structure, in new repo due to messing up old repo + drastically changing project structure to accomodate pre-phonics approaches, materials and research in combination with the original phonics materials.
```

**Key Decisions:**
- New repo created
- Tidied versioning

**Documents Modified:**
- Entire document


---

## 📝 How This Log Works

### For Claude (Session End)
1. Add new entry at top with current date
2. Use exact commit message format provided
3. Summarise key decisions that affect project direction
4. List all modified documents with correct paths
5. Keep entries concise but complete

### For New Sessions
1. Read this log to understand recent changes
2. Note any decisions that affect current work
3. Check if planned items from previous sessions were completed

### Maintenance
- Keep latest 10-15 entries visible
- Older entries can be archived at bottom or removed
- Each entry should stand alone (don't assume previous context)

---

*This log maintains project continuity between AI sessions. Each entry represents actual work completed and decisions made.*