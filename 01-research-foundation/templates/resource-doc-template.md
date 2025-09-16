---
title: Resource Document Template
permalink: 01-research-foundation/templates/resource-doc-template
entity_type: template
status: ✅ Completed
created: 2025-08-09
modified: 2025-08-09
tags:
  - template
  - resource
  - documentation
---

<!-- 
RESOURCE DOCUMENT TEMPLATE
==========================
This template is for structured data resources like word lists, progression maps, assessment rubrics, 
and other reference materials that support the project.

KEY PRINCIPLES FOR CONCISE, EFFECTIVE RESOURCE DOCS:
1. Combine related points - Don't separate "Coverage" and "Modern relevance" if they support the same idea
2. Use plain language headers - "Why frequency matters" not "Frequency principle"
3. Be specific with metrics - "315 words = 78% coverage" not "provides good coverage"
4. Remove redundant explanations - If it's in the data table, don't repeat in notes
5. Group similar limitations - All L1 issues in one bullet, not five separate ones
6. Avoid bloat - Every sentence should add value; if it doesn't, cut it

REMEMBER: Start concise. It's easier to add detail later than to remove redundancy.
-->

## 📝 Template Instructions

### When to Use This Template
Use for:
- Word lists and frequency data
- Assessment rubrics and checklists  
- Progression maps and sequences
- Reference data sets
- Any structured data supporting teaching materials

Do NOT use for:
- Research papers (use research-doc-template)
- Planning documents (use general-doc-template)
- Teaching materials themselves

### Section-Specific Guidance

**What is this resource?**: Maximum 3-4 sentences. No academic jargon. State what it IS, not what it does.

**How can I use it?**: Start with action verbs. Be specific enough that a substitute teacher could follow. Refer to [[Project Brief]] to ensure suggestions are relevant and concrete.

**Why was it selected?**: Look for opportunities to combine points. If two reasons support the same benefit, merge them.

**Research Basis**: Only include if you have actual citations. Translate academic concepts into "Why X matters" statements.

**Quick Stats**: Every statistic needs context. What does "78% coverage" mean for a teacher in the classroom?

**Limitations**: Group similar issues. Five bullets about L1 interference becomes one bullet listing all problematic sounds.

### Quality Checklist
Before finalising, check:
- [ ] No redundancy between sections
- [ ] Every bullet point adds unique value  
- [ ] Statistics have practical context
- [ ] Academic language translated to plain English
- [ ] Related points combined
- [ ] Optional sections removed if not needed
- [ ] Data structure table only has necessary notes

### Example of Good vs Poor Practice

❌ **Poor** (redundant and vague):
- Coverage: Provides 90% coverage
- Modern: Updated for contemporary usage  
- ESL-friendly: Good for ESL learners
- Data-driven: Includes frequency data

✅ **Good** (combined and specific):
- **Modern coverage**: Provides 90% coverage of current children's texts (vs 70% for 1936 Dolch list)
- **ESL/Context**: Designed for ESL learners; addresses irregular words Cantonese L1 speakers cannot decode
- **Data-driven**: Includes SFI scores and per-million counts for prioritised teaching

---

*Remember: If you can't explain why a section adds value, remove it. Conciseness with precision is the goal.*

---
## 📝 Template structure

```
> [!doc-resource] Resource Overview
> | **Source**        | [Publisher/Creator]                       |
> |-------------------|-------------------------------------------|
> | **Published**     | DD/MM/YYYY                                |
> | **Version**        | [version number]                          |
> | **Licence**        | [licence type]                            |
> | **Source URL**    | [if applicable]                           |

<!-- Keep overview table lean - only essential metadata -->

## 🔍 What is this resource?
<!-- 3-4 sentences max. Answer: What IS it? What's it FOR? Who created it and why? -->
[One sentence describing what the resource is]. [One sentence about its purpose/origin]. [One sentence about what it enables/facilitates]. 

## 🎨 How can I use it?
<!-- Be specific and action-oriented. 3-5 bullet points max -->
Use the [resource name] to:
1. **[Primary use]** - [Specific action with concrete example]
2. **[Secondary use]** - [Specific action with concrete example]  
3. **[Assessment/Tracking]** - [How to measure progress with this resource]

## 🎯 Why was it selected?
<!-- 4 bullets max. Combine related reasons. Be specific about benefits -->
<!-- Example from NDL: Don't separate "Coverage" and "Modern relevance" - combine them -->
- **[Main reason]**: [Specific metric/benefit, with comparison if relevant]
- **[Context reason]**: [Why it fits your specific learners/situation]
- **[Technical reason]**: [What data/features make it useful]
- **[Pedagogical reason]**: [How it aligns with teaching approach]

## 📚 Research Basis
<!-- Optional section - only if research backing exists -->
<!-- Use "Why X matters" format rather than academic jargon -->
<!-- Example: "Why frequency matters" not "Frequency principle" -->
- **Why [concept] matters**: [Simple explanation with outcome] (Author, Year)
- **Why [approach] works**: [Clear mechanism in plain language] (Author, Year)

## 📈 Quick Stats & Summary
<!-- Include only meaningful statistics. Be specific about what numbers mean -->
<!-- Good example: "315 words = 78% coverage: Children recognise roughly 8 out of 10 words" -->
<!-- Bad example: "Provides good coverage of common words" -->
- **Total entries**: [number]
- **[Key metric]**: [Specific number with explanation of what it means practically]
- **[Coverage/Range]**: [Specific data with context]
- **[Notable feature]**: [Interesting finding that affects usage]

## Data

#### 📋 Data Structure
<!-- Only include "Notes" column if adding non-obvious information -->
<!-- Don't note "Lower rank = more frequent" - that's obvious from description -->
| Field | Type | Description | Notes |
|-------|------|-------------|-------|
| [Field1] | [Type] | [Clear description] | [Only if needed] |
| [Field2] | [Type] | [Clear description] | |

<!-- Embed your data file - can be CSV, JSON, or other formats -->
![[resource-file.csv]]

---

## 🔍 Implementation Notes
<!-- Keep practical and specific to your context -->

### Integration with Teaching Method:
<!-- 5 bullets max. Focus on HOW to use with your specific approach -->
- **[Integration point]**: [Specific instruction]
- **[Selection criteria]**: [How to choose what to use when]
- **[Progression]**: [How usage changes over time]
- **[Documentation]**: [What to track and how]

## ❗Limitations & Considerations
<!-- Group related items. Be specific but concise -->
- **[Technical limitation]**: [Brief explanation with example]
- **[Contextual limitation]**: [Specific to your learners/setting]
<!-- Example of grouping: "L1 interference for Cantonese speakers: Common challenges include /v/ (very), /z/ (is), th sounds (the, this), and /r/ (for, from)" -->
<!-- Rather than listing each sound as separate bullet -->

<!-- OPTIONAL SECTIONS - Include only if relevant -->

## 🔗 Dependencies
<!-- Only include if this resource directly supports other materials -->
<!-- If no dependencies exist yet, note that and leave blank otherwise -->
### Which materials use this resource?
- **[Material type]**: [[memory://path]] - [How it's used]

---

## 📝 Appendices

### About this resource:
<!-- Technical details about creation/methodology -->
- **Methodology**: [How the resource was created/compiled]
- **Updates**: [What changed in this version]

### References:
<!-- Use full citations in consistent format -->
- (Author, A., Year, Title, Publisher)
- (Author, B. & Author, C. (Eds.), Year, Title, Publisher)


---
```