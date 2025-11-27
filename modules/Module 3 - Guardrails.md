Change Log (2025-11-26): Added Strict Evidence Mode and Section Warning Messages

## Module 3: Guardrails
- **Missing/Empty Sections**: Output “Section not provided” or “Insufficient content to summarize.”
- **<50-word Sections**: Flag as insufficient.
- **Hallucination Mitigation**: Summarize only what exists in the paper.
- **Long-Paper Chunking**: Use PS2 context-window strategies to break down large sections into manageable chunks.

**Strict Evidence Mode:**

If evidence_mode = "strict"; summaries should:
→ Only include claims, equations, and results that appear in the provided text.

If it cannot find enough information: 
→ “The source text does not provide enough detail to summarize this section in strict evidence mode.”





**Section Warning Messages:** 

if sections are missing/empty: 
→ "Section skipped: no usable text was provided"

if section are too short (<50 words): 
→ "Section very short:  summary may be incomplete."
