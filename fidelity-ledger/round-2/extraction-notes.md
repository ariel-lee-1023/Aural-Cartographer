# Source recovery and reading limits

The round-two request lists nine distinct works plus a PDF copy of *The Classical Style*. Its named Markdown path is absent. The supplied 547-page PDF has no text layer. Local Tesseract OCR recovered all pages to private scratch, followed by bounded selection rather than a full reading. OCR was rerun using the resolved `/private/tmp` scratch location after the first invocation failed to open images through the `/tmp` alias. Failed empty outputs were not treated as completed pages. Original books, OCR text and rendered pages are not distributed.

Eight supplied Markdown works were extracted with the metatool's technical-mode runtime. Several conversions lose front matter or scramble score/table reading order. Six existing local sibling PDFs (Laitz, Caplin, Straus, Cook, Meyer, Romantic Generation) were used to verify metadata or recover selected prose. They are alternate witnesses to the same works. Their filenames and hashes are in the manifest.

The PDF page totals in references count physical PDF pages, not printed pagination. Printed chapters/sections/pages in the reference bodies are navigation locators. Source-local line ranges in the reading ledger refer to scratch renditions and require matching the rendition and source hash; they are not printed page numbers.

## Visual checks actually made

- Straus, PDF page 62 / printed page 45: Example 2-3 normal-form rule and tie-breaking convention. Confirmed the fourth edition differs from the traditional always-bottom-packed rule; retained that qualification.
- Caplin, PDF page 22 / printed page 9: formal function versus grouping and the identity/scope of the opening Beethoven Op. 2 No. 1 example. The subsequent sentence/cadence account was checked in prose. This was not a note-by-note audit of every score example.
- Rosen, *Classical Style*, PDF page 71 / printed page 59: Mozart K. 271 opening, solo/orchestra entries and repeated grouping. Nearby prose provides Rosen's interpretation.
- Laitz, PDF page 505 / printed page 468: Example 19.6 and the larger tonal/prolongational analysis; printed explanatory prose confirms the contrasting Haydn example. This does not validate damaged notation throughout the corpus.

## Scope of claims

Each new reference reconstructs a selected framework with prerequisites, qualifications and an attributed example where study depth applies. Taruskin is reference depth: volume/chapter routes and representative causal arguments, without an invented comprehensive synopsis or a worked-example requirement. Historical source claims remain attributed and bounded; no contemporary release/availability research or audio listening was performed.

Supplementary coverage samples and targeted verification are recorded separately. Tool-output truncation affected some broad probes; those probes were not used as evidence of exhaustive coverage. The logged emitted text counts are estimates and upper bounds where an output was truncated. No controlled model evaluation, ablation experiment or measured reference gain was performed.
