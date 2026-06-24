## Updates
This repository is modified for GoDMC vmeQTL project. Specifically, GoDMC vmeQTL run gene-environment interaction analysis on candidate associations while tensorQTL run interactions with SNPs in a certain cis-window.

I modified
1/ The cis-window to 2Mbp (default is 1Mbp)
2/ Interaction can be run on selected SNPs (need to have an additional candidate file)

The original tensorQTL repository can be found here https://github.com/broadinstitute/tensorqtl/tree/master

## tensorQTL

tensorQTL is a GPU-enabled QTL mapper, achieving ~200-300 fold faster *cis*- and *trans*-QTL mapping compared to CPU-based implementations.

If you use tensorQTL in your research, please cite the following paper:
[Taylor-Weiner, Aguet, et al., *Genome Biol.*, 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1836-7).</br>
Empirical beta-approximated p-values are computed as described in [Ongen et al., *Bioinformatics*, 2016](https://academic.oup.com/bioinformatics/article/32/10/1479/1742545).
