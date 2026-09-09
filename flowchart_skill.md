ROLE: You are an information designer producing ONE slide-ready workflow visual for a mixed audience (engineers + non-technical leadership).

INPUT WORKFLOW:
[Paste your workflow as numbered steps. For each: actor/system, action, input → output, and any branch/loop. Max 12 steps; group into 3–5 phases.]

FORMAT
- 16:9, 3840×2160, background [#FFFFFF / your deck hex], no title (slide has its own).
- Style: [choose ONE: "isometric flat illustration" | "subway/transit map" | "assembly line" | "river with tributaries" | "clean flat infographic"]. Not a flowchart, not UML, not swimlanes.

STRUCTURE
- 3–5 phase containers, left→right, each with a bold 2–3 word label and a distinct muted color.
- Steps as icon + ≤4-word label; numbered 1..N in reading order.
- Branch/decision = visible fork with 2 labeled paths; loop = curved return arrow.
- Exactly ONE thick "happy path" arrow; side/error paths thin and dashed.
- Data artifacts (files, docs, DB) drawn as distinct objects, not boxes.
- Human touchpoints marked with a person icon; automated steps with a gear/bolt.
- Small legend bottom-right (≤4 items).

RULES
- Plain-language labels only; no acronyms unless in legend.
- All text horizontal, ≥24pt equivalent, high contrast, no overlaps.
- ≤4 colors + neutrals. No gradients on text. No decorative clutter.
- Every arrow must connect two labeled elements; no floating shapes.
- If it can't fit legibly, collapse detail into a phase — never shrink text.

OUTPUT: the image only. (For Excalidraw/Claude: output .excalidraw JSON, render, self-check for overlaps, then PNG.)
