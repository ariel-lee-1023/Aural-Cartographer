# Aural-Cartographer

I begin with the moment a record earns—or loses—your attention. If a close, dry voice moves you in one song and irritates you in another, I want to understand the difference: the phrasing, the surrounding instruments, the person the recording seems to place before you, or the situation in which you heard it. I can judge a work highly while expecting you not to enjoy it. Those are different conclusions, and I keep their reasons visible.

I build a map from those distinctions. One route might lead to an earlier recording practice; another to a different genre that solves a similar musical problem. A third might deliberately test my theory of your taste. I recommend a few encounters with a reason to hear each, and I keep the exceptions when your response surprises me. I also question my own dislikes: dismissing a performance as sentimental is only the start of explaining what its sentiment does and whether it works.

I work with the evidence available. If I have no access to the audio, I can use an attributed analysis or your account, but I will not invent what I heard. My purpose is to help you understand recordings, their histories and your changing judgments—not to turn every question into a prediction of your next favorite song.

## What this repository provides

A directly usable Agent Skill, with four distinct lines of work:

| Line of work | Typical result |
|---|---|
| Critical judgment | A reasoned account of a recording's project, means and achievement |
| Genealogy and curation | Version-aware records and historically qualified connections |
| Discovery | A short route for deepening, historical inquiry, structural analogy or disconfirmation |
| Taste research | A revisable hypothesis with context, rivals, exceptions and a next comparison |

The core synthesizes methods from twelve supplied books. Each has one canonical, independently loadable reference. This is a knowledge skill, not a streaming integration, audio-analysis engine, database application or automatically persistent listener profile.

## Layout

```text
Aural-Cartographer/
├── SKILL.md
├── references/                   # 12 source-specific runtime references
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

The critic's main analytical line joins Frith, Moore and Zak. Hennion, DeNora and Huron inform different parts of listener research. Brackett, Lena, Wald and Katz support historically grounded curation. Wilson scrutinizes the critic's exclusions; *Spotify Teardown* scrutinizes discovery's platform assumptions. Their disagreements remain visible.

## Coverage and limits

The references preserve selected frameworks, conditions, examples and judgment rules useful for this project. They are not chapter-complete substitutes for the books. In particular, Wilson's expanded edition contains other authors' essays: two dissenting responses are represented explicitly, while the other response essays and afterword are outside detailed coverage. Hennion's art-historical disputes and the historical repertory surveys are compressed. See the [coverage ledger](fidelity-ledger/source-and-coverage-ledger.md).

The corpus is predominantly about Western recorded popular music, with limited comparative cases. It does not establish expertise in every musical tradition. Historical platform findings and older empirical proposals need current verification when used for current factual claims. Converted score examples, diagrams and tables are not treated as reliable audio or notation evidence.

## Build and verification

Built on 2026-09-22 from eleven user-supplied Markdown conversions and one PDF. Bounded source excerpts informed the distillation; original files and intermediate extraction text are not included. The [manifest](fidelity-ledger/source-manifest.json) records editions, source hashes, structure counts and estimated sizes without private absolute paths.

Structural validation, separate core/reference instruction scans and link/symlink checks are recorded with actual outputs in [validation records](fidelity-ledger/validation.json). [Editorial evaluation](fidelity-ledger/evaluation.md) explains the decisions reviewed and their limits. Independent fresh-context baseline/core/core-plus-references behavioral comparison has **not been run**; no claim of measured improvement over a general model is made. The frozen development/final [scenario suite](fidelity-ledger/acceptance-suite.json) is available for a future authorized run.

## License

[MIT](LICENSE) applies to the original skill instructions, synthetic reference text and project documentation. The books, recordings, lyrics and other third-party works retain their own rights. No source books or audio are distributed.
