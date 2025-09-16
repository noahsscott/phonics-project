---
title: Git Collaboration Guide for Phonics Project
type: Guide
permalink: 00-project-overview/ai-guides/git-collaboration-guide
entity_type: guide
status: 🚧 Under review
created: 2025-08-09
modified: 2025-08-09
tags:
  - git
  - version-control
  - ai-guide
---

> [!important] Purpose
> This guide establishes Git conventions for our collaboration on the Phonics Project, ensuring clear version history and easy rollback if needed.

## 🎯 Commit Message Convention

### Format
```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types
- **feat**: New feature or document (new template, new resource)
- **fix**: Corrections to existing content
- **refactor**: Restructuring without changing meaning (like our NDL cleanup)
- **docs**: Documentation only changes
- **style**: Formatting, spelling (UK/US fixes)
- **chore**: Maintenance tasks (file moves, renames)
- **review**: Changes from review session with Claude

### Examples for Our Project

```bash
# After our NDL refinement session:
git commit -m "refactor(resources): streamline NDL document for conciseness

- Consolidated L1 interference into single bullet
- Simplified Research Basis section language  
- Removed redundant data table notes
- Fixed heading hierarchy

Co-authored-by: Claude"

# Adding new template:
git commit -m "feat(templates): add resource-doc template

- Created template for data resources
- Included examples of good vs poor practice
- Added quality checklist

Based on NDL document structure"

# Quick fixes:
git commit -m "fix(docs): correct UK spelling in flashcard guide"

# Moving files:
git commit -m "chore(structure): move style guide to ai-guides folder"
```

## 📝 Our Collaboration Workflow

### Before Our Session
```bash
# Always start fresh
git pull
git status

# Create a session branch
git checkout -b session-YYYY-MM-DD-topic
# Example: git checkout -b session-2025-08-09-templates
```

### During Our Session

**After each significant change:**
```bash
# See what changed
git status
git diff

# Stage specific files
git add [specific-file-path]
# Or stage everything if all changes are related
git add .

# Commit with meaningful message
git commit -m "type(scope): what we did"
```

### After Our Session
```bash
# Final commit for session
git commit -m "review(session): summary of 09/08/2025 session

- Refined NDL document for conciseness
- Created resource-doc template
- Updated research-doc template with examples
- Created project style guide

Co-authored-by: Claude"

# Push to GitHub
git push origin session-2025-08-09-templates

# If you're happy with changes, merge to main
git checkout main
git merge session-2025-08-09-templates
git push origin main
```

## 🔄 Version Control Best Practices for Our Work

### When to Commit
- ✅ After completing a document refinement
- ✅ When creating new templates or guides
- ✅ Before starting a new task in same session
- ✅ After any significant structural change
- ❌ Not mid-edit when things are broken

### What Goes in Each Commit
- **One concept per commit** - Don't mix NDL changes with template updates
- **Complete thoughts** - Ensure documents are valid/complete
- **Related changes together** - If you update a doc and its template, that's one commit

### Co-authoring with Claude
When we work together, add to commit message:
```bash
git commit -m "feat(resources): create sight words progression map

Developed comprehensive progression from Phase 1-5
Mapped decodable vs irregular words per phase

Co-authored-by: Claude"
```

## 💡 Quick Reference Commands

### Daily Use
```bash
# Start your day
git pull
git status

# Save work in progress (not ready to commit)
git stash
git stash pop  # when ready to continue

# See what you changed
git diff
git diff --staged  # after git add

# Commit with message
git add .
git commit -m "type(scope): description"
git push
```

### Fixing Mistakes
```bash
# Undo last commit (keep changes)
git reset --soft HEAD~1

# Fix commit message
git commit --amend -m "new message"

# Discard local changes to specific file
git checkout -- [file-path]

# See commit history
git log --oneline -10
```

### Working with Me (Claude)
```bash
# Start session
git checkout -b session-date-topic

# During session - commit after each document
git add [changed-file]
git commit -m "review(doc-name): specific changes"

# End session
git commit -m "review(session): session summary"
git push origin branch-name
```

## 📊 Commit Message Templates for Common Tasks

### Template Refinement
```
refactor(templates): improve [template-name] clarity

- Added usage instructions
- Included good/bad examples
- Simplified structure
- Added quality checklist
```

### Resource Data Updates
```
feat(resources): add [resource-name] data

- [X] entries covering [scope]
- Includes [key features]
- Source: [source]
```

### Documentation Improvements
```
docs(guides): enhance [guide-name]

- Clarified [section]
- Added examples for [concept]
- Fixed UK spelling throughout
```

### Session Summary
```
review(session): [date] collaboration with Claude

Summary:
- [Major achievement 1]
- [Major achievement 2]

Documents affected:
- [doc1]: [change]
- [doc2]: [change]

Next steps: [what's planned]

Co-authored-by: Claude
```

## 🚀 Making This Easier

### Git Aliases for Common Operations
Add to your `~/.gitconfig`:
```ini
[alias]
    # Quick status
    s = status -s
    
    # Pretty log
    lg = log --oneline --graph -10
    
    # Add and commit
    ac = !git add . && git commit -m
    
    # Commit with review type
    review = commit -m "review: 
    
    # Today's commits
    today = log --since="00:00:00" --oneline
```

### Session Script
Create `session.sh` in project root:
```bash
#!/bin/bash
DATE=$(date +%Y-%m-%d)
echo "Starting session for $DATE"
git checkout -b session-$DATE-$1
echo "Created branch: session-$DATE-$1"
echo "Ready for collaboration!"
```

Use with: `./session.sh templates`

## 📝 For Our Next Session

At the start, tell me:
1. What branch we're on
2. Any uncommitted changes
3. What we're working on today

I can then remind you to commit at appropriate points and help write meaningful commit messages.

---

*Remember: Version control is just structured storytelling about your project's evolution. Your commits are the chapters.*