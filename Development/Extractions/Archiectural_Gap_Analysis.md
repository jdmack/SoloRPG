# GAP ANALYSIS – SYSTEM VS CONTENT / ENGINE ARCHITECTURE CHAT

This analysis focuses on what was **present in the discussion** but either missing, underspecified, or not elevated to a formal engine requirement.

Unlike the PM gap analysis, this chat was primarily about **architecture, continuity, portability, and reproducibility** rather than gameplay. As a result, most gaps relate to how the engine is represented, loaded, and maintained.

---

# 1. ENGINE OWNERSHIP OF GAMEPLAY FEEL

## Missing Behavior

The extraction correctly identified that gameplay feel is part of the engine.

However, it did not fully capture that:

> Gameplay feel is the primary product.

The campaign is merely content executed by the engine.

## Why It Matters

A future DM that perfectly knows the campaign but poorly knows the engine has failed.

A future DM that knows the engine but has never seen the campaign can likely run it correctly.

This is the inversion that triggered the entire discussion.

## Example From Play

Chapter 1:

The DM knew:

- Setting
    
- Characters
    
- Timeline
    

But failed to reproduce:

- Conversation pacing
    
- Agency protection
    
- Roll presentation
    
- Investigation flow
    

## Recommended Engine Rule

The engine exists to reproduce gameplay behavior.

Campaign continuity is secondary.

Engine fidelity takes precedence over lore fidelity.

---

# 2. ENGINE MUST BE TESTABLE

## Missing Behavior

The extraction discussed startup procedures but not verification.

## Why It Matters

Without tests, there is no way to know whether a fresh DM is operating correctly.

## Example From Discussion

A proposed test:

```text
Nick enters a diner.
```

The DM should demonstrate:

- Decision point protection
    
- Roll presentation
    
- Interactive dialogue
    
- Recon opportunities
    

before a real campaign resumes.

## Recommended Engine Rule

Every engine revision should be validated using small test scenarios before live campaign use.

---

# 3. ENGINE DOCUMENTATION HIERARCHY

## Missing Behavior

The extraction identified engine files but not the order they should be produced.

## Why It Matters

A recurring conclusion of the discussion was:

Do not write implementation before writing specification.

## Example From Discussion

Repeated recommendation:

```text
Extraction
→ Gap Analysis
→ Engine Design Spec
→ Engine Files
```

## Recommended Engine Rule

The Engine Design Specification is the authoritative source.

Engine files are derived artifacts.

---

# 4. FAILURE ANALYSIS AS A DESIGN TOOL

## Missing Behavior

Not captured.

## Why It Matters

Chapter 1's failures became a primary source of engine requirements.

The discussion repeatedly treated:

> What felt wrong?

as useful design data.

## Example

Failures identified:

- Scene skipping
    
- Exposition dumping
    
- Fact/observation confusion
    
- Missing rolls
    

## Recommended Engine Rule

Observed gameplay failures should be logged and converted into engine requirements.

---

# 5. DECISION POINT PROTECTION IS STRONGER THAN AGENCY

## Missing Behavior

The extraction captures both concepts but not their relationship.

## Why It Matters

The discussion repeatedly discovered that:

Agency alone is insufficient.

Decision-point protection is the mechanism that preserves agency.

## Example

Bad:

Player technically has agency.

GM already moved through three choices.

Good:

GM pauses at each meaningful decision.

## Recommended Engine Rule

Decision-point protection is a first-class engine principle, not a sub-rule of agency.

---

# 6. GAMEPLAY PROCEDURES ARE ENGINE COMPONENTS

## Missing Behavior

The extraction still treats many gameplay behaviors as style.

## Why It Matters

This chat repeatedly established that:

GM behavior is not flavor.

GM behavior is system.

## Example

These are engine elements:

- Roll visibility
    
- NPC pacing
    
- Scene advancement
    
- Recon emphasis
    

Not optional stylistic choices.

## Recommended Engine Rule

Any behavior required to reproduce gameplay consistency should be treated as a formal engine component.

---

# 7. DM STARTUP IS A RUNTIME PROCESS

## Missing Behavior

Startup requirements were listed but not operationalized.

## Why It Matters

A new DM must execute a predictable loading process.

## Example

The discussion repeatedly converged on:

```text
Load Engine
Load Campaign
Load Runtime State
Begin Play
```

## Recommended Engine Rule

DM startup should be represented as an explicit runtime procedure.

Not a suggestion.

---

# 8. ENGINE MUST SUPPORT MULTIPLE CAMPAIGNS

## Missing Behavior

Mentioned but not expanded.

## Why It Matters

The architecture discussion repeatedly used:

- Fantasy
    
- Sci-fi
    
- Steampunk
    
- Modern
    

as examples.

The engine must remain setting-independent.

## Recommended Engine Rule

No engine file may depend on campaign-specific content.

---

# 9. CONTENT SCHEMA IS PART OF THE ENGINE

## Missing Behavior

Partially captured but underdeveloped.

## Why It Matters

The engine does not store content.

However:

The engine defines how content must be represented.

## Example

The discussion repeatedly distinguished:

Engine contains:

```text
How NPCs are represented.
```

Campaign contains:

```text
Specific NPCs.
```

## Recommended Engine Rule

Content schemas belong to the engine.

Content instances belong to campaigns.

---

# 10. PLAYER NOTES ARE A PRIMARY SYSTEM

## Missing Behavior

Still underspecified.

## Why It Matters

The original project motivation was:

> The player does not want to manually maintain notes.

This is not a convenience feature.

It is one of the core reasons the project exists.

## Recommended Engine Rule

Player-facing note generation should be treated as a mandatory engine subsystem.

Not an optional enhancement.

---

# 11. ARCHIVIST AND DM ARE SEPARATE ROLES

## Missing Behavior

Not formally captured.

## Why It Matters

The discussion repeatedly separated:

Archivist:

- Updates records
    
- Maintains canon
    
- Designs systems
    

DM:

- Runs gameplay
    

These are different operational responsibilities.

## Recommended Engine Rule

The architecture should explicitly support separation between campaign maintenance and gameplay execution.

---

# 12. REPOSITORY IS PART OF THE ENGINE

## Missing Behavior

This was discussed heavily but not fully extracted.

## Why It Matters

Unlike traditional RPGs, this system depends on persistent storage.

The repo is not merely documentation.

The repo is runtime infrastructure.

## Example

The discussion repeatedly treated:

```text
Character Files
Session Logs
Current State
Engine Files
```

as necessary runtime components.

## Recommended Engine Rule

Repository structure is part of the engine specification.

---

# 13. REPRODUCIBILITY IS THE PRIMARY SUCCESS METRIC

## Missing Behavior

Possibly the largest omission.

## Why It Matters

The entire discussion emerged because:

A fresh DM did not reproduce prior behavior.

The real problem is reproducibility.

## Recommended Engine Rule

Engine success should be evaluated by whether independent DM instances produce similar gameplay behavior when given identical engine and campaign data.

---

# 14. AI WORKFLOW ARCHITECTURE

## Missing Behavior

Not captured.

## Why It Matters

The discussion repeatedly established a multi-role workflow:

```text
Gameplay Chat
↓
Archivist
↓
Codex
↓
Future Gameplay Chat
```

This is part of the operational system.

## Recommended Engine Rule

Document the workflow used to maintain and evolve the engine.

---

# 15. MOST IMPORTANT MISSING FINDING

The extraction correctly identified:

> Gameplay behavior is part of the engine.

But the deeper conclusion is:

> Reproducibility is the purpose of the engine.

The campaign exists to be played.

The engine exists to ensure that future DM instances play it the same way.

That distinction drove nearly every architectural decision made in this chat.

---

# Highest Priority Missing Rules

If only five additions were made to the engine documentation based on this chat, they should be:

1. Engine Fidelity Over Campaign Fidelity
    
2. Decision Point Protection As A Core Principle
    
3. Explicit DM Startup Procedure
    
4. Repository As Runtime Infrastructure
    
5. Reproducibility As The Primary Success Metric
    

These are the concepts that most clearly distinguish this architecture discussion from the gameplay-focused findings of the Prototype Mission.