# Research Assistant Flow

## Product context

A research assistant helps teams synthesize sources, track assumptions, and maintain continuity across literature reviews, interviews, and analysis sessions.

## User goal

A researcher wants the product to remember project assumptions and synthesis preferences while keeping source provenance visible and separating confirmed findings from working hypotheses.

## Memory involved

- Project assumption: focus on small-team adoption barriers
- Synthesis preference: separate evidence from interpretation
- Working hypothesis: users trust memory more when correction is visible
- Temporary interview context: participant-specific notes for current analysis session

## UI sequence

1. The researcher saves a project assumption with source links to notes.
2. The memory appears in a project memory drawer during synthesis.
3. Each assumption card shows source, confidence, and status: confirmed, working, or needs review.
4. When generating a synthesis, the product lists which project memories shaped the output.
5. The researcher can open a timeline of how assumptions changed over the project.

## Correction moment

A synthesis treats a working hypothesis as a confirmed finding. The researcher opens the confidence indicator and changes the memory status to "working hypothesis." Future outputs separate it from findings.

## Forgetting moment

After analysis, participant-specific memory is deleted from active project context while source notes remain governed by the research archive policy.

## Trust risk

Research memory can blur evidence and interpretation. If the product overstates uncertain memory, it may distort research conclusions.

## Success criteria

- Project memories distinguish assumptions, findings, and hypotheses.
- Outputs show which memories shaped synthesis.
- Confidence and source are visible for each memory.
- Participant-specific context is scoped and removable.

## Templates used

- [Why Remembered This](../templates/provenance-confidence/why-remembered-this.md)
- [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md)
- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)
- [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md)
