# Extraction, recovery and evidence limits

The first-party extractor used PyMuPDF on the four requested PDFs. Three had usable text, with damaged OCR or missing symbolic notation in places. Del Mar yielded only 864 characters over 529 pages and was correctly rejected as a textless scan. Local Tesseract OCR at 155 dpi recovered all 529 pages into private scratch. No alternative book or external service was substituted. No source files or OCR text are distributed.

The first three sources were split once using the extractor's metadata start/end lines; the resulting source-local renditions were reused. Del Mar's rendition includes physical page markers. Every substantive read was a bounded slice, cleaned without modifying the corpus. Navigation probes located chapters and concepts; the author did not read the entire extracted text. Some multi-slice outputs were truncated. Recorded cleaned-token counts and source-span coverage for those reads are conservative upper bounds, not proof that every line was visible. The focused Berliner inner-dialogue reread resolved the relevant truncated material.

Prose was selected in text mode despite the books' notation. This is an explicit selective extraction boundary: the output does not reproduce complete scores, exercises or timing tables. Chapter counts were checked against contents, not accepted from automatic detection (which returned 3, 3 and 12 for the first three books). Retained counts are 16 Berliner numbered chapters, 6 Monson chapters, 11 Danielsen chapters and 6 Del Mar major sections. Introduction/epilogue/apparatus and internal subdivisions are documented but not used to inflate budgets.

## Visual inspections actually performed

- Danielsen PDF p. 11 / printed ix: confirmed chapters 9–11, resolving detached OCR numbering.
- Danielsen PDF p. 92 / printed 76: inspected figure 7 and the start of the Sex Machine discussion. This was the initial search hit, not figure 8.
- Danielsen PDF p. 93 / printed 77: inspected figure 8, its four labeled layers and the adjacent discussion of Starks and the Collins brothers. The worked example follows her prose; no independent onset measurement was made.
- Monson PDF p. 182 / printed 170: verified the account of Tucker's turnaround and the accompanists' adjustment into the seventh chorus. This supports an attributed example, not a new audition.
- Del Mar PDF/printed p. 123: verified the mutes discussion and the Dvořák Largo example.
- Del Mar PDF/printed p. 178: verified bassoon–horn blend and the source's historical qualification about changed instruments. Exact pitches were not transcribed.

Berliner locators use chapter titles rather than inventing print-page numbers for the digital PDF. Monson and Danielsen references use printed pages with their checked PDF offsets; Del Mar locators use printed pages coinciding with inspected physical PDF pages. Visual checks cover selected claims only. No recording was auditioned, and no unsupported instrumentation, voicing, timing or interaction was inferred.

The reference budgets are provisional ceilings/targets computed by the metatool, not required lengths. Actual references are deliberately shorter. The always-loaded core must remain under the 4,500-token body cap; on-demand references preserve detail. The source-language default remains English, with explicit user language requests overriding it.
