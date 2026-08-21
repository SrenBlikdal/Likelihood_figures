# Likelihood_figures
Code to reproduce the plots for [link to paper]

Descriptions for aquring data is included in Final_figures_re.Rmd

For knitting Final_figures_re.Rmd # Likelihood_figures

Code used to reproduce the figures presented in **[paper title]** ([link to paper]).

## Data acquisition

Instructions for downloading and preprocessing all required datasets are provided in `Final_figures_re.Rmd`.

## Reproducing the figures

To knit `Final_figures_re.Rmd`, the `data/` directory must contain the following structure and filenames:

data/
├── bedMethyls/
│   ├── HG002_nanopore_chr1.bedMethyl.gz
│   ├── HG002_pacbio_chr1.bedMethyl.gz
│   ├── NN1854_ch24.bedmethyl
│   ├── NN1867_ch24.bedmethyl
│   ├── NN1870_ch24.bedmethyl
│   ├── NS1841_ch24.bedmethyl
│   ├── NS1860_ch24.bedmethyl
│   ├── NS1872_ch24.bedmethyl
│   ├── SS1849_ch24.bedmethyl
│   ├── SS1871_ch24.bedmethyl
│   └── SS1881_ch24.bedmethyl
│
└── truthset/
    ├── GCF_000001405.40_GRCh38.p14_genomic_CG_chr1.bed
    ├── GCF_000001405.40_GRCh38.p14_genomic_CH_chr1.bed
    ├── HG002_GRCh38_1_22_v4.2.1_benchmark_chr1.vcf
    ├── HG002_GRCh38_1_22_v4.2.1_benchmark_noinconsistent_chr1.bed
    └── Mmenidia_refgenome_anchored.all_renamed_v2_CG_ch24.bed- data folder should have this structure and filenames:
 
Likelihood_figures % ls data/*/ 
data/bedMethyls/:
HG002_nanopore_chr1.bedMethyl.gz	NN1870_ch24.bedmethyl			SS1849_ch24.bedmethyl
HG002_pacbio_chr1.bedMethyl.gz		NS1841_ch24.bedmethyl			SS1871_ch24.bedmethyl
NN1854_ch24.bedmethyl			NS1860_ch24.bedmethyl			SS1881_ch24.bedmethyl
NN1867_ch24.bedmethyl			NS1872_ch24.bedmethyl

data/truthset/:
GCF_000001405.40_GRCh38.p14_genomic_CG_chr1.bed
GCF_000001405.40_GRCh38.p14_genomic_CH_chr1.bed
HG002_GRCh38_1_22_v4.2.1_benchmark_chr1.vcf
HG002_GRCh38_1_22_v4.2.1_benchmark_noinconsistent_chr1.bed
Mmenidia_refgenome_anchored.all_renamed_v2_CG_ch24.bed
