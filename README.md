# Seduce & Untether
### A Game of Influence

> *"The most dangerous game is the one played with the heart."*

A social strategy card game for **2–5 players** played over **8 rounds** on one shared device. Players use Seduction cards to place Tether tokens on each other — accumulating Influence — while Untether and Special cards help break free, expose secrets, or reshape the board entirely. The tension isn't moral. It's social. Who has power over whom, and what are you willing to do about it.

The game rewards reading people more than playing optimally. Every player carries a secret **Vulnerability Trait** that changes how cards land on them. Learning those weaknesses is where the real game lives.

---

## Files

| File | Description |
|------|-------------|
| `seduce-and-untether.html` | Playable digital prototype — open in any browser |
| `seduce-untether-cards.pdf` | Print-and-cut card deck (A4, 3×3 grid per page) |
| `seduce-untether-rulebook.pdf` | Full illustrated rulebook |

---

## Victory Conditions

| Condition | Details |
|-----------|---------|
| **Most Influence** | Highest score after Round 8 — standard win |
| **The Untethered** | Reach 0 Tethers + 5 Influence at any point — instant win |
| **Hopelessly Entangled** | 10+ Tethers — eliminated; highest remaining Influence wins |

---

## The Cards

### 💋 Seduction (Red) — Places Tethers on others

| Card | Effect |
|------|--------|
| 💋 Velvet Tongue | +1 Tether on target |
| 🌹 Slow Burn | +2 Tethers, delayed until next round |
| 🔥 Irresistible Pull | +2 Tethers immediately |
| 🫦 The Forbidden Glance | AOE — +1 Tether on ALL other players |
| 🌙 Midnight Confession | +1 Tether + mutual Shield + mutual trait reveal |
| 🌃 Lover's Night Out | Pass-device rendezvous: accepted = both +2 Inf + Shield (invisible to accusations); rejected = proposer −1, rejecter +1 |
| 🥀 The Fade | Remove all YOUR tethers on target → +1 Inf per tether shed → target gains 1 back from longing |
| 💝 Love Bomb | +3 Tethers on target, +3 Influence — but you catch feelings too: +1 Tether back on yourself |
| 🍸 The Nightcap | Target discards their highest-value card. No tethers. Nobody suspects a thing. +1 Influence |

### 🧊 Untether (Blue) — Protect yourself or remove Tethers

| Card | Effect |
|------|--------|
| 🧊 Cold Shoulder | −1 Tether from any source |
| ✂️ Cut Loose | Clear ALL Tethers — skip next turn |
| 🛡️ Preemptive Shield | Block next Seduction entirely (looks identical to Smoke Screen) |
| 🧠 Detachment Protocol | Hard to Get — all others gain +1 Tether toward you |
| 🚶 The Alibi | Reactive: cancel any card OR accusation played against you. Attacker −1 Influence. Grants Shield |
| 🛡️ Smoke Screen | Halves incoming Tethers (looks identical to full Shield publicly) |

### ✨ Special (Gold) — Wildcards that reshape the board

| Card | Effect |
|------|--------|
| 🪞 Mirror | Reflect the next Seduction back onto its caster (until end of round) |
| 🔗 Entanglement | Split one of your own Tether tokens — pass halves to two different players |
| 🎭 Persona Swap | Swap ALL your Tether tokens with a target |
| 👁️ Voyeur's Eye | Secretly reveal one player's Vulnerability Trait. +1 Influence |
| 🕵️ Caught You | Accuse 1–2 players of a real affair. Correct = −2 Inf each + Tethers exposed. Wrong = −2 Inf to you. Blocked by Alibi or Plausible Deniability |
| 🎴 Plausible Deniability | Passive trap — hold it. Auto-intercepts Caught You or Walk of Shame against you. Attacker −2 Influence. Your secret holds |
| 👠 Walk of Shame | Expose one player's affair publicly. −2 Influence, affair Tethers go visible. Partner untouched. Blocked by Plausible Deniability |

---

## Vulnerability Traits

Every player is secretly assigned one at game start. Affects how cards land on them.

| Trait | Effect |
|-------|--------|
| 💬 Craves Validation | Velvet Tongue & Midnight Confession deal +1 extra Tether |
| 🌒 Fears Abandonment | Cold Shoulder & Cut Loose backfire — Tethers tighten |
| 👑 Power-Hungry | Immune to seductions from players with less Influence |
| 🕯️ Secretly Lonely | AOE cards deal +1 extra Tether |
| ⚡ Thrill Seeker | Irresistible Pull deals +2 extra Tethers |
| 🌹 Romantic Idealist | Slow Burn deals double Tethers |
| 🎭 Control Freak | 50% chance direct seductions bounce back onto the seducer |
| ✨ Attention Addict | Loses 1 Influence at end of any round they receive zero Tethers |

---

## Status Events

Fire at **40% probability** from Round 2 onward after a successful seduction. Only one per seduction. Full-screen overlay, auto-resolves after 6 seconds.

| Event | Trigger | Effect |
|-------|---------|--------|
| **That's Bold** | Top-scoring player seduces someone | All watchers +1 Tether toward leader; leader +1 Influence |
| **Who Is That?** | Lowest-scoring player tethers the top scorer | All watchers +1 Tether toward underdog; underdog +2 Influence |

---

## Accusation Counterplay

Three layers of protection against Caught You and Walk of Shame:

1. **Use Lover's Night Out** — affairs stored in `rendezvous`, invisible to all accusation cards
2. **Hold The Alibi** — reactive cancel (any card or accusation), −1 to attacker, grants Shield
3. **Hold Plausible Deniability** — passive trap, auto-intercepts accusations and exposures, −2 to attacker

---

## Awkward Mechanics

| Mechanic | Effect |
|----------|--------|
| **Overreach** | Target has more Influence than you + zero Tethers toward you — seduction fails |
| **Thread Snap** | 3 Tethers from you on target — a 4th attempt snaps one loose instead |
| **Audience Effect** | 2+ watchers from Round 3+ — you lose 1 Influence regardless of outcome |

---

## Expansion Pack (Planned)

The following cards are designed and reserved for a future expansion add-on:

- 🍿 **The Distraction** — skip a target's next turn
- 🌅 **The Entourage** — public sunset drive; target's Tethers toward you double but everyone knows
- 🩴 **The Slow Dance** — neither player can be targeted until next round
- 🤝 **The Borrow** — temporarily take someone else's Tether for Influence then return it

---

## Strategy Tips

- **The Fade** — most underused card. Removes your Tethers, gains Influence, pulls target closer
- **Love Bomb** — massive swing but you catch feelings. Best when you can absorb the self-tether
- **The Nightcap** — invisible on the board. Nobody will even look at you funny
- **Plausible Deniability** — holding it is psychological warfare. Make them afraid to accuse
- **Smoke Screen** — looks identical to full Shield. Use the ambiguity
- **Midnight Confession** — reveals traits mutually. Only use if willing to be known
- **Persona Swap** — most lethal when someone is close to 10 Tethers

---

*For 2–5 players · 8 rounds · One shared device*
