# Integrated Multi-Omics Reveal Polycomb Repressive Complex 2 Restricts Human Trophoblast Induction
:tada: **Welcome** to the GitHub repository for our manuscript entitled ["Integrated Multi-Omics Reveal Polycomb Repressive Complex 2 Restricts Human Trophoblast Induction"](https://www.nature.com/articles/s41556-022-00932-w).

## Code availability
**Scripts** related to the manuscript from Pasque lab are available in this GitHub repository in [SCRIPTS](SCRIPTS) directory.

## Shiny App for multi-omic data exploration 
The multi-omic data comprising **acid extractome protein abundance**, **chromatin-associated protein abundance**, **gene expression** and **histone modifications** for naive and primed hPSCs +/- PRC2i can be explored using the online resource: https://www.bioinformatics.babraham.ac.uk/shiny/shiny_omics/Shiny_omics.

## Loom files for scRNAseq data visualization
As a resource to community we provide 2 Loom files that contain UMAP-clustering, cluster annotation and gene expression from: 

**1.** The scRNA-seq datasets sequenced on this study (naive hPSCs and day 4 of trophoblast conversion +/- PRC2 inhibition).

**2.** Integration of day 4 of trophoblast conversion +/- PRC2 inhibition with early human embryo datasets [Petropoulos et al., 2016](https://www.cell.com/cell/fulltext/S0092-8674(16)30280-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS009286741630280X%3Fshowall%3Dtrue) and [Zhou et al., 2019](https://www.nature.com/articles/s41586-019-1500-0).

You can browse interactively these two loom files using [SCope platform/PRC2](https://scope.aertslab.org/#/HumanPluripotencyPRC2/*/welcome), click on the arrow found on the left of the screen under DATASETS > Session Looms > Uncategorized, and select the non-integrated dataset or the human embryo integrated dataset to display and browse.

Loom files can be downloaded here: [GSE176173](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE176173) using the http links at the bottom of the page. After unzipping, you can browse interactively using [SCope platform](https://scope.aertslab.org/#/0e367043-465c-442d-8b64-4af393567818/*/welcome). In order to browse the datasets, upload loom files by clicking on "Upload new dataset" in the menu on the left-side of SCope website. Uploading may take a few minutes. Successful upload will activate a private, temporary session for the user. Each session expires after 5 days, but can be renewed by re-uploading the loom file. 

Standalone SCope apps for macOS and Linux can be downloaded from [here](https://github.com/aertslab/SCope/releases).

SCope was developed and is maintained by [Aerts lab](https://www.aertslab.org/).

## Data availability
Raw and processed sequencing data for **cCUT&RUN**, **RNA-seq** and **scRNA-seq** can be found here: [GSE176175](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE176175).

The **ChEP mass spectrometry proteomics data** can be found here: [PXD028111](https://www.ebi.ac.uk/pride/).

The **hPTM mass spectrometry proteomics data** can be found here: [PXD028162](https://www.ebi.ac.uk/pride/) and [PXD032792](https://www.ebi.ac.uk/pride/).
