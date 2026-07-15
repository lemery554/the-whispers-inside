# Foundation Continuity Audit — TWI-023

Pre-M1-close continuity sweep across the eight required categories: **time, geography, character knowledge, injuries, objects, symptoms, direct statements, and rejected concepts** (STORY_RULES Rule 16). Audited against the bible, the timeline set, the clue ledger, the knowledge matrix, the chapter outline, and the scene inventory.

**Result: 1 P0 finding — now RESOLVED this session — 0 P1, 3 notes.** With the P0 finding reconciled and the last detail-lock (OQ-09) now closed, the Foundation has no known continuity defects blocking the TWI-109 drafting gate.

---

## Findings

### F1 — P0 — Anna's first house-entry day contradicts itself across files — **RESOLVED**
**Category:** time, character knowledge, objects.

After TWI-009 locked Anna's **two** school-day visits (investigate first, take the journal second), the two visits were placed on **Day 18** (investigation) and **Day 19** (journal). Several files were never updated from the earlier single-visit-on-Day-19 model, so canon now says both things:

| Says first entry = **Day 18** (two-visit model, current) | Says first/only entry = **Day 19** (pre-TWI-009, stale) |
|---|---|
| `outline/CHAPTER_OUTLINE.md` Ch 19 (Day 18) + Ch 20 (Day 19) | `planning/BACKLOG.md` TWI-008 note ("first confirmed entry is Day 19") |
| `outline/TIMELINE.md` rows Day 18 / Day 19 | `outline/TIMELINE.md` continuity constraint line ("first confirmed house entry is Day 19") |
| `outline/ANNA_KNOWLEDGE_MATRIX.md` lines 13, 18, verification line 32 | `outline/CLUE_LEDGER.md` AN-02 & AN-03 (both "Day 19") |
| `outline/SCENE_INVENTORY.md` S20 (Day 18) / S21 (Day 19) | `bible/world/BENNETT_HOUSE.md` line 66 ("enters … on Day 19"; second visit still "blocked by #7") |
| | `outline/ANNA_KNOWLEDGE_MATRIX.md` line 9 ("Uses it on Day 19") — internally contradicts lines 13/32 |

**Recommended resolution (reconcile to locked canon, not a new decision):** adopt the two-visit model everywhere — **first/investigation visit Day 18, journal visit Day 19** — since it is what TWI-009, the chapter outline, the timeline rows, and the scene inventory already encode. Then update the five stale references above (BACKLOG TWI-008 note, TIMELINE continuity constraint, CLUE_LEDGER AN-02/AN-03, BENNETT_HOUSE line 66 incl. removing the "#7 blocked" second-visit language, and matrix line 9).

**Resolution (applied this session, author-approved):** adopted the two-visit model — investigation **Day 18**, journal **Day 19** — and updated all five stale references (`planning/BACKLOG.md` TWI-008, `outline/TIMELINE.md` constraint, `outline/CLUE_LEDGER.md` AN-02, `bible/world/BENNETT_HOUSE.md` incl. removing the "#7 blocked" second-visit language, and `ANNA_KNOWLEDGE_MATRIX.md` line 9). **OQ-11 closed.**

---

## Category-by-category results

### Time — PASS (except F1)
- Institutional phases (`INSTITUTIONAL_TIMELINE.md`) align with the day-by-day `TIMELINE.md` public column at every boundary: P1 ends Day 5, P2 Day 6–10, P3 Day 11–16, P4 Day 17–22, P5 Day 23–27, P6 Day 28–30. The **Day 9↔12 swap** (this session) correctly kept the public-phase column anchored to its calendar day. ✔
- Purge duration (12–36 h, `RULES.md`) is consistent: Claire onset Day 4 → hospital Day 5 → apparent recovery Day 6; Sarah onset Day 14 → severe Day 15 → recovered Day 16. ✔
- **Ending rework (this session):** the narrative now concludes on the night of Day 26 (siege → escape → engineered car pickup → journal reveal, all one night); Days 27–30 of institutional drift continue off-page. Anna's two in-person meetings are placed Day 11 (dog park) and Day 23 (diner), both consistent with her knowledge timeline (Day-11 meeting uses video knowledge only; Day-23 meeting follows the house entries and resemblance). The changed-police arrival is cut. ✔

### Geography — PASS
- Ashcroft, CT (TWI-005) used consistently; the chase (S26/S27) and final drive (S32) follow the town map's back-roads/state-route logic. House interior routes (`BENNETT_HOUSE.md`) are internally consistent: gun safe in the attached garage, porch-roof escape below Brooke's rear window, hall bathroom upstairs.

### Character knowledge — PASS (feeds F1)
- Every private fact Anna uses has a documented public-video or house-material source (`ANNA_KNOWLEDGE_MATRIX.md`); Brooke, not Anna, introduces the biological-mother claim. The only knowledge-timing defect is F1 (which day the house-derived knowledge is acquired).
- Brooke never knows anything unsourced; she is never given information the POV rules withhold.

### Injuries — PASS
- Claire injures her hand breaking the bathroom lock and does not react in the moment (pain felt, self-preservation absent, `RULES.md`) — now on **Day 10** after the swap; the injury has no downstream reference that pins it to the old Day 9. ✔
- Sarah's gunshot through the latch-side door panel keeps Brooke crouched out of the direct line (`BENNETT_HOUSE.md` siege route). No character sustains an injury that later disappears.

### Objects — PASS (except F1)
- Journal (taken on the second visit), keypad, garage gun safe, camera/phone, escape bag (placed Day 22 / Ch 23), Cooper's leash, beach photo — all introduced before use. The escape window is established in ordinary family life before the siege. ✔
- The AN-02 displaced object is now locked (**OQ-09 resolved**): the adoption-papers container left slightly ajar in the keepsake box at the foot of Brooke's bed.

### Symptoms — PASS
- Eating changes, muted hunger, dulled self-preservation, reflective green eye, whisper repetition, and animal detection are used consistently and never explained (Rule 2). The green-eye discovery moved cleanly from Day 10 to **Day 9** in the swap; no other file pins it to Day 10 (`BENNETT_HOUSE.md`'s green-eye note is day-agnostic). ✔

### Direct statements — PASS
- Spot audit of changed-character lines against Rule 11: Sarah's "You came home" and her safety reassurances are true-and-reframed; Anna's "Every second," "I knew you were waiting," "You don't owe me anything," "Somewhere quiet" all pass the literal-truth test (see TWI-107). No changed character states a knowing falsehood. ✔

### Rejected concepts — PASS
- Cross-checked all Foundation + new Story-Design docs against `notes/REJECTED_IDEAS.md`: no immunity/bloodline/chosen framing, no Anna-searches-for-real-mother, no cure/full recovery, no monster name, no romance, no immediate apocalypse, no green-eye-only ending. The new `CHARACTER_ARCS`, `ESCALATION_LADDERS`, `ANNA_TRUST_LADDER`, and `SCENE_INVENTORY` all stay inside canon. ✔

---

## Result

**TWI-023: audit complete; F1 resolved this session.** Foundation is now continuity-clean: the Day 18 / Day 19 two-visit model has been applied across all previously conflicting files, and the AN-02 object is locked (OQ-09). No continuity items remain open; M1 has no known continuity defects blocking the TWI-109 drafting gate.
