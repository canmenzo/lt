---
name: lt
description: Re-explain your previous response in layman terms, short. Only when the user types /lt.
disable-model-invocation: true
argument-hint: "[part to focus on] [language]"
---

Re-explain your **last response** (the one right before this command) in layman terms, for a smart person with no background in the topic.

Rules:
- Explain what is already there. No tool calls, no new work, no new facts or claims.
- Lead with the one-sentence bottom line: what happened or what the answer is.
- Then at most 3 to 5 short bullets: what it means in practice, and what the user has to do, if anything. Skip a bullet that would be empty.
- Plain words. Drop jargon, file paths, flags and code unless the user needs to type or click them; if a term has to stay, explain it in a few words. One everyday comparison is fine when it really helps.
- Keep every warning, risk, number or open item that matters. Shorter must not mean less true.
- Language: the one the user has been writing in lately. A language name or code in the arguments (`en`, `tr`, `de`...) overrides that.
- If the arguments name a part ("only the risks", "the second point"), explain only that part.
- No em dashes, no emojis, no closing summary, no "let me know if".

Arguments: $ARGUMENTS
