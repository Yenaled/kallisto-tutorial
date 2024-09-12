kallisto | bustools
===================

The `kallisto <https://github.com/pachterlab/kallisto>`_, `bustools <https://github.com/BUStools/bustools>`_, and `kb-python <https://github.com/pachterlab/kb_python>`_ programs are free, open-source software tools that are used together to perform RNA-seq quantification.


.. note::

   This is unofficial documentation that is under active development.

A paper describing the protocols is available as follows:

* `Protocols Manual <https://www.biorxiv.org/content/10.1101/2023.11.21.568164v2.full.pdf>`_
* `Supplementary Manual <https://www.biorxiv.org/content/biorxiv/early/2024/01/23/2023.11.21.568164/DC1/embed/media-1.pdf>`_

.. toctree::
   :maxdepth: 2
   :caption: Overview:

   introduction  # only text, background, link to protocols paper
   references
   list of tools that use kb

.. toctree::
   :maxdepth: 2
   :caption: Quick Start:

   installation + getting_started    # only pip, quick start guide + link to colab notebook

.. toctree::
   :maxdepth: 1
   :caption: Bulk RNA seq:
      Pseudoalignment
      Tutorials
         use with edgeR

.. toctree::
   :maxdepth: 1
   :caption: Single-cell RNA seq:
      Technologies and the x-string (link to seqspec)
      Pseudoalignment
         standard
         matrices
         (link to translated alignment section)
      Tutorials
         Biophysical modeling
         use with Seurat
         use with scanpy

.. toctree::
   :maxdepth: 1
   :caption: long reads:
      Pseudoalignment
         bulk
         single-cell
      Tutorials
         Longer tutorial

.. toctree::
   :maxdepth: 1
   :caption: ATAC seq:
      Pseudoalignment
      Tutorials

.. toctree::
   :maxdepth: 1
   :caption: Translated pseudoalignment:
      Pseudoalignment
      Tutorials
         virus_detection

.. toctree::
   :maxdepth: 1
   :caption: Using seqspec:

.. toctree::
   :maxdepth: 1
   :caption: Manuals:

   kallisto
      bus
   bustools
      count
      extract
   kb_python
      ref
      count
      extract

.. toctree::
   :maxdepth: 1
   :caption: Advanced installation:

   installation from source

.. toctree::
   :maxdepth: 1
   :caption: Advanced bustools:

   tasks you can do with bustools

.. toctree::
   :maxdepth: 1
   :caption: FAQ:



If you are using kallisto, bustools, or kb-python in a publication:   

- **Please cite:**  
   protocols paper

- **When performing alignment of single-cell RNA seq data, please also cite:**  
   Melsted P*, Booeshaghi AS*, Liu L, Gao F, Lu Lambda, Min KH, da Veiga Beltrame E, Hjörleifsson KE, Gehring J, Pachter L. `Modular, efficient and constant-memory single-cell RNA-seq preprocessing. <https://doi.org/10.1038/s41587-021-00870-2>`_ Nature Biotechnology 39, 813–818 (2021). https://doi.org/10.1038/s41587-021-00870-2

- **When performing alignment of bulk RNA seq data or referencing pseudo-alignment, please also cite:**  
   Bray N, Pimentel H, Melsted P, Pachter L. `Near-optimal probabilistic RNA-seq quantification. <https://doi.org/10.1038/nbt.3519>`_ Nature Biotechnology 34, 525–527 (2016). https://doi.org/10.1038/nbt.3519

- **When analyzing long-read RNA seq data, please also cite:**  
   Bekka's paper

- **When performing translated alignment, please also cite:**  
   Veira paper

**Additional relevant paper(s):**  

Melsted P*, Ntranos V*, Pachter L*. `The barcode, UMI, set format and BUStools. <https://doi.org/10.1093/bioinformatics/btz279>`_ Bioinformatics 35(11), 4472–4473 (2019). https://doi.org/10.1093/bioinformatics/btz279
