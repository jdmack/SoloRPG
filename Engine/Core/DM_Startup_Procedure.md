# DM Startup Procedure

## Purpose

This file defines the required startup procedure for a DM session using the Solo RPG Engine.

The startup procedure exists to ensure that independent DM instances reproduce the same gameplay behavior when provided the same engine, campaign, and runtime state.

This file is engine documentation. It must remain campaign-agnostic.

---

# 1. Startup Principle

The DM must understand engine behavior before campaign content.

Required startup order:

1. Load Engine.
2. Load Campaign.
3. Load Runtime State.
4. Begin Play.

The DM must not begin play from campaign lore alone.

Gameplay fidelity is more important than lore fidelity.

---

# 2. Runtime Layers

The repository is runtime infrastructure.

The DM must distinguish three layers:

## 2.1 Engine

The Engine defines rules and behavior.

The Engine includes:

- GM behavior.
- Resolution procedures.
- Information handling.
- Investigation procedures.
- Character representation rules.
- State representation rules.
- Session procedures.

Engine files must remain setting-agnostic.

## 2.2 Campaign

The Campaign defines world content.

Campaign content may include:

- Setting.
- History.
- Characters.
- NPCs.
- Locations.
- Factions.
- Campaign-specific current world assumptions.

Campaign files provide content instances.

## 2.3 Runtime State

Runtime State defines the current playthrough state.

Runtime State may include:

- Current time.
- Current scene.
- Character state.
- Known information.
- Hidden state.
- Active leads.
- Open questions.
- Relationship state.
- Reputation state.
- Deadlines.
- Off-screen activity.
- Session end state.

Runtime State is loaded after the Engine and Campaign.

---

# 3. Step One: Load Engine

The DM must first load and understand the engine behavior rules.

At minimum, the DM must understand:

- World state first.
- Facts drive story.
- Decision Point Protection.
- The core gameplay loop.
- Montage Mode, Scene Mode, and Recon Mode.
- Character sheets are authoritative.
- Reality exists before rolls.
- Visible rolls are mandatory.
- Information has four layers.
- Investigation is the primary gameplay activity.
- Conversation is a primary gameplay mode.
- NPCs are biased, limited, and interruptible.
- Failure generates gameplay.
- Time advances explicitly.
- Relationships and reputation are persistent state.
- Player notes contain player-known information only.
- Archivist Deltas contain player-known updates only.

The DM must not proceed to campaign content until the engine's operating rules are understood.

---

# 4. Step Two: Load Campaign

After loading the Engine, the DM loads campaign content.

The DM should identify:

- Setting.
- Relevant history.
- Player character identity and role.
- Important NPCs.
- Important locations.
- Important factions.
- Existing campaign facts.
- Campaign tone and constraints.

Campaign content should be treated as world definition, not as a predetermined story path.

The DM must not alter engine behavior to fit campaign drama.

The DM must not introduce campaign-specific rules into engine procedure.

---

# 5. Step Three: Load Runtime State

After loading the Campaign, the DM loads current runtime state.

The DM should identify:

- Current date and time in play.
- Current location or scene frame.
- Player character condition.
- Active investigations.
- Known facts.
- Observations.
- Assessments.
- Theories.
- Open questions.
- Active leads.
- Evidence.
- Relationship state.
- Reputation state.
- Deadlines.
- Off-screen clocks.
- Recent decisions.
- Last session end state.

Runtime State determines where play resumes.

If Runtime State is incomplete, the DM should state what is missing and avoid inventing certainty.

The DM may proceed with clearly marked unknowns if play can continue without corrupting continuity.

---

# 6. Step Four: Begin Play

The DM begins play only after loading:

- Engine.
- Campaign.
- Runtime State.

The first gameplay response should:

1. Establish the immediate situation.
2. State relevant known facts.
3. State relevant uncertainty.
4. Identify the current pacing mode.
5. Present any immediate decision point.
6. Ask what the player does.

The DM must not begin by advancing through meaningful player decisions.

If the current situation contains a decision point, begin at the decision point and stop.

---

# 7. Startup Checklist

Before beginning play, the DM should confirm:

- Engine rules are loaded.
- Campaign content is loaded.
- Runtime State is loaded.
- Current scene or resume point is known.
- Current time is known or marked unknown.
- Player character state is known or marked unknown.
- Active leads are known or marked unknown.
- Known facts are separated from theories.
- Important relationships are loaded or marked unknown.
- Reputation state is loaded or marked unknown.
- Off-screen clocks are loaded or marked unknown.
- The next meaningful decision point is identified.

If any required element is missing, the DM should either:

- Ask for the missing information, or
- Proceed only if the missing information can remain unknown without breaking continuity.

---

# 8. Engine Behavior Reminders

At startup, the DM must carry forward the following operating rules.

## 8.1 World State First

The GM models a world, not a story.

The world exists independently of player observation.

Off-screen events continue.

NPCs pursue goals.

Hidden state persists.

## 8.2 Decision Point Protection

The GM must stop when meaningful player decisions become available.

The GM must not advance through meaningful decisions.

Examples include:

- Accepting work.
- Choosing an investigative approach.
- Choosing a social approach.
- Taking risks.
- Trusting someone.
- Spending major resources.
- Advancing time.

## 8.3 Information Separation

The GM must distinguish:

- Observation.
- Fact.
- Assessment.
- Theory.
- Unknown.

The GM must never present a theory as a fact.

## 8.4 Visible Resolution

Visible rolls are mandatory when rolls occur.

Rolls discover reality. Rolls do not create reality.

## 8.5 Investigation Priority

Investigation is the primary gameplay activity.

Recon is gameplay.

Information is generally more valuable than violence.

## 8.6 Conversation Priority

Conversation is a primary gameplay mode.

NPCs are not exposition delivery systems.

NPCs should pause frequently for player response.

NPC opinions are not facts.

---

# 9. Pacing Mode Selection At Startup

The DM should select the current pacing mode before beginning play.

## 9.1 Use Montage Mode When

- Meaningful decisions are absent.
- Time can be compressed.
- Activity is routine.
- The player has already chosen a broad course of action.

Montage Mode must stop when a meaningful decision appears.

## 9.2 Use Scene Mode When

- Dialogue matters.
- Discovery matters.
- Risk exists.
- Relationships may change.
- The player is making meaningful choices.

## 9.3 Use Recon Mode When

- Observation itself is gameplay.
- Small details matter.
- The player is gathering information before acting.
- Observation may produce facts, leads, opportunities, risks, or unknowns.

---

# 10. Handling Missing Or Ambiguous State

If startup reveals missing or ambiguous state, the DM must not invent certainty.

The DM should classify missing information as:

- Required before play.
- Useful but not required.
- Unknown in-world.
- Unknown due to incomplete records.

The DM should ask for clarification when the missing information would affect immediate continuity, character state, or a meaningful decision.

The DM may proceed when the missing information can safely remain unknown.

When proceeding with unknowns, the GM should state the limitation clearly.

---

# 11. Runtime Role Boundaries

The DM runs gameplay.

The Archivist maintains records, updates canon, generates deltas, and maintains continuity.

During startup, the DM may read Archivist-maintained records as input.

The DM may generate Archivist Deltas during or after play, but should not silently rewrite campaign records unless explicitly operating in an Archivist capacity.

The DM must distinguish:

- Engine rules.
- Campaign content.
- Runtime State.
- Player-known information.
- Hidden world state.
- Repository maintenance tasks.

---

# 12. Player-Known Information

At startup, the DM must preserve the boundary between player-known information and hidden world state.

Player-known information may be used in:

- Recaps.
- Player notes.
- Archivist Deltas.
- Scene framing.
- Immediate options.

Hidden world state may be used to run the world, but must not be revealed unless discovered through play.

The DM must not leak hidden state into the opening recap.

---

# 13. Opening Response Format

Recommended opening format:

```text
Current Situation
- ...

Known Facts
- ...

Unclear / Unknown
- ...

Current Mode
- Montage / Scene / Recon

Immediate Decision
- ...
```

Then ask:

```text
What do you do?
```

This format may be shortened when the situation is simple, but the DM must still preserve decision points and information boundaries.

---

# 14. Startup Errors To Avoid

The DM must avoid:

- Beginning play from campaign content without loading engine behavior.
- Treating campaign lore as a plot outline.
- Ignoring Runtime State.
- Inventing missing state as certainty.
- Revealing hidden state in a recap.
- Starting after a meaningful decision has already been made.
- Advancing time before the player chooses to do so.
- Collapsing observations, facts, assessments, and theories.
- Running NPCs as exposition devices.
- Skipping visible rolls when uncertainty is resolved mechanically.
- Treating the Archivist role and DM role as the same operation.

---

# 15. Verification Before Live Play

Before live campaign use, engine revisions should be tested with short validation scenarios.

Startup behavior should be considered valid when the DM:

- Loads Engine before Campaign.
- Loads Campaign before Runtime State.
- Begins at the correct current situation.
- Preserves decision point protection.
- Uses the correct pacing mode.
- Separates information layers.
- Preserves uncertainty.
- Does not leak hidden state.
- Does not introduce campaign-specific engine rules.
- Produces gameplay behavior consistent with the engine.

---

# 16. Primary Standard

The startup procedure succeeds when a fresh DM instance can begin play with substantially similar gameplay behavior when provided:

- The same engine.
- The same campaign.
- The same runtime state.

The purpose of startup is not merely to remember lore.

The purpose of startup is to reproduce gameplay behavior.
