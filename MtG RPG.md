# MtG RPG

## Definitions

### Player Creature

A player creature is both a player and a creature.

### Wounded

A wounded player creature is one that no longer benefits from its toughness, and instead loses life whenever it takes damage.

### Roll

A roll is the numerical result of rolling 2d6. A stat roll is an ordinary roll plus the value of the named stat. (For example, a speed roll is 2d6 + speed.)

### Channeling Action

A channeling action is any of the following:

* casting a spell
* activating an activated ability of a non-land non-player permanent (Activated abilities on player creatures do not count as channeling actions.)

### Swift Strike X

Whenever combat damage would be dealt, creatures with the highest swift strike X deal their damage first, then creatures with the next-highest, and so on. This happens during the first-strike combat step and during the regular combat damage step. Between each set of swift-strike damage, creatures can die and be removed from combat, and players gain priority. (Swift Strike is like first strike, except scalable, and weaker unless combined with first strike.)

### Limited X

A limited X activated ability cannot be activated more than X times per turn.

### Identity Affinity

If your color identity matches an activated ability's identity affinity, that activated ability costs {2} less to cast or activate.

----

## Universal Effects

If a player creature is not wounded, treat damage it takes as if that player creature were only a creature. (Usually, it loses no life. Marked damage is removed at the end of turn, as usual.)

If a player creature is wounded, treat damage it takes as if that player creature were only a player. (Usually, it loses life equal to the damage taken. Abilities like infect may add poison counters.)

Player creatures cannot be sacrificed.

If a player creature would be exiled or would die because of a destroy effect or because its damage equals or exceeds its toughness, instead it becomes wounded. Then it takes damage equal to the amount by which its marked damage exceeds its toughness. (This damage must be treated as if the player creature is only a player.)

If a permanent would enter the battlefield as or would become a copy of a player creature, instead it becomes a creature. (It has only the stats a creature would normally have. It has no spells, but it does copy any activated abilities on the player creature. It copies name, subtypes, power, and toughness.)

Whenever a wounded player creature is controlled by a player other than its owner, its owner gains control of it.

If you would untap lands during your untap step, instead untap a number of lands up to your rejuvenation.

Whenever you control a number of non-land, non-player-creature permanents greater than your concentration, sacrifice a non-land, non-player-creature permanent. Split-second. (Lands, artifacts, enchantments, creatures, and planeswalkers on the battlefield are permanents.)

Whenever you control a number of lands greater than your level, sacrifice a land.

Whenever your mana pool contains an amount of mana greater than your mastery, pay {X}, where X is the difference, and you lose X life. Split-second.

Whenever you take a channeling action, put a fatigue counter on yourself. Split-second.

If the number of fatigue counters on you equals or exceeds your channeling, you cannot take any channeling actions.

At the beginning of your untap step, remove all fatigue counters from yourself.

Your life cannot exceed your maximum life.

You have a maximum hand size equal to your memory.

If you would draw your starting hand, instead draw a number of cards equal to your memory.

If you would cast a spell or activate an activated ability, instead do the following:

> * If you do not have a reaction speed value, make a speed roll. The result becomes your reaction speed value until the stack becomes empty.
> * You may cast your chosen spell or activate your chosen activated ability only if either the stack is empty or your reaction speed roll exceeds the reaction speed roll associated with the controller of the topmost spell or activated ability on the stack. (If you do not cast a spell or activate an activated ability, you are not required to announce which spell you would have cast or which activated ability you would have activated. Triggered abilities trigger as usual. They do not interact with any speed rolls.)

Effects in card text override these effects.

## Universal Rules

Memory cannot exceed 10.

Focus cannot exceed 20.

Your minimum deck size is 40 + your level - your focus. (As you gain levels, you will be able to remove more and more lands from your library when you enter combat mode.)

Your maximum sideboard size is your Focus + your memory.

The 4-card-per-name limit is instead a 1-card-per-name limit. (Exceptions such as basic lands and Relentless Rats still are not limited.)

Your life total is persistent between combats.

When you finish a rest, your life total becomes equal to your maximum life.

When you enter encounter mode, you may search your library for a number of land cards up to to your level and put them onto the battlefield.

Your deck cannot include spells with a CMC greater than your mastery.

Your deck cannot include cards that do not match your color identity. For a spell to match your color identity, its text cannot include any colored mana symbol that does not appear in your color identity. Additionally, for each colored mana symbol in a spell's casting cost, your color identity must have a distinct mana symbol corresponding to that one. (For example, you can only include Counterspell if your color-identity contains {U}{U}. However, you can include Syncopate if your color identity contains only a single {U}. For a spell costing {G/R}, your identity would need to include either green or red.)

Whenever your level increases, gain a number of build points equal to 5 times your level. Your level cannot increase by more than one at a time, and it cannot increase while this effect is on the stack.

X build points: Choose one of your growable stats with a value of X-1. Increase the value of that stat to X. This ability can only be activated at the end of a short rest.

## Characters

### Stats

* Level: starting lands
* Life
* Maximum Life
* Power
* Toughness
* Mastery: max mana-pool size
* Rejuvenation: number of lands untapped per turn
* Concentration: number of permanents maintained
* Channeling: number of actions per turn
* Speed: determines turn order and reaction speed value
* Focus: reduces deck size
* Memory: increases hand size
* color identity

### Abilities

> {4}: Prevent the next 1d6 damage you would take this turn. Identity affinity {W}.

> {4}: Gain swift strike X until end of turn, where X is the result of a speed roll. Identity affinity {R}. Limited 1.

> {5}: The next time you deal damage this turn, that damage is increased by 1d6. Identity affinity {R/G}.

> {3}: Gain reach until end of turn. Identity affinity {G}.

> {5}: Gain flying until end of turn. Identity affinity {W/U}.

> {5}: Gain lifelink until end of turn. Identity affinity {W/B}.

> {8}: Gain deathtouch until end of turn. Identity affinity {B/G}.

> {6}: Gain trample until end of turn. Identity affinity {G}{R}.

> {6}: Counter target spell or ability that targets you. Identity affinity {U}{U}.

> {7}: Change the target of a spell or ability that targets you. Identity affinity {U}{U/R}.

> {3}: Gain provoke until end of turn. Identity affinity {R/G}.

> {3}: You may block an additional creature this turn. Identity affinity {W}.

> When you gain this ability, choose a color.
> {6}: Gain protection from the chosen color until end of turn. Identity affinity {W}{W}.

> {8}: You are no longer wounded. Identity affinity {W}{G}.

> {2}, Pay 5 life: You are no longer wounded. Use this ability only at any time you could cast a sorcery. Identity affinity {B}{B}.

> Werewolf-transformation thing, except with relative power/toughness change. Gain a lycanthropy counter, yadda, yadda.
>
> As long as you have a lycanthropy counter, you gain +X/+Y and some other selected abilities.

