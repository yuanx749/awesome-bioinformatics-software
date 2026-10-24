# Awesome Bioinformatics Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Computational analysis of biological sequences, omics data, and molecular structures.

A curated directory of bioinformatics software organized by research area and analysis task, with package download statistics, GitHub activity, and publication links. Updated regularly.

**239 tools | 9 domains | 48 task groups | Downloads: 2026-09 | Repository snapshot: 2026-10-25**

- Tools are listed alphabetically within each task group. Stars are GitHub-only and are not a quality score.
- Download counts cover the period shown above. They cannot be compared across sources or added together, and do not represent unique users.
- Updated is the latest commit date.
- `-` indicates unavailable data.

## Contents

- [Core & Shared Tools](#core--shared-tools) (32)
- [Sequence & Genome Analysis](#sequence--genome-analysis) (54)
- [Genetics & Evolution](#genetics--evolution) (23)
- [Transcriptomics & Epigenomics](#transcriptomics--epigenomics) (26)
- [Microbiome & Metagenomics](#microbiome--metagenomics) (33)
- [Proteomics & Metabolomics](#proteomics--metabolomics) (19)
- [Single-cell & Spatial Omics](#single-cell--spatial-omics) (31)
- [Structural Bioinformatics](#structural-bioinformatics) (10)
- [Functional Analysis, Integration & Visualization](#functional-analysis-integration--visualization) (11)

## Core & Shared Tools

[Libraries & data access](#libraries--data-access) | [Sequence & genomic files](#sequence--genomic-files) | [Read quality, preprocessing & reports](#read-quality-preprocessing--reports) | [Sequence alignment, search & clustering](#sequence-alignment-search--clustering) | [Workflows & platforms](#workflows--platforms)

### Libraries & data access

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Biopython](https://github.com/biopython/biopython) | Official git repository for Biopython (originally converted from CVS) | 5,244 | [273,213](https://anaconda.org/conda-forge/biopython) | [4,030,704](https://pypi.org/project/biopython/) | 2026-10-22 | [Bioinformatics (2009)](https://doi.org/10.1093/bioinformatics/btp163) |
| [Biotite](https://github.com/biotite-dev/biotite) | A comprehensive library for computational molecular biology | 980 | [20,146](https://anaconda.org/conda-forge/biotite) | [805,594](https://pypi.org/project/biotite/) | 2026-10-24 | [BMC Bioinformatics (2018)](https://doi.org/10.1186/s12859-018-2367-z) |
| [gget](https://github.com/scverse/gget) | 🧬 gget enables efficient querying of genomic reference databases | 1,208 | [176](https://anaconda.org/bioconda/gget) | [39,528](https://pypi.org/project/gget/) | 2026-10-22 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btac836) |
| [HTSlib](https://github.com/samtools/htslib) | C library for high-throughput sequencing data formats | 956 | [372,543](https://anaconda.org/bioconda/htslib) | - | 2026-10-22 | [GigaScience (2021)](https://doi.org/10.1093/gigascience/giab007) |
| [pysam](https://github.com/pysam-developers/pysam) | Pysam is a Python package for reading, manipulating, and writing genomics data such as SAM/BAM/CRAM and VCF/BCF... | 911 | [647,657](https://anaconda.org/bioconda/pysam) | [1,140,422](https://pypi.org/project/pysam/) | 2026-09-07 | - |
| [scikit-bio](https://github.com/scikit-bio/scikit-bio) | scikit-bio: a community-driven Python library for bioinformatics, providing versatile data structures, algorithms and... | 1,255 | [14,879](https://anaconda.org/conda-forge/scikit-bio) | [77,456](https://pypi.org/project/scikit-bio/) | 2026-10-17 | [Nat Methods (2026)](https://doi.org/10.1038/s41592-025-02981-z) |

See also: [Mass spectrometry libraries & formats](#mass-spectrometry-libraries--formats).

### Sequence & genomic files

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [bedtools](https://github.com/arq5x/bedtools2) | bedtools - the swiss army knife for genome arithmetic | 1,055 | [171,268](https://anaconda.org/bioconda/bedtools) | 2026-06-10 | [Bioinformatics (2010)](https://doi.org/10.1093/bioinformatics/btq033) |
| [SAMtools](https://github.com/samtools/samtools) | Tools (written in C using htslib) for manipulating next-generation sequencing data | 1,970 | [323,321](https://anaconda.org/bioconda/samtools) | 2026-10-22 | [GigaScience (2021)](https://doi.org/10.1093/gigascience/giab008) |
| [SeqKit](https://github.com/shenwei356/seqkit) | A cross-platform and ultrafast toolkit for FASTA/Q file manipulation | 1,606 | [50,153](https://anaconda.org/bioconda/seqkit) | 2026-10-19 | [iMeta (2024)](https://doi.org/10.1002/imt2.191) |
| [seqtk](https://github.com/lh3/seqtk) | Toolkit for processing sequences in FASTA/Q formats | 1,565 | [29,659](https://anaconda.org/bioconda/seqtk) | 2025-06-01 | - |

See also: [DNA read mapping](#dna-read-mapping); [RNA-seq alignment & filtering](#rna-seq-alignment--filtering).

### Read quality, preprocessing & reports

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Cutadapt](https://github.com/marcelm/cutadapt) | Cutadapt removes adapter sequences from sequencing reads | 590 | [30,787](https://anaconda.org/bioconda/cutadapt) | [41,254](https://pypi.org/project/cutadapt/) | 2026-09-14 | [EMBnet.journal (2011)](https://doi.org/10.14806/ej.17.1.200) |
| [fastp](https://github.com/OpenGene/fastp) | An ultra-fast all-in-one FASTQ preprocessor (QC/adapters/trimming/filtering/splitting/merging...) | 2,447 | [48,368](https://anaconda.org/bioconda/fastp) | - | 2026-10-07 | [iMeta (2025)](https://doi.org/10.1002/imt2.70078) |
| [FastQC](https://github.com/s-andrews/FastQC) | A quality control analysis tool for high throughput sequencing data | 624 | [47,060](https://anaconda.org/bioconda/fastqc) | - | 2026-10-07 | - |
| [Filtlong](https://github.com/rrwick/Filtlong) | quality filtering tool for long reads | 421 | [1,554](https://anaconda.org/bioconda/filtlong) | - | 2025-09-17 | - |
| [MultiQC](https://github.com/MultiQC/MultiQC) | Aggregate results from bioinformatics analyses across many samples into a single report. | 1,496 | [33,231](https://anaconda.org/bioconda/multiqc) | [25,601](https://pypi.org/project/multiqc/) | 2026-10-06 | [Bioinformatics (2016)](https://doi.org/10.1093/bioinformatics/btw354) |
| [NanoPlot](https://github.com/wdecoster/NanoPlot) | Plotting scripts for long read sequencing data | 564 | [3,727](https://anaconda.org/bioconda/nanoplot) | [1,924](https://pypi.org/project/NanoPlot/) | 2026-09-05 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btad311) |

### Sequence alignment, search & clustering

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [BLAST+](https://blast.ncbi.nlm.nih.gov/doc/blast-help/) | - | - | [125,166](https://anaconda.org/bioconda/blast) | - | - | [BMC Bioinformatics (2009)](https://doi.org/10.1186/1471-2105-10-421) |
| [CD-HIT](https://github.com/weizhongli/cdhit) | Automatically exported from code.google.com/p/cdhit | 732 | [8,489](https://anaconda.org/bioconda/cd-hit) | - | 2021-04-20 | [Bioinformatics (2012)](https://doi.org/10.1093/bioinformatics/bts565) |
| [DIAMOND](https://github.com/bbuchfink/diamond) | Accelerated BLAST compatible local sequence aligner. | 1,331 | [101,702](https://anaconda.org/bioconda/diamond) | - | 2026-10-21 | [Nat Methods (2021)](https://doi.org/10.1038/s41592-021-01101-x) |
| [FAMSA2](https://github.com/refresh-bio/FAMSA) | Algorithm for ultra-scale multiple protein sequence alignments: 3 million ABC transporters analyzed in 5 minutes and... | 277 | [17,091](https://anaconda.org/bioconda/famsa) | - | 2026-09-10 | [Nat Biotechnol (2026)](https://doi.org/10.1038/s41587-026-03095-3) |
| [HH-suite](https://github.com/soedinglab/hh-suite) | Remote protein homology detection suite. | 630 | [10,908](https://anaconda.org/bioconda/hhsuite) | - | 2026-10-07 | [BMC Bioinformatics (2019)](https://doi.org/10.1186/s12859-019-3019-7) |
| [HMMER](https://github.com/EddyRivasLab/hmmer) | HMMER: biological sequence analysis using profile HMMs | 429 | [143,635](https://anaconda.org/bioconda/hmmer) | - | 2026-10-24 | [PLOS Comput Biol (2011)](https://doi.org/10.1371/journal.pcbi.1002195) |
| [Kalign](https://github.com/TimoLassmann/kalign) | A fast multiple sequence alignment program. | 163 | [2,209](https://anaconda.org/conda-forge/kalign) | [9,378](https://pypi.org/project/kalign-python/) | 2026-07-22 | [Bioinformatics (2020)](https://doi.org/10.1093/bioinformatics/btz795) |
| [MAFFT](https://mafft.cbrc.jp/alignment/software/) | Multiple sequence alignment program | - | [59,482](https://anaconda.org/conda-forge/mafft) | - | 2025-12-11 | [Mol Biol Evol (2013)](https://doi.org/10.1093/molbev/mst010) |
| [MMseqs2](https://github.com/soedinglab/MMseqs2) | MMseqs2: ultra fast and sensitive search and clustering suite | 2,158 | [32,496](https://anaconda.org/bioconda/mmseqs2) | - | 2026-10-25 | [Nat Biotechnol (2017)](https://doi.org/10.1038/nbt.3988) |
| [MUSCLE 5](https://github.com/rcedgar/muscle) | Multiple sequence and structure alignment with top benchmark scores scalable to thousands of sequences. Generates... | 290 | [45,349](https://anaconda.org/bioconda/muscle) | - | 2026-08-29 | [Nat Commun (2022)](https://doi.org/10.1038/s41467-022-34630-w) |
| [T-Coffee](https://github.com/cbcrg/tcoffee) | A collection of tools for Multiple Alignments of DNA, RNA, Protein Sequence | 118 | [19,998](https://anaconda.org/bioconda/t-coffee) | - | 2026-07-21 | [J Mol Biol (2000)](https://doi.org/10.1006/jmbi.2000.4042) |
| [VSEARCH](https://github.com/torognes/vsearch) | Versatile open-source tool for microbiome analysis | 762 | [18,314](https://anaconda.org/bioconda/vsearch) | - | 2026-09-18 | [PeerJ (2016)](https://doi.org/10.7717/peerj.2584) |

See also: [Phylogeny & evolutionary models](#phylogeny--evolutionary-models); [Structure search & alignment](#structure-search--alignment); [Genome & protein annotation](#genome--protein-annotation).

### Workflows & platforms

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Galaxy](https://github.com/galaxyproject/galaxy) | Data intensive science for everyone. | 1,880 | - | [878](https://pypi.org/project/galaxy-app/) | 2026-10-25 | [Nucleic Acids Res (2026)](https://doi.org/10.1093/nar/gkag469) |
| [Nextflow](https://github.com/nextflow-io/nextflow) | A workflow language for data-driven computational pipelines | 3,517 | [20,203](https://anaconda.org/bioconda/nextflow) | - | 2026-10-23 | [Nat Biotechnol (2017)](https://doi.org/10.1038/nbt.3820) |
| [Rachis](https://github.com/rachis-org/rachis) | Rachis Framework (Formerly Known as QIIME 2 Framework (Q2F)) | 533 | - | [84](https://pypi.org/project/rachis/) | 2026-10-21 | [Nat Biotechnol (2019)](https://doi.org/10.1038/s41587-019-0209-9) |
| [Snakemake](https://github.com/snakemake/snakemake) | This is the development home of the workflow management system Snakemake. For general information, see | 2,890 | [49,629](https://anaconda.org/bioconda/snakemake) | [164,306](https://pypi.org/project/snakemake/) | 2026-10-19 | [F1000Res (2021)](https://doi.org/10.12688/f1000research.29032.1) |

See also: [Integrated microbial analysis](#integrated-microbial-analysis); [Single-cell analysis & quality](#single-cell-analysis--quality); [Proteomics processing & DIA](#proteomics-processing--dia).

## Sequence & Genome Analysis

[DNA read mapping](#dna-read-mapping) | [Genome assembly & assessment](#genome-assembly--assessment) | [Genome & protein annotation](#genome--protein-annotation) | [Resistance, biosynthesis & metabolic models](#resistance-biosynthesis--metabolic-models) | [Comparative genomics](#comparative-genomics) | [Genome visualization](#genome-visualization) | [Variant calling](#variant-calling) | [Variant annotation](#variant-annotation)

### DNA read mapping

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Bowtie 2](https://github.com/BenLangmead/bowtie2) | A fast and sensitive gapped read aligner | 811 | [214,736](https://anaconda.org/bioconda/bowtie2) | - | - | 2026-10-24 | [Nat Methods (2012)](https://doi.org/10.1038/nmeth.1923) |
| [BWA](https://github.com/lh3/bwa) | Burrow-Wheeler Aligner for short-read alignment (see minimap2 for long-read alignment) | 1,769 | [61,714](https://anaconda.org/bioconda/bwa) | - | - | 2026-08-07 | [Bioinformatics (2009)](https://doi.org/10.1093/bioinformatics/btp324) |
| [BWA-MEM2](https://github.com/bwa-mem2/bwa-mem2) | The next version of bwa-mem | 866 | [15,642](https://anaconda.org/bioconda/bwa-mem2) | - | - | 2025-10-15 | [IPDPS (2019)](https://doi.org/10.1109/IPDPS.2019.00041) |
| [minimap2](https://github.com/lh3/minimap2) | A versatile pairwise aligner for genomic and spliced nucleotide sequences | 2,259 | [59,340](https://anaconda.org/bioconda/minimap2) | [57,393](https://pypi.org/project/mappy/) | - | 2026-05-19 | [Bioinformatics (2018)](https://doi.org/10.1093/bioinformatics/bty191) |
| [Subread / featureCounts](https://github.com/ShiLab-Bioinformatics/subread) | The Subread software package is a tool kit for processing next-gen sequencing data. It includes Subread aligner... | 61 | [16,656](https://anaconda.org/bioconda/subread) | - | [8,154](https://bioconductor.org/packages/Rsubread/) | 2026-10-24 | [Bioinformatics (2014)](https://doi.org/10.1093/bioinformatics/btt656) |

See also: [RNA-seq alignment & filtering](#rna-seq-alignment--filtering); [Comparative genomics](#comparative-genomics); [Variant calling](#variant-calling).

### Genome assembly & assessment

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [ABySS](https://github.com/BirolLab/abyss) | :microscope: Assemble large genomes using short reads | 334 | [1,026](https://anaconda.org/bioconda/abyss) | - | 2026-04-30 | [Genome Res (2017)](https://doi.org/10.1101/gr.214346.116) |
| [BUSCO](https://gitlab.com/ezlab/busco) | Assessing genome assembly and annotation completeness with Benchmarking Universal Single-Copy Orthologs (BUSCO) | - | [12,679](https://anaconda.org/bioconda/busco) | - | 2026-06-05 | [Nucleic Acids Res (2025)](https://doi.org/10.1093/nar/gkae987) |
| [Flye](https://github.com/mikolmogorov/Flye) | De novo assembler for single molecule sequencing reads using repeat graphs | 954 | [7,658](https://anaconda.org/bioconda/flye) | - | 2025-05-02 | [Nat Biotechnol (2019)](https://doi.org/10.1038/s41587-019-0072-8) |
| [hifiasm](https://github.com/chhylp123/hifiasm) | Hifiasm: a haplotype-resolved assembler for accurate Hifi reads | 818 | [1,979](https://anaconda.org/bioconda/hifiasm) | - | 2025-03-18 | [Nat Methods (2021)](https://doi.org/10.1038/s41592-020-01056-5) |
| [Merqury](https://github.com/marbl/merqury) | k-mer based assembly evaluation | 356 | [978](https://anaconda.org/bioconda/merqury) | - | 2026-05-21 | [Genome Biol (2020)](https://doi.org/10.1186/s13059-020-02134-9) |
| [QUAST](https://github.com/ablab/quast) | Genome assembly evaluation tool | 522 | [6,953](https://anaconda.org/bioconda/quast) | [3,692](https://pypi.org/project/quast/) | 2026-06-10 | [Bioinformatics (2013)](https://doi.org/10.1093/bioinformatics/btt086) |
| [SPAdes](https://github.com/ablab/spades) | SPAdes Genome Assembler | 967 | [26,833](https://anaconda.org/bioconda/spades) | - | 2026-10-22 | [Curr Protoc Bioinformatics (2020)](https://doi.org/10.1002/cpbi.102) |
| [Unicycler](https://github.com/rrwick/Unicycler) | hybrid assembly pipeline for bacterial genomes | 656 | [2,394](https://anaconda.org/bioconda/unicycler) | - | 2026-07-29 | [PLOS Comput Biol (2017)](https://doi.org/10.1371/journal.pcbi.1005595) |
| [Verkko](https://github.com/marbl/verkko) | Telomere-to-telomere assembly of accurate long reads (PacBio HiFi, Oxford Nanopore Duplex, HERRO corrected Oxford... | 421 | [340](https://anaconda.org/bioconda/verkko) | - | 2026-08-25 | [Genome Res (2025)](https://doi.org/10.1101/gr.280383.124) |

See also: [Metagenome assembly & binning](#metagenome-assembly--binning); [Transcript reconstruction & expression](#transcript-reconstruction--expression); [Microbial genome assessment & taxonomy](#microbial-genome-assessment--taxonomy).

### Genome & protein annotation

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [AUGUSTUS](https://github.com/Gaius-Augustus/Augustus) | Genome annotation with AUGUSTUS | 346 | [15,108](https://anaconda.org/bioconda/augustus) | - | 2026-05-18 | [Bioinformatics (2008)](https://doi.org/10.1093/bioinformatics/btn013) |
| [Bakta](https://github.com/oschwengers/bakta) | Rapid & standardized annotation of bacterial genomes, MAGs & plasmids | 686 | [2,868](https://anaconda.org/bioconda/bakta) | [362](https://pypi.org/project/bakta/) | 2026-10-11 | [Microb Genom (2021)](https://doi.org/10.1099/mgen.0.000685) |
| [BRAKER](https://github.com/Gaius-Augustus/BRAKER4) | BRAKER re-implemented with snakemake | [469](https://github.com/Gaius-Augustus/BRAKER) | - | - | 2026-09-22 | [Genome Res (2024)](https://doi.org/10.1101/gr.278090.123) |
| [DRAM](https://github.com/BortonWrightonLabs/DRAM) | Distilled and Refined Annotation of Metabolism: A tool for the annotation and curation of function for microbial and... | 343 | - | - | 2026-10-19 | [Nucleic Acids Res (2020)](https://doi.org/10.1093/nar/gkaa621) |
| [eggNOG-mapper](https://github.com/eggnogdb/eggnog-mapper) | Fast genome-wide functional annotation through orthology assignment | 798 | [2,860](https://anaconda.org/bioconda/eggnog-mapper) | [788](https://pypi.org/project/eggnog-mapper/) | 2026-08-13 | [Mol Biol Evol (2021)](https://doi.org/10.1093/molbev/msab293) |
| [funannotate](https://github.com/nextgenusfs/funannotate) | Eukaryotic Genome Annotation Pipeline | 402 | [426](https://anaconda.org/bioconda/funannotate) | [116](https://pypi.org/project/funannotate/) | 2026-10-25 | - |
| [InterProScan](https://github.com/ebi-pf-team/interproscan) | Genome-scale protein function classification | 393 | - | - | 2026-10-01 | [Bioinformatics (2014)](https://doi.org/10.1093/bioinformatics/btu031) |
| [Liftoff](https://github.com/agshumate/Liftoff) | An accurate GFF3/GTF lift over pipeline | 562 | [1,115](https://anaconda.org/bioconda/liftoff) | [301](https://pypi.org/project/Liftoff/) | 2023-08-01 | [Bioinformatics (2021)](https://doi.org/10.1093/bioinformatics/btaa1016) |
| [PGAP](https://github.com/ncbi/pgap) | NCBI Prokaryotic Genome Annotation Pipeline | 391 | - | - | 2026-06-02 | [Nucleic Acids Res (2016)](https://doi.org/10.1093/nar/gkw569) |
| [Pharokka](https://github.com/gbouras13/pharokka) | Pharokka is a rapid standardised annotation tool for bacteriophage genomes and metagenomes. | 237 | [795](https://anaconda.org/bioconda/pharokka) | [124](https://pypi.org/project/pharokka/) | 2026-08-16 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btac776) |
| [Prodigal](https://github.com/hyattpd/Prodigal) | Prodigal Gene Prediction Software | 552 | [37,323](https://anaconda.org/bioconda/prodigal) | - | 2023-01-27 | [BMC Bioinformatics (2010)](https://doi.org/10.1186/1471-2105-11-119) |
| [Prokka](https://github.com/tseemann/prokka) | :zap: :aquarius: Rapid prokaryotic genome annotation | 997 | [4,393](https://anaconda.org/bioconda/prokka) | - | 2026-01-06 | [Bioinformatics (2014)](https://doi.org/10.1093/bioinformatics/btu153) |

See also: [Resistance, biosynthesis & metabolic models](#resistance-biosynthesis--metabolic-models); [Viral sequence identification](#viral-sequence-identification); [Gene sets & functional activity](#gene-sets--functional-activity).

### Resistance, biosynthesis & metabolic models

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [ABRicate](https://github.com/tseemann/abricate) | :mag_right: :pill: Mass screening of contigs for antimicrobial and virulence genes | 515 | [4,198](https://anaconda.org/bioconda/abricate) | - | 2026-07-17 | - |
| [AMRFinderPlus](https://github.com/ncbi/amr) | AMRFinderPlus - Identify AMR genes and point mutations, and virulence and stress resistance genes in assembled... | 391 | [5,520](https://anaconda.org/bioconda/ncbi-amrfinderplus) | - | 2026-08-10 | [Sci Rep (2021)](https://doi.org/10.1038/s41598-021-91456-0) |
| [antiSMASH](https://github.com/antismash/antismash) | antiSMASH | 270 | [1,096](https://anaconda.org/bioconda/antismash) | - | 2026-10-22 | [Nucleic Acids Res (2025)](https://doi.org/10.1093/nar/gkaf334) |
| [CarveMe](https://github.com/cdanielmachado/carveme) | CarveMe: genome-scale metabolic model reconstruction | 223 | [138](https://anaconda.org/bioconda/carveme) | [576](https://pypi.org/project/carveme/) | 2025-09-12 | [Nucleic Acids Res (2018)](https://doi.org/10.1093/nar/gky537) |
| [DeepBGC](https://github.com/Merck/deepbgc) | BGC Detection and Classification Using Deep Learning | 161 | [183](https://anaconda.org/bioconda/deepbgc) | [173](https://pypi.org/project/deepbgc/) | 2023-11-11 | [Nucleic Acids Res (2019)](https://doi.org/10.1093/nar/gkz654) |
| [gapseq](https://github.com/jotech/gapseq) | Informed prediction and analysis of bacterial metabolic pathways and genome-scale networks | 229 | [305](https://anaconda.org/bioconda/gapseq) | - | 2026-10-20 | [Genome Biol (2021)](https://doi.org/10.1186/s13059-021-02295-1) |
| [RGI](https://github.com/arpcard/rgi) | Resistance Gene Identifier (RGI). Software to predict resistomes from protein or nucleotide data, including... | 436 | [3,480](https://anaconda.org/bioconda/rgi) | - | 2026-10-17 | [Nucleic Acids Res (2023)](https://doi.org/10.1093/nar/gkac920) |

See also: [Genome & protein annotation](#genome--protein-annotation).

### Comparative genomics

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [FastANI](https://github.com/ParBLiSS/FastANI) | Fast Whole-Genome Similarity (ANI) Estimation | 486 | [10,742](https://anaconda.org/bioconda/fastani) | - | 2026-09-14 | [Nat Commun (2018)](https://doi.org/10.1038/s41467-018-07641-9) |
| [Mash](https://github.com/marbl/Mash) | Fast genome and metagenome distance estimation using MinHash | 455 | [21,570](https://anaconda.org/bioconda/mash) | - | 2025-09-19 | [Genome Biol (2016)](https://doi.org/10.1186/s13059-016-0997-x) |
| [minigraph](https://github.com/lh3/minigraph) | Sequence-to-graph mapper and graph generator | 492 | [442](https://anaconda.org/bioconda/minigraph) | - | 2025-08-11 | [Genome Biol (2020)](https://doi.org/10.1186/s13059-020-02168-z) |
| [minimap2](https://github.com/lh3/minimap2) | A versatile pairwise aligner for genomic and spliced nucleotide sequences | 2,259 | [59,340](https://anaconda.org/bioconda/minimap2) | [57,393](https://pypi.org/project/mappy/) | 2026-05-19 | [Bioinformatics (2018)](https://doi.org/10.1093/bioinformatics/bty191) |
| [MUMmer4](https://github.com/mummer4/mummer) | Mummer alignment tool | 578 | [4,070](https://anaconda.org/bioconda/mummer4) | - | 2025-02-04 | [PLOS Comput Biol (2018)](https://doi.org/10.1371/journal.pcbi.1005944) |
| [OrthoFinder](https://github.com/OrthoFinder/OrthoFinder) | Phylogenetic orthology inference for comparative genomics | 195 | [2,974](https://anaconda.org/bioconda/orthofinder) | - | 2026-10-23 | [Genome Biol (2019)](https://doi.org/10.1186/s13059-019-1832-y) |
| [Panaroo](https://github.com/gtonkinhill/panaroo) | An updated pipeline for pangenome investigation | 378 | [1,402](https://anaconda.org/bioconda/panaroo) | - | 2026-07-02 | [Genome Biol (2020)](https://doi.org/10.1186/s13059-020-02090-4) |
| [PPanGGOLiN](https://github.com/labgem/PPanGGOLiN) | Build a partitioned pangenome graph from microbial genomes | 312 | [1,557](https://anaconda.org/bioconda/ppanggolin) | [1,120](https://pypi.org/project/PPanGGOLiN/) | 2026-09-28 | [PLOS Comput Biol (2020)](https://doi.org/10.1371/journal.pcbi.1007732) |
| [skani](https://github.com/bluenote-1577/skani) | Fast average nucleotide identity (ANI) calculator for bacterial genomes, MAGs, and contigs. Supports genome... | 269 | [7,383](https://anaconda.org/bioconda/skani) | - | 2026-10-14 | [Nat Methods (2023)](https://doi.org/10.1038/s41592-023-02018-3) |
| [vg](https://github.com/vgteam/vg) | tools for working with genome variation graphs | 1,347 | [1,288](https://anaconda.org/bioconda/vg) | - | 2026-10-25 | [Nat Biotechnol (2018)](https://doi.org/10.1038/nbt.4227) |

See also: [Genome visualization](#genome-visualization); [Microbial genome assessment & taxonomy](#microbial-genome-assessment--taxonomy).

### Genome visualization

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [clinker](https://github.com/gamcil/clinker) | Gene cluster comparison figure generator | 660 | [489](https://anaconda.org/bioconda/clinker-py) | [1,067](https://pypi.org/project/clinker/) | 2025-12-18 | [Bioinformatics (2021)](https://doi.org/10.1093/bioinformatics/btab007) |
| [IGV](https://github.com/igvteam/igv) | Integrative Genomics Viewer. Fast, efficient, scalable visualization tool for genomics data and annotations | 768 | [1,421](https://anaconda.org/bioconda/igv) | - | 2026-10-24 | [Nat Biotechnol (2011)](https://doi.org/10.1038/nbt.1754) |
| [JBrowse 2](https://github.com/GMOD/jbrowse-components) | Source code for JBrowse 2, a modern React-based genome browser | 297 | [1,331](https://anaconda.org/bioconda/jbrowse2) | - | 2026-10-24 | [Genome Biol (2023)](https://doi.org/10.1186/s13059-023-02914-z) |
| [pyGenomeViz](https://github.com/moshi4/pyGenomeViz) | A genome visualization python package for comparative genomics | 426 | [310](https://anaconda.org/conda-forge/pygenomeviz) | [28,754](https://pypi.org/project/pygenomeviz/) | 2026-06-14 | - |

See also: [Chromatin analysis](#chromatin-analysis).

### Variant calling

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [BCFtools](https://github.com/samtools/bcftools) | This is the official development repository for BCFtools. See installation instructions and other documentation here... | 901 | [179,828](https://anaconda.org/bioconda/bcftools) | - | 2026-10-24 | [GigaScience (2021)](https://doi.org/10.1093/gigascience/giab008) |
| [Clair3](https://github.com/HKU-BAL/Clair3) | Clair3 - Symphonizing pileup and full-alignment for deep learning-based long-read variant calling | 394 | [1,390](https://anaconda.org/bioconda/clair3) | - | 2026-10-05 | [Nat Comput Sci (2022)](https://doi.org/10.1038/s43588-022-00387-x) |
| [DeepVariant](https://github.com/google/deepvariant) | DeepVariant is an analysis pipeline that uses a deep neural network to call genetic variants from next-generation DNA... | 3,825 | [369](https://anaconda.org/bioconda/deepvariant) | - | 2026-03-19 | [Nat Biotechnol (2018)](https://doi.org/10.1038/nbt.4235) |
| [Delly](https://github.com/dellytools/delly) | DELLY2: Structural variant discovery by integrated paired-end and split-read analysis | 538 | [3,157](https://anaconda.org/bioconda/delly) | - | 2026-10-14 | [Bioinformatics (2012)](https://doi.org/10.1093/bioinformatics/bts378) |
| [FreeBayes](https://github.com/freebayes/freebayes) | Bayesian haplotype-based genetic polymorphism discovery and genotyping. | 880 | [46,291](https://anaconda.org/bioconda/freebayes) | - | 2026-09-03 | [arXiv (2012)](https://doi.org/10.48550/arXiv.1207.3907) |
| [GATK](https://github.com/broadinstitute/gatk) | Official code repository for GATK versions 4 and up | 2,007 | [15,600](https://anaconda.org/bioconda/gatk4) | - | 2026-08-18 | [Genome Res (2010)](https://doi.org/10.1101/gr.107524.110) |
| [Sniffles2](https://github.com/fritzsedlazeck/Sniffles) | Structural variation caller using third generation sequencing | 685 | [2,080](https://anaconda.org/bioconda/sniffles) | [2,593](https://pypi.org/project/sniffles/) | 2026-10-18 | [Nat Biotechnol (2024)](https://doi.org/10.1038/s41587-023-02024-y) |

See also: [Association & genetic architecture](#association--genetic-architecture); [Variant annotation](#variant-annotation).

### Variant annotation

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [Ensembl VEP](https://github.com/Ensembl/ensembl-vep) | The Ensembl Variant Effect Predictor predicts the functional effects of genomic variants | 578 | [14,442](https://anaconda.org/bioconda/ensembl-vep) | 2026-10-09 | [Genome Biol (2016)](https://doi.org/10.1186/s13059-016-0974-4) |
| [SnpEff](https://github.com/pcingola/SnpEff) | Genomic variant annotation and functional effect prediction | 313 | [7,381](https://anaconda.org/bioconda/snpeff) | 2026-03-09 | [Fly (2012)](https://doi.org/10.4161/fly.19695) |

See also: [Variant calling](#variant-calling).

## Genetics & Evolution

[Association & genetic architecture](#association--genetic-architecture) | [Population structure, history & simulation](#population-structure-history--simulation) | [Phylogeny & evolutionary models](#phylogeny--evolutionary-models) | [Phylogenetic tree analysis & visualization](#phylogenetic-tree-analysis--visualization)

### Association & genetic architecture

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [bigsnpr](https://github.com/privefl/bigsnpr) | R package for the analysis of massive SNP arrays. | 227 | [665](https://anaconda.org/conda-forge/r-bigsnpr) | - | [2,079](https://cran.r-project.org/package=bigsnpr) | 2026-07-10 | [Bioinformatics (2018)](https://doi.org/10.1093/bioinformatics/bty185) |
| [GCTA](https://github.com/jianyangqt/gcta) | GCTA software | 109 | - | - | - | 2025-07-09 | [Am J Hum Genet (2011)](https://doi.org/10.1016/j.ajhg.2010.11.011) |
| [GEMMA](https://github.com/genetics-statistics/GEMMA) | Genome-wide Efficient Mixed Model Association | 416 | [558](https://anaconda.org/bioconda/gemma) | - | - | 2025-12-10 | [Nat Genet (2012)](https://doi.org/10.1038/ng.2310) |
| [LDSC](https://github.com/CBIIT/ldsc) | - | [804](https://github.com/bulik/ldsc) | - | [1,037](https://pypi.org/project/ldsc/) | - | 2026-08-10 | [Nat Genet (2015)](https://doi.org/10.1038/ng.3211) |
| [PLINK](https://github.com/chrchang/plink-ng) | PLINK is a free, open-source whole genome association analysis toolset, designed to perform a range of basic... | 529 | [8,393](https://anaconda.org/bioconda/plink2) | [16,205](https://pypi.org/project/pgenlib/) | [1,100](https://cran.r-project.org/package=pgenlibr) | 2026-10-25 | [GigaScience (2015)](https://doi.org/10.1186/s13742-015-0047-8) |
| [regenie](https://github.com/rgcgithub/regenie) | regenie is a C++ program for whole genome regression modelling of large genome-wide association studies. | 271 | [2,078](https://anaconda.org/bioconda/regenie) | - | - | 2026-10-02 | [Nat Genet (2021)](https://doi.org/10.1038/s41588-021-00870-7) |
| [SAIGE](https://github.com/saigegit/SAIGE) | Development for SAIGE and SAIGE-GENE(+) | 104 | [745](https://anaconda.org/bioconda/r-saige) | - | - | 2026-06-26 | [Nat Genet (2018)](https://doi.org/10.1038/s41588-018-0184-y) |
| [susieR](https://github.com/stephenslab/susieR) | R package for "sum of single effects" regression. | 271 | [1,403](https://anaconda.org/conda-forge/r-susier) | - | [11,057](https://cran.r-project.org/package=susieR) | 2026-10-22 | [J R Stat Soc Series B Stat Methodol (2020)](https://doi.org/10.1111/rssb.12388) |
| [tensorQTL](https://github.com/broadinstitute/tensorqtl) | Ultrafast GPU-enabled QTL mapper | 218 | - | [8,254](https://pypi.org/project/tensorqtl/) | - | 2025-06-29 | [Genome Biol (2019)](https://doi.org/10.1186/s13059-019-1836-7) |
| [TwoSampleMR](https://github.com/MRCIEU/TwoSampleMR) | R package for performing 2-sample MR using IEU OpenGWAS database | 560 | - | - | - | 2026-10-20 | [eLife (2018)](https://doi.org/10.7554/eLife.34408) |

See also: [Population structure, history & simulation](#population-structure-history--simulation).

### Population structure, history & simulation

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [ADMIXTOOLS 2](https://github.com/uqrmaie1/admixtools) | - | 105 | - | - | 2026-06-28 | [eLife (2023)](https://doi.org/10.7554/eLife.85492) |
| [EIGENSOFT](https://github.com/DReichLab/EIG) | Eigen tools by Nick Patterson and Alkes Price lab | 207 | [398](https://anaconda.org/bioconda/eigensoft) | - | 2026-07-20 | [PLOS Genet (2006)](https://doi.org/10.1371/journal.pgen.0020190) |
| [msprime](https://github.com/tskit-dev/msprime) | Simulate ARGs and genomic sequence data using population genetic models | 218 | [10,811](https://anaconda.org/conda-forge/msprime) | [22,331](https://pypi.org/project/msprime/) | 2026-09-15 | [Genetics (2022)](https://doi.org/10.1093/genetics/iyab229) |
| [SLiM](https://github.com/MesserLab/SLiM) | SLiM is a genetically explicit forward simulation software package for population genetics and evolutionary biology... | 235 | [1,566](https://anaconda.org/conda-forge/slim) | - | 2026-07-22 | [Mol Biol Evol (2026)](https://doi.org/10.1093/molbev/msaf313) |

See also: [Association & genetic architecture](#association--genetic-architecture).

### Phylogeny & evolutionary models

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [BEAST 2](https://github.com/CompEvol/beast2) | Bayesian Evolutionary Analysis by Sampling Trees | 286 | [364](https://anaconda.org/bioconda/beast2) | 2026-03-27 | [PLOS Comput Biol (2019)](https://doi.org/10.1371/journal.pcbi.1006650) |
| [HyPhy 2](https://github.com/veg/hyphy) | HyPhy 2.5.x (Maintenance Mode - bug fixes only). All active development has moved to HyPhy 3... | 275 | [2,550](https://anaconda.org/bioconda/hyphy) | 2026-10-13 | [Mol Biol Evol (2020)](https://doi.org/10.1093/molbev/msz197) |
| [IQ-TREE](https://github.com/iqtree/iqtree3) | IQ-TREE version 3: software for phylogenetics | [338](https://github.com/iqtree/iqtree2) | [26,065](https://anaconda.org/bioconda/iqtree) | 2026-09-10 | [Mol Biol Evol (2026)](https://doi.org/10.1093/molbev/msag117) |
| [MrBayes](https://github.com/NBISweden/MrBayes) | MrBayes is a program for Bayesian inference and model choice across a wide range of phylogenetic and evolutionary... | 280 | [632](https://anaconda.org/bioconda/mrbayes) | 2026-10-15 | [Syst Biol (2012)](https://doi.org/10.1093/sysbio/sys029) |
| [PAML](https://github.com/abacus-gene/paml) | PAML is a package of programs for phylogenetic analyses of DNA or protein sequences using maximum likelihood. Please... | 209 | [22,460](https://anaconda.org/bioconda/paml) | 2026-01-29 | [Mol Biol Evol (2007)](https://doi.org/10.1093/molbev/msm088) |
| [RAxML-NG](https://codeberg.org/amkozlov/raxml-ng) | RAxML Next Generation: faster, easier-to-use and more flexible | - | [5,187](https://anaconda.org/bioconda/raxml-ng) | 2026-09-14 | [Bioinformatics (2019)](https://doi.org/10.1093/bioinformatics/btz305) |

See also: [Sequence alignment, search & clustering](#sequence-alignment-search--clustering); [Phylogenetic tree analysis & visualization](#phylogenetic-tree-analysis--visualization).

### Phylogenetic tree analysis & visualization

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [DendroPy](https://github.com/jeetsukumaran/DendroPy) | A Python library for phylogenetic scripting, simulation, data processing and manipulation. | 237 | [40,760](https://anaconda.org/bioconda/dendropy) | [88,548](https://pypi.org/project/DendroPy/) | - | 2026-10-25 | [J Open Source Softw (2024)](https://doi.org/10.21105/joss.06943) |
| [ETE Toolkit](https://github.com/etetoolkit/ete) | Python package for building, comparing, annotating, manipulating and visualising trees. It provides a comprehensive... | 883 | [5,250](https://anaconda.org/conda-forge/ete4) | [8,468](https://pypi.org/project/ete4/) | - | 2026-06-01 | [Mol Biol Evol (2016)](https://doi.org/10.1093/molbev/msw046) |
| [ggtree](https://github.com/YuLab-SMU/ggtree) | :christmas_tree:Visualization and annotation of phylogenetic trees | 935 | [28,118](https://anaconda.org/bioconda/bioconductor-ggtree) | - | [105,250](https://bioconductor.org/packages/ggtree/) | 2026-09-14 | [Methods Ecol Evol (2017)](https://doi.org/10.1111/2041-210X.12628) |

## Transcriptomics & Epigenomics

[RNA-seq alignment & filtering](#rna-seq-alignment--filtering) | [Transcript reconstruction & expression](#transcript-reconstruction--expression) | [Differential expression & splicing](#differential-expression--splicing) | [Chromatin analysis](#chromatin-analysis) | [DNA methylation](#dna-methylation) | [3D genome & Hi-C](#3d-genome--hi-c)

### RNA-seq alignment & filtering

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [HISAT2](https://github.com/DaehwanKimLab/hisat2) | Graph-based alignment (Hierarchical Graph FM index) | 542 | [22,691](https://anaconda.org/bioconda/hisat2) | - | - | 2026-07-31 | [Nat Biotechnol (2019)](https://doi.org/10.1038/s41587-019-0201-4) |
| [minimap2](https://github.com/lh3/minimap2) | A versatile pairwise aligner for genomic and spliced nucleotide sequences | 2,259 | [59,340](https://anaconda.org/bioconda/minimap2) | [57,393](https://pypi.org/project/mappy/) | - | 2026-05-19 | [Bioinformatics (2018)](https://doi.org/10.1093/bioinformatics/bty191) |
| [SortMeRNA](https://github.com/sortmerna/sortmerna) | SortMeRNA: next-generation sequence filtering and alignment tool | 303 | [3,356](https://anaconda.org/conda-forge/sortmerna) | - | - | 2026-10-24 | [Bioinformatics (2012)](https://doi.org/10.1093/bioinformatics/bts611) |
| [STAR](https://github.com/alexdobin/STAR) | RNA-seq aligner | 2,273 | [31,244](https://anaconda.org/bioconda/star) | - | - | 2024-01-25 | [Bioinformatics (2013)](https://doi.org/10.1093/bioinformatics/bts635) |
| [Subread / featureCounts](https://github.com/ShiLab-Bioinformatics/subread) | The Subread software package is a tool kit for processing next-gen sequencing data. It includes Subread aligner... | 61 | [16,656](https://anaconda.org/bioconda/subread) | - | [8,154](https://bioconductor.org/packages/Rsubread/) | 2026-10-24 | [Bioinformatics (2014)](https://doi.org/10.1093/bioinformatics/btt656) |

See also: [Transcript reconstruction & expression](#transcript-reconstruction--expression); [DNA read mapping](#dna-read-mapping).

### Transcript reconstruction & expression

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [HTSeq](https://github.com/htseq/htseq) | HTSeq is a Python library to facilitate processing and analysis of data from high-throughput sequencing (HTS)... | 109 | [70,381](https://anaconda.org/bioconda/htseq) | [14,275](https://pypi.org/project/HTSeq/) | - | 2026-02-04 | [Bioinformatics (2022)](https://doi.org/10.1093/bioinformatics/btac166) |
| [kallisto](https://github.com/pachterlab/kallisto) | Near-optimal RNA-Seq quantification | 775 | [10,749](https://anaconda.org/bioconda/kallisto) | - | - | 2026-01-20 | [Nat Biotechnol (2016)](https://doi.org/10.1038/nbt.3519) |
| [RSEM](https://github.com/deweylab/RSEM) | RSEM: accurate quantification of gene and isoform expression from RNA-Seq data | 479 | [3,354](https://anaconda.org/bioconda/rsem) | - | - | 2026-08-03 | [BMC Bioinformatics (2011)](https://doi.org/10.1186/1471-2105-12-323) |
| [Salmon](https://github.com/COMBINE-lab/salmon) | 🐟 🍣 🍱 Highly-accurate & wicked fast transcript-level quantification from RNA-seq reads using selective alignment | 939 | [23,843](https://anaconda.org/bioconda/salmon) | - | - | 2026-09-25 | [Nat Methods (2017)](https://doi.org/10.1038/nmeth.4197) |
| [SPAdes](https://github.com/ablab/spades) | SPAdes Genome Assembler | 967 | [26,833](https://anaconda.org/bioconda/spades) | - | - | 2026-10-22 | [Curr Protoc Bioinformatics (2020)](https://doi.org/10.1002/cpbi.102) |
| [StringTie](https://github.com/gpertea/stringtie) | Transcript assembly and quantification for RNA-Seq | 535 | [51,687](https://anaconda.org/bioconda/stringtie) | - | - | 2026-06-03 | [Nat Methods (2026)](https://doi.org/10.1038/s41592-026-03080-3) |
| [Subread / featureCounts](https://github.com/ShiLab-Bioinformatics/subread) | The Subread software package is a tool kit for processing next-gen sequencing data. It includes Subread aligner... | 61 | [16,656](https://anaconda.org/bioconda/subread) | - | [8,154](https://bioconductor.org/packages/Rsubread/) | 2026-10-24 | [Bioinformatics (2014)](https://doi.org/10.1093/bioinformatics/btt656) |
| [Trinity](https://github.com/trinityrnaseq/trinityrnaseq) | Trinity RNA-Seq de novo transcriptome assembly | 902 | [9,685](https://anaconda.org/bioconda/trinity) | - | - | 2024-08-01 | [Nat Biotechnol (2011)](https://doi.org/10.1038/nbt.1883) |

See also: [RNA-seq alignment & filtering](#rna-seq-alignment--filtering).

### Differential expression & splicing

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [DESeq2](https://github.com/thelovelab/DESeq2) | Differential expression of RNA-seq data using the Negative Binomial | 485 | [53,807](https://anaconda.org/bioconda/bioconductor-deseq2) | - | [121,204](https://bioconductor.org/packages/DESeq2/) | 2026-10-01 | [Genome Biol (2014)](https://doi.org/10.1186/s13059-014-0550-8) |
| [edgeR](https://bioconductor.org/packages/edgeR/) | Empirical Analysis of Digital Gene Expression Data in R | - | [60,298](https://anaconda.org/bioconda/bioconductor-edger) | - | [117,230](https://bioconductor.org/packages/edgeR/) | 2026-10-18 | [Nucleic Acids Res (2025)](https://doi.org/10.1093/nar/gkaf018) |
| [limma](https://bioconductor.org/packages/limma/) | Linear Models for Microarray and Omics Data | - | [70,809](https://anaconda.org/bioconda/bioconductor-limma) | - | [264,866](https://bioconductor.org/packages/limma/) | 2026-10-22 | [Nucleic Acids Res (2015)](https://doi.org/10.1093/nar/gkv007) |
| [PyDESeq2](https://github.com/scverse/PyDESeq2) | A Python implementation of the DESeq2 pipeline for bulk RNA-seq DEA. | 767 | [4,295](https://anaconda.org/bioconda/pydeseq2) | [229,277](https://pypi.org/project/pydeseq2/) | - | 2026-09-28 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btad547) |
| [rMATS turbo](https://github.com/Xinglab/rmats-turbo) | - | 312 | [1,633](https://anaconda.org/bioconda/rmats) | - | - | 2026-08-10 | [Nat Protoc (2024)](https://doi.org/10.1038/s41596-023-00944-2) |
| [SUPPA2](https://github.com/comprna/SUPPA) | SUPPA: Fast quantification of splicing and differential splicing | 307 | [333](https://anaconda.org/bioconda/suppa) | [149](https://pypi.org/project/SUPPA/) | - | 2025-11-06 | [Genome Biol (2018)](https://doi.org/10.1186/s13059-018-1417-1) |

See also: [Gene sets & functional activity](#gene-sets--functional-activity).

### Chromatin analysis

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ChIPseeker](https://github.com/YuLab-SMU/ChIPseeker) | :dart: ChIP peak Annotation, Comparison and Visualization | 259 | [1,115](https://anaconda.org/bioconda/bioconductor-chipseeker) | - | [13,217](https://bioconductor.org/packages/ChIPseeker/) | 2026-10-05 | [Bioinformatics (2015)](https://doi.org/10.1093/bioinformatics/btv145) |
| [deepTools](https://github.com/deeptools/deepTools) | Tools to process and analyze deep sequencing data. | 770 | [7,552](https://anaconda.org/bioconda/deeptools) | [7,817](https://pypi.org/project/deeptools/) | - | 2026-10-22 | [Nucleic Acids Res (2016)](https://doi.org/10.1093/nar/gkw257) |
| [MACS3](https://github.com/macs3-project/MACS) | MACS -- Model-based Analysis of ChIP-Seq | 789 | [2,966](https://anaconda.org/bioconda/macs3) | [13,555](https://pypi.org/project/MACS3/) | - | 2026-10-21 | [Genomics Proteomics Bioinformatics (2026)](https://doi.org/10.1093/gpbjnl/qzag097) |

See also: [Single-cell chromatin analysis](#single-cell-chromatin-analysis).

### DNA methylation

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Bismark](https://github.com/FelixKrueger/Bismark) | A tool to map bisulfite converted sequence reads and determine cytosine methylation states | 468 | [11,597](https://anaconda.org/bioconda/bismark) | - | 2026-10-09 | [Bioinformatics (2011)](https://doi.org/10.1093/bioinformatics/btr167) |
| [MethylDackel](https://github.com/dpryan79/MethylDackel) | A (mostly) universal methylation extractor for BS-seq experiments. | 181 | [786](https://anaconda.org/bioconda/methyldackel) | - | 2026-10-20 | - |
| [methylpy](https://github.com/yupenghe/methylpy) | WGBS/NOMe-seq Data Processing & Differential Methylation Analysis | 148 | [94](https://anaconda.org/bioconda/methylpy) | [211](https://pypi.org/project/methylpy/) | 2023-05-20 | - |
| [Modkit](https://github.com/nanoporetech/modkit) | A bioinformatics tool for working with modified bases | 280 | [1,808](https://anaconda.org/bioconda/ont-modkit) | - | 2026-06-12 | - |

See also: [Single-cell chromatin analysis](#single-cell-chromatin-analysis).

### 3D genome & Hi-C

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [cooler](https://github.com/open2c/cooler) | A cool place to store your Hi-C | 247 | [6,002](https://anaconda.org/bioconda/cooler) | [10,051](https://pypi.org/project/cooler/) | 2026-10-24 | [Bioinformatics (2020)](https://doi.org/10.1093/bioinformatics/btz540) |
| [HiCExplorer](https://github.com/deeptools/HiCExplorer) | HiCExplorer is a powerful and easy to use set of tools to process, normalize and visualize Hi-C data. | 281 | [819](https://anaconda.org/bioconda/hicexplorer) | - | 2024-11-28 | [Nucleic Acids Res (2020)](https://doi.org/10.1093/nar/gkaa220) |
| [Juicer](https://github.com/aidenlab/juicer) | A One-Click System for Analyzing Loop-Resolution Hi-C Experiments | 492 | - | - | 2025-08-31 | [Cell Syst (2016)](https://doi.org/10.1016/j.cels.2016.07.002) |

## Microbiome & Metagenomics

[Metagenome assembly & binning](#metagenome-assembly--binning) | [Microbial genome assessment & taxonomy](#microbial-genome-assessment--taxonomy) | [Microbial classification & abundance](#microbial-classification--abundance) | [Microbial functional profiling](#microbial-functional-profiling) | [Amplicons & community analysis](#amplicons--community-analysis) | [Viral sequence identification](#viral-sequence-identification) | [Integrated microbial analysis](#integrated-microbial-analysis)

### Metagenome assembly & binning

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [CONCOCT](https://github.com/BinPro/CONCOCT) | Clustering cONtigs with COverage and ComposiTion | 140 | [932](https://anaconda.org/bioconda/concoct) | - | 2019-11-11 | [Nat Methods (2014)](https://doi.org/10.1038/nmeth.3103) |
| [DAS Tool](https://github.com/cmks/DAS_Tool) | DAS Tool | 178 | [735](https://anaconda.org/bioconda/das_tool) | - | 2026-10-09 | [Nat Microbiol (2018)](https://doi.org/10.1038/s41564-018-0171-1) |
| [Flye](https://github.com/mikolmogorov/Flye) | De novo assembler for single molecule sequencing reads using repeat graphs | 954 | [7,658](https://anaconda.org/bioconda/flye) | - | 2025-05-02 | [Nat Biotechnol (2019)](https://doi.org/10.1038/s41587-019-0072-8) |
| [MEGAHIT](https://github.com/voutcn/megahit) | Ultra-fast and memory-efficient (meta-)genome assembler | 727 | [24,239](https://anaconda.org/bioconda/megahit) | - | 2025-10-28 | [Bioinformatics (2015)](https://doi.org/10.1093/bioinformatics/btv033) |
| [MetaBAT 2](https://bitbucket.org/berkeleylab/metabat) | MetaBAT: A robust statistical framework for reconstructing genomes from metagenomic data | - | - | - | 2026-08-20 | [PeerJ (2019)](https://doi.org/10.7717/peerj.7359) |
| [SemiBin](https://github.com/BigDataBiology/SemiBin) | SemiBin: metagenomics binning with self-supervised deep learning | 175 | [1,167](https://anaconda.org/bioconda/semibin) | [381](https://pypi.org/project/SemiBin/) | 2026-10-13 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btad209) |
| [SPAdes](https://github.com/ablab/spades) | SPAdes Genome Assembler | 967 | [26,833](https://anaconda.org/bioconda/spades) | - | 2026-10-22 | [Curr Protoc Bioinformatics (2020)](https://doi.org/10.1002/cpbi.102) |
| [Vamb](https://github.com/RasmussenLab/vamb) | Variational autoencoder for metagenomic binning | 335 | - | [210](https://pypi.org/project/vamb/) | 2026-04-27 | [Nat Biotechnol (2021)](https://doi.org/10.1038/s41587-020-00777-4) |

See also: [Genome assembly & assessment](#genome-assembly--assessment); [Microbial genome assessment & taxonomy](#microbial-genome-assessment--taxonomy).

### Microbial genome assessment & taxonomy

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [BUSCO](https://gitlab.com/ezlab/busco) | Assessing genome assembly and annotation completeness with Benchmarking Universal Single-Copy Orthologs (BUSCO) | - | [12,679](https://anaconda.org/bioconda/busco) | - | 2026-06-05 | [Nucleic Acids Res (2025)](https://doi.org/10.1093/nar/gkae987) |
| [CAT/BAT/RAT](https://github.com/MGXlab/CAT_pack) | CAT/BAT/RAT: tools for taxonomic classification of contigs and metagenome-assembled genomes (MAGs) and for taxonomic... | 236 | [254](https://anaconda.org/bioconda/cat) | - | 2026-10-01 | [Genome Biol (2019)](https://doi.org/10.1186/s13059-019-1817-x) |
| [CheckM](https://github.com/Ecogenomics/CheckM) | Assess the quality of microbial genomes recovered from isolates, single cells, and metagenomes | 411 | [2,138](https://anaconda.org/bioconda/checkm-genome) | [722](https://pypi.org/project/checkm-genome/) | 2026-03-02 | [Genome Res (2015)](https://doi.org/10.1101/gr.186072.114) |
| [CheckM2](https://github.com/chklovski/CheckM2) | Assessing the quality of metagenome-derived genome bins using machine learning | 282 | [2,458](https://anaconda.org/bioconda/checkm2) | [196](https://pypi.org/project/CheckM2/) | 2025-03-20 | [Nat Methods (2023)](https://doi.org/10.1038/s41592-023-01940-w) |
| [CheckV](https://bitbucket.org/berkeleylab/checkv) | Assessing the quality of metagenome-assembled viral genomes | - | [1,323](https://anaconda.org/bioconda/checkv) | [396](https://pypi.org/project/checkv/) | 2026-05-24 | [Nat Biotechnol (2021)](https://doi.org/10.1038/s41587-020-00774-7) |
| [dRep](https://github.com/MrOlm/drep) | Rapid comparison and dereplication of genomes | 360 | [901](https://anaconda.org/bioconda/drep) | [412](https://pypi.org/project/drep/) | 2026-10-09 | [ISME J (2017)](https://doi.org/10.1038/ismej.2017.126) |
| [GTDB-Tk](https://github.com/Ecogenomics/GTDBTk) | GTDB-Tk: a toolkit for assigning objective taxonomic classifications to bacterial and archaeal genomes. | 625 | [2,186](https://anaconda.org/bioconda/gtdbtk) | [510](https://pypi.org/project/gtdbtk/) | 2026-10-13 | [Bioinformatics (2022)](https://doi.org/10.1093/bioinformatics/btac672) |
| [GUNC](https://github.com/grp-bork/gunc) | Python package for detection of chimerism and contamination in prokaryotic genomes. | 97 | [483](https://anaconda.org/bioconda/gunc) | [74](https://pypi.org/project/gunc/) | 2026-05-11 | [Genome Biol (2021)](https://doi.org/10.1186/s13059-021-02393-0) |

See also: [Genome assembly & assessment](#genome-assembly--assessment); [Microbial classification & abundance](#microbial-classification--abundance); [Comparative genomics](#comparative-genomics); [Genome & protein annotation](#genome--protein-annotation); [Viral sequence identification](#viral-sequence-identification).

### Microbial classification & abundance

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Bracken](https://github.com/jenniferlu717/Bracken) | Bracken (Bayesian Reestimation of Abundance with KrakEN) is a highly accurate statistical method that computes the... | 358 | [4,157](https://anaconda.org/bioconda/bracken) | - | 2026-03-16 | [PeerJ Comput Sci (2017)](https://doi.org/10.7717/peerj-cs.104) |
| [CAT/BAT/RAT](https://github.com/MGXlab/CAT_pack) | CAT/BAT/RAT: tools for taxonomic classification of contigs and metagenome-assembled genomes (MAGs) and for taxonomic... | 236 | [254](https://anaconda.org/bioconda/cat) | - | 2026-10-01 | [Genome Biol (2019)](https://doi.org/10.1186/s13059-019-1817-x) |
| [CoverM](https://github.com/wwood/CoverM) | Read alignment statistics for metagenomics | 410 | [1,300](https://anaconda.org/bioconda/coverm) | - | 2026-10-20 | [Bioinformatics (2025)](https://doi.org/10.1093/bioinformatics/btaf147) |
| [inStrain](https://github.com/MrOlm/inStrain) | Bioinformatics program inStrain | 192 | [341](https://anaconda.org/bioconda/instrain) | [120](https://pypi.org/project/instrain/) | 2026-10-20 | [Nat Biotechnol (2021)](https://doi.org/10.1038/s41587-020-00797-0) |
| [Kraken 2](https://github.com/DerrickWood/kraken2) | The second version of the Kraken taxonomic sequence classification system | 948 | [13,237](https://anaconda.org/bioconda/kraken2) | - | 2026-10-20 | [Genome Biol (2019)](https://doi.org/10.1186/s13059-019-1891-0) |
| [Metabuli](https://github.com/steineggerlab/Metabuli) | Metabuli: specific and sensitive metagenomic classification via joint analysis of DNA and amino acid. | 186 | [269](https://anaconda.org/bioconda/metabuli) | - | 2026-10-18 | [Nat Methods (2024)](https://doi.org/10.1038/s41592-024-02273-y) |
| [MetaPhlAn](https://github.com/biobakery/MetaPhlAn) | MetaPhlAn is a computational tool for profiling the composition of microbial communities from metagenomic shotgun... | 429 | [2,858](https://anaconda.org/bioconda/metaphlan) | [1,071](https://pypi.org/project/MetaPhlAn/) | 2026-08-05 | [Nat Biotechnol (2023)](https://doi.org/10.1038/s41587-023-01688-w) |
| [sylph](https://github.com/bluenote-1577/sylph) | ultrafast taxonomic profiling and genome querying for metagenomic samples by abundance-corrected minhash. | 332 | [1,228](https://anaconda.org/bioconda/sylph) | - | 2026-10-10 | [Nat Biotechnol (2025)](https://doi.org/10.1038/s41587-024-02412-y) |

See also: [Microbial genome assessment & taxonomy](#microbial-genome-assessment--taxonomy).

### Microbial functional profiling

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [HUMAnN](https://github.com/biobakery/humann) | HUMAnN is the next generation of HUMAnN 1.0 (HMP Unified Metabolic Analysis Network). | 253 | [707](https://anaconda.org/bioconda/humann) | [1,988](https://pypi.org/project/humann/) | 2026-07-10 | [eLife (2021)](https://doi.org/10.7554/eLife.65088) |
| [PICRUSt2](https://github.com/picrust/picrust2) | Code, unit tests, and tutorials for running PICRUSt2 | 399 | [1,199](https://anaconda.org/bioconda/picrust2) | - | 2026-10-23 | [Nat Biotechnol (2020)](https://doi.org/10.1038/s41587-020-0548-6) |

### Amplicons & community analysis

| Project | Description | Stars | Conda | Bioconductor | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ANCOMBC](https://github.com/FrederickHuangLin/ANCOMBC) | Differential abundance (DA) and correlation analyses for microbial absolute abundance data | 144 | [4,016](https://anaconda.org/bioconda/bioconductor-ancombc) | [9,802](https://bioconductor.org/packages/ANCOMBC/) | - | 2026-09-18 | [Nat Methods (2024)](https://doi.org/10.1038/s41592-023-02092-7) |
| [DADA2](https://github.com/benjjneb/dada2) | Accurate sample inference from amplicon data with single nucleotide resolution | 560 | [6,402](https://anaconda.org/bioconda/bioconductor-dada2) | [12,643](https://bioconductor.org/packages/dada2/) | - | 2026-07-31 | [Nat Methods (2016)](https://doi.org/10.1038/nmeth.3869) |
| [decontam](https://github.com/benjjneb/decontam) | Simple statistical identification and removal of contaminants in marker-gene and metagenomics sequencing data | 175 | [4,409](https://anaconda.org/bioconda/bioconductor-decontam) | [8,492](https://bioconductor.org/packages/decontam/) | - | 2025-09-04 | [Microbiome (2018)](https://doi.org/10.1186/s40168-018-0605-2) |
| [MaAsLin](https://github.com/biobakery/maaslin3) | MaAsLin3: Microbiome Multivariate Association with Linear Models | [155](https://github.com/biobakery/Maaslin2) | [425](https://anaconda.org/bioconda/bioconductor-maaslin2) | [6,108](https://bioconductor.org/packages/Maaslin2/) | - | 2026-10-19 | [Nat Methods (2026)](https://doi.org/10.1038/s41592-025-02923-9) |
| [mothur](https://github.com/mothur/mothur) | Welcome to the mothur project, initiated by Dr. Patrick Schloss and his software development team in the Department... | 279 | [7,408](https://anaconda.org/bioconda/mothur) | - | - | 2026-08-21 | [Appl Environ Microbiol (2009)](https://doi.org/10.1128/AEM.01541-09) |
| [phyloseq](https://github.com/joey711/phyloseq) | phyloseq is a set of classes, wrappers, and tools (in R) to make it easier to import, store, and analyze phylogenetic... | 651 | [6,823](https://anaconda.org/bioconda/bioconductor-phyloseq) | [19,992](https://bioconductor.org/packages/phyloseq/) | - | 2026-02-27 | [PLOS One (2013)](https://doi.org/10.1371/journal.pone.0061217) |
| [vegan](https://github.com/vegandevs/vegan) | R package for community ecologists: popular ordination methods, ecological null models & diversity analysis | 550 | [96,753](https://anaconda.org/conda-forge/r-vegan) | - | [145,607](https://cran.r-project.org/package=vegan) | 2026-10-23 | - |

See also: [Sequence alignment, search & clustering](#sequence-alignment-search--clustering); [Gene sets & functional activity](#gene-sets--functional-activity).

### Viral sequence identification

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [geNomad](https://github.com/apcamargo/genomad) | geNomad: Identification of mobile genetic elements | 337 | [1,695](https://anaconda.org/bioconda/genomad) | [1,063](https://pypi.org/project/genomad/) | 2026-10-14 | [Nat Biotechnol (2024)](https://doi.org/10.1038/s41587-023-01953-y) |
| [VirSorter2](https://github.com/jiarong/VirSorter2) | customizable pipeline to identify viral sequences from (meta)genomic data | 300 | [403](https://anaconda.org/bioconda/virsorter) | - | 2024-11-28 | [Microbiome (2021)](https://doi.org/10.1186/s40168-020-00990-y) |

See also: [Genome & protein annotation](#genome--protein-annotation).

### Integrated microbial analysis

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [anvi'o](https://github.com/merenlab/anvio) | An analysis and visualization platform for 'omics data | 544 | - | 2026-10-22 | [Nat Microbiol (2021)](https://doi.org/10.1038/s41564-020-00834-3) |
| [Metagenome-Atlas](https://github.com/metagenome-atlas/atlas) | ATLAS - Three commands to start analyzing your metagenome data | 404 | [303](https://anaconda.org/bioconda/metagenome-atlas) | 2025-03-19 | [BMC Bioinformatics (2020)](https://doi.org/10.1186/s12859-020-03585-4) |

## Proteomics & Metabolomics

[Mass spectrometry libraries & formats](#mass-spectrometry-libraries--formats) | [Proteomics processing & DIA](#proteomics-processing--dia) | [Peptide identification & validation](#peptide-identification--validation) | [Metabolomics processing & identification](#metabolomics-processing--identification)

### Mass spectrometry libraries & formats

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [MSnbase](https://github.com/lgatto/MSnbase) | Base Classes and Functions for Mass Spectrometry and Proteomics | 140 | [1,150](https://anaconda.org/bioconda/bioconductor-msnbase) | - | [18,257](https://bioconductor.org/packages/MSnbase/) | 2026-10-05 | [Bioinformatics (2012)](https://doi.org/10.1093/bioinformatics/btr645) |
| [ProteoWizard](https://github.com/ProteoWizard/pwiz) | The ProteoWizard Library is a set of software libraries and tools for rapid development of mass spectrometry and... | 324 | [421](https://anaconda.org/bioconda/proteowizard) | - | - | 2026-10-24 | [Bioinformatics (2008)](https://doi.org/10.1093/bioinformatics/btn323) |
| [Pyteomics](https://github.com/levitsky/pyteomics) | Pyteomics is a collection of lightweight and handy tools for Python that help to handle various sorts of proteomics... | 162 | [3,985](https://anaconda.org/conda-forge/pyteomics) | [279,861](https://pypi.org/project/pyteomics/) | - | 2026-10-23 | [J Proteome Res (2019)](https://doi.org/10.1021/acs.jproteome.8b00717) |

See also: [Proteomics processing & DIA](#proteomics-processing--dia); [Metabolomics processing & identification](#metabolomics-processing--identification).

### Proteomics processing & DIA

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [alphaDIA](https://github.com/MannLabs/alphadia) | modular & open DIA search | 118 | - | [201](https://pypi.org/project/alphadia/) | 2026-10-23 | [Nat Biotechnol (2026)](https://doi.org/10.1038/s41587-025-02791-w) |
| [AlphaPept](https://github.com/MannLabs/alphapept) | A modular, python-based framework for mass spectrometry. Powered by nbdev. | 192 | - | [158](https://pypi.org/project/alphapept/) | 2024-04-19 | [Nat Commun (2024)](https://doi.org/10.1038/s41467-024-46485-4) |
| [DIA-NN](https://github.com/vdemichev/DiaNN) | DIA-NN - a universal automated software suite for DIA proteomics data analysis. | 493 | - | - | 2026-09-16 | [Nat Methods (2020)](https://doi.org/10.1038/s41592-019-0638-x) |
| [FragPipe](https://github.com/Nesvilab/FragPipe) | A cross-platform proteomics data analysis suite | 327 | [124](https://anaconda.org/bioconda/fragpipe) | - | 2026-08-05 | [Nat Methods (2017)](https://doi.org/10.1038/nmeth.4256) |
| [OpenMS](https://github.com/OpenMS/OpenMS) | The codebase of the OpenMS project | 627 | [917](https://anaconda.org/bioconda/openms) | [169,402](https://pypi.org/project/pyopenms/) | 2026-10-24 | [Nat Methods (2024)](https://doi.org/10.1038/s41592-024-02197-7) |

See also: [Peptide identification & validation](#peptide-identification--validation).

### Peptide identification & validation

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [AlphaPeptDeep](https://github.com/MannLabs/alphapeptdeep) | Deep learning framework for proteomics | 160 | - | [1,131](https://pypi.org/project/peptdeep/) | 2026-07-30 | [Nat Commun (2022)](https://doi.org/10.1038/s41467-022-34904-3) |
| [Casanovo](https://github.com/Noble-Lab/casanovo) | De Novo Mass Spectrometry Peptide Sequencing with a Transformer Model | 204 | - | [816](https://pypi.org/project/casanovo/) | 2026-10-11 | [Nat Commun (2024)](https://doi.org/10.1038/s41467-024-49731-x) |
| [Comet](https://github.com/UWPR/Comet) | An tandem mass spectrometry (MS/MS) sequence database search tool. | 56 | [7,687](https://anaconda.org/bioconda/comet-ms) | - | 2026-10-15 | [Proteomics (2013)](https://doi.org/10.1002/pmic.201200439) |
| [FragPipe](https://github.com/Nesvilab/FragPipe) | A cross-platform proteomics data analysis suite | 327 | [124](https://anaconda.org/bioconda/fragpipe) | - | 2026-08-05 | [Nat Methods (2017)](https://doi.org/10.1038/nmeth.4256) |
| [Percolator](https://github.com/percolator/percolator) | Semi-supervised learning for peptide identification from shotgun proteomics datasets | 143 | [667](https://anaconda.org/bioconda/percolator) | - | 2026-05-21 | [Nat Methods (2007)](https://doi.org/10.1038/nmeth1113) |
| [Sage](https://github.com/lazear/sage) | Proteomics search & quantification so fast that it feels like magic | 317 | [2,366](https://anaconda.org/bioconda/sage-proteomics) | - | 2026-10-22 | [J Proteome Res (2023)](https://doi.org/10.1021/acs.jproteome.3c00486) |

See also: [Proteomics processing & DIA](#proteomics-processing--dia).

### Metabolomics processing & identification

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [matchms](https://github.com/matchms/matchms) | Python library for processing (tandem) mass spectrometry data and for computing spectral similarities. | 276 | [1,070](https://anaconda.org/bioconda/matchms) | [23,080](https://pypi.org/project/matchms/) | - | 2026-10-08 | [J Open Source Softw (2020)](https://doi.org/10.21105/joss.02411) |
| [MS-DIAL](https://github.com/systemsomicslab/MsdialWorkbench) | Universal workbench incorporating msdial, msfinder, and mrmprobs | 124 | - | - | - | 2026-10-22 | [Nat Methods (2015)](https://doi.org/10.1038/nmeth.3393) |
| [mzmine](https://github.com/mzmine/mzmine) | mzmine source code repository | 307 | [42](https://anaconda.org/bioconda/mzmine) | - | - | 2026-10-19 | [Nat Biotechnol (2023)](https://doi.org/10.1038/s41587-023-01690-2) |
| [peakonly](https://github.com/Arseha/peakonly) | - | 122 | - | - | - | 2021-09-17 | [Anal Chem (2020)](https://doi.org/10.1021/acs.analchem.9b04811) |
| [SIRIUS](https://github.com/sirius-ms/sirius) | SIRIUS is a software for discovering a landscape of de-novo identification of metabolites using tandem mass... | 172 | [1,509](https://anaconda.org/conda-forge/sirius-ms) | - | - | 2026-08-25 | [Nat Methods (2019)](https://doi.org/10.1038/s41592-019-0344-8) |
| [xcms](https://github.com/sneumann/xcms) | This is the git repository matching the Bioconductor package xcms: LC/MS and GC/MS Data Analysis | 236 | [831](https://anaconda.org/bioconda/bioconductor-xcms) | - | [13,007](https://bioconductor.org/packages/xcms/) | 2026-10-08 | [Anal Chem (2025)](https://doi.org/10.1021/acs.analchem.5c04338) |

See also: [Multi-omics integration](#multi-omics-integration).

## Single-cell & Spatial Omics

[Single-cell analysis & quality](#single-cell-analysis--quality) | [Integration, reference mapping & annotation](#integration-reference-mapping--annotation) | [Cell trajectories, markers & regulation](#cell-trajectories-markers--regulation) | [Cell-cell communication](#cell-cell-communication) | [Single-cell chromatin analysis](#single-cell-chromatin-analysis) | [Spatial omics analysis & data](#spatial-omics-analysis--data) | [Spatial mapping & deconvolution](#spatial-mapping--deconvolution)

### Single-cell analysis & quality

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [alevin-fry](https://github.com/COMBINE-lab/alevin-fry) | 🐟 🔬🦀 alevin-fry is an efficient and flexible tool for processing single-cell sequencing data, currently focused on... | 219 | [1,010](https://anaconda.org/bioconda/alevin-fry) | - | - | 2026-09-13 | [Nat Methods (2022)](https://doi.org/10.1038/s41592-022-01408-3) |
| [Cell Ranger](https://github.com/10XGenomics/cellranger) | 10x Genomics Single Cell Analysis | 482 | - | - | - | 2026-07-16 | [Nat Commun (2017)](https://doi.org/10.1038/ncomms14049) |
| [CellBender](https://github.com/broadinstitute/CellBender) | CellBender is a software package for eliminating technical artifacts from high-throughput single-cell RNA sequencing... | 426 | [70](https://anaconda.org/bioconda/cellbender) | [3,066](https://pypi.org/project/cellbender/) | - | 2026-08-18 | [Nat Methods (2023)](https://doi.org/10.1038/s41592-023-01943-7) |
| [DoubletFinder](https://github.com/chris-mcginnis-ucsf/DoubletFinder) | R package for detecting doublets in single-cell RNA sequencing data | 574 | [157](https://anaconda.org/bioconda/r-doubletfinder) | - | - | 2025-03-21 | [Cell Syst (2019)](https://doi.org/10.1016/j.cels.2019.03.003) |
| [Scanpy](https://github.com/scverse/scanpy) | Single-cell analysis in Python. Scales to >100M cells. | 2,594 | [30,987](https://anaconda.org/conda-forge/scanpy) | [702,628](https://pypi.org/project/scanpy/) | - | 2026-10-23 | [Genome Biol (2018)](https://doi.org/10.1186/s13059-017-1382-0) |
| [Scrublet](https://github.com/swolock/scrublet) | Detect doublets in single-cell RNA-seq data | 184 | [2,515](https://anaconda.org/bioconda/scrublet) | [62,762](https://pypi.org/project/scrublet/) | - | 2020-12-29 | [Cell Syst (2019)](https://doi.org/10.1016/j.cels.2018.11.005) |
| [Seurat](https://github.com/satijalab/seurat) | R toolkit for single cell genomics | 2,807 | [24,657](https://anaconda.org/conda-forge/r-seurat) | - | [58,046](https://cran.r-project.org/package=Seurat) | 2026-10-23 | [Nat Biotechnol (2024)](https://doi.org/10.1038/s41587-023-01767-y) |
| [SoupX](https://github.com/constantAmateur/SoupX) | R package to quantify and remove cell free mRNAs from droplet based scRNA-seq data | 347 | [1,015](https://anaconda.org/conda-forge/r-soupx) | - | [3,713](https://cran.r-project.org/package=SoupX) | 2022-11-01 | [GigaScience (2020)](https://doi.org/10.1093/gigascience/giaa151) |

See also: [Omics visualization & exploration](#omics-visualization--exploration); [Integration, reference mapping & annotation](#integration-reference-mapping--annotation); [Cell trajectories, markers & regulation](#cell-trajectories-markers--regulation).

### Integration, reference mapping & annotation

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [CellTypist](https://github.com/Teichlab/celltypist) | A tool for semi-automatic cell type classification | 515 | [2,227](https://anaconda.org/bioconda/celltypist) | [14,331](https://pypi.org/project/celltypist/) | - | 2025-06-25 | [Science (2022)](https://doi.org/10.1126/science.abl5197) |
| [Harmony 2](https://github.com/immunogenomics/harmony) | Fast, sensitive and accurate integration of single-cell data with Harmony | 676 | [3,810](https://anaconda.org/conda-forge/r-harmony) | - | [19,244](https://cran.r-project.org/package=harmony) | 2026-10-15 | [Nat Methods (2019)](https://doi.org/10.1038/s41592-019-0619-0) |
| [muon](https://github.com/scverse/muon) | muon is a multimodal omics Python framework | 279 | [2,518](https://anaconda.org/conda-forge/muon) | [14,135](https://pypi.org/project/muon/) | - | 2026-10-19 | [Genome Biol (2022)](https://doi.org/10.1186/s13059-021-02577-8) |
| [Scanorama](https://github.com/brianhie/scanorama) | Panoramic stitching of single cell data | 295 | [2,724](https://anaconda.org/bioconda/scanorama) | [4,310](https://pypi.org/project/scanorama/) | - | 2025-07-14 | [Nat Biotechnol (2019)](https://doi.org/10.1038/s41587-019-0113-3) |
| [scArches](https://github.com/theislab/scarches) | Reference mapping for single-cell genomics | 414 | [48](https://anaconda.org/bioconda/scarches) | [677](https://pypi.org/project/scarches/) | - | 2026-06-26 | [Nat Biotechnol (2022)](https://doi.org/10.1038/s41587-021-01001-7) |
| [scvi-tools](https://github.com/scverse/scvi-tools) | Deep probabilistic analysis of single-cell and spatial omics data | 1,717 | [4,068](https://anaconda.org/conda-forge/scvi-tools) | [45,191](https://pypi.org/project/scvi-tools/) | - | 2026-10-22 | [Nat Biotechnol (2022)](https://doi.org/10.1038/s41587-021-01206-w) |
| [Seurat](https://github.com/satijalab/seurat) | R toolkit for single cell genomics | 2,807 | [24,657](https://anaconda.org/conda-forge/r-seurat) | - | [58,046](https://cran.r-project.org/package=Seurat) | 2026-10-23 | [Nat Biotechnol (2024)](https://doi.org/10.1038/s41587-023-01767-y) |

See also: [Multi-omics integration](#multi-omics-integration); [Single-cell chromatin analysis](#single-cell-chromatin-analysis).

### Cell trajectories, markers & regulation

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [CellRank](https://github.com/scverse/cellrank) | CellRank: dynamics from multi-view single-cell data | 459 | [579](https://anaconda.org/conda-forge/cellrank) | [3,784](https://pypi.org/project/cellrank/) | - | 2026-10-14 | [Nat Methods (2024)](https://doi.org/10.1038/s41592-024-02303-9) |
| [Monocle 3](https://github.com/cole-trapnell-lab/monocle3) | - | 468 | [1,024](https://anaconda.org/bioconda/r-monocle3) | - | - | 2026-05-04 | [Nature (2019)](https://doi.org/10.1038/s41586-019-0969-x) |
| [Presto](https://github.com/immunogenomics/presto) | Fast Wilcoxon and auROC | 220 | [807](https://anaconda.org/bioconda/r-presto) | - | [238](https://cran.r-project.org/package=presto) | 2026-09-20 | [bioRxiv (2019)](https://doi.org/10.1101/653253) |
| [pySCENIC](https://github.com/aertslab/pySCENIC) | pySCENIC is a lightning-fast python implementation of the SCENIC pipeline (Single-Cell rEgulatory Network Inference... | 646 | [412](https://anaconda.org/bioconda/pyscenic) | [4,466](https://pypi.org/project/pyscenic/) | - | 2025-01-09 | [Nat Protoc (2020)](https://doi.org/10.1038/s41596-020-0336-2) |
| [scVelo](https://github.com/theislab/scvelo) | RNA Velocity generalized through dynamical modeling | 513 | [1,133](https://anaconda.org/conda-forge/scvelo) | [7,254](https://pypi.org/project/scvelo/) | - | 2026-02-25 | [Nat Biotechnol (2020)](https://doi.org/10.1038/s41587-020-0591-3) |
| [VISION](https://github.com/YosefLab/VISION) | Signature Analysis and Visualization for Single-Cell RNA-seq | 186 | [67](https://anaconda.org/bioconda/r-vision) | - | - | 2024-06-10 | [Nat Commun (2019)](https://doi.org/10.1038/s41467-019-12235-0) |

### Cell-cell communication

| Project | Description | Stars | Downloads | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [CellChat](https://github.com/jinworks/CellChat) | R toolkit for inference, visualization and analysis of cell-cell communication from single-cell and spatially... | [790](https://github.com/sqjin/CellChat) | - | 2026-03-04 | [Nat Protoc (2025)](https://doi.org/10.1038/s41596-024-01045-4) |

See also: [Cell trajectories, markers & regulation](#cell-trajectories-markers--regulation); [Spatial omics analysis & data](#spatial-omics-analysis--data).

### Single-cell chromatin analysis

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ArchR](https://github.com/GreenleafLab/ArchR) | ArchR : Analysis of Regulatory Chromatin in R (www.ArchRProject.com) | 467 | [180](https://anaconda.org/bioconda/r-archr) | - | - | 2025-02-18 | [Nat Genet (2021)](https://doi.org/10.1038/s41588-021-00790-6) |
| [EpiScanpy](https://github.com/colomemaria/epiScanpy) | Episcanpy: Epigenomics Single Cell Analysis in Python | 153 | [34](https://anaconda.org/bioconda/episcanpy) | [572](https://pypi.org/project/episcanpy/) | - | 2024-12-05 | [Nat Commun (2021)](https://doi.org/10.1038/s41467-021-25131-3) |
| [Signac](https://github.com/stuart-lab/signac) | R toolkit for the analysis of single-cell chromatin data | 431 | [1,550](https://anaconda.org/bioconda/r-signac) | - | [6,036](https://cran.r-project.org/package=Signac) | 2026-04-06 | [Nat Methods (2021)](https://doi.org/10.1038/s41592-021-01282-5) |
| [SnapATAC2](https://github.com/scverse/SnapATAC2) | Single-cell epigenomics analysis tools | 329 | [766](https://anaconda.org/bioconda/snapatac2) | [4,929](https://pypi.org/project/snapatac2/) | - | 2026-08-14 | [Nat Methods (2024)](https://doi.org/10.1038/s41592-023-02139-9) |

See also: [Chromatin analysis](#chromatin-analysis); [DNA methylation](#dna-methylation).

### Spatial omics analysis & data

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [Giotto Suite](https://github.com/giotto-suite/Giotto) | Spatial omics analysis toolbox | 394 | - | - | 2026-08-26 | [Genome Biol (2021)](https://doi.org/10.1186/s13059-021-02286-2) |
| [SpatialData](https://github.com/scverse/spatialdata) | An open and interoperable data framework for spatial omics data | 403 | [3,761](https://anaconda.org/conda-forge/spatialdata) | [89,013](https://pypi.org/project/spatialdata/) | 2026-10-21 | [Nat Methods (2025)](https://doi.org/10.1038/s41592-024-02212-x) |
| [Squidpy](https://github.com/scverse/squidpy) | Spatial Single Cell Analysis in Python | 611 | [3,128](https://anaconda.org/conda-forge/squidpy) | [66,635](https://pypi.org/project/squidpy/) | 2026-10-09 | [Nat Methods (2022)](https://doi.org/10.1038/s41592-021-01358-2) |

See also: [Spatial mapping & deconvolution](#spatial-mapping--deconvolution).

### Spatial mapping & deconvolution

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [cell2location](https://github.com/BayraktarLab/cell2location) | Comprehensive mapping of tissue cell architecture via integrated single cell and spatial transcriptomics... | 463 | - | [2,250](https://pypi.org/project/cell2location/) | - | 2026-02-22 | [Nat Biotechnol (2022)](https://doi.org/10.1038/s41587-021-01139-4) |
| [spacexr / RCTD](https://github.com/dmcable/spacexr) | Spatial-eXpression-R: Cell type identification (including cell type mixtures) and cell type-specific differential... | 489 | [36](https://anaconda.org/bioconda/bioconductor-spacexr) | - | [3,613](https://bioconductor.org/packages/spacexr/) | 2026-01-22 | [Nat Biotechnol (2022)](https://doi.org/10.1038/s41587-021-00830-w) |
| [Tangram](https://github.com/broadinstitute/Tangram) | Spatial alignment of single cell transcriptomic data. | 375 | - | [1,160](https://pypi.org/project/tangram-sc/) | - | 2025-07-01 | [Nat Methods (2021)](https://doi.org/10.1038/s41592-021-01264-7) |

## Structural Bioinformatics

[Structure prediction & protein design](#structure-prediction--protein-design) | [Structure search & alignment](#structure-search--alignment) | [Molecular visualization](#molecular-visualization)

### Structure prediction & protein design

| Project | Description | Stars | Conda | PyPI | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [AlphaFold 2](https://github.com/google-deepmind/alphafold) | Open source code for AlphaFold 2. | 14,910 | - | - | 2026-04-22 | [Nature (2021)](https://doi.org/10.1038/s41586-021-03819-2) |
| [AlphaFold 3](https://github.com/google-deepmind/alphafold3) | AlphaFold 3 inference pipeline. | 8,678 | - | - | 2026-10-23 | [Nature (2024)](https://doi.org/10.1038/s41586-024-07487-w) |
| [Boltz](https://github.com/jwohlwend/boltz) | Official repository for the Boltz biomolecular interaction models | 4,269 | - | [19,925](https://pypi.org/project/boltz/) | 2026-05-29 | [bioRxiv (2025)](https://doi.org/10.1101/2025.06.14.659707) |
| [ColabFold](https://github.com/sokrypton/ColabFold) | Making Protein folding accessible to all! | 2,970 | [207](https://anaconda.org/bioconda/colabfold) | [7,519](https://pypi.org/project/colabfold/) | 2026-10-21 | [Nat Methods (2022)](https://doi.org/10.1038/s41592-022-01488-1) |
| [ProteinMPNN](https://github.com/dauparas/ProteinMPNN) | Code for the ProteinMPNN paper | 1,890 | - | - | 2023-06-27 | [Science (2022)](https://doi.org/10.1126/science.add2187) |
| [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion) | Code for running RFdiffusion | 3,106 | - | - | 2026-07-15 | [Nature (2023)](https://doi.org/10.1038/s41586-023-06415-8) |

See also: [Structure search & alignment](#structure-search--alignment); [Molecular visualization](#molecular-visualization).

### Structure search & alignment

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [Foldseek](https://github.com/steineggerlab/foldseek) | Foldseek enables fast and sensitive comparisons of large structure sets. | 1,317 | [33,175](https://anaconda.org/bioconda/foldseek) | 2026-09-09 | [Nat Biotechnol (2024)](https://doi.org/10.1038/s41587-023-01773-0) |
| [US-align](https://github.com/pylelab/USalign) | Universal Structure Alignment of Monomeric and Complex Structure of Nucleic Acids and Proteins | 193 | [3,951](https://anaconda.org/bioconda/usalign) | 2026-10-19 | [Nat Methods (2022)](https://doi.org/10.1038/s41592-022-01585-1) |

### Molecular visualization

| Project | Description | Stars | Conda | Updated | Paper |
| --- | --- | --- | --- | --- | --- |
| [Mol\*](https://github.com/molstar/molstar) | A comprehensive macromolecular library | 1,036 | - | 2026-10-25 | [Nucleic Acids Res (2021)](https://doi.org/10.1093/nar/gkab314) |
| [Open-Source PyMOL](https://github.com/schrodinger/pymol-open-source) | Open-source foundation of the user-sponsored PyMOL molecular visualization system. | 1,764 | [26,714](https://anaconda.org/conda-forge/pymol-open-source) | 2026-10-07 | - |

## Functional Analysis, Integration & Visualization

[Gene sets & functional activity](#gene-sets--functional-activity) | [Multi-omics integration](#multi-omics-integration) | [Biological networks](#biological-networks) | [Omics visualization & exploration](#omics-visualization--exploration)

### Gene sets & functional activity

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [clusterProfiler](https://github.com/YuLab-SMU/clusterProfiler) | :bar_chart: A universal enrichment tool for interpreting omics data | 1,243 | [23,638](https://anaconda.org/bioconda/bioconductor-clusterprofiler) | - | [75,674](https://bioconductor.org/packages/clusterProfiler/) | 2026-10-23 | [Innovation (2021)](https://doi.org/10.1016/j.xinn.2021.100141) |
| [decoupler](https://github.com/scverse/decoupler) | Python package to perform enrichment analysis from omics data. | 300 | [2,041](https://anaconda.org/conda-forge/decoupler-py) | [29,569](https://pypi.org/project/decoupler/) | - | 2026-10-24 | [Bioinform Adv (2022)](https://doi.org/10.1093/bioadv/vbac016) |
| [fgsea](https://github.com/alserglab/fgsea) | Fast Gene Set Enrichment Analysis | 460 | [31,526](https://anaconda.org/bioconda/bioconductor-fgsea) | - | [67,351](https://bioconductor.org/packages/fgsea/) | 2026-09-22 | [bioRxiv (2021)](https://doi.org/10.1101/060012) |
| [GSEApy](https://github.com/zqfang/GSEApy) | Gene Set Enrichment Analysis in Python | 716 | [6,247](https://anaconda.org/bioconda/gseapy) | [171,320](https://pypi.org/project/gseapy/) | - | 2026-09-02 | [Bioinformatics (2023)](https://doi.org/10.1093/bioinformatics/btac757) |

See also: [Genome & protein annotation](#genome--protein-annotation); [Cell trajectories, markers & regulation](#cell-trajectories-markers--regulation).

### Multi-omics integration

| Project | Description | Stars | Conda | PyPI | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [mixOmics](https://github.com/mixOmics-org/mixOmics) | Development repository for the Bioconductor package 'mixOmics ' | 270 | [455](https://anaconda.org/bioconda/bioconductor-mixomics) | - | [12,560](https://bioconductor.org/packages/mixOmics/) | 2026-10-23 | [PLOS Comput Biol (2017)](https://doi.org/10.1371/journal.pcbi.1005752) |
| [MOFA2](https://github.com/bioFAM/MOFA2) | Multi-Omics Factor Analysis | 429 | [277](https://anaconda.org/bioconda/bioconductor-mofa2) | [8,001](https://pypi.org/project/mofapy2/) | [7,099](https://bioconductor.org/packages/MOFA2/) | 2026-08-26 | [Genome Biol (2020)](https://doi.org/10.1186/s13059-020-02015-1) |

See also: [Integration, reference mapping & annotation](#integration-reference-mapping--annotation); [Omics visualization & exploration](#omics-visualization--exploration).

### Biological networks

| Project | Description | Stars | Conda | PyPI | CRAN | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Arboreto](https://github.com/aertslab/arboreto) | A scalable python-based framework for gene regulatory network inference using tree-based ensemble regressors. | 71 | [531](https://anaconda.org/bioconda/arboreto) | [5,197](https://pypi.org/project/arboreto/) | - | 2024-04-05 | [Bioinformatics (2019)](https://doi.org/10.1093/bioinformatics/bty916) |
| [Cytoscape](https://github.com/cytoscape/cytoscape) | Cytoscape: an open source platform for network analysis and visualization | 735 | [214](https://anaconda.org/bioconda/cytoscape) | - | - | 2026-10-09 | [Genome Res (2003)](https://doi.org/10.1101/gr.1239303) |
| [pySCENIC](https://github.com/aertslab/pySCENIC) | pySCENIC is a lightning-fast python implementation of the SCENIC pipeline (Single-Cell rEgulatory Network Inference... | 646 | [412](https://anaconda.org/bioconda/pyscenic) | [4,466](https://pypi.org/project/pyscenic/) | - | 2025-01-09 | [Nat Protoc (2020)](https://doi.org/10.1038/s41596-020-0336-2) |
| [WGCNA](https://cran.r-project.org/package=WGCNA) | Weighted Correlation Network Analysis | - | [2,214](https://anaconda.org/bioconda/r-wgcna) | - | [32,832](https://cran.r-project.org/package=WGCNA) | - | [BMC Bioinformatics (2008)](https://doi.org/10.1186/1471-2105-9-559) |

See also: [Cell trajectories, markers & regulation](#cell-trajectories-markers--regulation); [Multi-omics integration](#multi-omics-integration).

### Omics visualization & exploration

| Project | Description | Stars | Conda | Bioconductor | Updated | Paper |
| --- | --- | --- | --- | --- | --- | --- |
| [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap) | Make Complex Heatmaps | 1,561 | [10,216](https://anaconda.org/bioconda/bioconductor-complexheatmap) | [48,288](https://bioconductor.org/packages/ComplexHeatmap/) | 2026-04-02 | [Bioinformatics (2016)](https://doi.org/10.1093/bioinformatics/btw313) |
| [iSEE](https://github.com/iSEE/iSEE) | R/shiny interface for interactive visualization of data in SummarizedExperiment objects | 231 | [255](https://anaconda.org/bioconda/bioconductor-isee) | [6,161](https://bioconductor.org/packages/iSEE/) | 2026-07-13 | [F1000Res (2018)](https://doi.org/10.12688/f1000research.14966.1) |

See also: [Single-cell analysis & quality](#single-cell-analysis--quality).

## Footnotes

- Descriptions come from official repositories or package metadata.
- Package mappings and paper references are checked against official sources. One representative paper is linked for each tool, where available.
- Downloads cover the linked packages, including official interfaces. Each cell shows the largest count among the tool's curated packages in that source; its link identifies the package.
- For software that moved between GitHub repositories, Stars show the highest count among its current and previous official repositories.
- Updated is the committer date of the latest commit on the default or documented development branch.
- A tool may appear in several task groups; Contents counts each tool once.
- Licenses vary, and some tools restrict commercial use; check each project's terms before use.

Repository metadata: official repositories and package records, including the [GitHub REST API](https://docs.github.com/en/rest). Conda downloads: [Anaconda package data](https://github.com/anaconda/anaconda-package-data), Copyright Anaconda, Inc., [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). PyPI downloads: [PyPI Stats](https://pypistats.org/api/), excluding known mirrors. Bioconductor downloads: [official package statistics](https://bioconductor.org/packages/stats/). CRAN downloads: [cranlogs](https://cranlogs.r-pkg.org/), covering the RStudio CRAN mirror.
