# Creature Wars

Take control of an empire and force creatures to duel against your enemy to conquer them!

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

> A creature's base strength represents the resources it costs your empire to summon. Therefore, when a stronger creature loses a fight, your empire takes more damage!

After the fight, both creatures are __discarded__.

- If the creatures have equal power, they each return to their player's hand and cannot be played on the next turn.

- When 2 creatures from the same Tribe duel, it becomes a _Tribal Clash!_

	__Tribal Clash__: The winner of the duel draws a card.

- When a creature with a type disadvantage wins its duel, you may encounter a strange figure within your Empire …

	__Bizarre Victory__: Get a random Witch card.

---

### Witch Cards

Besides the 7 tribes of creatures, there are also __Witch cards__.

Witches all …
- Have __3 base strength__
- Have __no Power Type__
- Don't duel in the normal way

Instead, when a Witch is played it first casts an __effect__ that changes the game. Then, the enemy creature fights the Witch. If it wins, you take damage equal to the Witch's base strength (3). Otherwise, nothing happens—the Witch wins the fight and flees from battle! Either way, the enemy creature is _not_ discarded, and returns to their hand without cooldown. If two Witch cards are played, they still duel and damage the losing empire, but none are returned to a player's hand.

The __effect__ a Witch casts can:

- Change the levels of creatures
- Change the Power Types of creatures
- Draw/discard cards for a player
- Modify Tribes
- Manipulate game mechanics
- Add new cards to the deck/hand

These effects may affect your hand, your opponent's hand, or _ALL_ cards wherever they are!

Witches may be good or bad for you depending on your hand, so hang on to your Witch cards and use them wisely.

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
| Invisible Witch | This witch cannot be attacked. |
| Angry Witch | If this witch loses its duel, discard a random card from your opponent's hand. |
| Magic Witch | Transform a card in your opponent's hand into a random __Serpent__. |
| Voodoo Witch | If this witch is killed, your opponent also takes damage but their's is doubled. |
| Greedy Witch | Draw 2 cards. |
| Which Witch | Become a random Witch and cast its effect at the start of the duel. |
| Witcheroo | Swap hands with your opponent. |
| Kind Witch | Give creatures in both players' hands `+1 levels`. |
| Cocksure Witch | If this witch wins its duel, draw a card. Otherwise, your opponent does. |
| Flamboyant Witch | Representation from the underworld. |
| Envious Witch | Get a copy of the strongest (`base str`, `level`) creature in your opponent's hand. |
| Cursed Witch | Each turn this is in your hand, take 1 damage. |
| Sick Witch | If this witch survives its duel, turn all witches in your opponent's hand into __Sick Witches__. |
| Sacrificial Witch | If this witch dies, give all creatures in your hand `+2 levels`. |
| Snake-Eyed Witch | If you're holding at least 2 Serpents, draw a card. |
| The Witch Collector | Your opponent takes 3 damage, you gain 3 health. |
| Wet Witch | Each player doesn't ask… |
| Flying Witch | If this witch escapes, add 2 random Sacred Witch cards to your hand. |
| Wilbur Witch | If this witch escapes, get Orville Witch. If he already escaped, get a Flying Witch instead. |
| Orville Witch | If this witch escapes, get Wilbur Witch. If he already escaped, get a Flying Witch instead. |
| The Early Witch | If you play this card before turn 7, get 3 random Serpents. |
| Pick a Witch | Choose to keep 1 of 3 random Witch cards. <br>"… Any Witch!"|
| Witch in Time | If this witch survives, the next card you play has `+3 power`. |
| Premature Witch | At the start of each turn, there is a *50% chance* Premature Witch will spring into action. ;) |
| Slumbering Witch | This witch cannot be played until you have formed a Rally. |
| McWitch | Restore `4 HP` to your Empire and get a random `Lvl.1` creature with a `base str` of 4 or less. <br>"I'm loving it!" |
| Jittery Witch |
| Mundane Witch |


</details>
<br>

__Sacred Witches__ — Lvl. 4-6

- Sacred Witches are honorable and highly-respected witches. They have greater control of their magic and cast more powerful, often symmetric, effects. However, if used at the right time these Witches can serve to benefit the caster greater.

| Name | Effect |
|------|--------|
| Witch of Despair | Both players discard their entire hand. |
| Witch of the Hesperus | __ALL__ Pirates are drown and replaced with __Phantoms__. <br>Phantoms lose 2 base strength but gain `+5 levels`, and have no Power Type. |
| Vengeful Witch | If this Witch loses its duel, gain a __Primordial Butterfly__. |
| Moon Charm Witch | Transform _ALL_ Wolves into __Werewolves__. They now have a base strength of 8 and are all `Nightmare` types. |
| Prophetic Witch | See your opponent's hand. |
| Shifting Witch | Become an exact copy of the opponent's card at the start of the duel. |
| Democratic Witch | Disband any __Rallies__ in your opponent's hand. Those cards cannot be used in future Rallies. |
| Scary Witch | Turn the Power Types of creatures in your opponent's hand into `Nightmare`. Any `Holy` creatures are discarded instead. |
| Frost Witch | Remove all `Fire` creatures from each player's hand. |
| Hectic Witch | Shuffle 15 more Witch cards into the deck. |
| Chaotic Witch |
| Wicked Witch | After this Witch dies or flees, give a random card in your hand its *enchanted ring*: *+2 levels*. When a card with the *enchanted ring* is defeated in duel, give it to a random card in the victor's hand. |
| Witch of the Hallowed Circle | 
| Wallowing Witch | 
| Summoning Witch | 
| Necrotic Witch |
| S | Serpents become venomous this game; they will always win their duel. |
| Grim Witch | 
| Feigglehorne's Witch | Send your opponent's 2 weakest (*base str*) creatures to the circus; they won't be back. |
| Foreboding Witch | If this Witch dies, add 2 random Wolves to your hand. |
| Lusting Witch | Summon the largest (*base str*) creature from your hand to "battle" the smallest creature in your opponent's hand. You take damage from the small one and your opponent takes damage from the big one, equal to their base strengths. The Lusting Witch watches… |
| Sun Witch | Shuffle `Nightmare` and Witch cards in each player's hand back into the deck. `Fire` creatures in both hands get `+3 levels`, but explode in 2 turns if left unplayed, dealing their `base str` to the holder's Empire. |
| Gluttonous Witch | Both player's increase their Empire's health by 20 HP. |
| Witch of Slothing | Discourage 2 cards in your opponent's hand. They can no longer be played or used in Rallies. |
| Proud Witch | If this Witch escapes, the next time your opponent loses a duel they take double the damage. |
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
| The High Witch | The next card played by your opponent has *+3 levels*, but they take __double damage__ from it if it loses. |
| Shady Witch | "Wanna make a deal…?" <br>Give your opponent the most powerful creature from your hand. You take their least powerful creature in return. If they don't play their gift next turn, it becomes defective (*level 1*)! |
| Questing Witch | If your empire has slain a creature from every Kinship, choose a potion to drink: <br><br>Potion of Deception – discard your 3 most powerful creatures <br>Potion of Ferocity – all creatures in you hand gain *+3 levels* <br>Potion of Endurance – your Empire gains *+15 HP* |
| Berserker Witch | On the next duel, the losing Empire also takes damage from the winning card's level. |
| Pandora's Witch | Cast the effects of all Witches in your opponent's hand for them. Those witches flee afterwards. |
| Odd Witch | Both players discard all even-leveled cards in hand. |
| Witch of the Firehawks | Set your hand ablaze. All creatures you hold become `Fire` Power Types; `Nightmare` and Witch cards are destroyed. |
| Talismanic Witch | Cast a protective ward. The next time your Empire takes damage, only take half (rounded down). |
| Chthonic Witch | Add the last creature that was slain to your hand, it has *-1 level*. |
| Necromancing Witch | Resurrect all Skeleton creatures that have died in battle. Give them *+3 levels* and add them to your hand. |
| Sepulchrul Witch | Res
| Graveyard Witch | 
| Circe's Witch | Transform Pirates in each player's hand into Wolves. |
| Angitia's Witch | Eat all Serpents in your hand. For each discarded, your Empire gains *+5 HP*. |
| Minerva's Witch | Choose to trade your 2 least powerful creatures with the opponent's 2 most powerful creatures. Or, your 2 most powerful creatures for the opponent's 2 least powerful creatures. |
| Succubus' Witch | Discard a random `Nightmare` in your hand to summon a succubus that desecrates an enemy creature. The victim loses *-3 levels* and a Lvl.1 *cambion* is added to your opponent's hand. The cambion has the same *base str* and Power Type as the victim, but deals double damage to their Empire. |
| Sin-Eater Witch | The next time one of your creatures dies, a random creature in your hand absorbs its transgressions and you take no damage. That creature becomes an outcast and can no longer be played. |
| Charlotte's Witch | Trap a card in your opponent's hand in a web. It can never be played. |
| The Sand Witch | Spell the air with sleep sand. For the rest of the game, `Nightmare` creatures have an additional 2 power when dueling. |
| Green Witch | The player with less cards draws cards until both players share the same hand size. |
| Reincarnating Witch | 
| Wiccan Little | !!play on chicken little!! Whenever Wiccan Little panics, the sky __might__ fall. |
| Coven-Calling Witch | Shuffle 13 Sacred Witches into the deck. |
| Wraith Witch | If this witch dies, add a Wraith to your hand; it deals 3 damage to the enemy Empire when played and immediately disappears. Enemy creatures facing the Wraith are sent back to hand with a 1-turn cooldown. |
| Witcher in the Rye | 
| The Witch of Wallstreet |
| Witchlock | 
| Lenore's Witch | Choose from 3 creatures in your opponent's hand to send to the quiet fields. In its place, a Raven is fixed. The Raven cannot be played, but pecks your opponent for 2 damage when they are reminded of their beloved. |
| The Witcherwocky | 
| The Tin Witch |
| Little Witchard |
| Oscar the Witch |
| Von Witch | 
| Trick or Witch |
| Witchy Wonka |
| Forbidden Hag |
| Witch McConnell |
| Witchatter, The Mad |
| Wichita Witch |
| Nikola Witchla |
| Witchabel Lee |
| The Witch of the Cumaean Sibyl | _The Scattered Prophecies:_ Your opponent reveals their hand and shuffles 3 cards back into the deck. They then draw 3 new ones. |
| Medusa's Witch | If this witch lives, petrify the enemy card; it cannot be played or participate in Rallies. |
| Crusader Witch |
| Chiquita Witch | While this is in your hand, at the end of every turn, give creatures in your hand *+1 levels*. Any creatures level 5 or more turn sour and attack you, then flee. |
| Midas Witch | For the rest of the game, cards that enter your hand gain *+2 base str*. |
| Santa Witch | Both player gets 2 wrapped gifts! Inside each present may be a random creature or a lump of coal. You get to peek at two of them. "Merry Witchmas!" |
| Regal Witch |
| Wolf King Witch |
| Herculean Witch |
| David's Witch | Less powerful creatures now win against Giants, but higher-powered creatures lose to them. |
| Goliath Witch | The weaker creature will win the next duel. |
| S | Sound the horn of Juno: Giants are permanently twice as strong against and susceptible to type advantages. |
| Heretic Witch |
| S | Choose from 3 enemy creatures. Pick one to free from its sinful cage of flesh. |
| Side Witch |
| Hecate's Three |
| Bubonic Witch |
| Buried Witch | If you control a Pirate rally, get 3 Cannonballs. When played, they do 5 damage to the enemy Empire. You still take damage from creatures they play. |
| Skeletal Witch | If you control an Enhanced Skeleton, skellify all other creatures in your hand. They now belong to the Skeleton Tribe and only deal 3 damage to your empire, despite their original base _str_. |
| Black Witch |
| S | Shuffle every Skeleton that has died this game back into the deck with *+1 level*. |
| S | Steal a random Witch card in your opponents hand, if one is present. |
| S | For the remainder of the game, whenever a creature with level 6+ wins a duel, it also damages the Empire who sent it. |
| Benevolent Witch | Give a random creature from each Tribe in your hand `+2 levels`. |
| Prehistoric Witch | Make all creatures in your hand `Ancient`. |


| Indignified Witch |
| Perverted Witch |
| Paraphillic Witch |
| Etymological Witch |
| Nude Witch |
| Taboo Witch |
| Death Witch |
| Pork Witch |
| Prohabitionist Witch |
| The Lost Witch |
| Forbidden Hag |
| Transcendental Witch |
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
| S | Transform Serpents in both player's hand into random Dragons. |
| Haughty Witch | If this witch is a greater level than its challenger, take a random card from the opponent. |
| Haggel & Witchel | The next player to draw a Witch card takes 12 damage. Both players draw cards until they're holding 8. |
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
| Storytime Witch | Read a story to both players that adds a creature to your hand. |
| The Witchler |
| Witchitaur |
| Ondu's Witch | Reverse the effects of the previous duel. Damage is taken back and the cards are returned to hand with cooldown 1. |
| The Coven of Babel | Each player shuffles a random creature from each Tribe in their hand into the deck. |
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
| Witchset |
| Witch of the Nile |
| Witchley |
| Xeno-Witch |
| Witchmere the Grey |
| Witch of the Nine Realms |
| Ms. Witchster |
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
| Trumpeting Witch |
| Divine Witch |
| Continental Witch |
| Tectonic Witch |
| Colossal Witch |
| Witchosaurus |
| Abominable Witch |
| La Llorona Witch |
| El Charro Negro's Witch |
| The Witch That Keeps on Witching |
| Colombus Witch |
| The Great Imitator's Witch |
| Scarecrow Witch | Transform a random creature in your opponent's hand into a Scarecrow. The Scarecrow has base _str_ 3, level 1, no Power Type, and "doesn't care": If dueled, it results in a tie and both cards are discarded. Each turn the Scarecrow is held, `Nightmare` types lose `1 level`. |
| Vegetable Mask Witch | Lose `1 level` each turn. When this reaches level 0, draw 2 cards and discard this Witch. If this witch wins a duel, discard your entire hand. |
| S | Transform `Nightmare` creatures into `Holy`, for both players. `Holy` creatures permanently deal double damage to Empires. |
| Arnold Layne's Witch | _Steal from the line_: Swap a creature from each player's hand. The creature you receive gets `+2 levels` and `cooldown 1`. |
| Emily's Hiding Witch | Choose a creature in your hand. At the start of each turn, it changes level randomly (1-6). |
| Golden Veil Witch | Get a random creature from a Tribe you don't currently have. |
| Dark Globe Witch | Creatures in both hands lose their Power Type for the rest of the game. |
| Gnome Witch | Scramble the levels and Power Types of all creatures in your hand. <br>"Ooh, my" |
| Jugband Witch | Add 3 random creatures to your hand. They must be played before any other card. |
| Jugband Witch | Choose a card in your hand to discard. Draw 3 new cards. If all 3 win their duel, reobtain the discarded card with `+7 levels`. |
| Jugband Witch | Discard a random creature from your hand. Create a Lvl.1 __Stand-In__ copy of it. If it dies, draw 2 cards. |
| The Scarlet Letter Witch |
| Scientific Witch | Choose a creature in your hand and a new Power Type for it to become. |
| Overdrive Witch | Damage the enemy Empire equal to your most recent number of consecutive duel wins. |
| Straight Witch | If you're holding at least 5 cards with consecutive levels, give them `+3 levels`. |
| The Madcap's Witch | Shuffle your hand into the deck. Draw the same number of cards plus one. If this witch dies, discard 3 cards. |
| Witch of Silence |
| Pied Piper's Witch |
| Clockwork Crier Witch | Set a prophecy: name a number (1-3). After that many turns, draw that many cards and take double the damage. |
| Robin Witch |
| Crow-Laughing Witch | Whenever a witch escapes, give a creature in the opponent's hand `-2 levels`. |
| Toymaker Witch |
| Daisy-Chain Witch |
| Cracked Ceremony Witch | Whenever a Witch card is played, the other player discards a random card from their hand. Starting now. |
| No Good Trying Witch | Skip your next turn. Draw 3 cards at the end of the skipped turn. |
| Scarecrow Witch | As long as this witch is in your hand, you may not play creatures. Creatures in your hand gain `+1 level` at the end of each turn. |
| False Witch |






__Sinful Witches__ — Lvl. 7-9

- Sinful witches have mastered the forms of dark magick and dissent the laws governing sorcery. They are nasty beings who cast the most perilous effects, entirely transforming how the game is played.

| Name | Effect |
|------|--------|
| Cataclysmic Witch | Destroy half of the remaining deck (rounded up)! |
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

Creatures of all different kinds are dispersed in the deck…until they __Rally__ in your hand.

__Rally__ — If your hand contains __4 or more cards__ of the same __Tribe__ or __Power Type__, they gain `+2 levels` (*enhanced*).

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

2. Creatures in hand deal damage to their holder equal to their base strength.

3. Whoever's Empire is less destroyed wins!
	- There may be a draw.
	- HP may become negative.
	
- Triggered _after_ the turn in which the final card was drawn.
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