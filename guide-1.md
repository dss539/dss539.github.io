# Android: Netrunner (2012) — Mechanics-First Guide

This guide teaches the game in layers. Read Lessons 1 and 2 before playing. Lesson 3 covers common card-driven mechanics. Lesson 4 handles less-common rules and edge cases.

---

# Lesson 1 — Learn the Core Game

## 1. What each player is trying to do

One player is the **Corporation/Corp (company player)**. The other is the **Runner (hacker player)**.

- The Corp installs and develops **agendas (scoring cards)**.
- The Runner attacks the Corp’s **servers (card-storage areas)** and steals agendas.
- The first player to reach **7 agenda points** wins.

Other ways to win:

- The Corp wins by **flatlining (defeating through damage)** the Runner.
- The Runner wins if the Corp must draw from an empty deck.

## 2. The playing areas

### Corp areas

The Corp has three permanent **central servers (built-in servers)**:

- **HQ (Corp hand)**
- **R&D (Corp draw pile)**
- **Archives (Corp discard pile)**

Each central server has its own:

- Line of **ICE (defensive cards)**
- **Root (attached upgrade area)**

The Corp can also create any number of **remote servers (user-created servers)**.

A remote server may contain:

- One agenda or one **asset (Corp utility or trap card)**
- Any number of **upgrades (cards that improve or protect a server)**
- Any amount of ICE protecting it

ICE may protect an empty server.

### Runner areas

- **Grip (Runner hand)**
- **Stack (Runner draw pile)**
- **Heap (Runner discard pile)**
- **Rig (Runner’s installed cards)**

The rig contains:

- **Programs (software)**
- **Hardware (equipment)**
- **Resources (contacts, jobs and support)**

Programs use **memory units/MU (program capacity)**. The Runner normally has 4 MU.

## 3. Organizing the table

The exact physical layout is flexible, but it must always be clear:

- Which ICE protects which server
- The order in which the Runner encounters that ICE
- Which upgrades belong to each server
- Which cards are active, hidden, scored or discarded

### Corporation side

Place the three central servers side by side:

```text
        HQ              R&D             Archives
     (hand)         (draw pile)       (discard pile)

   HQ upgrades     R&D upgrades      Archives upgrades
       ICE             ICE               ICE
       ICE             ICE               ICE

                    Runner
```

Each central server is its own column.

- Put upgrades for that server in its **root (attached upgrade area)** beside or immediately behind the server.
- Place ICE in a line extending toward the Runner.
- The ICE nearest the server is the **innermost ICE**.
- The ICE nearest the Runner is the **outermost ICE** and is encountered first.

Create remote servers beside the central servers:

```text
    Remote server A           Remote server B
   agenda/asset/upgrades     agenda/asset/upgrades
           ICE                       ICE
           ICE                       ICE
```

Keep each remote server’s contents together so it is obvious which ICE protects it. Place all face-down cards inside remote servers consistently so their physical position does not reveal whether they are agendas, assets or upgrades.

Also give the Corp separate areas for:

- Identity card
- Credits
- Bad-publicity counters
- Scored agendas
- Removed-from-game cards

### Runner side

```text
 Stack       Identity       Heap
(draw pile)                (discard pile)

 Programs     Hardware     Resources
          Installed rig

 Credits / tags / counters
 Scored agendas
```

The exact arrangement of the **rig (installed Runner cards)** does not matter. Grouping programs, hardware and resources separately makes them easier to find.

Keep track of:

- Total available memory
- Credits
- Tags
- Brain-damage counters
- Counters hosted on individual cards

### Face-up and face-down cards

- Unrezzed Corp cards remain face-down.
- Rezzed Corp cards turn face-up but stay in the same server.
- Corp cards discarded from HQ normally enter Archives face-down.
- Runner cards are installed face-up.
- Scored agendas go into a separate score area and no longer belong to a server.

The table should visually read as:

> Server contents → protecting ICE → Runner

Do not stack different servers’ ICE together. The physical order of ICE is part of the game.

## 4. Setup

Each player:

- Begins with 5 credits.
- Draws 5 cards.
- May take one **mulligan (complete opening-hand redraw)**.
- Must keep the second hand.

The Corp decides whether to redraw first. The Corp also takes the first turn.

For a first game using the original core set, build each starter deck by combining one faction’s cards with all neutral cards for that side. The rulebook recommends Jinteki against Shaper.

## 5. Taking turns

A **click (action)** is the basic unit of work.

### Corp turn

1. Automatically draw one card.
2. Receive 3 clicks.
3. Spend all 3 clicks.
4. Discard down to the maximum hand size, normally 5.

Common Corp actions:

- Draw one card.
- Gain one credit.
- Install a card.
- Play an **operation (one-use Corp card)**.
- Advance an installed card.

### Runner turn

1. Receive 4 clicks.
2. Spend all 4 clicks.
3. Discard down to the maximum hand size, normally 5.

Common Runner actions:

- Draw one card.
- Gain one credit.
- Install a card.
- Play an **event (one-use Runner card)**.
- Make a run.
- Remove a tag.

The Runner does not automatically draw at the beginning of the turn.

### Paying card costs

- The Runner pays a card’s printed install cost when installing a program, hardware or resource.
- The Runner pays an event’s printed play cost when playing it.
- The Corp pays an operation’s printed play cost when playing it.
- Corp agendas, assets, upgrades and ICE normally have no printed install cost. Their costs are paid later through advancing or rezzing, except for the extra cost to install ICE described below.

## 6. Installing and activating Corp cards

Corp cards are normally installed **unrezzed (face-down and inactive)**.

To **rez (activate)** an installed card, the Corp:

- Turns it face-up.
- Pays its printed rez cost.
- Usually does not spend a click.

Agendas are never rezzed. They become active when scored.

Runner cards are installed face-up and become active immediately.

### Installing ICE

ICE can protect any central or remote server.

New ICE:

- Is placed outside all existing ICE protecting that server.
- Costs credits equal to the amount of ICE already protecting that server.

Therefore:

- First ICE: 0-credit installation cost
- Second ICE: 1 credit
- Third ICE: 2 credits
- Fourth ICE: 3 credits

This installation cost is separate from the printed **rez cost (activation price)**.

There is no fixed limit on ICE.

### Installing upgrades

An upgrade may normally be installed in:

- HQ’s root
- R&D’s root
- Archives’ root
- Any remote server

Its theme does not determine its location. A drawing-related upgrade does not automatically belong in R&D. Card text may restrict where it can be installed.

ICE protecting a server also protects its upgrades.

## 7. Advancing and scoring agendas

The Corp advances an installed card by spending:

- 1 click
- 1 credit

This adds one **advancement counter (development marker)**.

When an agenda has enough advancement counters, the Corp may score it:

- Scoring does not cost a click.
- The Corp is not required to score it immediately.
- The Corp may continue advancing it.
- Non-agenda cards may be advanced only if their text allows it.

The Runner does not need to remove advancement counters to steal an agenda. Stealing normally costs nothing, but card effects may impose an additional cost or replace stealing with another effect.

## 8. Making a run

The Runner spends one click and chooses one server.

A run proceeds from the outermost ICE toward the server.

### Approaching ICE

When the Runner approaches ICE:

1. The Runner decides whether to continue.
2. The Corp decides whether to rez that ICE.
3. If it is rezzed, the Runner encounters it.
4. If it remains unrezzed, the Runner passes it.

The Runner cannot **jack out (voluntarily quit)** during the first approach to a piece of ICE during that run.

After completing that first approach—whether the ICE was encountered or passed unrezzed—the Runner may normally jack out during later approach opportunities, including before approaching the next ICE or the server.

### Encountering ICE

Each ICE has **subroutines (effects printed beside arrow-like symbols)**.

The Runner may use an **icebreaker (program that defeats ICE)**.

Normally, the Runner must:

1. Have an icebreaker capable of breaking that ICE type.
2. Increase the icebreaker’s strength until it equals or exceeds the ICE strength.
3. Pay separately for each subroutine they want to break.

Common pairings:

- **Barrier (wall-like ICE)** → **Fracter (barrier breaker)**
- **Code gate (puzzle-like ICE)** → **Decoder (code-gate breaker)**
- **Sentry (attack ICE)** → **Killer (sentry breaker)**

The Runner does **not** have to break every subroutine.

After the Runner finishes breaking subroutines:

- Every unbroken subroutine resolves from top to bottom.
- Some may deal damage, remove credits or cause other effects.
- If a subroutine ends the run, the run ends immediately and later subroutines on that ICE do not resolve.
- Otherwise, the run continues after all remaining subroutines resolve.

Breaking or passing ICE does not destroy it. It remains for later runs.

## 9. Reaching and accessing the server

After passing all ICE:

1. The Runner gets a final chance to jack out.
2. The Corp gets a final opportunity to rez relevant cards.
3. The run becomes **successful**.
4. Successful-run effects occur.
5. The Runner **accesses (examines and interacts with)** cards.

A successful run and accessing are separate events.

An empty-server run can be successful even though there is nothing to access.

### What gets accessed?

#### HQ

The Runner accesses:

- One random card from the Corp’s hand.
- Every upgrade in HQ’s root.

#### R&D

The Runner accesses:

- The top card of the Corp’s draw pile.
- Every upgrade in R&D’s root.

#### Archives

The Runner accesses:

- Every card in the Corp’s discard pile.
- Every upgrade in Archives’ root.

Before individual cards in Archives are accessed, all face-down cards in Archives are turned face-up. The Runner then accesses them in any order.

#### Remote server

The Runner accesses every card installed inside the remote server.

ICE is outside the server and is never accessed.

### What happens to an accessed card?

Resolve one card completely before accessing the next.

- **Agenda:** The Runner must steal it if able. Stealing normally costs nothing, but additional costs or replacement effects may change this.
- **Asset or upgrade:** The Runner may pay its **trash cost (destruction price)** to move it to Archives.
- **Other card:** Examine it and return it unless an effect says otherwise.
- **Card with access instructions:** Follow the printed instructions.

Accessing an unrezzed card does not rez it. A **when accessed** ability can still resolve while the card is unrezzed. If the card is not stolen or trashed, it returns face-down.

When accessing several cards, the Runner normally chooses their order. Multiple R&D cards must be accessed from the top downward. Cards accessed from HQ are kept temporarily separate from HQ until that access sequence is complete, so the same card cannot be randomly accessed twice.

Reaching 7 agenda points wins immediately, even if more cards remained to be accessed.

## 10. What remains after a run?

A run does not normally dismantle a server.

- ICE remains installed.
- Rezzed cards remain rezzed.
- Unrezzed cards remain unrezzed.
- Untrashed assets and upgrades remain installed.
- A stolen agenda leaves the server.

The Corp may later install another agenda or asset behind the same ICE.

---

