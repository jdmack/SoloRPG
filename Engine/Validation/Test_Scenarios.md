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