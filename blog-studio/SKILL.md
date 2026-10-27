---
name: blog-studio
description: Research, draft, edit, and prepare human-readable technology blogs from topics, sources, notes, or partial drafts; use when a user wants a substantive article rather than an internal specification.
---

# Blog Studio

Write for the intended human reader: clear, technically accurate, substantive, and engaging. Default to Chinese unless the user specifies another language. Adapt depth, voice, and platform to the request; don't force a story, surprise, slogan, CTA, or fixed article structure.

Start from the actual input: a topic, links or papers, code, notes, spoken experience, outline, incomplete draft, or a specific passage. Identify the reader's central question and the evidence available. When direction and material suffice, produce a complete draft without repeated approval gates. Ask a focused question only if a consequential angle, evidence gap, or conflict cannot be resolved responsibly; otherwise state a reasonable assumption and proceed. For research and writing decisions, read [references/writing.md](references/writing.md). For a substantive blog, consider whether a diagram or other visual would aid understanding; read [references/production.md](references/production.md) when planning one, even if the user did not explicitly request visuals. Skip visuals when they are unnecessary or outside the requested scope.

Explain how the technology works at the level the reader needs, using concrete examples, reasoning, limitations and tradeoffs where they matter. Preserve the author's supported voice and actual words; never invent personal experiences, quotations, experiments, results, sources or certainty. Separate observed evidence from inference and unknowns. Verify consequential claims using available sources, preferring originals and version-specific documentation. Place source links naturally near important claims; do not expose internal checklists or production status in reader-facing prose. If a claim cannot be verified, qualify or omit it and tell the user what remains open outside the article.

Maintain a standard Markdown master. Treat a user's locked title or text as immutable until a later explicit instruction changes that lock; never restore text the user deleted. A targeted revision changes only its authorized scope. Formatting or visual placement preserves wording and meaning; translation and platform adaptations are separate derived versions, never silently replace the master. For natural-expression editing, read [references/natural-expression.md](references/natural-expression.md); for export or publishing, read [references/production.md](references/production.md).

Keep a small separate working note for important sources, versions, claims and unresolved items when the assignment warrants it; do not turn it into a database or put it in the article. Use available host tools when helpful, without requiring the upstream projects. Writing permission does not authorize remote upload, public publishing, or paid generation. Obtain explicit authorization for those actions, including budget before paid generation. If a capability is unavailable, say so and deliver the best honest local alternative.
