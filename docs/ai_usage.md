AI Use Log

Quick notes on how I used AI for Beginning Bioinformatics (Part 3). I wrote and ran the final code myself, and I confirmed results with toy inputs and sample datasets.

1 — Python refreshers (variables + types)
AI provided short demonstrations of strings, ints, floats, and how type() works. I edited examples to use my own values (like student_id) and printed extra checks. Verified by matching expected type outputs.

2 — Basic slicing and lists
Asked for simple slice/index patterns. AI gave draft snippets; I rewrote variable names and added comments about 0-based indexing. Verified by running on my custom lists and checking slice results.

3 — DNA transcription
Prompted AI for both plain-Python (replace) and Biopython (Seq.transcribe) solutions. I simplified the cleaning step and kept both versions in my notebook. Verified by ensuring sequence lengths match and outputs only contain A/U/G/C.

4 — File handling examples
AI showed patterns for read(), readlines(), and loops. I swapped in my own practice file and used .rstrip() to avoid blank lines. Verified by checking even-line printing matches expectations.

5 — Word counts
Asked AI for both collections.Counter and dictionary-only approaches. I reformatted outputs to print in sorted order. Verified by comparing with a short handmade sentence.

6 — FASTA + GC-content
Got a scaffold using SeqIO.parse and gc_fraction. I adjusted to round decimals and added a safeguard for empty sequences. Verified by hand-checking one record and ensuring the max matches expectation.

7 — Other Rosalind tasks (translation, Hamming, Mendel’s law)
AI gave starter code; I rewrote loops/conditions for clarity. Verified by cross-checking against Rosalind sample outputs and small test cases.

Closing note
AI mainly acted as a helper for patterns and syntax. I customized all final code and validated correctness with small examples before submitting.
