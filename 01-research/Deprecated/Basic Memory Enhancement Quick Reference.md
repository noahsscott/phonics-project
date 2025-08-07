# Basic Memory Enhancement Quick Reference

**Project**: Phonics-Project
**Purpose**: Guidelines for enhancing documents with Basic Memory features while maintaining readability 
**Created**: July 2025 
## Overview 
This guide ensures consistent implementation of Basic Memory features (Relations, Observations, and Knowledge Graph) across all project documentation without compromising the clean markdown structure. 
## Core Principles 
1. **Additive Enhancement**: Never change existing content structure, only add semantic layers 
2. **Natural Reading Flow**: All enhancements should feel natural to readers 
3. **Searchable Metadata**: Use features that make project knowledge discoverable 
4. **Progressive Enhancement**: Start simple, add complexity only where valuable ## Feature Implementation Guide 

### 1. HTML Comments for Observations 
**Purpose**: Capture decisions, insights, and context without cluttering documents 
**Format**: ```markdown <!-- [Type]: [Description] --> ``` 
**Standard Types**: 
- `Key Decision`: Major project decisions with rationale 
- `Market Gap/Insight`: Important discoveries or opportunities 
- `Technical Decision`: Technology choices and reasoning 
- `Status Update`: Milestone achievements or changes 
- `Critical Path`: Dependencies and blockers 
- `Milestone Achievement`: Completed objectives 
**Examples**: ```markdown <!-- Key Decision: Dual learning mode approach chosen to balance structured progress with exploration freedom --> <!-- Market Gap: No major AI provider offers 9-tone Cantonese assessment - this is our competitive advantage --> <!-- Technical Decision: Hybrid approach necessary due to lack of Cantonese-specific pronunciation APIs --> <!-- Status Update 2025-07-11: Audio generation pipeline validated, ready for production --> <!-- Critical Path: Audio generation completion blocks MVP development --> <!-- Milestone Achievement: Pipeline proven with test batch, ready to scale --> ``` 
**Placement**: - At document start: Overall document insights - Before sections: Section-specific context - After items: Specific achievements or notes 
### 2. Wiki-Style Links for Relations 
**Purpose**: Create navigable connections between related documents 
**Format**: ```markdown [[path/to/document|descriptive text]] ```
**Path Structure**: ``` [[folder/subfolder/Document Name|description]] ``` 
**Standard Link Patterns**: **Research → Decision**: ```markdown Based on our [[01-research/ai-services/Executive Summary|AI services research]], we selected... ``` 
**Overview → Detail**: ```markdown - Azure TTS selected ([[03-implementation/audio-generation/azure-tts/Implementation Handover|see implementation]]) - Test batch generated ([[03-implementation/audio-generation/Development Log|see dev log]]) ``` **Cross-References**: ```markdown See [[01-research/linguistics/Why Audio Concatenation Doesn't Work|why concatenation fails]] ``` 
**Status → Implementation**: ```markdown - ✅ **Research**: Complete - [[01-research/Research README|see all research]] - 🏗️ **Implementation**: In Progress - [[03-implementation/Implementation README|see implementation]] ``` 
### 3. Project Metadata Sections 
**Purpose**: Explicit relationship mapping and decision tracking **Standard Section** (append to document end): ```markdown --- ## Project Metadata <!-- Basic Memory Relations and tracking --> ### Key Document Relations This [document type] **connects to**: - **[Relationship]**: [[path|description]] → [impact/purpose] - **[Relationship]**: [[path|description]] → [impact/purpose] ``` 

**Relationship Types**: 
- `Research Foundation`: Documents that informed this one 
- `Drives/Implements`: Documents this one influences 
- `Depends on`: Prerequisites or dependencies 
- `Validates`: Confirms or tests assumptions 
- `Details`: Provides implementation specifics 

### 4. Quick Status Summaries 
**For Overview Documents**: ```markdown ### Quick Status Summary - ✅ **Phase**: Complete - [[link|see details]] - 🏗️ **Phase**: In Progress - [[link|see details]] - 📋 **Phase**: Planned [timeframe] ```
### 5. Dependency Mapping 
**For Status/Roadmap Documents**: ```markdown ## Dependencies & Blockers ### Critical Path Dependencies ``` Component A → Component B → Component C ↓ Component D → Component E ``` ### Document Dependencies - **[Milestone]** depends on: - [[path|description]] - [what it provides] - [[path|description]] - [what it provides] ``` 

## Implementation Process ##
### Step 1: Analyse Document Type 
- **Overview documents**: Focus on Relations to details + Decision History
- **Status documents**: Add Progress Tracking + Dependencies 
- **Technical documents**: Link to research + implementation 
- **Design documents**: Connect to requirements + implementation 
- 
### Step 2: Add HTML Comments 
1. Read through document identifying key decisions/insights 
2. Add 2-4 strategic comments capturing critical information 
3. Focus on \"why\" rather than \"what\" 

### Step 3: Convert References to Relations 
1. Find existing mentions of other documents 
2. Convert to `[[path|description]]` format 
3. Ensure paths match actual file structure 
### Step 4: Add Metadata Section 
1. Append Project Metadata section 2. List 3-5 key Relations 3. Add 3-5 historical decisions with dates 4. Include 2-3 cross-references for common questions 

### Step 5: Validate - Document still reads naturally 
- Links resolve correctly 
- Comments provide value 
- Metadata doesn't duplicate content 

## Examples by Document Type 
### Project Overview ```markdown 
<!-- Key Decision: [strategic choice] --> 
<!-- Market Gap: [opportunity identified] --> 
Based on [[research|description]], we chose... 
--- ## Project Metadata ### 
Key Document Relations - **Research Foundation**: [[research doc]] → shaped approach - **Drives**: [[design doc]] → implementation spec ``` 
### Status & Roadmap 
```markdown <!-- Status Update YYYY-MM-DD: [milestone achieved] --> <!-- Critical Path: [blocker or dependency] --> ### Quick Status Summary - ✅ **Phase**: Complete - [[folder/README|see all items]] ### Dependencies - **[Milestone]** depends on: [[prerequisite doc]] ``` ### Technical Documentation ```markdown <!-- Technical Decision: [choice and rationale] --> Implementation based on [[research findings|research]]. For details see [[implementation guide|guide]]. ``` 
## Best Practices 
### DO: 
- ✅ Keep comments concise (1 line) 
- ✅ Use descriptive link text 
- ✅ Date important decisions 
- ✅ Link to source documents 
- ✅ Focus on \"why\" in comments 
### DON'T: 
- ❌ Duplicate existing content in comments 
- ❌ Over-link (3-5 relations per section max) 
- ❌ Create circular dependencies 
- ❌ Add metadata to every document 
- ❌ Break natural reading flow 

## Querying Enhanced Documents 
Once enhanced, you can: 
- Search for \"Key Decision\" to find all major choices 
- Ask \"What documents relate to [topic]?\" 
- Track \"Status Update\" entries chronologically 
- Follow Relations to understand document flow 
- Build knowledge graphs from Relations 

## Maintenance 
- Review metadata sections quarterly 
- Update status comments when milestones complete 
- Add new Relations as documents are created 
- Keep decision history current 
- Prune outdated cross-references -

--- *Remember: The goal is to enhance discoverability and navigation while maintaining the clean, readable documentation structure that makes your project accessible to all stakeholders.*


## 🎯 Quick examples

## 🔧 Three Enhancement Methods

### 1️⃣ HTML Comments → Observations

```markdown
<!-- Key Decision: Dual learning modes for flexibility -->
<!-- Technical Decision: Azure TTS for tone clarity -->
<!-- Status Update 2025-07-11: Pipeline validated -->
```

**Use for**: Decisions, insights, milestones  
**Benefit**: Searchable project memory

### 2️⃣ Wiki Links → Relations

```markdown
Based on [[01-research/ai-services/Executive Summary|our research]]...
See [[03-implementation/audio-generation/Development Log|dev log]]
```

**Use for**: Connecting related documents  
**Benefit**: Navigable knowledge graph

### 3️⃣ Metadata Section → Explicit Relations

```markdown
---
## Project Metadata
### Key Relations
- **Research Foundation**: [[path]] → shaped decisions
- **Implementation**: [[path]] → technical details

### Decision History
- **2025-07-11**: Chose Azure TTS (better tones)
```

**Use for**: Document relationships & history  
**Benefit**: Clear dependency tracking

## 📋 Implementation Checklist

For each document:

- [ ] Add 2-4 strategic HTML comments
- [ ] Convert mentions to wiki-links
- [ ] Add Project Metadata section (if major doc)
- [ ] Verify links resolve correctly
- [ ] Ensure natural reading flow maintained

## 🎯 Remember

**Goal**: Enhance discoverability without disrupting readability!