# Issue Flag Definitions

Flags in [`data/work-buckets.csv`](../data/work-buckets.csv) mark structural problems identified in a work bucket during a workshop review. A single bucket can carry multiple flags. Use these definitions to guide discussion, surface root causes, and prioritise redesign actions.

> **Note:** A blank Flags cell means "no issue flagged yet" — not necessarily that no issue exists. Unflagged buckets may still warrant review.

## Flag Reference Table

| Flag | Definition | Typical signals / examples | Suggested workshop question |
|------|-----------|---------------------------|----------------------------|
| **Boundary** | The bucket's scope is poorly defined — activities bleed into adjacent buckets or the bucket absorbs work that belongs elsewhere. | Two teams both claim ownership of the same task; handoffs are unclear; the bucket name doesn't match its actual content. | "Where does this bucket start and stop, and does everyone agree?" |
| **Gap** | A necessary activity has no clear home — it either falls between buckets or is missing entirely from the map. | Work that "just happens" informally; recurring escalations because nobody owns a task; customer complaints tied to an unassigned activity. | "Is there work that needs to be done that no bucket currently covers?" |
| **Duplication** | The same (or nearly the same) activity is performed in two or more buckets, creating redundant effort and potential conflicts. | Two teams maintaining separate versions of the same data; parallel approval loops; duplicate reporting. | "Which bucket should own this activity, and what should the other bucket stop doing?" |
| **WrongFunction** | The work in this bucket is being performed by a function or role that is not the best fit — either due to skill mismatch, cost, or span-of-control concerns. | A high-level manager doing transactional tasks; an operational team making strategic decisions; a support function owning a core process. | "Is the current owner the right function for this work, and if not, who should own it?" |
| **UnclearOwnership** | It is ambiguous who is accountable for the bucket's outcomes — multiple parties share nominal ownership without clear decision rights. | "Everyone owns it so nobody owns it"; escalations loop without resolution; metrics are tracked by multiple teams with different numbers. | "Who is the single accountable owner, and do they have the authority to act?" |
| **ExcessCoordination** | The bucket requires a disproportionate amount of cross-team coordination to execute, signalling that boundaries, ownership, or process design may need to change. | Weekly syncs just to complete routine tasks; decisions requiring sign-off from four or more stakeholders; high meeting load relative to output. | "What is driving the coordination overhead, and how could this work be restructured to reduce it?" |
