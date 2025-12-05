Change Log (2025-12-05): - Updated module to include conditional behaviour
**Module 2: Section Loop**
- Generate a summary following the word constraint for each section
- Ensure relavance
- Introduce variable: `summary_level`

**Conditional Behaviour**
- If `summary_level = "short"`
  - Produce a 1-2 sentence summary per section
- If `summary_level = "detailed"`
  - Generate a short paragraph
  - Add a bullet list of 3-5 key points for each section
