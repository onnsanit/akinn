# Kinship — brand concept

## The reference

**Nevin Aladağ, *Pattern Kinship*** (ongoing series). We came to it through
*Pattern Kinship, Bubbles, ping-pong* (2022, acrylic on waterjet-cut aluminium,
175.3 × 215.9 cm) at the Harn Museum of Art —
<https://harn.emuseum.com/objects/25229/pattern-kinship-bubbles-pingpong>

The series takes ornament from traditions and centuries that **could never
actually have met** — different geographies, different eras, motifs that in
reality never shared a room — and forces them into one silhouette. Standing in
front of it you stop reading "Ottoman" and "Bauhaus" and start seeing that the
chevron in one is the chevron in the other. Aladağ has described this as work
about hybridity and belonging, drawn from her own experience as an immigrant,
and about undoing a predetermined gaze that sorts ornament into "oriental" and
"western".

The Harn piece is specifically two circles that come together — *one piece, not
two separate circles*.

## Why it fits akinn

**Akin** means *related to; of the same kind*. The brand name is already a claim
about relatedness, and this pattern is that claim rendered as a graphic. It is
not a borrowed mood; it's the dictionary definition of the word on the door.

The useful part for a brand is that kinship here is **demonstrated, not
asserted**. Nothing says "we bring people together." You just look at the mark
and see two things that are obviously different and just as obviously family.

## The system

A mark is generated from a six-character seed. Two discs, each filled with
concentric bands of ornament, overlapping into a single silhouette.

| Rule | What it encodes |
| --- | --- |
| **One silhouette.** The union of the two circles is stroked as a single outline; the seam is never drawn. | One piece, not two. |
| **In the overlap, both patterns stay visible.** The lens is composited with `multiply` (light) / `screen` (dark) so neither disc wins. | The overlap is the only part you can't pull back apart — it's the whole argument. |
| **One colour wheel, dealt alternately.** Six stops are generated from a single hue arc; disc A takes stops 0/2/4, disc B takes 1/3/5. | The halves are siblings, not opposites. |
| **The echo band.** One band index carries the same motif in the same colour on both discs. | A shared trait you can point at. |
| **One stop is held back** as a low-chroma dark. | Ornament always keeps a colour in reserve for the ground; without it the mark reads as neon. |

### Motif vocabulary

Nine primitives, drawn from scratch, each tiled around an annular band:
chevron, triangle, rosette, lattice, meander/step, scallop, dot, radial bar,
ogee. These are the forms that recur *independently* across almost every
decorative tradition on earth — which is exactly why the kinship reading holds
rather than being a costume.

### Reduction

| Level | Bands | Use |
| --- | --- | --- |
| Full | 8 | Entry screen, posters, packaging |
| Mark | 5 | Navigation, business card |
| Bug | 3 | Favicon, avatar, stamp |

Same seed, same identity, three densities.

## As a website entry

`index.html` is the working entry screen.

- On load the bands stagger in from the outside, A and B interleaved so the two
  discs braid together rather than appearing one after the other. The overlap
  and the silhouette outline resolve last — the two halves become one piece in
  front of you.
- A hairline drops from the seam into the wordmark.
- **Every visitor gets a different mark. Every visitor gets the same family.**
  The seed is shown and written to the URL, so a pattern is addressable and
  shareable: `akinn.com/?seed=n4kp2r`.
- *Another* reseeds. The specimen sheet below shows the reduction row and eight
  siblings; clicking one adopts it.

The generated accent colour is pulled from the current seed and drives the seed
label, focus rings and hover states — so the interface chrome belongs to
whichever pattern you were dealt.

## Attribution, honestly

The **concept** is Aladağ's and should be credited publicly if this direction
ships. What is ours: every motif is generated from primitives rather than traced
or sampled, the palette logic is ours, and the geometry, reduction and
interaction are ours. Do not reproduce her specific colourways. If akinn ever
wants to go further than homage — using her work in a campaign, say — that's a
licensing conversation with the artist, not a design decision.

## Open questions

1. **What does akinn actually do?** The copy on the entry is deliberately thin
   for that reason. Sector and audience will change the tagline and probably the
   neutrals.
2. **Should the seed persist per visitor** (stored, so you keep "your" mark) or
   reroll every visit? Persisting makes it an identity; rerolling makes it a
   welcome.
3. **Print and favicon.** The bug holds at ~58px on screen; a true 16px favicon
   likely wants a hand-tuned 2-band version rather than a generated one.
