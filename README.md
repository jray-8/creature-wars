# Creature Wars

Take control of an empire and force creatures to duel against your enemy to conquer their land!

Creatures are captured (or bribed) and bound for battle to regain their freedom. However, if the enemy outnumbers your creature, it will turn on you and fight its way out instead! The magickal effects of witches may also flip the battle in unsuspected ways.

## Game Rules

- 2-player game

- Play from a shared deck of __52 cards__

- Each player controls an Empire with __30 HP__

- Whoever loses all their HP first loses

	- If the deck is empty before a player has won, go to *MAYHEM!*

- Both players start the game with __5 cards__

- Each turn players draw a card

	- Alternate who draws from the deck first each turn

---

### Creatures

Every creature has a __Base Strength__, a __Level__, and a __Power Type__.  
Creatures start in deck with a level from 1-6.

There are __7 Tribes__, each with a unique base strength:

| Tribe | Base _str_ |
|-------|------------|
| Serpent  | 0 |
| Wolf     | 2 |
| Skeleton | 3 |
| Pirate   | 3 |
| Giant    | 4 |
| Vampire  | 5 |
| Dragon   | 7 |

A creature can be one of __4 Power Types__: 

- `Ancient`
- `Fire`
- `Nightmare`
- `Holy`

<br>

Each Power Type has an advantage against one other type, and gains a __+3 Power__ bonus in fight.

This forms the cycle:  

&emsp; `Ancient` → `Fire` → `Nightmare` → `Holy` → `Ancient` → &nbsp;…

### Ancient
- The Ancients retain forbidden knowledge <br>from the past, allowing them to manipulate fire.

### Fire
- Fire provides safety, comfort, and exposes <br>shadows that protect the monsters of the night.

### Nightmare
- Dark illusions torment the minds of the righteous <br>until they cave to their inner temptations.

### Holy
- Priests and heroes are favored <br>by the gods to slay mythical beasts.

---

### Dueling

Each turn players will play a creature from their hand to duel.

The creature with the greater power wins the __FIGHT__:

	power = base_str + level + (3 if type_advantage)

Whoever loses the duel will take damage equal to _their own_ creature's base strength.

> A creature's base strength represents the resources it costs your empire to seize. Therefore, a stronger creature causes your empire a greater loss!

The winning creature will __escape__.

After the duel, both cards are discarded.

__Additional Rules__:

- If the creatures have equal power, they each return to their player's hand and cannot be played on the next turn (cooldown 1).

- If a player cannot play a creature for any reason, they simply take the Base Strength of the enemy creature.

	- Cards may be on cooldown or __Frozen__: cannot be played but remain in hand.

	- A non-dueling card may be played.

	- This counts as losing the duel.

- When 2 creatures from the same Tribe duel, it becomes a _Tribal Clash!_

	__Tribal Clash__: The winner of the duel draws a card.

- When a creature with a type disadvantage wins its duel, you may encounter a strange figure within your Empire…

	__Bizarre Victory__: Get a random Witch card.

---

### Witch Cards

Besides the seven tribes of creatures, the deck also contains __Witch cards__.

Witches all share the following traits:
- Base Strength: 3
- Power Type: None
- Duels: Witches do not duel like creatures

__Playing a Witch__  
When a Witch is played, it immediately casts its __effect__, altering the state of the game. 

After the effect resolves, the opposing card __fights the Witch__:

- If the Witch __loses__ (dies), your Empire takes damage equal to the Witch's base strength (3).
- If the Witch __escapes__ (wins/ties), no damage is dealt.  
	— This does not count as a duel win.

In either case:

- The opposing creature is __not discarded__.
- It returns to its owner's hand with __no cooldown__.

If __two Witch cards__ are played against each other, they duel normally but neither Witch returns to a player's hand.

__Witch Effects__  
A Witch's effect may do one or more of the following:

- Change the __levels__ of creatures
- Change or remove __Power Types__
- Draw, discard, steal, or reveal cards
- Modify or replace __Tribes__
- Alter core __game rules or timing__
- Add new cards to a player's hand or the deck

Effects may target:

- Your hand
- Your opponent's hand
- The deck
- __*ALL*__ cards, wherever they are

Because Witch effects can be unpredictable—and sometimes harmful—playing a Witch card is often a gamble. The same Witch may save your Empire with one hand and doom it with another. So hold onto your Witch cards and use them carefully.

---

### Timing Glossary

- __On Escape__ — When a Witch survives its duel.
- __On Death__ — When a Witch loses its duel.
- __While in hand__ — A continuous effect active as long as the card remains in hand.
- __At the start of your turn__ — Resolves before drawing a card.
- __At the end of your turn__ — Resolves after the duel.
- __For the rest of the game__ — A permanent rule change unless reversed.

---

### Complete List of Witches

They come in 3 rarities:

1. __Lesser Witches__ – `3/6`
1. __Sacred Witches__ – `2/6`
1. __Sinful Witches__ – `1/6`

These weights represent the probability of each tier being selected when a Witch is added to the deck or randomly generated. For instance, Lesser Witches appear 3 times more often than Sinful Witches.

__Lesser Witches__ — Lvl. 1-3

- Lesser Witches are students of the art.  
They have less powerful effects and come in lower levels.

<details>
<summary style="
    background:#0b0b0b;
    color:#e0e0e0;
    padding:10px;
    border:1px solid #3a3a3a;
    border-radius:6px;
    font-weight:600;
    cursor:pointer;
  ">
  View full list</summary>
<br>

| Name | Effect |
|------|--------|
| Blind Witch | This witch always loses its fight. |
| Invisible Witch | This witch cannot be attacked. It automatically escapes. |
| Angry Witch | If this witch loses its duel, discard a random card from the opponent's hand. |
| Magic Witch | Transform a random card in your opponent's hand into a level 1 Serpent. |
| Voodoo Witch | If this witch is killed, your opponent also takes damage but their's is doubled. |
| Greedy Witch | Draw 2 cards. |
| Which Witch | At the start of the duel, transform into a random Sacred Witch and cast its effect. |
| Witcheroo | Swap hands with your opponent. |
| Kind Witch | Give creatures in both hands `+1 level`. |
| Cocksure Witch | If this witch wins its duel, draw a card. Otherwise, your opponent does. |
| Flamboyant Witch | Representation from the underworld. |
| Envious Witch | Get a copy of the strongest creature in your opponent's hand. |
| Cursed Witch | Each turn this is in your hand, take 1 damage. |
| Sick Witch | If this witch survives, turn all witches in your opponent's hand into __Sick Witches__. |
| Sacrificial Witch | If this witch dies, give all creatures in your hand `+2 levels`. |
| Snake-Eyed Witch | If you're holding at least 2 Serpents, draw a card. |
| The Witch Collector | Your opponent takes 3 damage; you gain 3 health. |
| Wet Witch | Each player doesn't ask… |
| Flying Witch | If this witch escapes, add 2 random Sacred Witch cards to your hand. |
| Wilbur Witch | If this witch escapes, get Orville Witch. If she already escaped, get a Flying Witch instead. |
| Orville Witch | If this witch escapes, get Wilbur Witch. If she already escaped, get a Flying Witch instead. |
| The Early Witch | If you play this card before turn 6, get 3 random Serpents. |
| Pick a Witch | Look at 3 random Witch cards; add one to your hand. <br>"… Any Witch!"|
| Witch in Time | If this witch survives, the next card you play has `+3 power`. |
| Premature Witch | At the start of each turn, there is a _50% chance_ Premature Witch will spring into action. ;) |
| Slumbering Witch | This witch cannot be played until you have formed a Rally. |
| McWitch | Restore `4 HP` to your Empire and get a random `Lvl.1` creature with a Base Strength of 4 or less. <br>"I'm loving it!" |
| Jittery Witch | Both players discard a random card, then draw one. |
| Mundane Witch |
| Rebellious Witch | If this witch survives, it joins the opponent's hand. |
| Busy Witch | This witch must run her errands before being played: Cooldown 4. |

</details>
<br>

__Sacred Witches__ — Lvl. 4-6

- Sacred Witches are honorable and highly-respected witches. They have greater control of their magic and cast more powerful, often symmetric, effects. However, if used at the right time these Witches can serve to benefit the caster greater.

| Name | Effect |
|------|--------|
| Witch of Despair | Both players discard their entire hand. |
| Witch of the Hesperus | _ALL_ Pirates drown and are replaced with __Phantoms__ (-2 Base Strength, +4 levels, no Power Type). |
| S | _ALL_ Skeletons ressurect into __Fallen Heros__ with base strength 7. |
| S | _ALL_ Vampires become `Ancient` Vampires (+1 base strength, +1 level). Shuffle 4 of them into the deck. |
| Vengeful Witch | If this Witch loses its duel, gain a `Lvl.1 Primordial Butterfly {1}`. If the Primordial Butterfly ever wins a duel, the opposing Empire crumbles. |
| Moon Charm Witch | Transform _ALL_ Wolves into __Werewolves__. They now have a Base Strength of 8 and are permanently `Nightmare` types. |
| Prophetic Witch | See your opponent's hand. |
| Shifting Witch | Become an exact copy of the opponent's card at the start of the duel. |
| Democratic Witch | Disband any __Rallies__ in your opponent's hand. Those cards cannot be used in future Rallies. |
| Scary Witch | Turn the Power Types of creatures in your hand into `Nightmare`. Any `Holy` creatures are discarded instead. |
| Frost Witch | Remove all `Fire` creatures from each player's hand. |
| Hectic Witch | Shuffle 15 more Witch cards into the deck. |
| Wicked Witch | After this Witch dies or flees, give a random card in your hand its *enchanted ring*: *+2 levels*. When a card with the *enchanted ring* is defeated in duel, give it to a random card in the victor's hand. |
| Witch of the Hallowed Circle | While you hold this witch and at least 2 others, your creatures gain `+2 power` in duels. |
| Witch of the Hallowed Circle | _The Seance_: Look at the last 5 cards that lost their duel. Add one to your hand. |
| S | Serpents become venomous this game. They always win their duel. |
| Feigglehorne's Witch | Send your opponent's 2 weakest (*base str*) creatures to the circus. They won't be back. |
| Foreboding Witch | If this Witch dies, add 2 random Wolves to your hand. |
| Lusting Witch | Summon the largest (*base str*) creature from your hand to "battle" the smallest creature in your opponent's hand. You take damage from the small one and your opponent takes damage from the big one, equal to their base strengths. The Lusting Witch watches… |
| Sun Witch | Shuffle `Nightmare` and Witch cards in each player's hand back into the deck. `Fire` creatures in both hands get `+3 levels`, but explode in 2 turns if left unplayed, dealing their `base str` to the holder's Empire. |
| Gluttonous Witch | Both player's increase their Empire's health by 20 HP. |
| Witch of Slothing | Discourage 2 cards in your opponent's hand. They can no longer be played or used in Rallies. |
| Proud Witch | The player who loses this duel will take double damage the next time they lose again. |
| Lucky Witch | The next creature you play will always win its duel. |
| Wishing Witch | The next card you draw is replaced with one that can help you form a Rally. |
| Shamanic Witch | Randomize the Power Types of creatures in each player's hand. |
| Vortex Witch | Scramble the bounds of physics. Creatures in each player's hand are given a new tribe. |
| Grim Witch | Mark a random enemy creature for death. When played, it immediately dies. You get to see which creature was chosen. |
| Hallucinating Witch | Replace half of each player's hand with random Witch cards (rounded up). |
| The Big Bad Witch | "Then I'll cackle, and I'll curse, and I'll defile your corpse." Blow all those little Wolves in; they are removed from each player's hand and the deck. |
| Witch of the Emperor | Reveal a card in your opponent's hand. If it has a *base str* of 4 or less, steal it. |
| Witch of the Legion | Shuffle 6 random Skeletons into the deck. |
| Witch of the Legion | Choose a Tribe to get 2 random creatures from: *Wolf, Skeleton, or Pirate*. |
| Seductive Witch | If this witch escapes, the opponent automatically plays the creature returned to their hand next turn. |
| Rage Witch | Discard a random card from your hand to deal 1 damage to the enemy Empire for every duel you have lost this game. |
| Jesting Witch | Tell a joke that adds 3 cards to the top of the deck. |
| The High Witch | The next card played by your opponent has `+3 power`, but they take __double damage__ if it loses. |
| Shady Witch | "Wanna make a deal…?" <br>Give your opponent the most powerful creature from your hand. You take their least powerful creature in return. If they don't play their gift next turn, it becomes defective (*level 1*)! |
| Questing Witch | If your empire has slain a creature from every Kinship, choose a potion to drink: <br><br>Potion of Deception – discard your 3 most powerful creatures <br>Potion of Ferocity – all creatures in you hand gain *+3 levels* <br>Potion of Endurance – your Empire gains *+15 HP* |
| Berserker Witch | On the next duel, the losing Empire also takes damage from the winning card's level. |
| Pandora's Witch | Cast the effects of all Witches in your opponent's hand for them. Those witches flee afterwards. |
| Odd Witch | Both players discard all even-leveled cards in hand. |
| Witch of the Firehawks | Set your hand ablaze. All creatures you hold become `Fire` Power Types; `Nightmare` and Witch cards are destroyed. |
| Talismanic Witch | Cast a protective ward. The next time your Empire takes damage, only take half (rounded down). |
| Chthonic Witch | Add the last creature that was defeated to your hand. It has `-2 levels`. |
| Necromancing Witch | Resurrect all Skeleton creatures that have died in battle. Give them *+3 levels* and add them to your hand. |
| Circe's Witch | Transform Pirates in each player's hand into Wolves. |
| Angitia's Witch | Eat all Serpents in your hand. For each discarded, your Empire gains *+5 HP*. |
| Minerva's Witch | Choose to trade your 2 least powerful creatures with the opponent's 2 most powerful creatures. Or, your 2 most powerful creatures for the opponent's 2 least powerful creatures. |
| Succubus' Witch | Discard a random `Nightmare` in your hand to summon a succubus that desecrates an enemy creature. The victim loses *-3 levels* and a Lvl.1 *cambion* is added to your opponent's hand. The cambion has the same *base str* and Power Type as the victim, but deals double damage to their Empire. |
| Sin-Eater Witch | The next time one of your creatures dies, a random creature in your hand absorbs its transgressions and you take no damage. That creature becomes an outcast and can no longer be played. |
| Charlotte's Witch | Trap a card in your opponent's hand in a web. It can never be played. |
| The Sand Witch | Spell the air with sleep sand. For the rest of the game, `Nightmare` creatures have `+2 power` when dueling. |
| Green Witch | The player with less cards draws until both players share the same hand size. |
| Wiccan Little | Whenever Wiccan Little panics, the sky __might__ fall. |
| Coven-Calling Witch | Shuffle 13 Sacred Witches into the deck. |
| Wraith Witch | If this witch dies, add a Wraith to your hand; it deals 3 damage to the enemy Empire when played and immediately disappears. Enemy creatures facing the Wraith are sent back to hand with a 1-turn cooldown. |
| Lenore's Witch | Choose from 3 creatures in your opponent's hand to send to the quiet fields. In its place, a Raven is fixed. The Raven cannot be played, but pecks your opponent for 2 damage when they are reminded of their beloved. |
| The Witch of the Cumaean Sibyl | _The Scattered Prophecies:_ Your opponent reveals their hand and shuffles 3 cards back into the deck. They then draw 3 new ones. |
| Medusa's Witch | If this witch lives, petrify the enemy card; it cannot be played or participate in Rallies. |
| Chiquita Witch | While this is in your hand, at the end of every turn, give creatures in your hand *+1 levels*. Any creatures level 5 or more turn sour and attack you, then flee. |
| Midas Witch | For the rest of the game, cards that enter your hand gain *+2 base str*. |
| Santa Witch | Both player gets 2 wrapped gifts! Inside each present may be a random creature or a lump of coal. You get to peek at two of them. "Merry Witchmas!" |
| David's Witch | Less powerful creatures now win against Giants, but higher-powered creatures lose to them. |
| Goliath Witch | The weaker creature will win the next duel. |
| S | Sound the horn of Juno: Giants are permanently twice as strong against and susceptible to type advantages. |
| S | Choose from 3 enemy creatures. Pick one to free from its sinful cage of flesh. |
| Buried Witch | If you control a Pirate rally, get 3 Cannonballs. When played, they do 5 damage to the enemy Empire. You still take damage from creatures they play. |
| Skeletal Witch | If you control an Enhanced Skeleton, skullify all other creatures in your hand. They now belong to the Skeleton Tribe and deal 3 damage when defeated, despite keeping their original base strengths. |
| Black Witch | Steal a random Witch card from your opponent's hand, if present. |
| S | Shuffle every Skeleton that has died this game back into the deck with *+1 level*. |
| S | Steal a random Witch card in your opponents hand, if one is present. |
| S | For the remainder of the game, whenever a creature with level 6+ wins a duel, it also damages the Empire who sent it. |
| Benevolent Witch | Give a random creature from each Tribe in your hand `+2 levels`. |
| Prehistoric Witch | Make all creatures in your hand `Ancient`. |
| Transcendental Witch | Choose a card in your hand. It swaps its level and base strength. |
| S | _Divine Blessings_: If you control a `Holy` Rally, choose a card in your hand to give `+10 levels`. |
| S | S: If you control a `Fire` Rally, discard all your `Fire` cards and deal 3 damage to the enemy Empire for each. |
| S | S: If you control a `Nightmare` Rally, |
| S | S: If you control an `Ancient` Rally, |
| S | Transform Serpents in both player's hand into random Dragons. |
| Haughty Witch | If this witch is a greater level than its challenger, take a random card from the opponent. |
| Haggel & Witchel | Set a curse: The next player to draw a Witch card takes 12 damage. Both players draw cards until they're holding 8. |
| Little Witchard | _The Way God Wants It_: Renounce your previously unholy conduct and become an Evangelical Priest. Both players discard all their `Nightmare` cards, and convert their other creatures to the `Holy` type. The next `Nightmare` card to enter your hand triggers a relapse: All your `Holy` cards turn into `Nightmares`. |
| Storytime Witch | Tell a tale to both players that adds a creature to your hand. |
| Ondu's Witch | Reverse the effects of the previous duel. Damage is taken back and the cards are returned to hand with cooldown 1. |
| The Coven of Babel | Each player shuffles a random creature from each Tribe in their hand into the deck. |
| Witch of the Nine Realms | _Yggdrasil's Gift_: Replace your hand with a random creature from each of the 7 Tribes plus 2 Sacred Witches. |
| Scarecrow Witch | Transform a random creature in your opponent's hand into a __Scarecrow__. <br>Scarecrow: base strength 3, level 1, no Power Type, and "doesn't care." <br>- If dueled, the duel is a tie and both cards are discarded. <br>- While the Scarecrow is held, `Nightmare` creatures lose `1 level` at the end of the turn. |
| Vegetable Mask Witch | While in hand: This witch loses `1 level` each turn. When it reaches level 0, draw 2 cards and discard this Witch. If this witch wins a duel: Discard your entire hand. |
| Conversion Witch | Transform `Nightmare` creatures into `Holy`, for both players. `Holy` creatures permanently deal double damage to Empires. |
| Arnold Layne's Witch | _Steal from the line_: Swap a creature from each player's hand at random. The creature you receive gets `+3 levels` and `cooldown 2`. |
| Emily's Hiding Witch | Choose a creature in your hand. At the start of each turn, randomize its Power Type and level (1-6). |
| Golden Veil Witch | Add a random creature to your hand from a Tribe you do not currently control. |
| Dark Globe Witch | Creatures in both hands lose their Power Type for the rest of the game. |
| Gnome Witch | Scramble the levels and Power Types of all creatures in your hand. <br>"Ooh, my" |
| Jugband Witch | Add 3 random creatures to your hand. They must be played before any other card. |
| Jugband Witch | Choose a card in your hand to discard. Draw 3 new cards. If all 3 win their duel, reobtain the discarded card with `+7 levels`. |
| Jugband Witch | Discard a random creature from your hand. Create a level 1 __Stand-In__ copy of it. If the Stand-In dies, draw 2 cards. |
| S | Look at the top 2 cards of the deck. They each gain `+2 levels`. Choose one to keep, and give the other to your opponent. |
| Scientific Witch | Choose a creature in your hand and a new Power Type for it to become. |
| Overdrive Witch | Deal damage to the enemy Empire equal to your current number of consecutive duel wins. |
| Straight Witch | If you're holding at least 5 cards with consecutive levels, give each of them `+3 levels`. |
| The Madcap's Witch | Shuffle your hand into the deck. Draw the same number of cards plus one. If this witch dies, discard 3 cards. |
| Witch of Silence | _Hush_: For the next 3 turns, no Witch effects can be triggered. Witches played during this time duel without casting their effect. |
| Pied Piper's Witch | Choose a Tribe. Creatures of that Tribe in your opponent's hand are discarded. For each discarded, add a random creature of that Tribe to the deck. |
| Pied Piper's Witch | _The Rat-Run_: All Serpents and Wolves in both hands and the deck are immediately discarded. Draw 1 card for every 3 discarded. |
| Mimic Witch | Cast the effect of the last played Witch. |
| Clockwork Crier Witch | Set a prophecy: name a number (1-3). After that many turns, draw that many cards and take 2 damage for each drawn. |
| Crow-Laughing Witch | Whenever a witch escapes, give a creature in the opponent's hand `-2 levels`. |
| Daisy-Chain Witch | This witch casts the effects of all other Witch cards in your hand. They all flee afterwards. |
| Cracked Ceremony Witch | From now on, whenever a Witch card is played, the other player discards a random card. |
| No Good Trying Witch | Skip your next turn. Draw 3 cards at the end of the skipped turn. |
| Straw Witch | As long as this witch is in your hand, you may not play creatures. Creatures in your hand gain `+1 level` at the end of each turn. |
| Astronomy Witch | Give all cards in your hand `+1 level` for each Power Type you control. |
| Hostage Witch | While in hand: Whenever you lose a duel, reveal a random card from your hand to your opponent. <br>On Escape: Give cards in your opponent's hand `-2 levels`. |
| Falsely Imprisoned Witch | Choose a creature that was "slain" (lost a duel). Return it to your hand with `+3 levels`. |
| Premarital Witch | If you're holding another Witch card, add a random level 1 Witch to your hand. |
| Safe Witch | Discard your entire hand. <br>Gain 5 HP. |
| Safe Witch | _Protection_: You cannot take damage from your own creatures for the next 2 duels. |
| S | Whenever your opponent draws a creature or Witch, discard one in your hand with the same Tribe to destroy both of them. |
| S | Choose a Tribe. For the rest of the game that Tribe has +3 base strength. |
| S | Burn the top 5 cards of the deck. Any `Fire` creatures are added to your hand instead. |
| S | Discard all other Witches in your hand. For each discarded, give your creatures `+2 levels`. |
| S | Discard 3 random cards. Add three identical level 1 creatures to your hand. |
| S | For the rest of the game, cards enter your opponent's hand with cooldown 2. |
| Limp Witch | While in hand: All your creatures have their base strength reduced to 2. |
| Evasive Witch | _Smoke Screen_: This Witch cannot be discarded. <br>On Death: Return this to your hand with a random Sacred Witch effect. |
| S | Choose a card in your hand to drain and reduce its level to 1. For each level lost this way, give another card in your hand `+1 level`. |
| S | Choose a card in your hand to suck the life from. Reduce its level to 1. Your Empire gains +1 HP for each level sucked. |
| Kill's Witch | _The Hit List_: Secretly choose a Tribe and Power Type. The next time your opponent plays a creature, deal 5 damage to their Empire for each trait it matches. |
| Humbert's Witch | Reveal a random creature in your opponent's hand. While it remains there, it loses `1 level` at the end of each turn. |
| Sadistic Witch | _Proof of Life_: Whenever your opponent loses a duel, give a creature in your hand `+1 level`. |
| Masochist's Witch | _Pain is Pleasure_: Whenever your Empire takes damage, draw a card. |
| Playwright Witch | Rewrite the Tribe of one creature in your hand. It keeps its original base strength. |
| Divine Wind's Witch | _Banzai Charge_: Instead of dueling, both cards are promptly destroyed and each Empire takes 5 damage. Enemy Witches do not cast their effects. |
| S | Your Empire cannot take more than 5 damage at once. |
| S | Choose to target the enemy Empire or your own. A random creature will have its base strength reduced by half (rounded down). |
| S | Cards in both hands gain cooldown equal to their level. |
| Brute Keeping Witch | Add 2 steel cages to your opponent's hand. When played, or during Mayhem, a random creature with `base str` 5 or higher is released. |
| Wretched Witch | All creatures in your hand are butchered and stitched into one. <br>Resurrect the __Monster__ with combined levels, base strength, Tribes, and Power Types. <br>While the Monster is in hand, you do not draw at the start of your turn. |
| S | Discard your highest-level creature. Draw two level 1 creatures. |
| Candlelight Vigil Witch | Give `Holy` creatures in your hand `+1 level` for each `Fire` type you control. |
| Homophobic Witch | Destroy random cards in each player's hand until only one copy of each Tribe remains in hand. |
| Queen Nyssia's Witch | Instead of dueling, the opposing card is added to your hand and the strongest creature in your opponent's hand is slain. |
| Mazophilic Witch | Whenever a creature gains levels, this Witch gains the same number. |
| Elektra's Witch | If a creature in your hand is ever discarded before being played, give another creature in your hand `+4 levels`. |
| Cenophilic Witch | Give a random creature in your hand `+1 level` for each empty splot in your hand. |
| Engorged Witch | Whenever you draw beyond your hand limit, give your creatures `+2 levels`. Draw a card. |
| Logi's Witch | `Fire` creatures in your hand gain `+2 levels`. |
| S | `Holy` creatures in your hand gain `+2 levels`. |
| S | `Nightmare` creatures in your hand gain `+2 levels`. |
| S | `Ancient` creatures in your hand gain `+2 levels`. |
| Idolatrous Witch | Choose a creature in your hand to be worshipped. At the end of your turns, all other cards in your hand transfer `1 level` to this creature. Cards may not go below level 1. |
| Onan's Witch | Skip your next draw. Instead, gain `+5 levels` spread among your hand. |
| Magnetic Witch | After your next duel, draw a creature matching the Tribe played, or draw a Witch if you played a Witch. |
| S | Choose a Power Type. Draw a creature from the deck with this type. |
| Fool's Witch | This witch takes the appearance of another Witch. When played, you are revealed to be a fool! |
| Loki's Witch | Shuffle 5 Fool's Witches into the deck. Witch cards in both hands are shuffled back into the deck with new identitied. |
| Masquerader's Witch | Copy the effect of the last Witch played this game. |
| Crossdressing Witch | Give each creature in your hand a new Power Type. |
| Swarming Witch | Shuffle 12 __Locusts__ into the deck. <br>Locusts cannot be played and deal 1 damage to their holder after each duel. <br>Playing a Witch causes all Locusts in your hand to flee. |
| Espionage Witch | Infiltrate the enemy Empire: A random card in their hand becomes your mole. <br>After each duel, the mole reveals another card in your opponent's hand. <br>When the mole is discarded, the effect ends. |
| Peevish Witch | Give a random enemy creature `-2 levels`. |
| S | All cards in both hands become level 1. |
| Dyslexic Witch | Each turn this is in your hand, scramble the levels of your cards. |
| S | Swap the level and base strength of cards in both players' hands. |
| Aegean Witch | Discard a random card from each hand. |
| Schizophrenic Witch | At the start of each turn, gain the identity of a random other Witch. |
| Capgras Witch | Choose a creature in your hand. Give it a new Tribe. It keeps its original base strength. |
| Machiavellian Witch | _The End Justifies The Means_: Subdue two random creatures in your hand and set them to level 1. Redistribute their lost levels to your other creatures. Then decide to give them to your opponent or keep them. |
| S | The next Empire to play a Witch takes 2 damage. |
| S | Add 3 __Blood Giants__ to the top of the deck. When they win a duel, restore 5 HP to your Empire. |
| S | Add 3 Dragons to the bottom of the deck. |
| S | Whichever Empire has played more witches at the end of the game takes no damage during Mayhem. |
| S | Cards duel using levels only next turn. Base strength is ignored. |
| Sniper Witch | Instead of dueling, discard the enemy creature and flee. Witches duel normally. |
| Bone Witch | Choose to either give Skeletons in your hand `+1 level` or add a random Wolf to your hand. |
| Graveyard Witch | Discard the top 6 cards from the deck. Any Skeletons discarded enter your hand instead. |
| Neglected Witch | This witch gains `+1 level` for each turn unplayed. |
| Kosher Witch | Discard a random creature in your hand. Heal for twice its base strength. |
| Didactic Witch | Reveal your hand. Draw a card for each Witch shown. |
| S | _Sanctuary_: For the next 3 turns, your Empire cannot take damage from Base Strength. |
| Wallowing Witch | If your HP is lower than your opponent's, a creature in your hand gains `+4 levels`. |
| Heralding Witch | See the top 5 cards of the deck. |
| The Witch of Wallstreet | Look at the top 3 cards of the deck. Put one in your hand, and the others on the bottom. |
| S | Choose a Tribe. Creatures from that Tribe cannot be played for 2 turns. |
| The Tin Witch | If you hold a Rally, give them another `+2 levels` (including The Tin Witch). |
| The Tin Witch | _Heartless_: Remove the Power Type from all creatures in your opponent's hand. |
| Witchy Wonka | If your opponent has played more Witches than you, then your next card that loses buffs cards in your hand equal to its level. |
| Witchy Wonka | Hide 5 golden tickets on random creatures left in the deck. After a creature with a golden ticket is played, give creatures in your hand `+1 level` for each golden ticket uncovered. |
| S | Turn _ALL_ `Ancient` types (held or in deck) into Serpents. |
| Indignified Witch | If this witch wins the duel, the opposing creature is so embarrassed it loses its Power Type and `-2 levels` permanently. |
| Paraphilic Witch | _Curious Attraction_: Choose a Tribe from your hand. All creatures of that Tribe in your opponent's hand are immediately drawn to yours. |
| Nude Witch | Cards in both players' hands are set to `level 1`. |
| Nude Witch | _Nothing to Hide_: Both players must play with their hands revealed until this witch leaves your hand. |
| Racist Witch | _The Unspeakable_: Declare one of the 7 Tribes as uncouth. Whenever such a creature is played, the commanding Empire takes 3 damage. |
| Death Witch | Choose to victimize the opponent's Empire or your own. A random card in the victim's hand has its `base str` increased by 5. |
| Witch of Silencing | The first witch to be played while this is in your hand has its effect nullified. Whenever that happens, discard this witch. |
| Nymph Witch | This card counts as any Power Type to complete a Rally in hand. Once a Rally is formed, it keeps that Power Type. |
| S | This card counts as any Tribe to complete a Rally in hand. |
| S | Transform all other witches in your hand into random Vampires. |
| Witch of the Beasts and the Children | All creatures with a Base Strength greater than 4 flee from the deck. |
| Secular Witch | All `Holy` creatures in both hands are discarded. |
| The Ouroboros Witch | Transform Serpents in both players' hands into random Dragons. |
| S | Give creatures in both players' hands cooldown 3 (they cannot be played for the next 3 turns). |
| S | Swap the Base Strength of the strongest and weakest creatures in your hand. |
| Archwitch | Draw a Witch card from the deck and reveal it. Shuffle the deck. |
| Maiden Witch | All level 1-2 creatures in your hand gain `+3 levels`. |
| !!Wild-Tamer Witch | Reduce the Base Strength of all creatures in your hand by 2. Give them `+1 level` instead. |
| Suicidal Witch | Lose 6 HP. Draw a card and give it `+3 levels`. |
| Witch of Ravishment | Get a level 1 copy of a random creature in your opponent's hand. The victim can only be played after the copy is discarded. |
| Rape Witch | Take a random creature from your opponent. At the end of your next turn, it returns to them at level 1. |
| S | Name a Tribe. If your opponent has none in hand, draw 2 cards. If they do, discard a random card instead. |
| Joringel's Witch | Turn a random creature in your opponent's hand into a statue; it cannot be played. Transform a Witch in their hand into a Songbird, if present. Then, shuffle a nettle leaf into the deck. When drawn, reset the cooldown of all creatures in hand, unfreeze any statues, and transform the Songbird to its original form, if present. |
| The Ugly Witchling | While this is in your hand, your cards lose `-1 level` each turn. If this witch escapes, give all cards in your hand `+2 levels`. |
| S | Turn a random creature in your hand into a `Skeleton {3}`. |
| Glacial Witch | _Winter Stasis_: Freeze both players' hands. Cards affected cannot have their level changed ever again. |
| Skinwalker | Each turn this witch is in your hand, transform into a random creature. If a shapeshifted creature wins its duel, YOU damage the enemy Empire. If it loses, transform back into Skinwalker before taking damage. |
| Witch Wendigo | Discard the weakest creature in your hand. Damage the enemy Empire equal to its `Base Strength + 2`. |
| S | Eat the weakest creature in your opponent's hand. They take damage from its Base Strength. |
| S | Swap the highest-level creature in each player's hand. |
| Witch of Sirens | If your opponent loses the next duel, they take double damage. |
| Xeno-Witch | Randomize the Tribes of all creatures in both players' hands. |
| Witch of the Nile | Each player discards their lowest-level creature. |
| Witchmandias | Reduce both Empires to 15 HP if above it. |
| Witchley | Draw a card. If it's a Wolf or a Giant, give it `+4 levels`. |
| White Witch | _Eternal Winter_: Remove all `Fire` cards from the deck. Whenever a card is drawn, give it `Cooldown 2`. |
| Pack Witch | All Wolves in your hand become the same Power Type as your strongest. |
| S | Shuffle 6 Giants into the deck. Discard cards from the deck until there is a Giant on top. |
| Jungle Witch | Shuffle 6 random creatures into the deck. |
| It's a Wonderful Witch | Replace your hand with an alternate image. Your Witch cards are rerolled based on rarity and your creatures are given new Power Types and levels. The next duel you lose causes your cards to reset to their original versions. |
| Leviathan's Witch | _ALL_ creatures with Base Strength 5 or higher gain `+3 levels`, but deal double damage to their owner if they lose. |
| Ariadne's Witch | At the start of the next 3 turns, choose the rules of the proceeding duel: <br>Fight by level only. <br>Fight by Power Type only. <br>Fight by Base Strength only. |
| Set's Witch | Destroy the strongest creature in your opponent's hand. It is split into 3 pieces and shuffled into the deck. Only your opponent may draw the pieces, and they cannot be played individually. When all 3 pieces are assembled, resurrect the creature with `+3 levels` for your opponent. |
| Redcap Witch | _The Blood Curse_: Whenever you win a duel give your creatures `+1 levels`. Whenever you lose a duel, give your creatures `-1 levels`. When a creature would become level 0, instead it damages your Empire and flees. |
| Witch Domovoi | While this is in your hand and you have fewer than 5 cards, your Empire takes 2 less damage from duels. If you have more than 5 cards, take 2 more damage instead. |
| Willow The Witch | Force your opponent to reveal a card. If it is `Fire` or `Holy`, they must play it next turn. |
| Marduk's Witch | Slay and discard a Dragon in your hand to shuffle 21 new creatures into the deck. |
| Horned Witch | All creatures in your hand gain `+1 level` for each different Tribe you control. |
| Witch of Yule | Heal both Empires for 5 HP. Both player's exchange a random creature in their hand. |
| Krampus' Witch | If your opponent has more cards than you, slap them with rusty chains for 3 damage, and summon Krampus to stuff 2 of their cards in a sack which is subsequently dragged to hell. |
| Sonic Broomwitch | If this witch escapes, play the top card of the deck. If the card is a Witch, immediately cast its effect as Sonic Broomwitch. If it's a creature, it attacks the enemy Empire and flees. |
| S | If this witch is level 12 or higher, heal your Empire for 12 HP. |
| Wicarus | Choose a creature in your hand to give `+3 levels`. If it loses its duel, you also take damage equal to its full level. |
| Dover Witch | Each player discards their highest-level card. |
| Witchicus Rex | Destroy the strongest creature in your hand. Then take your opponent's strongest creature as your own. |
| S | Give all creatures in your hand `+3 levels`. The next time you win a duel, take the damage instead of your opponent. |
| Witch of Freyr | This witch plays the weakest creature in your hand that can beat the enemy in duel. If none exist, this witch fights instead. |
| Freyja's Witch | Give 4 creatures in the enemy hand `+1 level`. Then add the Brisingamen to your hand: Your cards duel with `+2 power`. After you lose 4 duels, give the Brisingamen to your opponent. |
| Calypso's Witch | Discard your hand. While you have two or less creatures in hand, they have `+5 levels`. |
| S | If you've defeated a Dragon in duel this game, add a random Dragon to your hand. |
| Susanoo's Witch | Both players shuffle their hand into the deck then draws new cards. |
| Miss Witchster | Your opponent discards a random card. If it was a Witch, give another card a permanent detention (it is Frozen). |
| Bondage Witch | Enslave a random creature from your opponent's hand. It may not be played. |
| Enslaved Witch | This card is Disabled. Other witches that enter your hand become Enslaved Witches too. Once your holding a Witch Rally, free the slaves! They become random Sinful Witches. |
| Nightmare Witch | This witch has the `Nightmare` Power Type. While in hand, `Nightmare` creatures have `+1 level` and `Holy` creatures have `-2 levels`. |
| Holy Witch | This witch has the `Holy` Power Type. While in hand, `Holy` creatures have `+1 level` and `Ancient` creatures have `-2 levels`. |
| Ancient Witch | This witch has the `Ancient` Power Type. While in hand, `Ancient` creatures have `+1 level` and `Fire` creatures have `-2 levels`. |
| Fire Witch | This witch has the `Fire` Power Type. While in hand, `Fire` creatures have `+1 level` and `Nightmare` creatures have `-2 levels`. |
| S | Choose a creature in your hand. It gets a random new Power Type. |
| Falsely Imprisoned Witch | This witch starts with Cooldown 6. 
| Convicted Witch | If this witch dies, get a Poisoned Shank. When played, fight the enemy barehanded. Take damage equal to the enemy's Base Strength then poison it, dealing 4 damage to the enemy Empire and destroying their card. |
| Carnal Witch | Choose a creature in your hand. It gains `+3 levels`. If it isn't played on your next turn it leaves in frustration. If it loses its next duel, discard a random card. |
| Witch of Banishment | Choose up to two cards in your hand to banish from the game. Give your creatures `+1 level` for each one discarded. |
| S | Creatures in both player's hands evolve into the next Tribe of greater Base Strength than it. |
| S | Look at 3 creatures that have been defeated in duel this game. Choose one to bring back to your hand. |
| Jurassic Witch | Pirates and Vampires in the deck are replaced with random Dragons or Giants. All Giants and Dragons in the deck gain `+2 levels`. |
| Fruit Basket Witch | Add a Pineapple that heals 6 HP when played to your hand. |
| Witchrend | Choose a creature in your hand to split into two Lvl.1 creatures of the same Tribe. |
| Familiar Witch | Get a random creature from the same Tribe as your most recently played creature. |
| Albatross Witch | If this witch dies, curse your opponent. _Heavy Burden_: While cursed you can no longer draw cards. The curse is lifted when you lose a duel or your hand is empty. |
| Mortal Witch | Cards battle using only their Base Strength for the next duel. Levels and Power Types are ignored. |
| S | For the rest of the game, your creatures have `+3 power` against creatures from the same Tribe. |
| The Great Imitator | While in hand, the very next card your opponent draws is secretly transformed into The Great Imitator, but theirs is fake. If the Fake Imitator is played, a random card in hand is paralyzed (Frozen). If the Real Imitator is played, reveal your opponent's entire hand and steal the "Fake" card back; it becomes a random Sinful Witch in your hand. If the Fake Imitator is not present, restore 12 HP to your Empire instead. |
| False Witch | `Holy` creatures in both hands are misled into Purgatory. Shuffle them back into the deck; they lose their holiness and become Lost Souls (no Power Type or Tribe). Creatures have `-2 power` for each Lost Soul in hand. |
| Summoning Witch | Choose to get a random creature from one of 3 Tribes. |
| S | Both player's discard 2 cards. You get to choose yours. |
| Trumpeting Witch | Sound the horns. Both players reveal their hand. Each `Holy` creature revealed deals 2 damage to its holder's Empire. |
| Continental Witch | Each player choose a creature in hand. Those creatures exchange Tribe and Power Type, but keep their original level and base strength. |
| Tectonic Witch | Permanently swap the base strengths of two Tribes of your choice. |
| Tectonic Witch | All creatures in both hands gain `+1 level`. Any creatures exceeding level 7 are immediately discarded. |
| Seismic Witch | Each player discards their strongest creature dealing its base strength to their Empire. |
| Evolutionary Witch | Creatures in each hand evolve to the next highest Tribe. Dragons ascend to the aether and are discarded. |
| Colossal Witch | `Ancient` creatures with a base strength of 5 or higher in each hand gain `+3 levels`. |
| Colossal Witch | _Titanism_: All Giants in your hand gain `+5 levels` and their base strength is reduced to 0. |
| Witchosaurus | Add a `Lvl.5 Ancient Dinosaur {6}` to your hand. If it ever loses a duel, discard your entire hand. |
| Witchosaurus | _Extinction Event_: Destroy all creatures in both hands that are level 4 or higher. |
| Abominable Witch | Fuse two creatures in your hand. They become one creature with: <br>- Combined levels <br>- Highest base strength <br>No Tribe or Power Type |
| The Witch That Keeps on Witching | The next 3 Witch cards played (by any player) cast their effects twice. |
| Bestialic Witch | Choose a creature in your hand. Get a random level 1 copy of it with a random witch effect. It duels like a creature but casts its effect at the start of battle. |
| S | If you have taken no damage the past 3 turns, draw 2 cards. |
| Blood Witch | For the rest of the game, your Vampires heal your Empire by their level when they win a duel. |
| Mixed-Race Witch | This witch has the effects of two Sacred Witches. |
| S | Combine all remaining witches in your hand into a Supreme Witch (taking on the highest level). It casts the effects of each the witches when played. |
| Capone's Witch | _Tax Evasion_: The next time you lose a duel, you take no damage. However, you must discard your highest-level card as "legal fees." |
| Twelfth Witch | Swap the Power Types of every creature in your hand to align with the Power Types of creature's in your opponent's hand. |
| Twelfth Witch | Swap hands with your opponent (next turn only). |
| Claudius' Witch | _Poison in the Ear_: While this is in your hand, you can look at the card your opponent draws each turn. |
| Claudius' Witch | The next duel is tainted. Both Empires take damage from its outcome. |
| Polonius' Witch | Reveal your opponent's hand. You choose a card for them to discard. |
| Trumpeting Witch | _False Rapture_: All `Holy` creatures in both hands are played immediately in a "False Duel." No damage is dealt, but they are all discarded. "Is it time? No." |
| S | _Burning Passion_: For the rest of the game, whenever you draw a `Fire` card, draw another card. |
| S | For the rest of the game, whenever you defeat a `Nightmare` card, give your `Fire` creatures `+1 level`. |
| The Last Witch | If there are no witches left in the deck or either player's hand, deal 10 damage to the enemy Empire. |
| Harvest Witch | Draw 3 cards. At the end of your next turn, discard 2 cards at random. |
| S | Give your creatures `+1 level` for each different Tribe you control. |
| Genocidal Witch | Choose a Tribe. All creatures in the deck sharing that Tribe are executed and discarded. |
| El Charro Negro's Witch | Make bargain: Gain +10 HP now. Every duel you lose from now on deals an extra 3 damage to your Empire. |
| El Charro Negro's Witch | Offer a deal: You choose one card to give your opponent. If they refuse the gift, they take 6 damage. |
| El Charro Negro's Witch | Offer a deal: Your opponent may give you a creature from their hand. If they refuse, the next time they lose a duel, they take +4 damage. |
| S | Choose a creature in your hand to discard. Heal your Empire for its level. |
| S | Discard a random card. Gain HP equal to x2 its level. If you discarded a `Nightmare` creature, draw a card. |
| Columbus Witch | Look at the top 5 cards of the deck. Choose one to add to your hand. The others are added to the bottom of the deck. |
| Banquo's Witch | If this witch is defeated, the enemy creature gains a _Guilty Conscience_: Each turn the guilty creature remains in hand, the enemy Empire takes 3 damage. |
| The Scarlet Witch | "A" creature in the opponent's hand becomes despicable. Give it cooldown 5 and publicly shame such creature. While in hand, no Rallies can be formed and creatures are no longer Enhanced. If the despicable creature wins a duel, you discard a card. |
| Yin Yang Witch | Choose to draw a card or discard one. Your opponent does the opposite. |
| Explosive Witch | _Timer of Destruction_: After a player loses 3 duels, their Empire takes 5 damage and the timer is removed. |
| Witchlet | If you are holding the fewest cards, gain 5 HP and draw a card. If Witchlet survives its duel, give a creature in your hand `+3 level`. |
| S | For the rest of the game, when you draw at the start of your turn, you may decide to discard the card and draw a new one. |
| Pinata Witch | If this witch dies, add 5 random small creatures to the top of the deck. Small creatures have base strength 3 or less. |
| S | _Endless Toil_: Mark a random creature in your opponent's hand. If they play it and lose, it returns to hand with `-1 level` and cooldown 3. |
| S | S: Give all Witches in your hand `+5 levels`. Witches that enter your hand gain `+2 levels`. |
| S | Add two random level 1 Skeletons to your hand. They gain `+1 level` for each Vampire you have. |
| S | Reveal the largest creature in both hands. If yours is bigger, your hand gains `+1 level`. Otherwise, your opponent's hand does. |
| S | Reveal a random creature with the greatest base strength from each hand. If they come from the same Tribe, destroy them both. |
| S | Reveal the weakest creature in your opponent's hand. You may choose to swap your weakest creature with it. |
| Emancipating Witch | Free all Frozen cards in your hand and reset your cooldowns. |
| S | Draw a `Nightmare` creature from the deck. It gains `-2 level`. |
| S | Reveal a random creature in your opponent's hand and light it on fire. It becomes the `Fire` type, but is discarded if not played next turn. |
| S | Choose a creature in your hand to become `Holy`. |
| S | If you're holding an Enhanced `Ancient` creature. Draw an `Ancient` creature from the deck. |
| S | The top 5 cards on the deck become `Fire`. Any Witches are discarded instead. |
| S | Turn the top 9 cards cards on the deck into `Nightmare` types. |
| Merciful Witch | If the weakest creature in your hand is level 1, give it `+3 levels`. If it is `Holy`, give it an additional `+5 levels`. |
| S | If the strongest creature in your hand is `Ancient`, give it `+5 levels`. |
| Oscar the Witch | Whenever a card is discarded from your hand or the deck, give your hand `+1 level` and gain +1 HP. |
| Oscar the Witch | Gain +2 HP for every card that was discarded or destroyed this game. |
| Reincarnating Witch | _Cycle of Life_: Your next creature to lose in battle returns to your hand with the next Tribe in the ladder of base strengths. It has a new level and Power Type. Dragons go back to Serpents. |
| Witcher in the Rye | Save a random small creature (base strength 0-3) in your opponent's hand. Add it to your hand with `+1 level`. |
| Summoning Witch | Choose a Tribe. Add a random creature from that Tribe to your hand. |
| S | Give the player whose hand has the greater total level +9 HP. |
| S | If your remaining hand has total level 12 or less, double the level of cards in your hand. |
| S | Choose two creatures in your hand. They each gain the other's Tribe. |
| Witch-atter, The Mad | Both players discard their hand and redraw the same number of cards. Randomly assign cooldown 0-3 to each. |
| Witchatter, The Mad | Both players discard their hand and draw 6 new cards. <br>Players no longer draw cards at the start of each turn. <br>Instead, when a player's hand is empty, they draw 6 new cards from the deck. <br>Mayhem occurs when a player's hand is empty and there are no cards left in the deck to draw from. |



\===================\
\    Working On 	\
\===================\

| Chaotic Witch |
| Wallowing Witch | 
| Necrotic Witch |
| Grim Witch |
| Sepulchrul Witch |
| Graveyard Witch |
| The Witch of Wallstreet |
| Witchlock |
| The Witcherwocky | 
| The Tin Witch |
| Little Witchard |
| Choir Witch | S: While you control all 4 Power Types, your cards duel with `+2 power`. |
| Half-Bred Witch |
| Half-Blood Witch | Halve the base strength of all creatures in both hands (rounded down). Gain HP equal to the total lost.
| Regressive Witch |
| Master Crone |
| Apostate Witch | Discard your `Holy` creatures. Your other creatures gain `+1 level`. |
| Syncretistic Witch | Choose two creatures in your hand. They each gain the other's Power Type. |
| Tambourine Witch |
| Ever-Present Sea Witch |
| Bouquet Witch | Discard 3 random cards and heal 2 HP for each Tribe lost. Then draw 3 new cards. |
| Sentimental Witch |
| Witch of Sorrows |
| Degenerating Witch |
| Millstone Witch |
| Bo Weevah Witch |
| Outlaw Witch |



| Amabel Bloundel's Witch |
| Fallen Witch |
| Witchalorum | Rewrite the rules of the next duel. <br>Choose two: <br>- Ignore Base Strength <br>- Ignore Level <br>- Ignore Power Types <br>Damage is dealt to the winner instead
| Seuss Witch | Replace all creatures in both hands with rhyming counterparts: <br>- Same base strength <br>- Random new Tribe <br>- Random Power Type <br>- Levels rerolled (1-6)
| Von Witch |
| Evangelical Witch |
| Penchant Witch |
| Affectionate Witch | Choose a creature in your hand. While it stays in hand, it gains `+1 level` at the end of each turn. You must play it before your other creatures. |
| Silver Witch |
| Archaic Witch |
| Gingerbread Witch |
| Trick 'r Witch |
| Witchy Wonka | Add 5 Golden Tickets to the deck. <br>Whenever a ticketed creature is played, its owner chooses: Gain 5 HP or Give all creatures in your hand `+1 level`. <br>When the last ticket is revealed, the player who found more Golden Tickets discards their hand. |
| Forbidden Hag |
| Witch McConnell |
| Thousand-Yard Witch |
| No Man's Witch |
| Trench Witch |
| Blitzkrieg Witch |
| Witchatter, The Mad |
| Wichita Witch |
| Nikola Witchla |
| Perpetual Time Witch |
| Witchabel Lee |
| Crusader Witch |
| Regal Witch |
| Wolf King Witch |
| Herculean Witch |
| Heretic Witch |
| Side Witch |
| Hecate's Three |
| Bubonic Witch |
| Indignified Witch |
| Perverted Witch |
| Paraphilic Witch |
| Etymological Witch |
| Nude Witch |
| Taboo Witch |
| Death Witch |
| Pork Witch |
| Prohabitionist Witch |

| The Lost Witch |
| Forbidden Hag |
| Culvert Witch |
| Archwitch |
| Bestialic Witch |
| Beastie Witch |
| Maiden Witch |
| Gossip Witch |
| Premarital Witch |
| Suicidal Witch |
| Secular Witch |
| Necro Witch |
| Islamophobic Witch |
| Slave Witch |
| Rape Witch |
| Witchlet |
| Joringel's Witch |
| White Witch |
| The Witch of Mithras |
| Witchibitionist |
| Bone Witch |
| Metal Witch |
| Lamia Witch |
| Secret Witch |
| Witch Hunter |
| The Witchler |
| Witchitaur |
| Witch of Sirens |
| Lamia Witch |
| Witchthazar |
| Witchicles |
| Witch Wendigo |
| Snow Witch |
| Geppetto's Witch |
| The Ugly Witchling |
| Witchmandius |
| Song of Witchself |
| It's a Wonderful Witch |
| Witchles Dickens |
| Seth's Witch |
| Witch of the Nile |
| Witchley |
| Xeno-Witch |
| Witchmere the Grey |
| Lich Witch |
| Sphinx's Witch |
| Blue Witchell |
| Witchaeus |
| The Witch of Jericho |
| Khonsu's Witch |
| Set's Witch |
| Glitch Witch |
| Witchrend |
| Nymph Witch |
| Sonic Broomwitch |
| Dover Witch |
| Witchicus Rex |
| Wicarus |
| Leviathan's Witch |
| Redcap Witch |
| Witch Domovoi |
| Witch of Yule |
| The Oak King's Witch |
| The Holly King's Witch |
| Krampus' Witch |
| Accursed Witch |
| Fellaro's Witch |
| Fellatio Witch |
| Irrumo's Witch |
| Willow The Witch |
| Sunasoo's Witch |
| Freyja's Witch |
| Worried Witch |
| Horned Witch |
| Carnal Witch |
| Greymalkin Witch |
| Orbital Witch |
| Jurassic Witch |
| Super Witch |
| Capone's Witch |
| Raven Witch |
| Alcatraz Witch |
| Ophelia's Witch |
| Banquo's Witch |
| Twelfth Witch |
| Claudius' Witch |
| Polonius' Witch |
| Albatross Witch |
| Mortal Witch |
| Flesh Witch |
| Beowulf's Witch |
| The Witch Can't Help It |
| Trumpeting Witch |
| Divine Witch |
| Continental Witch |
| Tectonic Witch |
| Seismic Witch |
| Colossal Witch |
| Witchosaurus |
| Abominable Witch |
| La Llorona Witch |
| El Charro Negro's Witch |
| The Witch That Keeps on Witching |
| Colombus Witch |
| The Great Imitator's Witch |
| Witchlet |
| The Scarlet Letter Witch |
| Robin Witch |
| Toymaker Witch |
| False Witch |
| Ambiguous Witch |
| Vampire Hunter's Witch |
| Ascetic Witch |
| Witch of Chastity |
| Lolita's Witch | _Forbidden Fruit_: |
| Humbert's Witch |
| Flagellant Witch |
| Tenno Heika's Witch |
| Erotic Witch |
| Quiet Gazer's Witch |
| Odax's Witch |
| Mule Witch |
| Phrayme's Witch |
| Klepto Witch |
| Haemato's Witch |
| Somnophilic Witch |
| Crack Witch |
| Swarm Witch |
| Temno's Witch |
| Frankenstein's Witch | 
| Actirastic Witch |
| Agalmatophilic Witch |
| Agrexophilic Witch |
| Asphyxia's Witch |
| Convicted Witch | 
| Vampiric Witch |
| Rapier Witch |
| Witchnapper |
| Biaste's Witch |
| Plato's Witch |
| Witch of Gyges |
| Bricked Witch |
| Elektra's Witch |
| Cenophilic Witch |
| Engorged Witch |
| Katoptron's Witch | _Magic Mirror_: |
| Teleios' Witch |
| Dakno's Witch |
| Hieros' Witch |
| Sekhmet's Witch | _The Wrath of Ra_: |
| Kukulkan's Witch |
| Baalham's Witch |
| Idolatrous Witch |
| Onan's Witch |
| Falsely Imprisoned Witch |
| Shadow Witch |
| Epiales' Witch |
| Pavlov's Witch |
| Re-educational Witch |
| Institutionalized Witch |
| Academic Witch |
| Brainwashed Witch |
| Reverse Polarity Witch |
| Schrodinger's Witch |
| Paradoxical Witch |
| Zeno's Witch |
| Achille's Witch |
| Prometheus' Witch |
| Sisyphean Witch |
| Agean Witch |
| Witch of Tantalus |
| Bellerophon's Witch |
| Milgaard's Witch |
| Potiphar's Witch |
| Eleusinian Witch |
| Afflicted Witch |
| Infected Witch |
| Wiccan, The Wise |
| Persephone's Witch |
| Mirror Master's Witch |
| Modravh's Witch |
| Newcastle's Witch |
| Grotto Witch |
| Ancestral Witch |
| The Great Leveler's Witch |
| Barbaric Witch |
| Terrorist's Witch |
| Halal Witch |
| Neglected Witch |
| Waiflike Witch |
| The Witch With Two Backs |
| The Emporer's New Witch |
| Mother Stork's Witch |
| Dino's Witch |
| Shehitah's Witch |
| New Year's Witch |
| Eon Witch |
| Miser's Witch |
| Snow Miser's Witch |
| Heat Miser's Witch |
| Jolly Witch |
| Holly Witch |
| Didactic Witch |
| Railroad Witch |
| King Cole's Old Witch |
| Hyperion's Witch |
| Hesiod's Witch |
| Father Time's Witch |
| Priestly Witch |
| Mother Nature's Witch |
| Nightmare Witch |
| Coven in the Oven |
| Holy Night's Witch |
| Age-Old Witch |
| Witch of Yore |
| Runic Witch |
| Kabal Witch |
| Seraphim Witch |
| Archangel's Witch |
| Witch of the Beasts and the Children |
| Whispering Witch |
| Foraging Witch |
| Backbiting Witch |
| Christian Witch |
| Toc H Witch |
| Non-Consenting Witch |
| Philomela's Witch |
| Urtica's Witch |
| Steadfast Witch |
| Templar Witch |
| Wood Witch |
| Orpheus' Witch |
| Ariadne's Witch |
| Witch Kikimora |
| Living Light Witch |
| Stingy Jack's Witch |
| Ptah's Witch |
| Marduk's Witch |
| Indecent Witch |
| Irresistible Witch |
| Witch of Freyr |
| Calypso's Witch |
| Witch of Tao |
| Wu Wei Witch |
| Disciplinary Witch |
| Mr. Witch |
| Master Witch |
| Tiro Witch |
| Centurion Witch |
| Testudo Witch |
| Primus Pilus Witch |
| Klan Witch |
| Minstrel Witch |
| Anhedonic Witch |
| Xulub's Witch |
| Self-Loathing Witch |
| Oiko's Witch |
| Gooey Witch |
| The Morning Witch |
| Tortured Witch |
| Rapture Witch |
| Shackled Witch |
| Witch Trapper |
| Where's Witch? |
| Wild Witch |
| Giant Witch |
| Brothel Keeping Witch |
| Genocidal Witch |
| Fairytale Witch |
| Puritan Witch |
| Harlot Witch |
| Sychopant's Witch |
| Explosive Witch |
| Balloon Witch |
| Wind Chime Witch |
| Witch Fawkes |
| Straw Witch |
| The Wicker Witch |
| Patient Witch |
| Witchitaur |
| Song of Witchself |
| Witchles Dickens |
| Geppetto's Witch |
| Seth's Witch |
| Witchibitionist |
| Balthazar's Witch |
| Witchicles |



| Divine Witch | If you're holding a `Holy` Rally, gain _Providence_: Your `Holy` creatures permanently heal your Empire by their level when they lose a duel. |
| S | If you're holding a `Fire` Rally, |
| S | If you're holding a `Nightmare` Rally, |
| S | If you're holding an `Ancient` Rally, |

| S | If you're holding an `Ancient` Rally, shuffle 12 `Ancient` creatures into the deck. Whenever you draw an `Ancient` creature, it gains `+3 levels`. |
| S | If you're holding a `Fire` Rally, for the rest of the game whenever your opponent loses a duel, they take an additional 2 damage. |
| S | If you're holding a `Nightmare` Rally, whenever you win a duel, discard a random card in your hand to destroy the top 3 cards of the deck. Any `Nightmare` creatures discarded give your opponent `-2 power` for the next duel. |
| Resolute Witch | _Unwavering Faith_: You're `Holy` creatures are no longer weak to `Nightmare` types. |
| S | _W_: You're `Ancient` creatures are twice as effective (+6 power) against `Fire` types. |

| Brewing Witch | Complete the recipe to get a Strange Brew that casts an effect related to its components. The ingredients are thrown into the cauldron and discarded. <br>- one Tribe <br>- one Power Type <br>- one level |




__Sinful Witches__ — Lvl. 7-9

- Sinful witches have mastered the forms of dark magick and dissent the laws governing sorcery. They are nasty beings who cast the most perilous effects, entirely transforming how the game is played.

| Name | Effect |
|------|--------|
| Cataclysmic Witch | Destroy half of the remaining deck (rounded up). |
| W | If you're holding 3 Giants, discard them and deal 10 damage to the enemy Empire. |
| W | If you're holding a Dragon of _each_ Power Type, destroy the enemy Empire. |
| Witch of Endor | _Prophecy of Doom:_ After 3 more turns have passed, all cards in your opponent's hand become *level 1*. |
| W | The Wolves in your opponent's hand become feral. <br>Discard each one, dealing damage equal to their level to the enemy empire. |
| W | _Call of the Ancients:_ Any `Ancient` creatures in your opponent's hand join yours instead. |
| Witch of Wrath | For the rest of the game, players take an extra 3 damage whenever they lose a duel. |
| Skeletor's Personal Witch | If the deck has no Skeletons left in it, get __Skeletor__. <br> Skeletor counts as a Lvl.9 Ancient Skeleton with a base strength of 7. After his duel, but before an Empire takes damage, swap Skeletor with a random Skeleton in hand (if present). It was an illusion! |
| The Beast's Witch | If you have 6 level 6 creatures in hand, obliterate the enemy Empire. |
| W | Shuffle the Four Horsemen//!!!!! |
| Lilith's Witch | For the rest of the game, cards *level 6+* refuse to be subservient and cannot be played. Instead, they lie in hand waiting to destroy your Empire! |
| Cannibalistic Witch | For the rest of the game, after you win a duel eat the enemy card and heal for its *base str*. |
| Richard Witchson | Start a "War on Witches." All Witch cards are banned from the game! |
| The Witch Who Stole Grinch | Choose to give Grinch to you or your opponent. Grinch is a level 6 creature with a base strength of 5, and no Power Type. While Grinch is in hand, any cards drawn enter his filthy sack. |
| The Witch of Tantalus | _The Eternal Thirst:_ For the rest of the game, whenever your opponent draws a card, they take 1 damage. |
| Witch of the Four Horsemen | 
| Baden's Witch | The next time you are about to lose a duel, switch the card played with the most powerful creature in hand. |
| Xartrath's Witch | 
| W | No player can lose until Mayhem. |
| Actaeon's Witch | Accidentally see a random witch in your opponent's hand. If you spot one, get a `White Stag {4}`. The next duel you lose causes the White Stag to damage your Empire and vanish. If you win your next 3 duels instead, the White Stag blesses your kingdom. <br>Blessing of the Stag: Every card you draw gains `+3 levels`. |
| Black Fly Witch | _The Pest from Hell_: The next time your opponent loses 3 duels in a row, all creature's in their hand damage them and flee. |

<br>

---

### Deck Structure

A 52-card deck is created as follows:

- 6 creatures leveled 1-6 from each creature group are added

	- This creates 6 &middot; 7 = 42 cards.

	__Ex.__
	```
	Lvl.1 Serpent
	Lvl.2 Serpent
	...
	Lvl.6 Serpent

	Repeat for Wolf, Skeleton, Pirate, Giant, Vampire, Dragon
	```

- Each creature is given a random __Power Type__

	__Ex.__ `Lvl.4 Ancient Vampire`

- 10 random Witch cards are added (based on their rarity $3:2:1$)

---

### Rallies

Creatures of all different kinds are dispersed in the deck … until they __Rally__ in your hand.

__Rally__ — If your hand contains __4 or more cards__ of the same __Tribe__ or __Power Type__, they gain `+2 levels` (__Enhanced__).

- New cards that share the rally trait automatically join and gain the buff.

- The buff applies __once per card__ and __persists permanently__ (even if your matching set drops below 4).

- __Double Rally__: A rally of both Tribe and Power Type gives `+6 levels` instead.

- __Witch Rally__: 4 Witch cards give the witches `+2 levels`.  
	Additionally, your first Witch Rally per game grants you a bonus Sinful Witch card.

__Ex.__

- 4 Wolves (of any __Power Types__)
- Wolf, Skeleton, Pirate, Vampire (all `Nightmare` __Power Type__)

---

### *MAYHEM!*

If the deck is fully drawn before either player loses, the creatures turn feral and mayhem ensues.

__Mayhem__ — Symmetric end-of-game effect that establishes a victor.

1. Witches flee.

1. Creatures remaining in hand damage their Empire equal to their Base Strength.

	- Any frozen creatures are freed first (can attack).

	- Enhanced creatures do not damage your Empire.

1. Whoever's Empire is less destroyed wins!

	- There may be a draw.
	- HP may become negative.
	
- Triggers _after_ the turn in which the final card was drawn.

	- One final duel takes place.

---

### Strategy Tips

Fuck-placeholder

---

### Text Formatting

In the game, cards will be represented as such:

	Lvl.X <Type> <Name> {b}

- Where `X` is the level of the card, and `b` is its base strength

__Ex.__

	Lvl.3 Fire Giant {5}



Rallies are denoted with a `!` after the Power Type or the Tribe to indicate the kind of Rally.

__Ex.__

	Lvl.2 Holy Wolf! {2}
	Lvl.6 Ancient! Skeleton {3}
	Lvl.4 Blind Witch! {3}

- A Tribe Rally of Wolves
- A Power Rally of `Ancient` types
- A Witch Rally

Cards that are on cooldown for `#` turns are marked with:

	Lvl.3 Nightmare Wolf {2}: (#)

__Ex.__

	Lvl.3 Nightmare Wolf {2}: (1)
	Lvl.4 Ancient Vampire {7}: (-)

- The Wolf can be played next turn
- The Vampire may _NEVER_ be played

Card upgrades are denoted by:

	Old Card → Upgraded Stat

__Ex.__

	Lvl.3 Fire Dragon {9} → Lvl.4
	Lvl.1 Nightmare Serpent → Dragon

---

## Setup

1. Install the required library

	```bash
	pip install cardlib
	```

1. Clone this repo

	```bash
	git clone 
	```

1. Run the script and play in the REPL

	```bash

	```