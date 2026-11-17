Java Code Commenting Dataset – Curated Version
====================================================

Dataset size: 25 Java source files, identified as C01–C25.
All source files are copied unchanged from the supplied repository snapshots.
No comments were inserted, deleted, or edited.

Comment screening:
- 9 files contain no Java comments.
- 16 files contain exactly one Java comment block/line.
- No file contains more than one detected comment block/line.
- Comment-like text inside Java string and character literals is excluded.

Quality checks performed:
- 25 unique source-file hashes; no byte-identical duplicates.
- Repeated/near-duplicate examples from the earlier draft were removed.
- Selected files cover multiple categories; see Dataset_Metadata.csv.
- Each selected source file has a class declaration and is not a test source.

Repositories:
- TheAlgorithms/Java: https://github.com/TheAlgorithms/Java
- otuemre/dsa-Java: https://github.com/otuemre/dsa-Java

Package contents:
- codes/: original Java files named C01–C25.
- Dataset_Metadata.csv: ID, category, repository, original path, URL, comment counts, SHA-256.

Limitations:
This preparation checks source-file structure and duplicate hashes, not full project compilation or runtime behavior.
Some algorithms may require their repository project dependencies or supporting classes.
GitHub URLs point to the master branch. For academic reproducibility, record the exact source commit IDs.

Additional curation note: the factorial-recursion sample was replaced with a floor-function implementation to avoid overlapping factorial examples.
