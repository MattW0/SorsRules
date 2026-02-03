Cards and entities have abilities. An ability has this structure *Trigger* **:** _Effect_, *Target*

## Triggers

At the beginning of [[Phases]]
```
// At the beginning of [Phase]
PhaseSelection = 1,
Draw = 2,
Invent = 3,
Develop = 4,
Combat = 5,
Recruit = 6,
Deploy = 7,
Prevail = 8,
CleanUp = 9,
```

When ... - State changes and actions of [[Card]] / [[Entity]]
```
// When triggers
WhenYouBuy,
WhenYouPlay = 20,
WhenDies,
WhenAttacks,
WhenBlocks,
WhenGetsBlocked,
WhenTakesDamage,
WhenDealsDamage,
```
## Effects
```
CardDraw = 1,
Damage = 5,
Life = 6,
Cash = 10,
PriceReduction = 11,
Destroy,
```
## Targets 
```
Any = 1,
You = 2,
Opponent = 3,
AnyPlayer = 4,
Self = 7,
Entity = 8,
Creature = 9,
Technology = 10,
```

