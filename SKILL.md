---
name: "stop-slop"
description: "Remove AI writing patterns from prose, headlines, slides and documents so they read as plain English. Use when drafting, editing, or reviewing text to eliminate predictable AI tells."
metadata:
  trigger: Writing prose, editing drafts, reviewing content for AI patterns
  author: Charlie Cheesman (based on the original by Hardik Pandya (https://hvpandya.com))
---

# Stop Slop

Make text read as if a capable person wrote it for a specific reader. This skill sets no personal tone. It removes the habits that mark text as machine-written and replaces them with plain, grammatical English.

The standard is Steven Pinker's classic style and the Plain English Campaign's guidance: write the sentence a sharp colleague would say aloud to this reader, across a table, in one breath.

Where `references/phrases.md` or `references/structures.md` say "always" or "never" and this file allows an exception, this file wins. Ignore the punchy one-line endings in `references/examples.md`; use the examples at the end of this file.

---

## 1. Start with the document, not the sentence

Before you edit a single line, settle four things:

- **Who wrote it.** This fixes "we" and "our".
- **Who reads it.** This fixes "you" and "your", and how to describe people. In a consultancy's proposal to a client, the client's safety officer is "your Clinical Safety Officer", not "our".
- **What the reader must decide or do.** Every headline should move the reader toward that decision. In a proposal, the reader is being persuaded; in a report, informed; in an instruction, told what to do.
- **What kind of document it is.** Proposal, board paper, slide deck, report, email, essay.

A rewrite that reads well but gets a role, relationship, number or commitment wrong is worse than the original. Never change who someone is, who they work for, or what a number is.

---

## 2. Write to the standard

**Read-aloud test.** Read each sentence aloud once. If you would stumble, restart or have to re-read it to parse it, rewrite it.

**Grammar rules**

1. **Actor, then verb, then object.** The subject is a person, team, organisation, or a measured number with a measuring verb (rose, fell, cost).
2. **Cause before effect.** State what happened, then what follows from it.
3. **Known before new.** Start with what the reader already has; end on the new information.
4. **One idea per sentence.** A second idea gets its own sentence. In a title, a semicolon or spaced hyphen can join two clauses.
5. **Main clause first, nothing bolted on.** No trailing phrases that carry a second fact (", on a Cardinal integration the pod builds", ", safely").
6. **Keep the small words.** "The", "that", "so", "is", "will" hold English together. Don't drop "that" from a relative clause to save a word.
7. **Match tense to time.** Facts now in the present. Plans and projections with "will". Don't use the present tense for a forecast ("EBITDA heads to £0m").
8. **Don't hedge a conditional.** "If nothing changes, EBITDA will fall to £0m" needs no "about" or "~"; the condition already does the hedging.
9. **State verbs need a value.** Never leave "holds", "heads", "stays", "remains" or "sits" bare. "EBITDA holds" becomes "EBITDA stays flat at £4m".
10. **Numerals for numbers.** 3, 7, 10, not three, seven, ten.
11. **One referent per pronoun.** Each "it" or "they" points at one thing. If two things could fit, name it.
12. **Precise verbs.** Replace fix, drive, reach, move, go, land, deliver, unlock, carry and give with what happens and by how much.
13. **Write at the lowest useful level of abstraction.** "Only owners can merge" over "merge authority is restricted to the owner role". Name the specific thing instead of a vague declarative ("The implications are significant").
14. **Headlines can run to 2 lines.** A longer grammatical headline beats a short broken one. Never compress a title to hit a word count.
15. **Headlines state the point.** A section or slide title says what the reader should conclude, framed toward the document's purpose. A chart label can name what's shown.

---

## 3. Patterns to remove

### Words

- **Emphasis adverbs:** really, just, literally, genuinely, honestly, simply, actually, deeply, truly, fundamentally, crucially. Keep adverbs that carry meaning: monthly, first, in-house.
- **Filler and throat-clearing:** "Here's the thing", any "here's what/this/that", "It turns out", "At its core", "It's worth noting", "When it comes to", "Let that sink in". Full list in `references/phrases.md`.
- **Staged emphasis labels:** "the deeper point", "the real question". Make the point.
- **Metaphors standing in for plain words:** load-bearing, surface, path, layer, leak. Use the plain word.
- **Lazy extremes** (every, always, never, nobody) doing vague work. Keep them when literally true.
- **Jargon and deck cliches:**

| Avoid | Use instead |
|-------|-------------|
| "what good looks like" | The benchmark and its number |
| "[patient / customer] journey" | The steps, by name |
| "AI-native" (unless the client's own phrase) | What the AI does |
| "levers", "unlock", "drive(s)" | The action and its effect in £ or % |
| "goes live" with an abstract subject | The tool and the site |
| "foundations", "pillars", "workstreams" | The work items |
| Team names the reader hasn't met ("the pod") | Who they are ("our engineers") |
| Nouns used as verbs ("baseline London West") | "measure London West's starting point" |
| Shorthand in reader-facing titles ("W2", "OOS") | "week 2", "out of scope" |
| Unquantified superlatives ("fastest payback", "no clinical risk", "Europe's first") | The number, or cut it |
| navigate, unpack, lean into, landscape, deep dive, circle back | handle, explain, accept, field, analysis, return to |

### Sentence shapes

- **False agency.** Ideas, steps, priorities, sites, bids, decisions, metrics and processes doing human things: "10 ideas go first", "each step loses", "outsourcing drives both", "German sites show what good looks like", "the bid carries measured results", "the decision emerges". Name who acts, or give the number.
- **Nominalisations hiding the actor.** "Merge authority is restricted" becomes "only owners can merge".
- **Bolt-on "with X -ing".** "Fix billing first, with Ravi signing off every tool" glues a second actor onto the first idea. Split it. "With" is fine when it introduces a direct consequence of the main clause: "EBITDA will fall to £0m, with all 3 contract KPIs missing target."
- **Reversed or trailing clauses.** The key dependency arrives last as an add-on: "3 priorities go live by March, on a Cardinal integration the pod builds." Put the actor and the dependency first.
- **Mid-sentence wedges.** A role or aside jammed between verb and object: "Ravi signs it, as Clinical Safety Officer, before it affects a patient." Put the role next to the name.
- **Balanced pairs with a summary tag.** "EBITDA heads to £0m and Wavelength misses all 3 KPIs. Outsourcing drives both." Two mirrored effects, then a short line naming the cause. Lead with the cause.
- **Unasked reassurance.** Tails that answer an objection nobody raised: "and none of them writes a report", "and does it safely", ", safely". Cut it, or prove it in the section that covers it.
- **Taglines.** Every item ending by restating what the reader gets. Cut them.
- **Triads with a vague last item.** "Reaches 3x patients, keeps its £80m contract and does it safely." Cut the item that carries no fact.
- **Mismatched lists.** Items in different grammar: "agree measures, baseline London West, results to the board". Make every item the same shape.
- **Mixed clauses across a semicolon.** "This week we agree measures; by W2 London West is baselined and the build has started" switches tense, voice and actor mid-sentence. Keep one actor and one tense.
- **Idioms in place of numbers.** "Reads rose and took the margin with them." Give the margin.
- **Wh- clefts and descriptive Wh- headings.** "What makes this hard is...", "That's what makes it work", "What drives the risk, and how we remove it", "What each step loses". State the finding instead. A plan title such as "How Wavelength reaches 3x patients by 2030" is fine.
- **"Which is why / what / the" tails.** Start a new sentence or cut.
- **Binary contrasts and negative listing.** "Not X, it's Y", "It wasn't X. It was Y.", a sentence ending on a "not X" tail. State Y. Keep a "rather than" clause only if the alternative was live. See `references/structures.md`.
- **Rhetorical setups.** "What if...?", "Think about it:", "And that's okay." Make the point.
- **Announced counts.** "Four ways to..." before a list. Cut the count.
- **Narrator-from-a-distance.** "Nobody designed this", "People tend to...". Put the reader in the scene; "you" beats "people".
- **Meta-joiners.** "The rest of this essay...", "Let me walk you through...". Delete.
- **Quotables, dramatic fragments and punchy endings.** "That's it. That's the tradeoff." If it sounds like a pull-quote, rewrite it. Vary paragraph endings.
- **Metronomic rhythm.** 3 sentences of the same length in a row, or the same paragraph opener 4 times running. Break the pattern.
- **Mirror-pair titles.** "Revenue up, EBITDA down." Keep only when the chart shows both numbers.
- **Em dashes.** Use commas, colons, semicolons or full stops.

### Across the document

- **Check every string the reader sees:** headlines, subtitles, cards, chart titles, axis labels, table cells, callouts, buttons, footnotes, and text built by script. Table cells can be fragments; every other rule still applies.
- **Repetition.** A sentence restating the one before it, or the same claim in 3 or more places ("Ravi signs every tool"). Keep it in the summary and the section that proves it.
- **Headline chain.** Read the headlines alone, in order. They should make the argument to the reader.

---

## 4. Don't over-correct

Every ban invites a substitute that is just as bad. Watch for these:

- **Passive is allowed** when the actor doesn't matter or is obvious: "before it is used on patients". Never invent an actor ("ideas go first") to avoid a passive.
- **Don't shorten past grammar.** If cutting a word breaks the sentence, keep the word. If the shorter version is less true, keep the longer one.
- **Don't move a cut word.** A banned adverb moved to a comma tail is still there.
- **Don't force two items** when the reader needs three facts. Cut the third item only when it carries no fact.
- **Check the rewrite** with every check above. A fix carries its own tells. See Over-Correcting in `references/structures.md`.

---

## 5. Process

1. Settle author, reader, purpose and document type (section 1).
2. Pull out every visible string. For HTML, include text in scripts and SVG; for slides, include titles, body, chart labels and notes.
3. Check each string against sections 2 and 3, and rewrite.
4. Read each rewrite aloud. Confirm names, roles, relationships, numbers and commitments match the original.
5. Read the headlines alone, in order, and check they make the argument.
6. For high-stakes documents (client proposals, board papers, decks going to a client), have a fresh reviewer with no sight of the drafting check the strings: give it the context from step 1, the strings, and this file, and ask for pass or rewrite on each.

---

## 6. Examples

From a consultancy's proposal asking a radiology company's CEO to fund the next phase. "We" is the consultancy; "your" is the client.

**1. Exec summary headline**
- Before: To rebuild Wavelength as an AI-native business, fix how work reaches the radiologist before AI reads scans
- After: To rebuild Wavelength as an AI-native business, start with routing, booking and billing, and add AI scan-reading in Phase III
- Why: "Fix how work reaches" is vague, with a "how" clause as its object. "Before AI reads scans" can mean a sequence or a workflow step.

**2. Answer paragraph**
- Before: Fix routing, booking and billing first, with Ravi signing off every tool.
- After: Start with routing, booking and billing; Ravi approves each tool before staff use it.
- Why: Bolt-on "with X -ing" joins two actors and makes them sound simultaneous.

**3. Problem headline**
- Before: FY27 EBITDA heads to ~£0m and Wavelength misses all 3 contract KPIs. Outsourcing drives both
- After: Outsourcing rose from [x]% to [y]% of MRI/CT reads in a year. If nothing changes, FY27 EBITDA will fall to £0m, with all 3 contract KPIs missing target.
- Why: Balanced effects then a cause tag; present tense for a forecast; a hedge on a conditional; vague "heads" and "drives".

**4. Solution headline**
- Before: Fix 7 steps of the patient journey. 10 ideas go first, worth £[x]m a year, and none of them writes a report
- After: We start with 10 admin tools across 7 steps, from referral to invoice, worth £[x]m a year. We add AI reporting in Phase III.
- Why: Ideas can't go anywhere; tools can't write; the tail answers an objection nobody raised.

**5. Chart title**
- Before: What each step loses, and the ideas that fix it
- After: Wavelength loses £[x]m a year across 7 steps, from referral to invoice; we fix the biggest losses first
- Why: Descriptive Wh- heading; steps and ideas acting. The title should state what the chart proves.

**6. Plan headline**
- Before: Three priorities go live at London West by March, on a Cardinal integration the pod builds
- After: Our engineers build a link into Cardinal so the first 3 tools can go live at London West by March
- Why: The dependency arrives last as an add-on; "that" dropped; priorities acting; jargon ("the pod"); number in words.

**7. Safety body**
- Before: Every tool gets a safety case. Ravi signs it, as Clinical Safety Officer, before it affects a patient.
- After: Ravi, your Clinical Safety Officer, signs a safety case for each tool before it is used on patients.
- Why: Role wedged mid-sentence; 3 "it"s for 2 things; "affects" is vague. "Your", because Ravi works for the reader. Passive is the honest form here.

**8. Subtitle**
- Before: How Wavelength reaches 3x patients by 2030, keeps its £80m contract and does it safely.
- After: How Wavelength reaches 3x patients by 2030 and keeps its £80m contract
- Why: The third item carries no fact.

**9. Risk chart title**
- Before: What drives the risk, and how we remove it
- After: The main risks, and how we reduce each
- Why: Descriptive Wh- heading; "drives"; "remove" claims more than any control delivers.

**10. Next steps**
- Before: This week we agree measures and access; by W2 London West is baselined and the build has started
- After: This week we agree the success measures and get access to Cardinal; in week 2 we measure London West's starting point and start the build.
- Why: Tense, voice and actor switch across the semicolon; "baselined" is a noun used as a verb; "W2" is shorthand in a title; "access" to what?

**11. Short fixes from the same document**
- "Outsourced reads rose and took the margin with them" becomes "Outsourced reads rose from [x]% to [y]%, cutting EBITDA margin from [a]% to [b]%"
- "That gives the September 2027 bid measured results" becomes "so Wavelength goes into the September 2027 bid with measured results"
- "Pilots at London West move turnaround and waits" becomes "London West pilots will cut turnaround to [x] days and waits to [y] weeks"
- "3x patients by 2030 needs ~32% a year" becomes "Reaching 3x patients by 2030 takes 32% growth a year"
- "We build normal-scan AI in-house in Phase III, on a certified medical-device route" becomes "In Phase III we build normal-scan AI in-house and certify it as a medical device"
- "£1.20 on all 3.4m studies for three years costs four times the £3m budget" becomes "Northlight charges £1.20 a study. Across 3.4m studies for 3 years that's £12m, 4 times the £3m budget."
- "Agree measures this week, baseline London West next week, results to the board on 25 March" becomes "This week we agree measures; next week we measure London West's starting point; on 25 March we bring results to the board"

---

## Scoring

Rate 1-10 on each:

| Dimension | Question |
|-----------|----------|
| Read-aloud | Can you say every sentence once, without restarting? |
| Fit | Right pronouns, roles and framing for this reader and purpose? |
| Directness | Statements, not announcements? |
| Specificity | Numbers and named actors, not abstractions? |
| Density | Anything cuttable without breaking grammar? |

Below 40/50: revise.

## License

MIT