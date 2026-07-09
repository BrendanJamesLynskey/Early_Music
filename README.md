# A History of Early Music

A growing collection of **22 interactive presentations** tracing a thousand years of Western music — from the unaccompanied plainchant of the early Church, through the birth of polyphony, the Ars Nova, the Franco-Flemish masters and the golden age of the Renaissance, to the threshold of the Baroque.

Each presentation is a self-contained, single-file HTML deployment using [Reveal.js](https://revealjs.com/), with hand-drawn inline-SVG diagrams, **synthesised audio examples you can play in the browser** (Web Audio API — including authentic *Pythagorean tuning* for the medieval examples), links to real recordings, and clear explanations of **how to read the notation of each age**. No build step, no bundler, no local dependencies beyond a CDN.

**Live site:** [brendanjameslynskey.github.io/Early_Music](https://brendanjameslynskey.github.io/Early_Music)

### How to Navigate

- **Arrow keys** or **click** to advance slides; **Esc** for the slide overview; **F** for fullscreen
- Look for the amber **▶ Listen** buttons — they synthesise chant, organum, cadences, isorhythm, chromaticism and more, live in your browser
- The landing page includes a **composer-lineage map** tracing the main lines of influence across the collection
- New to early music? Start with **Plainchant**, or jump to **Reading Early Music Notation** for the full notation guide

## Presentations

### Medieval · c. 500–1400

| # | Presentation | Dates | Slides |
|---|------------|-------|--------|
| 01 | [Plainchant — The Sung Prayer of the Latin Church & the Birth of Notation](Chant/) | c. 6th–10th c. | 14 |
| 02 | [Hildegard von Bingen — Visions in Sound & the Ecstatic Chant](Hildegard/) | 1098–1179 | 15 |
| 03 | [The Notre-Dame School — Léonin, Pérotin & the Birth of Polyphony](NotreDame/) | c. 1160–1250 | 16 |
| 04 | [Troubadours, Trouvères & Minnesänger — The Song of Courtly Love](Troubadours/) | c. 1100–1300 | 15 |
| 05 | [Guillaume de Machaut — The Ars Nova & the First Composed Mass](Machaut/) | c. 1300–1377 | 16 |
| 06 | [Francesco Landini — The Italian Trecento & the Sweet Cadence](Landini/) | c. 1325–1397 | 15 |
| 07 | [John Dunstaple — The Contenance Angloise & the Sweetness of Thirds](Dunstaple/) | c. 1390–1453 | 16 |

### Renaissance · c. 1400–1600

| # | Presentation | Dates | Slides |
|---|------------|-------|--------|
| 08 | [Guillaume Du Fay — The Burgundian Sun & the Cyclic Mass](DuFay/) | c. 1397–1474 | 15 |
| 09 | [Gilles Binchois — Master of the Burgundian Chanson](Binchois/) | c. 1400–1460 | 16 |
| 10 | [Johannes Ockeghem — The Master of Canon & Flowing Polyphony](Ockeghem/) | c. 1410–1497 | 16 |
| 11 | [Josquin des Prez — Pervasive Imitation & the High Renaissance](Josquin/) | c. 1450–1521 | 15 |
| 12 | [Thomas Tallis — The English Survivor & the 40-Voice Motet](Tallis/) | c. 1505–1585 | 16 |
| 13 | [Palestrina — The Serene Counterpoint of the Counter-Reformation](Palestrina/) | c. 1525–1594 | 16 |
| 14 | [Orlando di Lasso — The Cosmopolitan Genius of the Late Renaissance](Lassus/) | 1532–1594 | 15 |
| 15 | [Tomás Luis de Victoria — The Spanish Mystic](Victoria/) | c. 1548–1611 | 15 |
| 16 | [William Byrd — Master of Two Worlds & the English Virginals](Byrd/) | c. 1540–1623 | 16 |
| 17 | [Carlo Gesualdo — The Prince of Chromatic Anguish](Gesualdo/) | c. 1566–1613 | 15 |
| 18 | [John Dowland — The Melancholy Lutenist & the English Ayre](Dowland/) | 1563–1626 | 16 |

### Into the Baroque · c. 1600

| # | Presentation | Dates | Slides |
|---|------------|-------|--------|
| 19 | [Claudio Monteverdi — The Seconda Pratica & the Dawn of Opera](Monteverdi/) | 1567–1643 | 16 |

### The Christian East · Byzantine & Slavonic Orthodoxy

| # | Presentation | Dates | Slides |
|---|------------|-------|--------|
| 20 | [Byzantine Chant — The Sung Theology of the Christian East](Byzantine/) | 6th c. – present | 15 |
| 21 | [Slavonic & Russian Orthodox Chant — Znamenny to the All-Night Vigil](Slavonic/) | 988 – present | 16 |

### Reading the Notation

| # | Presentation | Dates | Slides |
|---|------------|-------|--------|
| 22 | [Reading Early Music Notation — From Gesture to Grid](Notation/) | A didactic guide | 15 |

_340 slides across the collection._

## Themes Covered

- **Notation, stage by stage** — neumes, Guido's staff & solmisation, square notation, the rhythmic modes, Franconian and Ars Nova mensural notation, white mensural notation, lute & keyboard tablature, and the road to the modern score, each with a worked "how to read it" example.
- **Technique** — modes, organum, isorhythm, the *formes fixes*, fauxbourdon, the cyclic cantus-firmus Mass, canon & mensuration canon, pervasive imitation, suspensions, chromaticism, the division on a ground, and the basso continuo.
- **The Christian East** — Byzantine chant (the *ison* drone, the Octoechos, the microtonal genera, St Romanos and St Kassia) and the Slavonic/Russian tradition (Znamenny chant and its hook-notation, the bells of the *zvon*, the deep oktavist basses, and the All-Night Vigil), including the wider Orthodox world.
- **Sound** — every deck plays idiomatic examples in the browser and links out to landmark recordings.

## Technical Notes

- Single-file HTML per presentation; Reveal.js 4.6.1 and fonts loaded from CDN.
- Audio is synthesised at runtime with the Web Audio API — a shared engine with multiple period timbres (voice, organ, reed, plucked lute/harp, bell), a generated stone-church convolution reverb, selectable equal or **Pythagorean** temperament so the medieval fifths ring true, and direct frequency control for the **microtonal Byzantine genera**.
- Dark theme; responsive; keyboard-navigable.

---

*Part of [Miscellaneous](https://github.com/BrendanJamesLynskey/Miscellaneous). A companion series to [Psychology & Philosophy](https://brendanjameslynskey.github.io/Psychology_Philosophy/).*
