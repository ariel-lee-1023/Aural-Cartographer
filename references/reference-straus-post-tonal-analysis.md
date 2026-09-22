# Introduction to Post-Tonal Theory — Joseph N. Straus
**Format**: md, checked against local PDF | **Pages**: 413 PDF pages | **Sections**: 6 | **Depth**: study | **Type**: technical

Fourth edition, W. W. Norton, 2016. Section numbers below refer to this edition. Damaged accidentals and lost musical notation in conversions require score verification before passage-specific calculations.

## Mental Model (read first)

Post-tonal music can organize pitch through recurring intervallic ideas, transposition, inversion, collections, centricity and ordered series. These are positive organizations, not measures of distance from successful functional tonality. Move between concrete pitch/register and abstract pitch-class relations, testing which abstraction explains the passage. Segmentation and perceptual relevance are analytical responsibilities, not automatic consequences of a calculation.

## Frameworks & Structure

### Chapter 1: Pitch and interval, with the abstraction stated

- **Pitch / pitch class:** a pitch has register; a pitch class groups octave-related pitches. Under the book's twelve-equal-tempered model, enharmonic spellings map to one pitch class. C=0, C♯/D♭=1, …, B=11; 10 and 11 may be written T and E. This representation does not claim that register, spelling, tuning or timbre are perceptually irrelevant.
- **Modular arithmetic:** reduce pitch-class calculations modulo 12. Ordered pitch interval preserves direction and octave size; unordered pitch interval gives absolute distance. Ordered pitch-class interval is `(b−a) mod 12`; unordered pitch-class interval takes the smaller circular distance. State which quantity is being used.
- **Interval class (ic):** octave- and inversion-equivalent intervals are grouped into classes 0–6; the six non-unison classes describe distinct-pc pairs. A minor second and major seventh share ic1 while differing dramatically in registral realization.
- **Interval-class vector:** count every unordered pair of distinct pitch classes into `[ic1, ic2, ic3, ic4, ic5, ic6]`. The entries should total `n(n−1)/2` for an n-note pc set. The vector characterizes interval content, not the order, voicing, dynamics or succession of events.
- **Spacing and register:** examine the actual pitches alongside abstractions. A registral extreme, repeated pitch or characteristic contour can articulate a motive that an unordered set representation hides. Source: §§1.1–1.13.

### Chapter 2: Sets, transformations and defensible segmentation

- **Pitch-class set:** an unordered collection with duplicates removed. Do not remove rhythm, order and doubling from the overall analysis simply because this particular representation omits them.
- **Normal form:** a compact ordering of the actual set. Sort cyclically, test rotations, and minimize the first-to-last span. **Edition-specific qualification:** Straus's fourth edition breaks ties by packing toward either end; if otherwise tied, prefer the more bottom-packed ordering. This differs from the traditional always-bottom-packed procedure for a few sets. Name the convention when checking another analyst or software; do not silently combine algorithms. Source: §2.2, Example 2-3, p. 45.
- **Transposition:** `T_n(x)=(x+n) mod 12`. Verify every element; for ordered series also preserve order. Distinguish transposition of actual pitches from transposition of pitch classes and from an unordered set correspondence.
- **Inversion:** `I_n(x)=(n−x) mod 12`. Corresponding pitch classes sum to n modulo 12. Straus also uses a contextual label identifying a mapped pair; its sum supplies n. A pc inversion can preserve set membership without preserving a heard contour or an instrument's physical voice-leading.
- **Set class:** sets related by transposition or inversion belong to the same class under this equivalence relation. A **prime form** names that class with a compact zero-based representative, not an actual temporal ordering or tonic. Use a verified table/algorithm when exact prime forms or Forte names matter. A Forte name's two numbers denote cardinality and catalogue position, not aesthetic properties.
- **Segmentation and analysis:** propose groupings using proximity, phrase boundaries, simultaneous sounding notes, register, rhythmic emphasis or timbre. **Imbrication** tests overlapping consecutive groups, but a group crossing a rest needs musical justification. Reconsider groupings as recurrences become apparent. Do not pluck unrelated notes merely to manufacture a favored set class. Source: §2.9, pp. 69–70.
- **Analytical sequence:** establish evidence → identify salient groups → calculate relations → check those relations against other parameters → retain what explains recurrence, transformation or contrast. Arithmetic correctness is necessary for a set claim, insufficient for its musical significance.

### Chapter 3: Relations beyond common membership

- **Common tones under T/I:** calculate actual intersections after transformation. An interval-class vector predicts aggregate common-tone behavior under transposition, but the exact shared pitches require the specific set. State whether tones stay fixed, exchange or recur in another register.
- **Transpositional symmetry:** a nonzero T operation maps a set onto itself. **Inversional symmetry:** an I operation maps a set onto itself. Equal division of the octave can reduce the number of distinct transpositions; it does not compel an uncentered perceptual result.
- **Z-relation:** different set classes can share an interval-class vector without being T/I-equivalent. The all-interval tetrachords (0146) and (0137) both have `[111111]`. Similar inventory is not identity of structure. Source: §3.6, pp. 112–114.
- **Complement:** the remaining pitch classes in the twelve-note aggregate. Distinguish literal complementary collections from an abstract relationship between their set classes. A complement calculation alone does not show that the music presents or emphasizes it.
- **Inclusion:** a literal subset is contained in an actual set; abstract inclusion concerns members of set classes. State which relationship is asserted. Repeated subsets can bind larger, otherwise different collections.
- **Transpositional combination (TC):** combining transposed copies of a smaller collection generates a larger one. Identify source collection, operation and union; test whether the music articulates this construction rather than merely permitting it mathematically.
- **Contour relations / CSEG:** replace pitches by their relative rank to compare rising/falling profiles despite different interval sizes. A contour relation answers another question than T/I-equivalence. The approach can also describe ordinal patterns of duration or dynamics, without claiming their perceptual effects are identical. Source: §§3.1–3.10.

### Chapter 4: Motive, voice leading and harmony

- **Composing-out:** relations compressed in a local idea can be projected over longer spans. Identify the evidence linking the distant notes—register, recurrence, contour or formal placement—before claiming structural expansion.
- **Interval cycles:** repeated motion by one interval produces a cycle; combinations and partitions can generate characteristic collections. Trace the actual order and point of return. An available cycle does not establish that every intermediate note has structural priority.
- **Transformational voice leading:** T/I mappings suggest connections between members of successive sets. Distinguish these abstract voices from notated parts and audible lines; they can cross. **Fuzzy transposition/inversion** describes a near relation with a stated offset rather than pretending it is exact. Source: §4.3, pp. 174–178.
- **Set-class space:** compare how much semitonal adjustment connects members of different classes. This is a measure under a particular mapping, not a universal distance between musical experiences. Voice-leading proximity and functional tonal proximity need not coincide.
- **Contextual inversion:** choose an inversion according to tones and relations in the passage, rather than applying a fixed external axis indiscriminately. In **triadic post-tonality**, recognizable major/minor triads can be connected by transformations or economical voice leading without governing tonic–dominant syntax. Triadic sound does not by itself establish a key. Source: §§4.4–4.6.

### Chapter 5: Centricity and referential pitch collections

- **Centricity / tonality:** a focal tone can be established through repetition, duration, register, accent or convergence without traditional tonal functions. More than one center may compete. Avoid calling every repeated bass note a tonic in the same sense as a common-practice key.
- **Inversional axis:** paired pitch classes can organize a passage around an axis. Verify the mapped sums; distinguish a pitch-space axis in register from a pc-space relation. Centricity is a musical interpretation of the pattern, not just a mathematical label.
- **Diatonic, pentatonic, whole-tone, octatonic and hexatonic collections:** identify membership and omissions first; then ask how the collection is partitioned, emphasized or connected to another. Diatonic collection does not require functional tonality; octatonic means alternating semitones and whole tones, not a vague synonym for dissonance. Whole-tone and symmetric collections have fewer distinct transpositions than a nonsymmetric set.
- **Interaction:** centric tones can be supported, contested or withheld within a referential collection. A work can change collections while maintaining a center, or maintain collection content while shifting the center. Source: chapter 5, beginning pp. 228–241.

### Chapter 6: Ordered twelve-tone structures

- **Twelve-tone row / series:** ordered presentation of twelve distinct pitch classes. **Aggregate:** all twelve pitch classes without an order claim. Mere chromatic completeness is not proof of serial composition.
- **Row operations:** prime, inversion, retrograde and retrograde inversion concern ordered relations. A row matrix enumerates possible forms; it does not identify which are present, how segmented rows interlock or which relations listeners notice. Name the indexing convention before reporting P/I/R/RI labels.
- **Invariance and partition:** inspect retained segments, shared content and how rows divide into trichords, tetrachords or hexachords. Collections within a row can support motives and harmonies independently of the complete ordering. Verify whether an apparent repetition is literal, transformed, reordered or merely a shared subset.
- **Combinatoriality:** appropriately transformed collections combine to complete an aggregate. For hexachords, distinguish mapping onto a complement from mapping onto itself, and specify T or I as relevant. Straus distinguishes P-, I-, R- and RI-combinatoriality; the existence of complementary halves in one row is not by itself evidence of a musically exploited combinatorial strategy. Source: chapter 6, pp. 322–325.
- **Varieties of twelve-tone music:** row identification starts an analysis rather than ending it. Examine motivic partitioning, voice leading, register, rhythm and formal placement. Avoid treating serial design as a guarantee of unity, difficulty, emotional coldness or merit.

## Worked Example

**Z-related all-interval tetrachords** (chapter 3, §3.6, Example 3-20, Carter's String Quartet No. 2). Straus describes instrument-specific intervals combining vertically into (0146) and (0137), and a later juxtaposition of melodic and harmonic forms of the two classes. Their common vector is not a license to identify them as the same set class.

Reconstruct the numerical check: the six distinct pairs in {0,1,4,6} yield interval classes 1,4,6,3,5,2; those in {0,1,3,7} yield 1,3,5,2,6,4. Both therefore give `[111111]`, yet no T or I maps one entire set onto the other. The interpretation must return to Carter's distribution across instruments and time. The calculation alone establishes neither an audible emotion nor the quartet's aesthetic success.

For comparison, the project illustration `{0,1,4} → {3,4,7}` is exactly T3, and `{0,1,4} → {0,8,11}` is I0. These examples demonstrate the operations only; they are not additional claims about Carter.

## Decision Rules & Judgment

- Require reliable pitches and segmentation before exact calculations. With damaged OCR, request a legible passage or give a conditional method; do not invent an accidental, row or Forte number.
- State what the abstraction discards, especially order, register, rhythm, spelling and timbre. Restore those dimensions for interpretation.
- Distinguish literal identity, pc identity, T/I-equivalence, equal vectors, inclusion and contour resemblance.
- Check arithmetic independently. A correct transformation is not proof of compositional intention or perceptual salience.
- Treat centric, modal, triadic and serial organizations as potentially interacting, not an obligatory ladder away from tonality.
- Use pitch tools where pitch relations answer the question. Sound masses, noise, tuning systems outside the twelve-pc model and production-led form require other descriptions.

## Key Takeaways

A post-tonal account should explain which relations recur and transform, how the music makes them available, and what other dimensions change their significance. It should never use “atonal” as a substitute for analysis or as an aesthetic verdict.
