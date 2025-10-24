# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Japanese-language knowledge base documenting MBA frameworks and concepts. Content is organized as standalone markdown files covering specific business concepts.

## Repository Structure

```
mba-knowledge/
├── docs/
│   └── courses/
│       └── [course_id]/         # Course-specific directories (e.g., 18_TVB)
│           └── framework.md     # MBA framework documentation
├── images/                       # Supporting diagrams and visuals
│   └── frameworkname.png
└── README.md
```

## File Organization

**Course Structure:**
- Location: `docs/courses/[course_id]/`
- Course directories are organized by course identifier (e.g., `18_TVB` for Thought-Value-Behavior)
- Each course directory contains multiple framework markdown files
- Example: `docs/courses/18_TVB/business_model_canvas.md`

**Documentation Files:**
- Location: `docs/courses/[course_id]/`
- Naming convention: `framework_name.md` (descriptive English name in lowercase with underscores)
- Examples: `business_model_canvas.md`, `swot_analysis.md`, `value_chain.md`
- Language: Japanese
- Structure:
  - `# Title` (Japanese framework name)
  - Image display: `![Framework Name](../../../images/filename.png)`
  - `## 概要` (Overview section)
  - Detailed explanation with sub-sections for framework components

**Images:**
- Location: `images/` (at repository root level)
- Naming: Descriptive lowercase names matching the concept (e.g., `businessmodelcanvas.png`)
- Format: PNG preferred
- Reference from docs: `![alt text](../../../images/filename.png)` (relative path from course directory)

## Content Guidelines

**Document Structure:**
Each MBA concept document should follow this pattern:
1. Title as H1 (concept name in Japanese)
2. `## 概要` section explaining what the framework is
3. Detailed breakdown of the framework components
4. Include relevant diagrams from `images/` directory

**Writing Style:**
- Professional business language in Japanese
- Clear explanations suitable for MBA-level understanding
- Include original English terms in parentheses where appropriate (e.g., `顧客セグメント (CS: Customer Segments)`)
- Cite source authors and publications when introducing frameworks

## Git Workflow

**Branch:** Work on `main` branch (no feature branches needed for documentation updates)

**Commits:** Use descriptive messages in English:
- `add [Framework Name]` for new documents
- `update [Framework Name]` for content improvements
- `fix typo in [Framework Name]` for corrections

## Common Tasks

**Adding a new MBA framework to an existing course:**
1. Navigate to the appropriate course directory: `docs/courses/[course_id]/`
2. Create a new markdown file: `framework_name.md` (descriptive English name)
3. Add supporting images to `images/` (repository root) if needed
4. Follow the standard document structure:
   ```markdown
   # [Framework Name in Japanese]

   ![Framework Name](../../../images/filename.png)

   ## 概要

   [Framework explanation, authors, publication year...]
   ```
5. Update README.md to add the framework to the content table
6. Commit with message: `add [Framework Name]`

**Adding a new course:**
1. Create a new directory: `docs/courses/[new_course_id]/`
2. Use a descriptive course identifier (e.g., `19_SM` for Strategic Management)
3. Add framework markdown files to the new course directory
4. Update README.md to add the new course section
5. Commit with message: `add course [Course Name]`

**Adding images:**
1. Place image file in `images/` (repository root) with descriptive name
2. Use lowercase English names (e.g., `swotanalysis.png`, `valuechain.png`)
3. Reference in markdown using relative path from course directory: `![Description](../../../images/filename.png)`
4. Prefer PNG format for diagrams

**No build, test, or deployment commands** - this is a static documentation repository.
