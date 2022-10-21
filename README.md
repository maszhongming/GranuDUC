# GranuDUC
Dataset for EMNLP 2022 Findings Paper: *[Unsupervised Multi-Granularity Summarization](https://arxiv.org/abs/2201.12502)*

GranuDUC includes 50 document clusters, as well as manually annotated summaries of three different semantic coverage for each cluster. Due to the copyright issue of DUC 2004, we only provide our annotated summary here, excluding the source files.

For each document cluster in ```GranuDUC_summary.json```:

* ```doc_id```: The document identifier in DUC 2004. Please request [DUC 2004 data](https://duc.nist.gov/duc2004/) and then get the source documents for each sample by ```doc_id```.
* ```summary_1```: coarse-grained summary.
* ```summary_2```: medium-grained summary.
* ```summary_3```: fine-grained summary.
