A top-down 2D narrative game (à la To the Moon) about a hooded Traveler walking an endless road "to Rome," fleeing an unnamed guilt/grief. The road is revealed to be a metaphysical trap that feeds on people who refuse to emotionally "stop." Rome doesn't exist as a destination — it's a lie travelers tell their feet so they keep moving. The whole game is one long extended metaphor for avoidance vs. confrontation of grief/guilt.
Structure (4 Acts + Final Choice)

Act I – The Beginning: Dusk entrance, milestone "Rome – 312 miles," the Old Man's warning ("You're walking away, not forward"), entrance vanishes once you turn — no going back.
Act II – The Empty World: Waystation 1 (hamlet) + Waystation 2 (church). Warm-but-abandoned houses, letters, a self-ringing bell, the ever-present Distant Figure exactly 100 paces ahead — never gains, never falls behind.
Act III – The Truth of the Road: Waystation 3 (Archivist's Rest/dead-letter office). Stone tablets reveal "Rome was never a place. Rome was an excuse." Road literally built by people convinced movement = meaning.
Final Act – Choice: Sign reads "ROME – 0 miles," no city, just a mirror/Shadowy Figure. Binary ending: Turn Back (world goes dark but real, road collapses, you stand still) or Keep Walking (you become the Distant Figure for the next traveler — the loop perpetuates).

Characters

The Protagonist/Traveler – silent, hooded, vessel for the player, driven by unnamed guilt.
The Old Man – blind, stationary, delivers the Act I warning, understands the loop.
The Distant/Shadowy Figure – beacon 100 paces ahead; eventually revealed as the Traveler's own projected shadow.
Old Martha – dried husk in Waystation 1 House 3, holds the Iron Key, died sitting still rather than confronting her past; her letter reveals the road doesn't kill the stopped — it just forgets them.
The Reflection/Lagging Mirror – in Waystation 2's confessional; the vulnerable true self lagging one second behind, holds the Crypt Key.
The Phantom Travelers – translucent ash-gray silhouettes from across history (Roman soldiers, Victorian peasants, moderns) seen during the midnight bell toll, walking in mechanical unison behind the Distant Figure.
The New Traveler – appears only in the "Keep Walking" ending; identical to the Protagonist's Act I appearance, completing the cycle.

Waystation 1 — The Hamlet of Leftovers (~20–25 min)
Arrival at dusk, iron toll gate blocks the road. Three houses:

House 1, The Hearth: warm stew mid-bite; Elena's diary about Thomas hearing his dead father, her hearing her dead sister from the well — the road "forces the past up through the floorboards." Standing still 10+ sec triggers whispering (ties directly into Dialogue Tree 2).
House 2, The Blacksmith: ledger of barter — people trading watches/wedding rings for boots/canes, abandoning attachment to time and memory. Blacksmith leaves the gate key with Old Martha before he too succumbs to the road's pull.
House 3, Martha's Rest: husk corpse holding the Iron Key + her final letter (the "stopping" lore-drop).
Conclusion: lights go out hamlet-wide once key is taken; gate opens; Distant Figure takes exactly 3 steps forward, mirroring the player.

Waystation 2 — The Hollow Bell Church (~30–35 min, the game's narrative center)
Sign: "All Roads Lead to Rome, but not this one." Self-ringing bell with no rope/clapper.

Puzzle 1, The Confessional: 3 torn log pages reveal travelers shed Memories (young), Gold (merchants), Names (the old) — slider solution [Memories→Gold→Names] opens the priest's booth, revealing the Silver Mirror (lagging Reflection, Dialogue Tree 3) and the Crypt Key.
Puzzle 2, The Altar Scales: Three stained-glass windows (cutting off one's shadow, burning letters/portraits at a milestone, a blank mirror) clue the player to place the Hollow Lead Heart on the scale — reveals The Liturgy of the Horizon parchment (a "religion" that worships moving forward and self-erasure) and opens the gate to the bell tower.
Climax: Midnight bell rings itself; phantom march of travelers appears with the Distant Figure 100 paces ahead, leading them; player pulls winch lever, drops a crate, clears the rockslide.

Waystation 3 — The Archivist's Rest (~35–45 min, bridges into Act IV)
Dead-letter office literally built across the road. Letters from Roman legionnaires to modern travelers — same sentiment across millennia ("I couldn't stay there after what I did"). First historical mention of the Distant Figure: "I believe it is a mirror. It moves only when we move."

Final Puzzle, Sorting of Regrets: Three Master Ledgers tied to each Waystation/era — Ledger of Grief (Waystation 1/the family), Ledger of Guilt (Waystation 2/the priest), Ledger of Deception (the player's own freshly-written record). Sorted in order [Grief→Guilt→Deception] to open the back gates.
Leads into Act IV: glitchy countdown milestones (10→3→1 mile), broken sign "ROME – Not Here," confrontation with the now-stationary Shadowy Figure in a fog clearing.

The Final Choice (mechanically + narratively)

Turn Back: hold back/down; fog → blinding black; road collapses behind you piece by piece; ending text: "The road is gone... you are finally standing still." Fade to black.
Keep Walking: hold forward/up; merge with the Figure; camera pulls back, you become the static distant figure; a new traveler enters from the bottom of the screen and looks up at you. Fade to grey.

Dialogue System (5 trees, consistent "illusion of choice" design pattern)
Every conversation gives 3 emotionally-different choices (e.g., Defiance/Confusion/Avoidance, or Guilt/Anger/Despair) that funnel to the same merge point and same outcome — reinforcing the game's central thesis that self-justification doesn't change the trajectory. Only the final choice (Tree 5) is real and changes the actual ending.

Tree 1 – Threshold Warning (Old Man, Act I): GameMaker-style trigger notes included (32px radius, Space/E interact, camera zoom, audio ducking). Ends with the entrance dissolving — no backtracking possible.
Tree 2 – Whispering Walls (House 1 environment-as-NPC): explicitly references the player having "burned down" a kitchen and left people screaming — this is the closest the doc gets to defining the Protagonist's actual backstory/sin. Forces player out the door (can't go deeper into the house).
Tree 3 – Confessional Plea (the Reflection): yields the Crypt Key; reflection turns away and hides once key is taken — a visual "abandonment of self" beat.
Tree 4 – Archivist's Judgment (Master Ledger): player picks a stated motive (Purpose/Justice/Survival) and the ledger deconstructs all three as the same cowardice ("Grief, guilt, purpose... just different ink used to write the same apology"). Confirms the "burned the hearth" detail again.
Tree 5 – Confronting the Shadow ([Myself] label, no NPC name): full monologue recap of the game's themes, then the real binary choice with full ending cinematics scripted for both branches.

Tech / Production Notes

Engine implied: GameMaker (explicit dialogue trigger pseudocode in trees 1–4).
Save/replay model inspired by Limbo/Inside — save before puzzles and after conversations.
Pause menu (Resume/Main Menu) and Main Menu (Continue/New Game/Quit/Help/Settings); Settings = sound + brightness; Help = controls list.

Inspirations cited

Dialogue box UI ← Doki Doki Literature Club
Top-down 2D RPG structure ← To the Moon
Visual theme: old, dark, period character design
Ending tone ← Little Nightmares 2 (visuals and sound design both)
