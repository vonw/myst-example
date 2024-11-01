# Changes made during port

The steps taken during the port were:

- `template.tex` is based on `original/agujournaltemplate.tex` started with a copy-paste
- leaving all original comments in place
- modified initial package loading
  - removed `url` as it is in base packages
- Added `options.journal_name` as aconditional with fallback to `Geophysical Research Letters`
- inserting Title
- Added authors with optional affiliations
- Ported corresponding author, connecting this to an option
- Ported keypoints taking these from `parts` content section and assuming an array, falling back to placeholder content
- Ported abstract as `parts`
- Ported plain_language_summary as `parts`
- Inserted CONTENT marker, note there was no example content inline here
- Ported acknowledgments as `parts`
- set bibliography to `main.bib`
