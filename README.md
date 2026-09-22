# Aural Cartographer

I begin with the moment a record earns—or loses—your attention. If a close, dry voice moves you in one song and irritates you in another, I want to understand the difference: the phrasing, the surrounding instruments, the person the recording seems to place before you, or the situation in which you heard it. I can judge a work highly while expecting you not to enjoy it. Those are different conclusions, and I keep their reasons visible.

I build a map from those distinctions. One route might lead to an earlier recording practice; another to a different genre that solves a similar musical problem. A third might deliberately test my theory of your taste. I recommend a few encounters with a reason to hear each, and I keep the exceptions when your response surprises me. I also question my own dislikes: dismissing a performance as sentimental is only the start of explaining what its sentiment does and whether it works.

When a passage feels tense, expansive or strange, I ask what changed: the bass and inner voices, a delayed cadence, the size of the phrases, a pitch-class relation, the performer’s timing or the recording’s space. I explain how those relations unfold before asking what they express and whether they serve the work. A pop loop need not behave like a Classical period; a Romantic fragment need not close like a Haydn theme. I carry formal knowledge into record criticism and bring the realities of performance, mediation and taste back to the score.

I work with the evidence available. If I have no access to the audio, I can use an attributed analysis or your account, but I will not invent what I heard. My purpose is to help you understand recordings, their histories and your changing judgments—not to turn every question into a prediction of your next favorite song.

## What this repository provides

A directly usable Agent Skill, with five connected lines of work:

| Line of work | Typical result |
|---|---|
| Critical judgment | A reasoned account of a recording's project, means and achievement |
| Genealogy and curation | Version-aware records and historically qualified connections |
| Discovery | A short route for deepening, historical inquiry, structural analogy or disconfirmation |
| Taste research | A revisable hypothesis with context, rivals, exceptions and a next comparison |
| Structural analysis | Repertoire-sensitive accounts of harmony, counterpoint, rhythm, formal function and post-tonal organization |

The core now connects twenty-one source works in one expert, retaining the original four roles and all twelve first-round references. Nine additions extend structural analysis and Western art-music history. Each source work has one canonical reference; Taruskin’s five-volume omnibus remains one on-demand historical layer. This is a knowledge skill, not a streaming integration, audio-analysis engine, database application or automatically persistent listener profile.

## Layout

```text
Aural-Cartographer/
├── SKILL.md
├── references/                   # 21 source-specific runtime references
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

The project discovery alias points to the root skill. Hosts that do not preserve symlinks can load the root `SKILL.md` directly, with `references/` beside it. For a personal installation, copy or link the complete root skill/reference tree into the host's configured skills location under `aural-cartographer`; do not copy only `SKILL.md` and leave its links broken. Read `AGENTS.md` for project behavior.

The default response language is **English**, matching the substantive supplied corpus. An explicit request such as “请用中文回答这次分析” overrides it for that scope.

Example requests:

- “I admire this album but rarely want to replay it. Help me separate its achievement from my liking. Here are the passages I notice…”
- “Compare these two specified recordings of the same song using my listening notes. Mark what you cannot establish without audio.”
- “Give me three routes out from this track: one historical, one structural analogy and one that tests your hypothesis about my taste.”
- “This song feels sentimental while that one moves me. Keep both cases and help me identify what difference matters.”
- “Organize these releases without merging alternate mixes, recording dates and reissues.”
- “Here is a legible passage. Separate the notes and formal functions from your expressive interpretation and aesthetic judgment.”
- “Compare what Meyer and Huron explain about this delayed resolution, including what neither can tell you about my taste.”
- “Build a route from this pop texture into twentieth-century art music. Distinguish documented lineage from useful analogy.”

The host loads the core first and normally opens one to three references when their depth is needed. It should answer the musical question rather than display the internal routing process. No audio access or connected account is assumed.

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

The critic's main analytical line joins Frith, Moore and Zak. Hennion, DeNora and Huron inform different parts of listener research. Brackett, Lena, Wald and Katz support historically grounded curation. Wilson scrutinizes the critic's exclusions; *Spotify Teardown* scrutinizes discovery's platform assumptions. Their disagreements remain visible.

Laitz, Caplin and Straus provide different structural tools; Cook governs method choice. Rosen and Meyer connect musical relations to aesthetic interpretation, with Meyer explicitly compared to Huron. Taruskin and Ross extend the historical map alongside Brackett and Wald. Composition, arrangement, performance and recorded construction remain distinct throughout.

## Coverage and limits

The references preserve selected frameworks, conditions, examples and judgment rules useful for this project. They are not chapter-complete substitutes for the books. In particular, Wilson's expanded edition contains other authors' essays: two dissenting responses are represented explicitly, while the other response essays and afterword are outside detailed coverage. Hennion's art-historical disputes and the historical repertory surveys are compressed. See the [coverage ledger](fidelity-ledger/source-and-coverage-ledger.md).

Recorded popular music remains the foundation, now extended into Western art-music structure and history. The corpus does not establish expertise in every musical tradition, and its tonal/Classical/post-tonal tools are not universal laws. Taruskin is selectively sampled across all five volumes; detailed historical questions may require the original chapter. Technical notation and complete exercise sequences are not reproduced. Historical platform findings and older empirical proposals need current verification when used for current factual claims. Converted score examples, diagrams and tables are not treated as reliable audio or notation evidence.

## Build and verification

Built and expanded on 2026-09-22. Round one used eleven Markdown conversions and one PDF; round two adds eight Markdown works and the supplied *Classical Style* PDF. Its listed Markdown file was absent, so the scanned PDF was recovered with OCR. Local sibling PDFs supplied front-matter, prose and selected notation checks; they are verification copies of the same works, not additional sources. Bounded source excerpts informed the distillation; original files and intermediate extraction text are not included. The [manifest](fidelity-ledger/source-manifest.json) records editions, source hashes, structure counts and estimated sizes without private absolute paths.

Structural validation, separate core/reference instruction scans and link/symlink checks are recorded with actual outputs in [validation records](fidelity-ledger/validation.json). [Editorial evaluation](fidelity-ledger/evaluation.md) explains the decisions reviewed and their limits. Independent fresh-context baseline/core/core-plus-references behavioral comparison has **not been run**; no claim of measured improvement over a general model is made. The frozen development/final [scenario suite](fidelity-ledger/acceptance-suite.json) now retains all eight original scenarios and adds eight for the expansion. It is available for a future controlled run. Original evidence is archived under `fidelity-ledger/round-1/`; fold-in preservation and coverage records are under `fidelity-ledger/round-2/`.

## License

[MIT](LICENSE) applies to the original skill instructions, synthetic reference text and project documentation. The books, recordings, lyrics and other third-party works retain their own rights. No source books or audio are distributed.
