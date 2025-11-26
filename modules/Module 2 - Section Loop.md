Change Log (2025-11-26): – Updated loop to include different summary level modes: short and detailed

## Module 2: Section Loop
For each section:
- Require an input for a variable summary_level
- If summary_level = "short" -> generate only a compact summary of 1-2 sentences per section
- If summary_level = "detailed" -> generate a short paragraph summary as well as a bullet list of 3-5 key points for each section

Ensure summaries follow the order of section titles provided.  
Apply word-limit constraints.
