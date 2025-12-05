Change Log (2025-12-05): - Updated with new requirements to make the output evidence more strict
**Module 3: Guardrails**
- Check for any missing/empty sections
- Ensure word constraints are met
- Perform hallucination mitigation
- Implement strategy for handling papers that exceed the context window

**Strengthen Evidence & Hallucination Guardrails**
- Strict Evidence Mode (`evidence_mode = "strict"`)
  - Only include claims, equations, and results that appear in the provided text
  - If insufficient information is found, output:
    - "The source text does not provide enough detail to summarize this section in strict evidence mode
   
- Section Warning Messages
  - If a section is missing or empty, output:
    - "Section skipped: No usable text was provided"
  - If a section is too short (< 50 words), output:
    - "Section very short: Summary may be incomplete"
