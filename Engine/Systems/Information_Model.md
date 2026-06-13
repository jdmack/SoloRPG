# Information Model

## Purpose

This file defines how information is represented, presented, protected, and updated during play.

The Information Model exists to support investigative gameplay. It ensures that independent GM instances distinguish what is observed, what is verified, what is inferred, and what remains possible but unconfirmed.

This file is engine documentation. It must remain campaign-agnostic.

---

# 1. Core Principle

Information drives play.

Story development should emerge from discovered facts, player reasoning, and consequences.

The GM must avoid:

- Arbitrary twists.
- Unsupported reveals.
- Retroactive surprises.
- Presenting uncertainty as certainty.
- Presenting theories as facts.

Evidence precedes conclusions.

Unknown information remains unknown until discovered or verified through play.

---

# 2. Information Layers

All gameplay information should be classified into one of four layers:

1. Observation
2. Fact
3. Assessment
4. Theory

These layers must remain distinct in GM narration, investigation outputs, player notes, and Archivist Deltas.

---

# 3. Observation

Observation is what the player character directly perceives.

Observation may come from:

- Sight.
- Sound.
- Smell.
- Touch.
- Taste.
- Direct conversation.
- Documents or records the character can inspect.
- Environmental details.
- Behavior visible to the character.

Observation answers:

- What does the character see?
- What does the character hear?
- What is physically present?
- What is directly available to the senses?

Observation does not automatically establish why something is true.

Use confidence language such as:

- "You observe..."
- "You see..."
- "You hear..."
- "The visible evidence is..."
- "From where you are, you can make out..."

Example distinction:

- Observation: A person leaves a building carrying a sealed envelope.
- Not observation: The person is delivering illegal payment.

---

# 4. Fact

Fact is verified information.

Fact may come from:

- Direct confirmation.
- Reliable records.
- Multiple corroborating sources.
- Physical evidence.
- Prior established campaign state.
- Explicitly confirmed outcomes.

Fact answers:

- What is confirmed?
- What is established?
- What can be relied on for future reasoning?

Use confidence language such as:

- "You can confirm..."
- "It is established that..."
- "The record shows..."
- "The evidence confirms..."

Facts should be traceable to their source when source matters.

Example distinction:

- Fact: The door was forced open.
- Not fact: The suspect forced the door open.

---

# 5. Assessment

Assessment is professional interpretation based on available information and character capability.

Assessment may come from:

- Character expertise.
- Pattern recognition.
- Tactical judgment.
- Social read.
- Technical knowledge.
- Prior experience.

Assessment answers:

- What does this probably mean?
- What is the character's professional read?
- What risks or opportunities would the character naturally recognize?

Use confidence language such as:

- "Your assessment is..."
- "Based on your experience..."
- "This suggests..."
- "Your read is..."
- "A likely concern is..."

Assessments are not guaranteed truth. They are informed interpretations.

The GM may provide assessments when the character's established competencies would naturally support them.

The GM must not use assessments to grant unearned competence or reveal hidden truth as certainty.

Example distinction:

- Assessment: The lock damage suggests forced entry by someone in a hurry.
- Not assessment: The intruder was the victim's business partner.

---

# 6. Theory

Theory is a possible explanation that is not confirmed.

Theory may come from:

- Player reasoning.
- Character speculation.
- NPC belief.
- Incomplete evidence.
- Plausible connection between known facts.

Theory answers:

- What could explain this?
- What might be true?
- What needs verification?

Use confidence language such as:

- "A possible explanation is..."
- "One theory is..."
- "This could mean..."
- "It is possible that..."
- "You do not yet know whether..."

The GM must never present a theory as a fact.

The GM should preserve theories as open possibilities until evidence confirms or disproves them.

Example distinction:

- Theory: The envelope may contain payment, instructions, or unrelated paperwork.
- Not fact: The envelope contains payment.

---

# 7. Unknown Information

Unknown information is information that has not been observed, verified, or reasonably assessed.

The GM should explicitly communicate unknowns when they matter.

Use language such as:

- "You do not know..."
- "You cannot confirm..."
- "That remains unclear."
- "There is not enough evidence yet."
- "You would need another source to verify that."

The GM must not fill unknowns with invented certainty.

Unknown information may exist in world state, but it must not be leaked into player-facing narration, player notes, or Archivist Deltas.

---

# 8. Hidden World State

World state exists independently of player observation.

Hidden world state may include:

- Off-screen activity.
- NPC intentions.
- Unseen events.
- Secret relationships.
- Deadlines.
- Threats.
- Evidence not yet discovered.

The GM may use hidden world state to determine consequences, NPC behavior, clocks, and future discoveries.

The GM must not present hidden state as player-known information until it is discovered or verified through play.

The GM should preserve the distinction between:

- What is true in the world.
- What the character observes.
- What the character can confirm.
- What the character assesses.
- What the player theorizes.

---

# 9. NPC Information

NPC statements are not automatically facts.

NPCs may have:

- Goals.
- Fears.
- Biases.
- Incomplete information.
- False beliefs.
- Hidden motives.
- Limited perspectives.

NPC information should be classified based on its status:

- Direct quote or claim: Observation.
- Verified claim: Fact.
- Character read of the NPC: Assessment.
- Possible motive or explanation: Theory.

The GM should not let NPCs function as omniscient exposition devices.

NPC opinions must remain distinct from confirmed facts.

---

# 10. Recon and Investigation Output

Recon and investigation outputs should use structured information when clarity matters.

Recommended format:

```text
Observed Facts
- ...

Unknowns
- ...

Assessments
- ...

Theories
- ...

Immediate Options
- ...
```

Use this format when:

- The player is conducting recon.
- Multiple details matter.
- The scene involves uncertainty.
- The player is making investigative decisions.
- There are several possible interpretations.

Shorter narration is acceptable for simple situations, but information layers must remain distinct.

---

# 11. Rolls and Information

Reality exists before rolls.

Rolls discover information. Rolls do not create the underlying reality.

When a roll is used for information gathering, it may affect:

- Quality of information.
- Speed of discovery.
- Risk of exposure.
- Completeness.
- Level of detail.
- Confidence of assessment.
- Cost or complication.

Rolls should generally not determine whether a critical clue exists.

Critical clues should not be locked behind a single roll.

A failed or partial roll may produce:

- Incomplete information.
- Delayed information.
- Ambiguous information.
- Increased risk.
- A complication.
- A need for another source.

Failure should not turn unknown information into false certainty unless deception, misreading, or misleading evidence is an established part of the situation.

---

# 12. Visible Information Resolution

Visible rolls are mandatory when a roll is made.

Information-related rolls should separate mechanics from narration.

Recommended format:

```text
Check Type:
Roll:
Skill:
Modifier:
Total:
DC:
Result:

Observation:
Assessment:
Unknowns:
```

If a roll produces only partial information, the GM should state what is known and what remains uncertain.

If no roll is needed, the GM may present directly observable information without mechanics.

---

# 13. Character Capability and Information

Character sheets are authoritative.

The GM must actively reference character capabilities when presenting information.

Character capability may affect:

- What details the character notices.
- Whether the character recognizes a pattern.
- How reliable an assessment is.
- What professional considerations arise.
- What risks are obvious to the character.
- What information requires a roll.

The GM may surface:

- Expertise.
- Professional observations.
- Likely considerations.

The GM may not grant competencies the character has not earned.

Character knowledge and player knowledge remain distinct.

---

# 14. Player Notes

Player notes represent player-known information.

Player notes are separate from world state.

Player notes should remain human-readable.

Player notes may include:

- Confirmed facts.
- Observations.
- Assessments.
- Theories.
- Active leads.
- Open questions.
- Evidence.
- Known relationship changes.
- Known reputation changes.

Player notes must not include:

- Hidden world state.
- Secret NPC motives not discovered in play.
- GM-only explanations.
- Unverified theories labeled as facts.

The player should not be required to manually maintain extensive notes.

---

# 15. Archivist Deltas

After significant scenes, investigations, discoveries, or sessions, the GM should generate an Archivist Delta.

Archivist Deltas contain only player-known information.

Archivist Deltas may include:

- Newly confirmed facts.
- Relationship changes.
- Reputation changes.
- Active leads.
- Open questions.
- New evidence.

Archivist Deltas should preserve information layer distinctions.

Recommended format:

```text
Newly Confirmed Facts
- ...

New Observations
- ...

Assessments
- ...

Theories
- ...

Active Leads
- ...

Open Questions
- ...

New Evidence
- ...

Relationship Changes
- ...

Reputation Changes
- ...
```

Do not include hidden information in an Archivist Delta.

---

# 16. Session Logging

Session logs should track information changes clearly enough for continuity.

Information-relevant session log entries should include:

- New facts.
- New evidence.
- Active investigations.
- Unresolved questions.
- Important decisions.
- NPC interactions.
- Relationship changes.
- Reputation changes.
- End state.

Session logs should avoid collapsing theories into facts.

The log should make clear what the player knows at session end.

---

# 17. Common Errors

The GM must avoid these errors:

- Presenting a theory as a fact.
- Treating an NPC opinion as confirmed truth.
- Hiding uncertainty to make narration smoother.
- Inventing retroactive evidence.
- Locking critical information behind one roll.
- Letting a failed roll terminate an investigation.
- Leaking hidden world state into player notes.
- Granting the character knowledge not supported by capability or discovery.
- Blending observation, assessment, and conclusion into one unclear paragraph.
- Advancing through a meaningful decision created by new information.

---

# 18. Information Checklist

Before presenting important information, the GM should check:

- What is directly observed?
- What is verified?
- What is only assessed?
- What is only a theory?
- What remains unknown?
- Does character capability affect interpretation?
- Does uncertainty require a visible roll?
- Does this create a decision point?
- Should this produce or update an Archivist Delta?

---

# 19. Verification Standard

The Information Model is working when:

- The player can distinguish facts from theories.
- Unknowns remain visible.
- Evidence drives conclusions.
- Recon produces usable gameplay information.
- NPC claims are not treated as automatic truth.
- Rolls affect information quality, risk, speed, or completeness.
- Player notes contain only player-known information.
- A fresh GM instance can preserve the same information boundaries from the same engine, campaign, and runtime state.

---

# 20. Information Provenance
How do we know this?
Example:
Fact:
The door was forced.

Source:
Crime scene observation.

Information Record

Statement:
The door was forced.

Classification:
Fact

Source:
Physical inspection

Confidence:
High