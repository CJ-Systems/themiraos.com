---
title: "Software 3.0 Needs a New Vocabulary"
date: 2026-05-30T07:30:00-06:00
description: "Software 3.0 reverses an old bargain — the machine starts learning our language. But the words we use for software are breaking, and we need a new vocabulary."
draft: false
---

For most of computing history, programming has meant translating human intention into a form the machine could accept.

At the lowest level, that meant machine code. Then assembly language gave programmers symbols instead of raw numbers. Compilers and high-level languages moved the work farther from the hardware. FORTRAN, COBOL, C, Java, Python, JavaScript, and countless others changed the way programming felt, but the basic relationship stayed familiar: the human learned a programming language for the machine, then expressed intent through formal syntax.

That was the bargain.

The computer would do exactly what it was told, but only if the programmer could describe the task in a language strict enough for the machine to understand.

Software 3.0 begins to change that bargain.

The phrase "Software 3.0" is not mine. Andrej Karpathy coined the [Software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35) framing for neural networks trained from data, and later used [Software 3.0](https://www.youtube.com/watch?v=LCEmiRjPEtQ) to describe the shift where large language models become programmable computers. This essay is not an attempt to rename that idea. It is an attempt to flesh out what that shift may require from our vocabulary.

It does not mean traditional programming disappears. We still need architecture, testing, security, performance, data modeling, deployment, maintainability, and careful engineering judgment. Serious software cannot be replaced by vibes. Software 3.0 should not mean "vibes replace engineering."

But it does change who can participate in programming, and where programming begins.

Programming has always required people to learn the machine's language. Software 3.0 begins reversing that relationship: the machine starts learning to work from ours.

A person can now sit down and explain what they want to accomplish. They can describe constraints, examples, edge cases, goals, permissions, and what success should look like. The agent can ask questions, propose structure, write code, run tests, revise, and explain what changed.

That is still programming, but it is programming at a different layer.

## The Three Layers

Software 1.0 is traditional code: explicit instructions written by humans. This is still the foundation. Operating systems, compilers, databases, APIs, browsers, runtimes, tests, deployment pipelines, and the tools agents use are all built from Software 1.0.

Software 2.0 is learned behavior: systems trained from data instead of directly programmed line by line. Neural networks, language models, vision models, recommendation systems, classifiers, and embeddings belong here. Software 2.0 gave us machines that can recognize patterns, generate language, and generalize from examples.

Software 3.0 does not erase either layer. It sits on top of them. It uses Software 1.0 as the deterministic substrate and Software 2.0 as the learned interpreter. What changes is the programming surface. Instead of starting with formal code, the human can now begin programming through natural language.

Software 3.0 is new not because it escapes code or models, but because it changes where human intent enters the system.

## A Long Desire

This desire is not new. Computing history is full of attempts to move programming away from raw machine instructions and closer to human thought.

FORTRAN moved programmers away from assembly. Grace Hopper's FLOW-MATIC, and the COBOL it helped inspire, pushed programming toward human-readable business language. Later, tools like Lex, Yacc, and Bison let programmers define the rules for languages themselves: tokens, grammars, and translation patterns.

Each step raised the level at which humans could describe intent.

But these were still formal systems. They could be more readable, more abstract, and more powerful, but they still required exact grammar, exact structure, and exact rules. The machine still demanded a language designed for it.

Software 3.0 pushes the old desire further. The "language" is no longer only a formal grammar defined ahead of time. It can include natural language, examples, tests, memory, tools, constraints, and feedback.

## Pseudocode Was The Bridge

Pseudocode was never meant for the machine. It was how humans clarified intent, designed algorithms, and reasoned about programs before translating them into formal code. Software 3.0 changes that relationship. The language of intent is no longer just preparation. It is becoming the programming medium.

That does not mean loose English magically becomes reliable software. The hard parts remain. Maybe they become even more important.

If natural language becomes the programming medium, then we need better words for the structures around it. We need vocabulary for intent, context, constraints, capabilities, delegation, authority, verification, memory, and recovery.

## Why The Old Words Break

Words like "app," "command," "interface," "automation," "tool," and even "program" still matter, but they do not fully describe what is happening.

A prompt is not just a command. Context is not just data. Memory is not just storage. A tool is not just a plugin. An agent is not just a chatbot. A user is not merely clicking buttons on an interface.

Something stranger and more interesting is emerging: systems shaped not only by code, but by intent, memory, permissions, and feedback.

A Software 3.0 system does not only need functions and APIs. It needs ways to describe what the human wants, what the agent is allowed to do, what tools it can reach, what memory it should use, what evidence counts as success, and when it should stop and ask.

That is a different kind of programming surface — not merely another English-like language, but a programming relationship. The vocabulary we need is not syntax for a compiler. It is coordination language for humans and agents working together through tools, memory, constraints, and feedback.

That is why the old words feel too small.

When we say "the interface," do we mean the screen, the chat, the agent, the tool call, the memory system, or the relationship among them?

When we say "memory," do we mean a file, a vector database, a summary, a preference, a past decision, or continuity across time?

When we say "tool," do we mean a button, an API, a script, a permissioned capability, or an extension of the agent's reach?

When we say "program," do we mean source code, prompt, context, tests, workflows, schemas, retrieved documents, or the behavior that emerges from all of them together?

Software 3.0 forces these questions because the thing we are building is no longer only a static artifact. It is an ongoing process of interpretation, action, correction, and memory.

That is the deeper reason vocabulary matters.

## A Starter Vocabulary

This does not need to begin as a grand theory. It can begin as a working vocabulary for builders.

**Intent** is the human's desired outcome. It is not merely a command. It includes purpose, preference, context, and what success is supposed to mean.

**Context** is the surrounding information that shapes interpretation. It can include files, history, prior decisions, user preferences, project state, environment, and the situation in which the request is made.

**Constraint** is a boundary the system must respect. Constraints include technical limits, safety rules, budget, style, deadlines, permissions, privacy, and things the agent must not do.

**Capability** is something the agent can actually do. A model may understand a request, but it only gains practical reach through capabilities: tools, APIs, scripts, filesystems, browsers, calendars, terminals, and other permissioned actions.

**Delegation** is the act of assigning work to an agent with a goal, scope, and expected result. Good delegation does not merely say what to do. It defines what the agent owns, what it may decide, and when it should return for help.

**Authority** is the agent's permission to act. It answers a different question than capability. Capability asks, "Can the system do this?" Authority asks, "Is it allowed to do this here, now, for this person?"

**Verification** is evidence that the work matches the intent. In Software 1.0, that might mean tests, types, logs, or review. In Software 3.0, it also includes explanations, citations, screenshots, dry runs, user confirmation, and observable outcomes.

**Memory** is retained context that can shape future behavior. It is not just storage. A useful memory system must distinguish facts, preferences, decisions, summaries, raw records, and uncertain interpretations.

**Recovery** is how the system handles failure. It includes noticing when something went wrong, explaining what happened, preserving enough state to continue, and repairing the result without pretending the failure did not occur.

These words are not final. They are a starting kit. But even this small vocabulary changes the design conversation. Instead of asking only, "What should the app do?" we can ask sharper questions: What is the user's intent? What context is relevant? What constraints apply? What capabilities are available? What authority has been granted? What evidence will verify success? What should be remembered? What happens when the agent is wrong?

That is the practical work ahead.

New words do not create the future by themselves. But without better words, we cannot clearly design, criticize, govern, or trust what we are building.

Software 3.0 needs a new vocabulary because vocabulary is how a new programming surface becomes visible. Once we can name its parts, we can build them deliberately.

---

*Written with Mira — an AI agent I'm building as part of Mira-OS, an ongoing build-in-public project. I brought the thesis, the historical framing, and the final call; Mira shaped the structure, language, and synthesis. An essay about humans and agents programming together through intent and feedback was, fittingly, produced exactly that way.*

## References

**Karpathy's framing**

- Andrej Karpathy, "[Software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35)," Medium, November 11, 2017.
- Andrej Karpathy, "[Software Is Changing (Again)](https://www.youtube.com/watch?v=LCEmiRjPEtQ)," keynote at Y Combinator's AI Startup School, San Francisco, June 17, 2025. ([Y Combinator library page](https://www.ycombinator.com/library/MW-andrej-karpathy-software-is-changing-again))

**Historical languages and tools**

- [FLOW-MATIC](https://en.wikipedia.org/wiki/FLOW-MATIC) — Grace Hopper, Remington Rand, for the UNIVAC; first English-like data-processing language (~1955–1959).
- [COBOL](https://en.wikipedia.org/wiki/COBOL) — CODASYL committee design, 1959–60, heavily influenced by FLOW-MATIC.
- [Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper) — FLOW-MATIC author; technical consultant and evangelist to the COBOL effort.
- [FORTRAN](https://www.ibm.com/history/fortran) — IBM, John Backus and team; shipped April 1957 for the IBM 704.
- [Lex](https://en.wikipedia.org/wiki/Lex_(software)) — Mike Lesk and Eric Schmidt, Bell Labs, 1975; generates lexical analyzers.
- [Yacc](https://en.wikipedia.org/wiki/Yacc) — Stephen C. Johnson, Bell Labs, early 1970s; generates parsers.
- [GNU Bison](https://www.gnu.org/software/bison/) — Robert Corbett, 1985; GNU reimplementation of Yacc, made Yacc-compatible by Richard Stallman.
