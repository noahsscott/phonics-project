---
title: Research Document Template
permalink: 01-research-foundation/templates/research-doc-template
entity_type: template
status:
  - ✅ Completed
created: 2025-08-06
modified: 2025-08-09
tags:
  - template
  - research
  - documentation
---

<!-- 
RESEARCH DOCUMENT TEMPLATE
==========================
This template is for capturing and organising research findings that inform project decisions.
Research docs preserve original research content while adding structured metadata for project integration.

KEY PRINCIPLES FOR EFFECTIVE RESEARCH DOCS:
1. Keep meta-sections (overview, objectives, findings) CONCISE - no academic bloat
2. Main document content remains unedited - preserve original research, add the contextual information on top and below
3. Objectives should be measurable and specific, not vague intentions
4. Key findings must be ACTIONABLE, not just interesting observations
5. Next actions should be specific enough that someone else could execute them
6. Evidence should cite specific sources, not general claims

DOCUMENT ID CONVENTION:
- Use sequential numbering: RD-001, RD-002, RD-003
- For major updates, create new document (RD-001 → RD-001a)
- Never reuse document IDs
-->

## 📝 Template Instructions

### When to Use This Template
Use for:
- Literature reviews and research synthesis
- Methodology investigations
- Best practice research
- Evidence gathering for decisions
- External resource evaluation

Do NOT use for:
- Resource data (use resource-doc-template)
- Planning documents (use general-doc-template)
- Meeting notes or brainstorming
- Teaching materials

### Section-Specific Guidance

**Research Overview Table**: One-line purpose. If you can't explain it in one line, narrow your scope.

**Research Triggered By**: Be specific - "Initial project planning needed X" not "To understand X better"

**Objectives & Results Table**: 
- Objectives must be measurable - "Identify 5+ techniques" not "Understand techniques"
- Evidence must cite specific sources - "(Smith 2023, p.45)" not "Research shows"

**Key Findings**: Must be implementable. "Use synthetic phonics 60% of time" not "Synthetic phonics is effective"

**Next Actions**: Specific enough for delegation. "Create word lists for SATPIN letters" not "Develop materials"

**Main Document**: This is your actual research content. Keep it intact, add citations properly, minimal Basic Memory links.

### Quality Checklist
Before finalising:
- [ ] Document ID assigned in sequence
- [ ] All objectives have measurable criteria
- [ ] Evidence column has specific citations
- [ ] Key findings are actionable, not theoretical
- [ ] Next actions could be assigned to someone else
- [ ] Main document has proper citations
- [ ] Related documents marked "planned" if not created

### Status Indicators
- 🔄 **In Progress**: Active research, incomplete sections
- ⚠️ **Needs Review**: Complete but requires validation
- 🚧 **Under review**: Actively being edited and not yet complete
- ✅ **Completed**: Finalised, findings confirmed
- ❌ **Deprecated**: Superseded by newer research

---

## 📋 Template Structure

```markdown
> [!doc-research] Research Overview
> | **Document ID**    | RD-XXX                                     |
> |--------------------|-------------------------------------------|
> | **Status**         | ✅ Completed / ⚠️ Needs Review / 🔄 In Progress |
> | **Purpose**        | [One-line description of research goal]   |
> | **Key Decision**   | [Main outcome/decision if applicable]     |

<!-- Keep overview concise - this is metadata, not an abstract -->

## 🎯 Research Objectives & Results

**Research triggered by**: [What prompted this research - gap identified, question raised, or follow-up needed. Include reference to previous document if applicable.]

<!-- Example of good trigger: "RD-001 identified need for Cantonese-specific phonics adaptations"
     Example of poor trigger: "To learn more about phonics" -->

| Objective | Success Criteria | Result | Evidence |
| --------- | --------------- | ------ | -------- |
| [Clear objective] | [Measurable criteria] | ✅/⚠️/❌ | [Specific evidence with citations] |
| [Clear objective] | [Measurable criteria] | ✅/⚠️/❌ | [Specific evidence with citations] |

<!-- Good objective: "Identify phonics methods for ESL" with criteria "Find 3+ evidence-based approaches"
     Poor objective: "Understand phonics better" with criteria "Good understanding" -->

## 💡 Key Findings for Implementation

<!-- These must be ACTIONABLE. Each finding should directly inform a project decision or action -->
1. **[Finding headline]**: [Specific details with supporting data/evidence]
2. **[Finding headline]**: [Specific details with supporting data/evidence]
3. **[Finding headline]**: [Specific details with supporting data/evidence]
4. **[Finding headline]**: [Specific details with supporting data/evidence]

<!-- Good finding: "Synthetic phonics: Teach letter sounds before blending, 60% of instruction time"
     Poor finding: "Synthetic phonics is an effective method supported by research" -->

## 📋 Next Actions Required

<!-- Specific enough that you could assign to someone tomorrow -->
- [ ] [Specific action with clear deliverable]
- [ ] [Specific action with clear deliverable]
- [ ] [Specific action with clear deliverable]
- [ ] [Specific action with clear deliverable]

<!-- Good action: "Create decodable word lists for SATPIN letters with 10 words per pattern"
     Poor action: "Develop teaching materials" -->

<!-- OPTIONAL SECTIONS - Include only if relevant -->

## ⚠️ Limitations & Gaps
<!-- What this research DOESN'T answer, what's still unknown -->
- [Limitation of research or remaining question]
- [Gap that needs future investigation]

---
# [Main Document Title]

<!-- MAIN RESEARCH CONTENT
This section contains your actual research document. Guidelines:
- Preserve original research content and structure
- Add proper citations in consistent format (Author, Year) or (Author, Year, p.X)
- Minimal Basic Memory connections - only where essential
- Include methodology notes if relevant
- Keep academic rigour while ensuring readability
-->

[Document content begins here - for research documents, this remains largely unmodified]

[Continue with document content...]

<!-- References/Bibliography -->
## References
<!-- Use consistent citation format throughout -->
[List all sources cited in the document]

---
## 🔗 Related Documents
<!-- Only include relationships that exist or are firmly planned -->
- **Builds on**: [[memory://01-research-foundation/path/to/previous-doc]] - Brief description
- **Next**: [[memory://01-research-foundation/path/to/next-doc]] - Brief description (mark as "planned" if not created)
- **Implements**: [[memory://01-research-foundation/path/to/methodology]] - What this puts into practice
- **Supports**: [[memory://01-research-foundation/path/to/related]] - What this enables

<!-- Relationship types explained:
     - Builds on: Previous research this extends
     - Next: Follow-up research planned
     - Implements: Practical application of this research
     - Supports: Other docs that depend on this research -->
```

---

### Examples of Good vs Poor Practice

❌ **Poor Objectives & Evidence**:
| Objective | Success Criteria | Result | Evidence |
| --------- | --------------- | ------ | -------- |
| Understand phonics | Good understanding | ✅ | Research shows it works |
| Review methods | Find information | ✅ | Various sources |

✅ **Good Objectives & Evidence**:
| Objective | Success Criteria | Result | Evidence |
| --------- | --------------- | ------ | -------- |
| Identify phonics methods for ESL | Find 3+ evidence-based approaches | ✅ | Synthetic (NICHD 2000), Analytic (Smith 2021), Embedded (Jones 2023) |
| Establish teaching sequence | Clear progression with 5+ stages | ✅ | SATPIN → Letters & Sounds phases (Oxford 2024) |

❌ **Poor Key Finding**:
"Research shows synthetic phonics is effective for teaching reading"

✅ **Good Key Finding**:
"**Synthetic phonics allocation**: Dedicate 60% of phonics time to synthetic methods, 30% to analytic, 10% to application (based on effect sizes: synthetic d=0.41, analytic d=0.27)"

❌ **Poor Next Action**:
- [ ] Create teaching materials

✅ **Good Next Action**:
- [ ] Create decodable word lists organised by pattern: Set 1 (SATPIN) - 10 CVC words per letter combination

---

*Remember: Research docs inform decisions. Every section should help move from research to action.*