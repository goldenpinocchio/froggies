# Froggies 🐸

**Froggies** is a Bitcoin-native pond collection designed for nat.fun, with a fixed supply of **4,032 unique Froggies**.

Both supply and trait generation are derived entirely from Bitcoin blockchain data, creating a collection that is deterministic, verifiable, and free from off-chain randomness.

---

## Supply Generation

Bitcoin adjusts mining difficulty every **2,016 blocks**, known as a *difficulty period*. Each block within a difficulty period shares the same compact difficulty value stored in the block header's `bits` field.

Froggies identifies difficulty periods whose `bits` value contains the **`fc` signal**. Across Bitcoin's history, this condition occurs in two qualifying difficulty periods:

| Generation | Block Range       | First Block Date (UTC) | `bits` Value |
| ---------- | ----------------- | ---------------------- | ------------ |
| Gen 1      | 266,112 – 268,127 | 2013-10-26 02:24:32    | `190afc85`   |
| Gen 2      | 933,408 – 935,423 | 2026-01-22 19:31:22    | `1701fca1`   |

Each qualifying difficulty period contains exactly **2,016 blocks**:

* Gen 1: 2,016 Froggies
* Gen 2: 2,016 Froggies

**Total Supply = 4,032 Froggies**

Every Froggie is permanently linked to one specific Bitcoin block from these qualifying periods.

---

## Trait Generation

Traits are generated directly from the assigned Bitcoin block hash.

For each Froggie:

1. The block hash is divided into deterministic roll values.
2. Each roll is mapped to predefined rarity ranges.
3. The resulting values determine the Froggie's attributes.

Trait categories include:

* Body Color
* Eyes
* Expression
* Headgear
* Swamp Accessories
* Background / Aura

Because all trait rolls originate from Bitcoin block hashes, every Froggie can be independently verified and reproduced from on-chain data alone.

---

## Bitcoin-Native by Design

Froggies uses Bitcoin as the sole source of truth for:

* Collection supply
* Generation assignment
* Trait rarity
* Trait selection

No off-chain randomness, reveal process, or external entropy source is required.

The result is a fully deterministic collection whose existence and attributes are anchored directly to Bitcoin's blockchain history.


## Trait Occurrences

| Trait | Trait Type | Occurrences |
|---|---:|---:|
| Body Color | swamp green | 701 |
| Body Color | pastel green | 585 |
| Body Color | turquoise | 468 |
| Body Color | toxic yellow | 496 |
| Body Color | neon pink | 394 |
| Body Color | night black | 414 |
| Body Color | albino white | 262 |
| Body Color | ghost | 333 |
| Body Color | gold body | 201 |
| Body Color | diamond body | 178 |
| Eyes | wide sleepy | 1473 |
| Eyes | one-eye wink | 904 |
| Eyes | bulging | 598 |
| Eyes | hypnotic spiral | 397 |
| Eyes | gold eyes | 291 |
| Eyes | diamond eyes | 192 |
| Eyes | laser eyes | 177 |
| Mouth / Expression | grin | 1551 |
| Mouth / Expression | croak | 980 |
| Mouth / Expression | deadpan | 618 |
| Mouth / Expression | shocked | 413 |
| Mouth / Expression | frog tongue | 290 |
| Mouth / Expression | chewing bug | 180 |
| Headgear / Props | none | 893 |
| Headgear / Props | leaf cap | 769 |
| Headgear / Props | ribbit hoodie | 604 |
| Headgear / Props | bandana | 399 |
| Headgear / Props | goggles | 398 |
| Headgear / Props | pirate hat | 316 |
| Headgear / Props | wizard hat | 322 |
| Headgear / Props | pin wheel hat | 169 |
| Headgear / Props | crown | 162 |
| Swamp Accessories | lily pad | 823 |
| Swamp Accessories | fly | 751 |
| Swamp Accessories | bubble | 698 |
| Swamp Accessories | mushrooms | 616 |
| Swamp Accessories | lightning bug | 469 |
| Swamp Accessories | bones | 290 |
| Swamp Accessories | fishing hook | 208 |
| Swamp Accessories | coin stack | 177 |
| Background / Aura | murky pond | 857 |
| Background / Aura | sunrise marsh | 903 |
| Background / Aura | moonlit swamp | 783 |
| Background / Aura | rainy night | 622 |
| Background / Aura | toxic swamp mist | 368 |
| Background / Aura | Bitcoin orange glow | 306 |
| Background / Aura | neon vapor | 193 |

## Notes
- Supply target: 4,032
- Traits are deterministic and driven by Bitcoin block data
