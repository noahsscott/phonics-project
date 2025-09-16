---
title: General Document Template
type: Template
permalink: 01-research/templates/general-doc-template
entity_type: template
status: ✅ Completed
created: 2025-08-07
modified: 2025-08-09
tags:
  - template
  - documentation
  - planning
---

<!-- 
GENERAL DOCUMENT TEMPLATE
=========================
This template is for internally-generated project documentation that doesn't fit research or resource categories.
General docs capture decisions, specifications, processes, and plans created by the project team.

KEY PRINCIPLES FOR EFFECTIVE GENERAL DOCS:
1. Start simple - use only the sections you need
2. Memory features should enhance, not clutter - use sparingly
3. Keep sections concise - this isn't academic writing
4. Action items must be specific and assignable
5. If a section doesn't add value, remove it
6. Clarity beats completeness every time

ENTITY TYPES TO USE:
- planning-document: Project plans, roadmaps, strategies
- technical-spec: Technical requirements, architecture docs
- process-doc: Workflows, procedures, guidelines
- decision-doc: Decision records, rationale documentation
- guide: How-to guides, instructional content
-->

## 📝 Template Instructions

### When to Use This Template
Use for:
- Project plans and strategies
- Technical specifications
- Process documentation
- Decision records
- Internal guides and procedures
- Meeting outcomes (not raw notes)
- Architecture documentation

Do NOT use for:
- External research (use research-doc-template)
- Data resources (use resource-doc-template)
- Raw meeting notes or brainstorming
- Teaching materials or flashcards

### Core vs Optional Sections
**Always include**: Overview, Key Points, Main Content, Related Documents
**Sometimes include**: Action Items (if actionable), Technical Details (if technical)
**Rarely include**: Appendices, Document History (only for frequently updated docs)

### Memory Features - Use Sparingly
Only use memory tags when they add clear value:
- `memory:decision` - Only for major project decisions that others need to reference
- `memory:section` - Only if you need to reference specific sections elsewhere
- Links `[[memory://]]` - Only for direct dependencies, not general references

### Quality Checklist
Before finalising:
- [ ] Can someone understand the purpose in 10 seconds?
- [ ] Are all sections necessary, or can some be cut?
- [ ] Do memory features add value or just complexity?
- [ ] Could action items be assigned tomorrow?
- [ ] Is language clear and jargon-free?

---

## 📋 Template Structure

```markdown
> [!doc-general] Document Overview
> | **Status**         | ✅ Completed / ⚠️ Needs Review / 🔄 In Progress |
> |--------------------|-----------------------------------|
> | **Purpose**        | [One-line description - what this doc achieves] |

<!-- One line is enough. If you need more, your scope is too broad -->

## 💡 Key Points
<!-- 3-4 maximum. These are your TL;DR takeaways -->
1. **[Point headline]**: [One sentence explanation]
2. **[Point headline]**: [One sentence explanation]
3. **[Point headline]**: [One sentence explanation]

## 📋 Action Items
<!-- Only include if there are specific follow-ups. Remove otherwise -->
- [ ] [Specific action] - Owner: [Name] - Due: [Date]
- [ ] [Specific action] - Owner: [Name] - Due: [Date]

---
# [Main Document Title]

## Overview
[1-2 paragraphs maximum. Set context and scope. What problem does this solve?]

## [Main Section 1]
[Your content here. Use clear headings and concise paragraphs.]

### [Subsection if needed]
[Content. Only create subsections if truly needed.]

## [Main Section 2]
[Continue with your core content.]

<!-- Only add memory features where they add clear value:
For major decisions only:
Decision: [What was decided]
Rationale: [Why in one sentence]
Date: YYYY-MM-DD
-->

## Technical Details
<!-- Only for technical documents. Remove otherwise -->
### Requirements
- [Specific requirement]
- [Specific requirement]

### Constraints  
- [Known limitation]
- [Known limitation]

---
## 🔗 Related Documents
<!-- Only list documents with direct relationships -->
- **Implements**: [[memory://path/to/source]] - What this puts into practice
- **Informs**: [[memory://path/to/next]] - What this enables (mark "planned" if not created)

<!-- Don't link everything. Only direct dependencies -->
```

---

### Examples of Good vs Poor Practice

❌ **Poor Key Points** (vague and verbose):
1. **Research Findings**: We conducted extensive research into various methodologies and found several interesting patterns that might be useful
2. **Implementation Approach**: There are multiple ways we could implement this system depending on various factors
3. **Stakeholder Considerations**: We should think about what different stakeholders might need

✅ **Good Key Points** (specific and concise):
1. **Method chosen**: Synthetic phonics for 60% of instruction time based on evidence
2. **Timeline**: 12-week implementation starting January 2025
3. **Success metric**: 80% of students reaching benchmark by week 8

❌ **Poor Action Item**:
- [ ] Review the documentation and provide feedback when possible

✅ **Good Action Item**:
- [ ] Review sections 2-3 for technical accuracy - Owner: Jane - Due: 15/08/2025

### When to Use Memory Features

❌ **Overuse** (clutters without adding value):
```markdown
<!-- memory:section:overview -->
This is the overview section where we discuss <!-- memory:insight --> 
the insight that <!-- memory:decision --> we decided to...
<!-- memory:section:end -->
```

✅ **Appropriate Use** (marks genuinely important decision):
```markdown
## Platform Selection

After comparing three options, we selected AWS for hosting.

<!-- Decision: Use AWS over Azure/GCP
Rationale: 40% lower costs for our use case
Date: 2025-08-09 -->
```

### Choosing Entity Types

Use this guide:
- **planning-document**: "We will do X by Y date"
- **technical-spec**: "The system must do X using Y"
- **process-doc**: "Here's how to do X step-by-step"
- **decision-doc**: "We chose X because Y"
- **guide**: "This is how X works"

---

*Remember: Perfect is the enemy of done. Ship clear, concise documentation that helps the team move forward.*