# Asset Library Roadmap

## 当前策略

先完成影视资产库，再进入 EP001 镜头生产。

## Phase A: F001 Carter Family Actors

| Actor ID | Character | Role | Status | Notes |
| --- | --- | --- | --- | --- |
| A001 | Emily Carter | protagonist / daughter | complete | Main EP001 POV |
| A002 | Helen Carter | mother | complete | Family portrait order |
| A003 | David Carter | father | complete | Left-side portrait anchor |
| A005 | Rose Carter | grandmother | complete | Shot 06-07 performance role |
| A006 | Claire Carter | first erased woman | pending | Right-side Photo A subject |
| A008 | Noah Carter | younger brother | complete | Second erased family member |
| A009 | Unknown Man | anomaly source | complete | P002-D earliest photo |

Next actor task:

```text
A006 Claire Carter
```

## Phase B: H001 Suburban House Location Library

| Location ID | Area | Required Views | Status |
| --- | --- | --- | --- |
| H001-LIVING-DINING | living / dining table | Front, Left45, Right45, Wide, Empty, Day, Night | text only |
| H001-HALLWAY | hallway | Front, Left45, Right45, Wide, Empty, Night | complete |
| H001-ROSE-BEDROOM | Rose bedroom | Front, Left45, Right45, Wide, Empty, Day, Night | complete |
| H001-ATTIC | attic | Front, Left45, Right45, Wide, Empty, Flashlight, Night | text only |
| H001-MIRROR-AREA | mirror area | Front, Wide, Empty, Normal, Final, Night | text only |

## Phase C: EP001 Props Library

| Prop ID | Prop | Required States | Status |
| --- | --- | --- | --- |
| P001 | Old Photo Album | Closed, Open, Spread, Holding, Close | text only |
| P002 | Family Portrait | Master, A, B, C, D, E, Back Writing | text only |
| P003 | Smartphone | Gallery, Zoom, Handheld, Table | text only |
| P004 | Wooden Table | Empty, Album Setup, Photo Layout | text only |
| P005 | Desk Lamp | Off, Warm On, Night Flicker | text only |
| P006 | Mirror | Normal, Final, Empty, Emily Reflection | text only |

## Phase D: Relationship Library

Required relationship records:

- Emily -> Claire: sister / erased memory target
- Emily -> Helen: daughter / mother
- Emily -> David: daughter / father
- Emily -> Rose: granddaughter / grandmother
- Emily -> Noah: sister / brother
- Carter family -> Unknown Man: forgotten / anomaly source

## Phase E: P002_MASTER

Build only after all P002 actors are complete:

```text
David | Helen | Rose | Emily | Noah | Claire
```

P002-D earliest version adds:

```text
Unknown Man centered
```

Rule:

```text
All P002 variants must be edited from the same master composition.
Do not regenerate each variant independently.
```
