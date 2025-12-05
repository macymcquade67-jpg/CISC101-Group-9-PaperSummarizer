##CISC101-Group#9-PaperSummarizer

**Project Overview**

This project implements a Research Paper Summarizer. It processes papers section by section, enforces word limits, and produces structured outputs.The summarizer follows the PS2 Summarizer Specification:
- Section summaries < 150 words
- Unified summaries < 500 words
- Relevant section order
- No hallucinated content

**Repository Components**
- system_prompt.md
    - Core system prompt: Rules, inputs, outputs, constraints
- modules/
  - Internal Architecture Modules
      - intake_setup.md
        - Module 1: Normalize sections, detect any missing sections
      - section_loop.md
        - Module 2: Generate section summaries following word constraint, ensure relevance
      - guardrails.md
        - Module 3: Ensure word constraints are met, perform hallucination mitigation
      - rendering_refinement.md
        - Module 4: Format outputs, create expert/lay summaries
      - citation_extractor.md
        - Module 5: List the 5 most relevant citations separately
      - key_contributions.md
        - Module 6: Identify top 3 findings distinct from the main summary
       
### Summary
This README explains the purpose of the project and documents each component of the repository. 
