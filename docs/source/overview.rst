Overview
===============

The tools:

* **kallisto**: Maps RNA-seq reads to a reference transcriptome and stores the results in a BUS file.

* **bustools**: Processes the results in the BUS file to correct barcodes, deduplicate UMIs, and generate quantification files (e.g. count matrices).

* **kb-python**: A wrapper around kallisto and bustools that facilitates usage of those tools and facilitates the generation of a reference transcriptome. The kallisto and bustools binaries come packaged in kb-python.
