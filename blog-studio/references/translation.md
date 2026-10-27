# Translation

Input: an article for a new language or audience. Read the whole source before translating, identify argument and register, and make a small working glossary for terms that recur or have competing translations. Draft a separate translation, preserving code, identifiers, citations, original quotations where required, numbers, negation, scope, causal relations, uncertainty and version conditions. Compare each paragraph with its source for omitted, added or strengthened claims; resolve terminology in context. Only then polish for natural target-language reading and repeat the semantic check. The Markdown source stays unchanged. Deliver the translation and any genuine unresolved ambiguity separately.

Example: “may reduce latency only in version 2” must retain both possibility and version restriction. “Version 2 reduces latency” silently changes the evidence and is not a faithful translation.

## Worked example

Source context (hypothetical): “In this system, the watermark is an estimate of event-time progress. The watermark is a low-water mark, not a clock: events arriving after it may still be accepted if the configured grace period has not expired.” A literal rendering of “low-water mark” as “低水位线” may suggest a literal river and obscure the technical threshold; rendering “not a clock” as “不是时钟” alone may leave a newcomer wondering why a clock is mentioned. For readers unfamiliar with stream processing, introduce the technical term and explain the comparison: “水位线表示系统对事件时间进度的估计，并非墙上时钟；水位线之后到达的事件，只要配置的宽限期尚未结束，仍可能被接受。”

Retain “may”, the configured grace condition, and the distinction between event time and clock time; do not say all late events are accepted. If the reader already knows the term, a concise translation needs no footnote. If a culturally specific metaphor is essential to the author's argument and its meaning cannot be conveyed naturally, add a brief note; do not annotate every idiom. The example assumes the surrounding article establishes the model; verify the source's actual definition before applying this interpretation elsewhere.
