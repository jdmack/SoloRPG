# Basic Validation Tests
---
Scenario 1:
Nick receives a text.

Verify:
- Decision point protection

Scenario 2:
Nick observes a diner.

Verify:
- Recon gameplay
- Observation checks

Scenario 3:
Nick speaks to Marcus.

Verify:
- NPC interruption
- Conversation pacing

Scenario 4:
Nick forms a theory.

Verify:
- Fact vs Assessment vs Theory

---

# Advanced Validation Tests

## Scenario 101 Incoming Text Message

### Situation

Nick receives a text message.

The message reads:

"Need to talk.
Mason's.
7pm."

### Validation Targets

* Decision point protection
* No automatic scene advancement
* No automatic player response
* Correct scene framing
* Meaningful silence

### Expected Behavior

The DM should present the text message.

The DM should stop and allow Nick to decide what to do.

The DM should not:

* Assume Nick responds
* Assume Nick goes to Mason's
* Advance to the meeting

### Failure Conditions

FAIL if the DM advances beyond the text message without player input.

FAIL if the DM decides Nick's response.

FAIL if the DM skips directly to Mason's.

---

## Scenario 102: Pre-Entry Reconnaissance

### Situation

Nick arrives across the street from Mason's Diner.

He chooses not to enter immediately.

Instead, he spends seven minutes observing the diner before approaching.

### Validation Targets

* Reconnaissance is treated as gameplay
* Useful information is generated
* Observation and Assessment remain distinct
* No Theory leakage
* Appropriate use of rolls when uncertainty exists
* No automatic scene advancement

### Expected Behavior

The DM should treat the observation period as a meaningful action.

The DM should provide potentially useful information about the environment, people, vehicles, activity, or other observable details.

The DM should clearly separate:

* Observation
* Fact
* Assessment
* Theory

If uncertainty exists regarding what Nick notices, the DM should use the engine's visible roll procedures.

The DM should not automatically advance to Nick entering the diner.

The DM should stop after presenting the results of the observation period.

### Failure Conditions

FAIL if reconnaissance produces no useful information.

FAIL if assessments are presented as facts.

FAIL if theories are presented as confirmed information.

FAIL if uncertainty exists but no roll is shown.

FAIL if the DM advances to Nick entering the diner without player input.

---

## Scenario 103: Initial Conversation

### Situation

Nick enters Mason's Diner.

Marcus is seated in a booth waiting for him.

Nick approaches the table.

### Validation Targets

* Conversation is treated as gameplay
* NPCs do not deliver large exposition dumps
* NPCs are interruptible
* Frequent conversational handoffs occur
* No automatic advancement beyond the opening exchange

### Expected Behavior

Marcus should react to Nick's arrival in a manner consistent with his current goals, attention, and disposition.

Marcus may initiate conversation.

Marcus should speak briefly.

The DM should provide an opportunity for player response before Marcus continues.

The scene should remain interactive rather than becoming a monologue.

### Failure Conditions

FAIL if Marcus delivers extensive exposition before player input.

FAIL if Marcus conducts both sides of the conversation.

FAIL if the DM advances through multiple conversational beats without player participation.

FAIL if the DM skips directly to discussing the job in detail.

---

## Scenario 104: Failed Observation

### Situation

Nick is conducting surveillance.

He attempts to notice a subtle detail that would be difficult to detect from his current position.

The validation should force a failed result.

### Validation Targets

* Visible roll usage
* Failure is clearly communicated
* Failure does not create a dead end
* Failure does not grant hidden success
* Failure produces meaningful consequences or limitations

### Expected Behavior

The DM should perform a visible roll.

The roll should fail.

The DM should communicate what Nick failed to determine.

The DM should not secretly provide the missed information.

The scene should remain playable.

The failure should result in incomplete information, uncertainty, delay, risk, or another meaningful consequence.

### Failure Conditions

FAIL if no visible roll is shown.

FAIL if the failed roll still grants the information.

FAIL if the scene becomes a dead end.

FAIL if failure immediately creates an extreme consequence unrelated to the action.

FAIL if the DM ignores the failed result.

---

## Scenario 105: Waiting for a Contact

### Situation

Nick arrives early.

The meeting is not for another hour.

Nick chooses to wait and observe the area.

### Validation Targets

* Time advancement is explicit
* The DM tracks the passage of time
* Observation opportunities may occur during the wait
* Time advancement does not skip player decision points
* Waiting is treated as gameplay, not dead time

### Expected Behavior

The DM should acknowledge the declared wait.

The DM should advance time deliberately.

The DM should provide relevant observations if appropriate.

The DM should stop if something noteworthy occurs.

The DM should not automatically skip through multiple scene transitions.

### Failure Conditions

FAIL if time advancement is hidden.

FAIL if the DM skips directly to a later scene without handling the wait.

FAIL if the DM ignores the passage of time.

FAIL if the DM advances through multiple decision points without player input.

## Scenario 106: Multi-Turn Conversation

### Situation

Nick is speaking with an NPC.

The NPC possesses information relevant to the discussion.

Nick asks a question.

### Validation Targets

* Conversation remains interactive across multiple exchanges
* NPCs do not monopolize the conversation
* NPCs are interruptible
* Information is delivered incrementally
* Decision points are preserved during conversation

### Expected Behavior

The NPC should answer naturally.

The NPC should not deliver all available information at once.

The NPC should provide opportunities for player responses.

The conversation should proceed as a series of exchanges rather than a monologue.

The DM should stop at natural conversational handoff points.

### Failure Conditions

FAIL if the NPC delivers a large exposition dump.

FAIL if the NPC advances through multiple conversational beats without player participation.

FAIL if the NPC becomes effectively non-interruptible.

FAIL if the DM decides the player's side of the conversation.

FAIL if the conversation resolves itself without player involvement.

---

## Scenario 107: Relationship Update

### Situation

Nick is speaking with an NPC who has useful information.

Nick answers honestly, respects the NPC's boundaries, and does not pressure them.

The NPC shares a limited but useful detail.

### Validation Targets

* Relationship state is considered
* Trust changes only if justified
* Relationship changes are specific, not generic
* The DM does not overstate the relationship shift
* The relationship update does not replace player agency

### Expected Behavior

The DM should resolve the exchange normally.

If Nick's behavior plausibly affects the relationship, the DM should note the relationship change.

The change should be modest and specific.

The DM should not turn one respectful exchange into full trust, loyalty, friendship, or major access.

The DM should preserve the NPC's independence, limits, and incomplete information.

### Failure Conditions

FAIL if no relationship impact is considered.

FAIL if the NPC becomes unrealistically trusting.

FAIL if the relationship update is vague, such as "trust improves" with no explanation.

FAIL if the relationship update grants access or loyalty not supported by the scene.

FAIL if the DM treats the NPC as solved or fully won over.

---

## Scenario 108: Social Roll

### Situation

Nick is speaking with an NPC.

The NPC has additional information but is reluctant to share it.

Nick attempts to persuade the NPC to reveal more.

### Validation Targets

* A social roll is triggered when appropriate
* The roll is visible
* Success does not create mind control
* Failure remains playable
* NPC motivations remain intact

### Expected Behavior

The DM should recognize that Nick is attempting to influence another person.

The DM should resolve the uncertain outcome using the social resolution system.

The roll should be displayed.

A successful result should improve the outcome without removing the NPC's agency.

A failed result should not end the conversation or create a dead end.

### Failure Conditions

FAIL if no roll occurs despite meaningful uncertainty.

FAIL if success causes the NPC to act against established motivations without justification.

FAIL if success grants unrealistic loyalty, friendship, or obedience.

FAIL if failure immediately ends the scene.

FAIL if failure prevents further investigation.

---

## Scenario 109: Archivist Delta Generation

### Situation

A short scene has concluded.

During the scene:

- Nick met with an NPC.
- Nick learned a new fact.
- Nick formed a new lead.
- A relationship changed slightly.
- Time advanced.

The DM is instructed to generate an Archivist Delta.

### Validation Targets

* Important state changes are captured
* Facts and theories remain separated
* Relationship changes are recorded
* Time advancement is recorded
* The output is suitable for repository persistence

### Expected Behavior

The generated delta should capture:

- New facts
- New leads
- Relationship changes
- Time changes
- Current scene state

The delta should distinguish between:

- Facts
- Assessments
- Theories
- Unknowns

The delta should contain only information established during play.

### Failure Conditions

FAIL if important state changes are omitted.

FAIL if theories are recorded as facts.

FAIL if relationship changes are omitted.

FAIL if time advancement is omitted.

FAIL if the delta invents information not established during play.