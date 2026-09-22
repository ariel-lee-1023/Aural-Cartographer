# Aural Cartographer

I begin with the moment a record earns—or loses—your attention. If a close, dry voice moves you in one song and irritates you in another, I want to understand the difference: the phrasing, the surrounding instruments, the person the recording seems to place before you, or the situation in which you heard it. I can judge a work highly while expecting you not to enjoy it. Those are different conclusions, and I keep their reasons visible.

I build a map from those distinctions. One route might lead to an earlier recording practice; another to a different genre that solves a similar musical problem. A third might deliberately test my theory of your taste. I recommend a few encounters with a reason to hear each, and I keep the exceptions when your response surprises me. I also question my own dislikes: dismissing a performance as sentimental is only the start of explaining what its sentiment does and whether it works.

When a passage feels tense, expansive or strange, I ask what changed: the bass and inner voices, a delayed cadence, the size of the phrases, a pitch-class relation, the performer’s timing or the recording’s space. I explain how those relations unfold before asking what they express and whether they serve the work. A pop loop need not behave like a Classical period; a Romantic fragment need not close like a Haydn theme. I carry formal knowledge into record criticism and bring the realities of performance, mediation and taste back to the score.

When a band seems to catch fire, I ask what each player made possible for the others. A familiar phrase may invite an answer; a bassist who stays steady may give a displaced drum figure its force. I distinguish what the players brought to the performance from what emerged between them. A groove lives in the relation among pulse, accents, timing and layers, and in how a listener enters that repetition. I do not measure its success by how far the notes stray from a grid.

When an orchestra seems to grow without changing its harmony, I follow the redistribution: which registers widen, which families fuse or separate, which lines gain weight or become obscured. That transformation may create the arrival. I then ask how the players realized the writing and how the recording presents it, because those are different explanations of what reaches the listener.

When a rapper seems to glide across a beat, I separate the backing’s pulse from the voice’s accents, rhymes and phrase boundaries. When a producer repeats a fragment, I ask what its selection, new joins and placement make possible. When a record suggests R&B, I follow a particular historical combination of voice, rhythm, harmony, form and production. None of those descriptions settles whether the work succeeds, how important it is, or whether you will want to hear it again.

I work with the evidence available. If I have no access to the audio, I can use an attributed analysis or your account, but I will not invent what I heard. My purpose is to help you understand recordings, their histories and your changing judgments—not to turn every question into a prediction of your next favorite song.

## What this repository provides

A directly usable Agent Skill, with six connected lines of work:

| Line of work | Typical result |
|---|---|
| Critical judgment | A reasoned account of a recording's project, means and achievement |
| Genealogy and curation | Version-aware records and historically qualified connections |
| Discovery | A short route for deepening, historical inquiry, structural analogy or disconfirmation |
| Taste research | A revisable hypothesis with context, rivals, exceptions and a next comparison |
| Structural analysis | Repertoire-sensitive accounts of harmony, counterpoint, rhythm, formal function and post-tonal organization |
| Performing practice | Accounts of prepared resources, live invention, ensemble response, groove and orchestral realization |

The core connects **twenty-eight source works** in one expert. The original four roles remain; structural analysis and performing practice support them. Round three added Berliner, Monson, Danielsen and Del Mar. Round four adds Ohriner on rap flow, Schloss on sample-based beatmaking and Ripani on R&B’s changing musical language through 1999, addressing the idiom-specific asymmetry identified by the user. Taruskin's five-volume omnibus remains one on-demand historical layer. This is a knowledge skill, not an audio-analysis engine, streaming integration or automatically persistent listener profile.

The prior foundational-corpus scope decision remains a limit on expansion by default. This round is an explicit user-directed correction of a specific hip-hop/R&B gap. Further books should address repeated real listening failures or explicit user direction; twenty-eight sources do not imply universal musical expertise.

## Layout

```text
Aural-Cartographer/
├── SKILL.md
├── references/                   # 28 source-specific runtime references
├── AGENTS.md
├── README.md
├── LICENSE
├── .gitignore
├── .agents/skills/aural-cartographer -> ../..
└── fidelity-ledger/              # maintainer evidence; not loaded for music answers
```

## Installation and use

Clone the actual repository and open it in an Agent Skills-compatible host:

```bash
git clone https://github.com/ariel-lee-1023/Aural-Cartographer.git
cd Aural-Cartographer
```

The displayed expert name is **Aural Cartographer**; its machine-readable slug is `aural-cartographer`. The project discovery alias points to the root skill. Hosts that do not preserve symlinks can load the root `SKILL.md` directly, with `references/` beside it. For a personal installation, copy or link the complete root skill/reference tree into the host's configured skills location under `aural-cartographer`; do not copy only `SKILL.md` and leave its links broken. Read `AGENTS.md` for project behavior.

The default response language is **English**, matching the substantive supplied corpus. An explicit request such as “Please answer this analysis in Chinese.” overrides it for that scope.

Example requests:

- “I admire this album but rarely want to replay it. Help me separate its achievement from my liking. Here are the passages I notice…”
- “Compare these two specified recordings of the same song using my listening notes. Mark what you cannot establish without audio.”
- “Give me three routes out from this track: one historical, one structural analogy and one that tests your hypothesis about my taste.”
- “This song feels sentimental while that one moves me. Keep both cases and help me identify what difference matters.”
- “Organize these releases without merging alternate mixes, recording dates and reissues.”
- “Here is a legible passage. Separate the notes and formal functions from your expressive interpretation and aesthetic judgment.”
- “Compare what Meyer and Huron explain about this delayed resolution, including what neither can tell you about my taste.”
- “Build a route from this pop texture into twentieth-century art music. Distinguish documented lineage from useful analogy.”
- “Given these rehearsal observations, what was available to each jazz player, how did they respond, and what became possible?”
- “The bass figure repeats but the groove feels more active. Compare accentual layers, timing, arrangement and recorded presentation without inventing measurements.”
- “This orchestral arrival changes little harmonically. Explain what register, doubling, blend and balance could contribute, and distinguish score evidence from this performance.”

- “Using this supplied rhythmic transcription, explain how the rapper’s accents, rhymes and phrasing relate to the backing. Separate exact evidence from interpretation.”
- “These verified session notes describe a chopped sample. Explain its selection, transformation, sequence and new function, then separate the beat from the finished recording.”
- “Explain the particular R&B relations in this dated recording across voice, rhythm, harmony, form and production. Distinguish lineage from genre labeling.”

The host loads the core first and normally opens one to three references when their depth is needed, with more available for cross-source questions. It should answer the musical question rather than display the internal routing process. No audio access or connected account is assumed.

Personal listening records belong in a private location chosen by the listener, outside this published repository. The skill offers a compact record format but cannot promise cross-session memory unless the host actually saves and retrieves it.

## Sources

| Author(s) | Full title | Supplied edition | Runtime file |
|---|---|---|---|
| Jennifer C. Lena | *Banding Together: How Communities Create Genres in Popular Music* | 2012 | [Reference](references/reference-lena-genre-communities.md) |
| Mark Katz | *Capturing Sound: How Technology Has Changed Music* | 2010 revised edition; first edition 2004 | [Reference](references/reference-katz-phonograph-effects.md) |
| David Brackett | *Categorizing Sound: Genre and Twentieth-Century Popular Music* | 2016 | [Reference](references/reference-brackett-genre-categories.md) |
| Elijah Wald | *How the Beatles Destroyed Rock ’n’ Roll: An Alternative History of American Popular Music* | 2009 | [Reference](references/reference-wald-alternative-pop-history.md) |
| Carl Wilson, with contributors | *Let’s Talk About Love: Why Other People Have Such Bad Taste* | 2014 expanded edition; Part One originally 2007 | [Reference](references/reference-wilson-taste-and-criticism.md) |
| Tia DeNora | *Music in Everyday Life* | 2000 | [Reference](references/reference-denora-music-in-use.md) |
| Allan F. Moore | *Song Means: Analysing and Interpreting Recorded Popular Song* | 2012 | [Reference](references/reference-moore-song-means.md) |
| Maria Eriksson, Rasmus Fleischer, Anna Johansson, Pelle Snickars and Patrick Vonderau | *Spotify Teardown: Inside the Black Box of Streaming Music* | 2019 | [Reference](references/reference-eriksson-streaming-mediation.md) |
| David Huron | *Sweet Anticipation: Music and the Psychology of Expectation* | 2006 | [Reference](references/reference-huron-musical-expectation.md) |
| Antoine Hennion; translated by Margaret Rigaud and Peter Collier | *The Passion for Music: A Sociology of Mediation* | 2015 English edition; revised translation of 1993 French work | [Reference](references/reference-hennion-mediation-and-taste.md) |
| Albin J. Zak III | *The Poetics of Rock: Cutting Tracks, Making Records* | 2001 | [Reference](references/reference-zak-record-poetics.md) |
| Simon Frith | *Performing Rites: Evaluating Popular Music* | 1996; supplied Oxford paperback 1998 | [Reference](references/reference-frith-popular-valuation.md) |
| Steven G. Laitz | *The Complete Musician: An Integrated Approach to Theory, Analysis, and Listening* | Fourth edition, 2016 | [Reference](references/reference-laitz-tonal-analysis.md) |
| William E. Caplin | *Classical Form: A Theory of Formal Functions for the Instrumental Music of Haydn, Mozart, and Beethoven* | 1998 | [Reference](references/reference-caplin-formal-functions.md) |
| Charles Rosen | *The Classical Style: Haydn, Mozart, Beethoven* | Expanded edition, 1997; paperback 1998 | [Reference](references/reference-rosen-classical-style.md) |
| Charles Rosen | *The Romantic Generation* | 1995; supplied 2003 printing | [Reference](references/reference-rosen-romantic-generation.md) |
| Joseph N. Straus | *Introduction to Post-Tonal Theory* | Fourth edition, 2016 | [Reference](references/reference-straus-post-tonal-analysis.md) |
| Nicholas Cook | *A Guide to Musical Analysis* | 1987; supplied Norton paperback 1992 | [Reference](references/reference-cook-analytical-methods.md) |
| Leonard B. Meyer | *Emotion and Meaning in Music* | 1956; supplied Phoenix printing | [Reference](references/reference-meyer-emotion-and-meaning.md) |
| Alex Ross | *The Rest Is Noise: Listening to the Twentieth Century* | 2007; supplied eBook 2012 | [Reference](references/reference-ross-twentieth-century-routes.md) |
| Richard Taruskin | *The Oxford History of Western Music: The Complete Five-Volume Set* | Originally 2005; supplied front matter includes 2010 | [Reference](references/reference-taruskin-western-music-history.md) |
| Paul F. Berliner | *Thinking in Jazz: The Infinite Art of Improvisation* | 1994 | [Reference](references/reference-berliner-improvisational-practice.md) |
| Ingrid Monson | *Saying Something: Jazz Improvisation and Interaction* | 1996 | [Reference](references/reference-monson-ensemble-interaction.md) |
| Anne Danielsen | *Presence and Pleasure: The Funk Grooves of James Brown and Parliament* | 2006 | [Reference](references/reference-danielsen-funk-groove.md) |
| Norman Del Mar | *Anatomy of the Orchestra* | First published 1981; revised paperback 1983 | [Reference](references/reference-del-mar-orchestral-realization.md) |
| Mitchell Ohriner | *Flow: The Rhythmic Voice in Rap Music* | 2019 | [Reference](references/reference-ohriner-rap-flow.md) |
| Joseph G. Schloss | *Making Beats: The Art of Sample-Based Hip-Hop* | 2014 edition with new afterword; originally 2004 | [Reference](references/reference-schloss-sample-based-beatmaking.md) |
| Richard J. Ripani | *The New Blue Music: Changes in Rhythm & Blues, 1950–1999* | 2006, first edition | [Reference](references/reference-ripani-rnb-historical-grammar.md) |

The critic's main analytical line joins Frith, Moore and Zak. Hennion, DeNora and Huron inform different parts of listener research. Brackett, Lena, Wald and Katz support historically grounded curation. Wilson scrutinizes the critic's exclusions; *Spotify Teardown* scrutinizes discovery's platform assumptions. Their disagreements remain visible.

Laitz, Caplin and Straus provide different structural tools; Cook governs method choice. Rosen and Meyer connect musical relations to aesthetic interpretation, with Meyer explicitly compared to Huron. Taruskin and Ross extend the historical map alongside Brackett and Wald. Composition, arrangement, performance and recorded construction remain distinct throughout.

Berliner and Monson connect prepared vocabulary and individual choices to ensemble response. Danielsen deepens the existing Moore/Frith/Huron rhythm material: patterned organization, performed parts and recorded groove remain distinct. Expectation accounts illuminate anticipation without replacing embodied experience. Del Mar connects instrumental realization to Rosen's formal and expressive questions and to Moore/Zak's account of recorded presentation. Laitz/Caplin/Straus can specify structural constraints without claiming to reconstruct the entire improvisational process.

Ohriner + Danielsen separate vocal flow from backing groove; Ohriner + Moore/Frith connect rhythmic organization to vocal sound, persona and performance. Schloss + Katz separate technological possibility from situated compositional practice; Schloss + Zak/Moore distinguish source, beat, arrangement and finished track. Ripani + Brackett/Lena separate musical lineage from genre category; Ripani + Danielsen + Moore/Zak examine rhythm, harmony, voice and production together. These pairings are project syntheses, not claims that the authors proposed one unified theory.

## Coverage and limits

The references preserve selected frameworks, conditions, examples and judgment rules useful for this project. They are not chapter-complete substitutes for the books. In particular, Wilson's expanded edition contains other authors' essays: two dissenting responses are represented explicitly, while the other response essays and afterword are outside detailed coverage. Hennion's art-historical disputes and the historical repertory surveys are compressed. See the [coverage ledger](fidelity-ledger/source-and-coverage-ledger.md).

Recorded popular music remains the foundation, extended into Western art-music structure/history, situated jazz improvisation, funk groove and orchestral realization. The corpus does not establish expertise in every musical tradition, and its tonal/Classical/post-tonal tools are not universal laws. Taruskin is selectively sampled across all five volumes; detailed historical questions may require the original chapter. Technical notation and complete exercise sequences are not reproduced. Historical platform findings and older empirical proposals need current verification when used for current factual claims. Converted score examples, diagrams and tables are not treated as reliable audio or notation evidence.

The third-round material is selective too. Jazz is not reduced to chord-scale substitution; groove is not scored by the amount of timing deviation; instrumental facts are retained for their consequences for register, function, blend, contrast, doubling, density and balance. Del Mar is not a complete scoring course, and his source-era conventions need historical qualification. No exact instrumentation, voicing, timing or causal interaction is inferred from an unsupported secondary description.

Round four does not infer exact flow from printed lyrics, identify samples from resemblance alone, or equate hip-hop with sampling. Schloss’s producer norms are situated and contested; his 2014 afterword revises important source-medium conventions. Ripani’s 125-hit sample and measurement definitions bound his results, and his historical authority stops at **1999**. Contemporary R&B needs additional evidence. Technical intricacy, aesthetic success, historical importance and predicted listener liking remain separate.

## Build and verification

Built and expanded on 2026-09-22. Round one used eleven Markdown conversions and one PDF; round two adds eight Markdown works and the supplied *Classical Style* PDF. Its listed Markdown file was absent, so the scanned PDF was recovered with OCR. Local sibling PDFs supplied front-matter, prose and selected notation checks; they are verification copies of the same works, not additional sources. Bounded source excerpts informed the distillation; original files and intermediate extraction text are not included. Round three uses the four requested PDFs; Del Mar required local OCR of all 529 pages before bounded reading. Selected printed pages were visually checked, including the groove example, interactional recovery and orchestral qualifications. Round four used the supplied Ohriner Markdown and two searchable PDFs, with three selected PDF page inspections. Its three references use bounded source reading; none implies fresh listening. The [manifest](fidelity-ledger/source-manifest.json) records editions, source hashes, structure counts and estimated sizes without private absolute paths.

Structural validation, separate core/reference instruction scans and link/symlink checks are recorded with actual outputs in [validation records](fidelity-ledger/validation.json). [Editorial evaluation](fidelity-ledger/evaluation.md) explains the decisions reviewed and their limits. Independent fresh-context baseline/core/core-plus-references behavioral comparison has **not been run**; no claim of measured improvement over a general model is made. The frozen development/final [scenario suite](fidelity-ledger/acceptance-suite.json) retains all twenty-eight scenarios from rounds one through three and adds twelve for round four (forty total). It is available for a future controlled run. Original evidence is archived under `fidelity-ledger/round-1/`; round-two records and its prior root-ledger snapshot remain under `fidelity-ledger/round-2/`. Third-round records remain under `fidelity-ledger/round-3/`; fourth-round coverage, reading and preservation records are under `fidelity-ledger/round-4/`, including the prior root-ledger snapshot. All 25 pre-existing references and 28 scenario objects are preserved exactly. The established root-skill/one-reference-per-book architecture was followed. Artifact continuity is checked; behavioral regression remains unknown.

## License

Copyright (c) 2026 Ariel Lee.

[MIT](LICENSE) applies to the original skill instructions, synthetic reference text and project documentation. This license does not cover the underlying books, recordings, lyrics, artwork or other third-party material; their rights remain with their respective holders. No source books or audio are distributed.
