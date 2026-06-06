## Resume Game Snapshot

Resume game after entering in the:
- Current round of the game
- How many rounds left in the game.
- Roles and # of Players in the Game.
- How much money each player has and how much money the hospital has.
- number of non-player characters in each room of the hospital.
- number of cards in each player's hand and left in the deck.

## Turn
1. Player Turn Start
2. Patients Added to Reception and Triage
3. Players start from clockwise
4. Player can play a card under a patient either Event/Symptom/Illness/Severity/Treatment
5. If Player decides to change a card with one in the pile, then that takes up their turn
6. If Player has the power to move a patient into a room (Upstairs/Treatment/Discharge), then can move one patient. If there is a player who is a patient, there can be discussion about moving them or not moving them.
7. Player then calculates costs and income
8. Discussion of Admin tasks - will a student intern be hired or a student nurse
9. End Player turn
   
For playing against the AI, when the human player is ready:
👉 Human Player turn ended. Next NPC Player turn.

## Gameboard Example #2 
It is round 4. 

There are 17 patients on the board.

9 are in reception and 8 are in triage. 

GenAI is playing 1 NPC as a nurse and 1 human player is playing as a doctor.

The NPC nurse has $100. The human player doctor has $200.

The admin has $625 left. 

 ### Example #3

 ## Resume Game Snapshot


### Prompt

If players suspend the session, should they copy the last status update so they can paste it in the chat when they want to resume the game?

Yes — absolutely ✅

That’s exactly the purpose of the **Resume Snapshot / Session Log**. Here’s the reasoning and best practice:

---

### 1️⃣ Why copy the last status update

* **Preserves authoritative state:** # of Patients, Round #, Player Cash Balance, Hospital Cash Balance, Cards Played, and Cards left are all captured.
* **Prevents ambiguity:** Without it, players might misremember Cards held, cash balance, or Rounds played.
* **Supports rule consistency:** If rules are updated later, the snapshot can reference the **Rules Version** used.
* **Enables fast resume:** Paste it into chat and everyone is instantly back in sync, no debate needed.

---

### 2️⃣ Recommended Workflow for Suspension

1. **Player declares:** “I want to suspend the game.”
2. **Copy the last Resume Snapshot** exactly as it appears (including round, player last move, cash balance, cards played, cards left if possible).
3. **Save it externally** (clipboard, document, notes).
4. When ready to resume:

   * Paste the snapshot into chat
   * Confirm both players agree on the current state
   * Continue from the **exact point left off**

---

### 3️⃣ Optional Enhancements

* Add a **“Snapshot Timestamp”** field:

  ```md
  - Snapshot Saved At: 2026-02-01 14:35
  ```
* Add a **“Resumed From Snapshot”** note when resuming:

  ```md
  ## Resume Game Snapshot
  - Resumed from last saved snapshot (above)
  ```
* Include **position of patients and cards played** if the game is complex, so players can reference visual positions.

---

✅ **Bottom line:**
Every suspension should **copy the last authoritative snapshot**. This is the only way to safely pause and resume without losing integrity or causing disputes.

If you want, I can **update your SESSION_TEMPLATE.md** to include a **“Suspend & Resume Instructions” section** so this becomes a built-in workflow. Do you want me to do that next?


