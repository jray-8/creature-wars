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

- If the creatures have equal power, they each return to their player's hand and cannot be played on the next turn (Cooldown 1).

- If a player cannot play a creature for any reason, they simply take the Base Strength of the enemy creature.

	- Cards may be on Cooldown or __Frozen__: cannot be played but remain in hand.

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
| Rebellious Witch | If this witch survives, join the opponent's hand. |
| Busy Witch | This witch must run her errands before being played. |


</details>
<br>

__Sacred Witches__ — Lvl. 4-6

- Sacred Witches are honorable and highly-respected witches. They have greater control of their magic and cast more powerful, often symmetric, effects. However, if used at the right time these Witches can serve to benefit the caster greater.

| Name | Effect |
|------|--------|
| Witch of Despair | Both players discard their entire hand. |
| Witch of the Hesperus | __ALL__ Pirates are drown and replaced with __Phantoms__. <br>Phantoms lose 2 base strength but gain `+5 levels`, and have no Power Type. |
| Vengeful Witch | If this Witch loses its duel, gain a __Lvl.1 Primordial Butterfly {1}__. If a Primordial Butterfly ever wins a duel, the opposing Empire crumbles. |
| Moon Charm Witch | Transform _ALL_ Wolves into __Werewolves__. They now have a base strength of 8 and are all `Nightmare` types. |
| Prophetic Witch | See your opponent's hand. |
| Shifting Witch | Become an exact copy of the opponent's card at the start of the duel. |
| Democratic Witch | Disband any __Rallies__ in your opponent's hand. Those cards cannot be used in future Rallies. |
| Scary Witch | Turn the Power Types of creatures in your hand into `Nightmare`. Any `Holy` creatures are discarded instead. |
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
| Paraphilic Witch |
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
| Haggel & Witchel | Set a curse: The next player to draw a Witch card takes 12 damage. Both players draw cards until they're holding 8. |
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
| Storytime Witch | Tell a tale to both players that adds a creature to your hand. |
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
| Seth's Witch |
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


| Scarecrow Witch | Transform a random creature in your opponent's hand into a Scarecrow. The Scarecrow has base _str_ 3, level 1, no Power Type, and "doesn't care": If dueled, it results in a tie and both cards are discarded. Each turn the Scarecrow is held, `Nightmare` types lose `1 level`. |
| Vegetable Mask Witch | Lose `1 level` each turn. When this reaches level 0, draw 2 cards and discard this Witch. If this witch wins a duel, discard your entire hand. |
| S | Transform `Nightmare` creatures into `Holy`, for both players. `Holy` creatures permanently deal double damage to Empires. |
| Arnold Layne's Witch | _Steal from the line_: Swap a creature from each player's hand. The creature you receive gets `+2 levels` and `cooldown 1`. |
| Emily's Hiding Witch | Choose a creature in your hand. At the start of each turn, it changes its Power Type and level (1-6) randomly. |
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
| Astronomy Witch | Give all cards in your hand `+1 level` for each Power Type you control. |
| Hostage Witch | Whenever you lose a duel while this is in your hand, reveal another random card to your opponent. If this witch escapes, 
| Falsely Imprisoned Witch |
| Premarital Witch | If you're holding another Witch card, add a random Lvl.1 Witch to your hand. |
| Safe Witch | Discard your entire hand. |
| Ambiguous Witch |
| Espionage Witch |


| Soy Witch |
| Evasive Witch |
| Kill's Witch |
| Lolita's Witch |
| Sadistic Witch |
| Divine Wind's Witch | Instead of dueling, both cards are promptly destroyed and each Empire takes 5 damage. Enemy witches fail to cast their effect. |
| Tenno Heika's Witch |
| Erotic Witch |
| S | Choose to target the enemy Empire or your own. A random creature will have its base strength reduced by half (rounded down). |
| Quiet Gazer's Witch |
| Odax's Witch |
| Mule Witch | Add 
| Phrayme's Witch |
| S | Cards in both hands gain cooldown equal to their level. |
| Brute Keeping Witch | Add 2 steel cages to your opponent's hand. When played, or during Mayhem, a random creature with `base str` 5 or higher is released. |
| Klepto Witch |
| Haemato's Witch |
| Somnophilic Witch |
| Crack Witch |
| Swarm Witch |
| Temno's Witch |
| Frankenstein's Witch | 
| Wretched Witch | All creatures in your hand are butchered and stitched back into one. Resurrect the __Monster__ with the combined levels and `base str` of your creatures, and no Power Type. While the Monster remains in hand, you no longer draw cards at the start of each turn. |
| Actirastic Witch |


| Vigil Witch | Give `Holy` creatures in your hand `+1 level` for each `Fire` type you control. |
| Agalmatophilic Witch |
| Agrexophilic Witch |
| Asphyxia's Witch |
| Convicted Witch | 
| Homophobic Witch | Destroy random cards in each player's hand such that only 1 of each creature remain. |
| Vampiric Witch |
| Rapier Witch |
| Witchnapper |
| Biaste's Witch |
| Plato's Witch |
| Witch of Gyges |
| Queen Nyssia's Witch | Instead of dueling, the opposing card is added to your hand and the strongest creature in your opponent's hand is slain. |
| Mazophilic Witch |
| Bricked Witch |
| Elektra's Witch |
| Cenophilic Witch |
| Engorged Witch |
| Katoptron's Witch |
| Teleois' Witch |
| Dakno's Witch |
| Hieros' Witch |
| Sekhmet's Witch |
| Logi's Witch |
| Kukulkan's Witch |
| Baalham's Witch |
| Idolatrous Witch |
| Onan's Witch |
| Magnetic Witch | After your next duel, draw a creature from the deck that matches the Tribe you played, or draw a Witch card from the deck if you played a Witch. |
| Fool's Witch | This witch appears to be another. When played, you are revealed to be a fool! |
| Loki's Witch | Shuffle 5 Fool's Witches into the deck. Witch cards in both players' hands are given a new identity and shuffled back into the deck. |
| Masquerader's Witch |
| Crossdressing Witch |
| Swarming Witch | Shuffle 12 __Locusts__ into the deck. Locusts cannot be played, but each in hand deals 1 damage to your Empire after every duel. Playing a Witch card causes all Locusts in your hand to flee. |
| Falsely Imprisoned Witch |
| Espionage Witch | Infiltrate the enemy Empire. A random card in their hand becomes your mole; you get to see who it is. At the end of each future duel, the mole reveals another card in your opponent's hand. When the mole is discarded your intel ceases. |
| Peevish Witch |
| Shadow Witch |
| Epiales' Witch |
| Re-educational Witch |
| Dyslexic Witch | Each turn this is in your hand, randomize the levels of all creatures in your hand. |
| S | Swap the level and `base str` of all cards in both players' hands. |
| Prometheus' Witch |
| Sisyphean Witch |
| Aegean Witch |
| Witch of Tantalus |
| Bellerophon's Witch |
| Milgaard's Witch |
| Potiphar's Witch |
| Schizophrenic Witch |
| Capgras Witch |
| Machiavellian Witch |
| Afflicted Witch |
| Infected Witch |
| Wiccan, The Wise |
| Persephone's Witch |
| S | Cards duel using levels only next turn. Base strength is ignored. |
| Sniper Witch | Instead of dueling, snipe the enemy creature; it is discarded and you win the duel. If a Witch is played instead, duel normally. |
| Mirror Master's Witch |
| Modravh's Witch |
| Newcastle's Witch |
| Bone Witch | Choose to either give Skeletons in your hand `+1 level` or add a random Wolf to your hand. |
| Grotto Witch |
| Graveyard Witch | Discard the top 6 cards from the deck. Any Skeletons enter your hand instead. |
| Ancestral Witch |
| The Great Leveler's Witch |
| Barbaric Witch |
| Terrorist's Witch |
| Halal Witch |
| Neglected Witch |
| The Emporer's New Witch |
| Mother Stork's Witch |
| Dino's Witch |
| Shehitah's Witch |
| Kosher Witch | Discard a random creature in your hand. Heal for x2 its Base Strength. |
| New Year Witch |
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



| S | _Sanctuary_: For the next 3 turns, your Empire cannot take damage from Base Strength. |
| Wallowing Witch | If your HP is lower than your opponent's, a creature in your hand gains `+4 levels`. |
| Heralding Witch | See the top 5 cards of the deck. |
| The Witch of Wallstreet | Look at the top 3 cards of the deck. Put one in your hand, and the others on the bottom. |
| S | Choose a Tribe. Creatures from that Tribe cannot be played for 2 turns. |
| The Tin Witch | If you hold a Rally, give them another `+2 levels` (including The Tin Witch). |
| Witchy Wonka | If your opponent has played more Witches than you, then your next card that loses buffs cards in your hand equal to its level. |
| Witchy Wonka | Hide 5 golden tickets on random creatures left in the deck. After a creature with a golden ticket is played, give creatures in your hand `+1 level` for each golden ticket uncovered. |
| Jittery Witch | Both players discard a random card, then draw one. |
| S | Turn _ALL_ `Ancient` types (held or in deck) into Serpents. |
| Indignified Witch | If this witch wins the duel, the opposing creature is so embarrassed it loses its Power Type and `-2 levels` permanently. |
| Paraphilic Witch | _Curious Attraction_: Choose a Tribe from your hand. All creatures of that Tribe in your opponent's hand are immediately drawn to yours. |
| Nude Witch | Cards in both players' hands are set to `level 1`. |
| Racist Witch | _The Unspeakable_: Declare one of the 7 Tribes as uncouth. Whenever such a creature is played, the commanding Empire takes 3 damage. |
| Death Witch | Choose to victimize the opponent's Empire or your own. A random card in the victim's hand has its `base str` increased by 5. |
| Witch of Silencing | The first witch to be played while this is in your hand has its effect nullified. Whenever that happens, discard this witch. |
| Nymph Witch | This card counts as any Power Type to complete a Rally in hand. Once a Rally is formed, it keeps that Power Type. |
| S | This card counts as any Tribe to complete a Rally in hand. |
| S | Transform all other witches in your hand into random Vampires. |
| Witch of the Beasts and the Children | All creatures with a Base Strength greater than a `Pirate {4}` flee from the deck. |
| Secular Witch | All `Holy` creatures in both players' hands lose their Power Type. |
| The Ouroboros Witch | Transform Serpents in both players' hands into random Dragons. |
| S | Give creatures in both players' hands cooldown 3 (they cannot be played for the next 3 turns). |
| S | Swap the Base Strength of the strongest and weakest creatures in your hand. |
| Archwitch | Draw a Witch card from the deck and reveal it. Shuffle the deck. |
| Maiden Witch | All level 1-2 creatures in your hand gain `+3 levels`. |
| !!Wild-Tamer Witch | Reduce the Base Strength of all creatures in your hand by 2. Give them `+1 level` instead. |
| Suicidal Witch | Lose 6 HP. Draw 2 cards and give them `+2 levels`. |
| Witch of Ravishment | Get a Lvl.1 copy of a random creature in your opponent's hand. The victim can only be played after the copy is discarded. |
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
| Witchitaur | 
| Xeno-Witch | Randomize the Tribes of all creatures in both players' hands. |
| Witch of the Nile | Each player discards their lowest-level creature. |
| Witchmandias | Reduce both Empires to 15 HP if above it. |
| Song of Witchself |
| Witchles Dickens |
| Geppetto's Witch |
| Seth's Witch |
| Witchibitionist |
| Balthazar's Witch |
| Witchicles |
| Witchley | Draw a card. If it's a Wolf or a Giant, give it `+4 levels`. |
| White Witch | _Eternal Winter_: Remove all `Fire` cards from the deck. Whenever a card is drawn, give it `Cooldown 2`. |
| Pack Witch | All Wolves in your hand become the same Power Type as your strongest. |
| S | Shuffle 6 Giants into the deck. Discard cards from the deck until there is a Giant on top. |
| Jungle Witch | Shuffle 6 random creatures into the deck. |
| It's a Wonderful Witch | Replace your hand with an alternate image. Your Witch cards are rerolled based on rarity and your creatures are given new Power Types and levels. The next duel you lose causes your cards to reset to their original versions. |
| Leviathan's Witch | All creatures with Base Strength 5 or higher gain `+3 levels`, but deal double damage to their owner if they lose. |
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
| Jurassic Witch | Pirates and Vampires are removed from the deck. Random Dragons or Giants replace them. All Giants and Dragons in the deck gain `+2 levels`. |
| Fruit Basket Witch | Add a Pineapple that heals 6 HP when played to your hand. |
| Witchrend | Choose a creature in your hand to split into two Lvl.1 creatures of the same Tribe. |
| Familiar Witch | Get a random creature from the same Tribe as your most recently played creature. |


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

1. Creatures remaining in hand damage their Empire equal to their Base Strength.

	- Any frozen creatures are freed first (can attack).

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