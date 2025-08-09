---
type: Template
permalink: 01-research/templates/general-doc-template
entity_type: template
status: 🚧 Under review
created: 2025-08-07
modified: 2025-08-08
tags:
  - template
  - documentation
  - planning
---

<!-- Template Usage Notes:
1. For entity_type: use "planning-document", "technical-spec", "process-doc" etc.
2. Keep 3-5 tags maximum for maintainability
3. Status indicators: ✅ Completed / ⚠️ Needs Review / 🔄 In Progress / ❌ Deprecated
4. Use Basic Memory features sparingly but precisely in main content
5. Optional sections can be removed if not applicable
6. Memory URLs: Use [[memory://path]] format for connections
-->

> [!doc-general] Document Overview
> | **Status**         | ✅ Completed / ⚠️ Needs Review / 🔄 In Progress |
> |--------------------|-----------------------------------|
> | **Purpose**        | [One-line description of document purpose] |
> | **Key Outcome**    | [Main outcome/deliverable if applicable] |

## 🎯 Document Purpose & Outcomes

**Created to address**: [What gap or need this document fills. Reference to triggering document/decision if applicable.]

| Purpose | Expected Outcome | Status | Notes |
| ------- | --------------- | ------ | ----- |
| [Clear purpose] | [Measurable/observable outcome] | ✅/⚠️/❌ | [Brief notes] |
| [Clear purpose] | [Measurable/observable outcome] | ✅/⚠️/❌ | [Brief notes] |

## 💡 Key Points

<!-- memory:keypoints:start -->
1. **[Point headline]**: [Specific details with context]
2. **[Point headline]**: [Specific details with context]
3. **[Point headline]**: [Specific details with context]
4. **[Point headline]**: [Specific details with context]
<!-- memory:keypoints:end -->

## 📋 Action Items
<!-- Optional section - remove if not applicable -->

- [ ] [Specific action with owner if applicable]
- [ ] [Specific action with owner if applicable]
- [ ] [Specific action with owner if applicable]

---
# [Main Document Title]

## Overview
<!-- memory:section:overview -->
[High-level introduction to the topic. This section should provide context and set expectations for the reader.]

Key aspects to consider:
- [[memory://related/context-doc]] - Related context
- [[memory://requirements/doc]] - Requirements reference
- [[memory://decisions/doc]] - Previous decisions
<!-- memory:section:end -->

## [Main Section 1]
<!-- memory:section:main1 -->
### [Subsection 1.1]
[Content with precise use of Basic Memory features where valuable]

<!-- memory:decision
Decision: [What was decided]
Rationale: [Why this decision]
Date: YYYY-MM-DD
-->

### [Subsection 1.2]
[Content continues...]

<!-- memory:insight
Key insight: [Important realisation or finding]
Implications: [What this means for the project]
-->
<!-- memory:section:end -->

## [Main Section 2]
<!-- memory:section:main2 -->
[Structure as needed for your content type]

When referencing other documents:
- See [[memory://path/to/detailed-spec]] for implementation details
- Builds on concepts from [[memory://path/to/foundation-doc]]
- Enables work described in [[memory://path/to/future-work]]
<!-- memory:section:end -->

## Technical Considerations
<!-- Optional section - particularly relevant for tech specs -->
<!-- memory:section:technical -->
### Requirements
- [Requirement 1]
- [Requirement 2]

### Constraints
- [Constraint 1]
- [Constraint 2]

### Dependencies
- [[memory://dependency/doc1]] - Description
- [[memory://dependency/doc2]] - Description
<!-- memory:section:end -->

## Implementation Notes
<!-- Optional section - remove if not applicable -->
<!-- memory:section:implementation -->
[Specific implementation guidance, code examples, or detailed instructions]

```json
{
  "example": "structure",
  "for": "data organisation"
}
```
<!-- memory:section:end -->

## Open Questions
<!-- Optional section - useful during development -->
- [ ] [Question needing resolution]
- [ ] [Question needing resolution]
- [ ] [Decision pending]

## Appendices
<!-- Optional section - for supporting materials -->
### Appendix A: [Title]
[Supporting information that would clutter main content]

### Appendix B: [Title]
[Additional reference material]

---
## 🔗 Related Documents
- **Builds on**: [[memory://path/to/previous-doc]] - Brief description
- **Informs**: [[memory://path/to/next-doc]] - What this enables (mark as "planned" if not created)
- **See also**: [[memory://path/to/related]] - Related documentation
- **References**: [[memory://path/to/source]] - Source material

---
## 📝 Document History
<!-- Optional section - useful for living documents -->
| Date | Changes | Author |
| ---- | ------- | ------ |
| YYYY-MM-DD | Initial draft | [Name] |
| YYYY-MM-DD | [What changed] | [Name] |

---

<!-- memory:keywords
[keyword1]
[keyword2] 
[keyword3]
[planning-specific-term]
[technical-term]
-->

*Note: This is a living document. Updates should maintain clarity and avoid unnecessary complexity.*