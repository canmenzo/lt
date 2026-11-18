---
name: lt
description: Re-explain your previous response concisely in layman terms. Only when the user types /lt.
disable-model-invocation: true
argument-hint: "[part to focus on] [language]"
---

Say your last response again, concisely and in layman terms.

Write it the way you would tell a friend who does not know the topic: two or three short paragraphs of plain prose, about a third of the original's length. Give the gist, not a translation of every point: the one thing that is going on, and what to do about it. Leave out side options and detail a layperson does not need, and keep a warning or a step only if the user would be worse off without it. One everyday comparison is welcome when it makes the idea click. No headers, no bullet list unless the user has steps to follow in order.

Explain only what you already said: no tool calls, no new work.

Answer in the language the user has been writing in. If the arguments name a language, use that one; if they name a part ("only the risks"), explain just that part.

Arguments: $ARGUMENTS
