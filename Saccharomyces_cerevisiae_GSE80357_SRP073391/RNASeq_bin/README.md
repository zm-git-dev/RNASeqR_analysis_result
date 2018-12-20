```
.
├── Download
│   ├── gffcompare-0.10.4.Linux_x86_64.tar.gz
│   ├── hisat2-2.1.0-Linux_x86_64.zip
│   └── stringtie-1.3.4d.Linux_x86_64.tar.gz
├── extract_exons.py
├── extract_splice_sites.py
├── gffcompare
├── hisat2
├── hisat2-align-l
├── hisat2-align-l-debug
├── hisat2-align-s
├── hisat2-align-s-debug
├── hisat2-build
├── hisat2-build-l
├── hisat2-build-l-debug
├── hisat2-build-s
├── hisat2-build-s-debug
├── hisat2_extract_exons.py
├── hisat2_extract_snps_haplotypes_UCSC.py
├── hisat2_extract_snps_haplotypes_VCF.py
├── hisat2_extract_splice_sites.py
├── hisat2-inspect
├── hisat2-inspect-l
├── hisat2-inspect-l-debug
├── hisat2-inspect-s
├── hisat2-inspect-s-debug
├── hisat2_simulate_reads.py
├── hisatgenotype_build_genome.py
├── hisatgenotype_extract_reads.py
├── hisatgenotype_extract_vars.py
├── hisatgenotype_hla_cyp.py
├── hisatgenotype_locus.py
├── hisatgenotype.py
├── stringtie
└── Unpacked
    ├── gffcompare-0.10.4.Linux_x86_64
    │   ├── gffcompare
    │   └── LICENSE
    ├── hisat2-2.1.0
    │   ├── AUTHORS
    │   ├── doc
    │   │   ├── manual.inc.html
    │   │   ├── README
    │   │   └── style.css
    │   ├── example
    │   │   ├── index
    │   │   │   ├── 22_20-21M_snp.1.ht2
    │   │   │   ├── 22_20-21M_snp.2.ht2
    │   │   │   ├── 22_20-21M_snp.3.ht2
    │   │   │   ├── 22_20-21M_snp.4.ht2
    │   │   │   ├── 22_20-21M_snp.5.ht2
    │   │   │   ├── 22_20-21M_snp.6.ht2
    │   │   │   ├── 22_20-21M_snp.7.ht2
    │   │   │   └── 22_20-21M_snp.8.ht2
    │   │   ├── reads
    │   │   │   ├── reads_1.fa
    │   │   │   └── reads_2.fa
    │   │   └── reference
    │   │       ├── 22_20-21M.fa
    │   │       └── 22_20-21M.snp
    │   ├── extract_exons.py
    │   ├── extract_splice_sites.py
    │   ├── hisat2
    │   ├── hisat2-align-l
    │   ├── hisat2-align-l-debug
    │   ├── hisat2-align-s
    │   ├── hisat2-align-s-debug
    │   ├── hisat2-build
    │   ├── hisat2-build-l
    │   ├── hisat2-build-l-debug
    │   ├── hisat2-build-s
    │   ├── hisat2-build-s-debug
    │   ├── hisat2_extract_exons.py
    │   ├── hisat2_extract_snps_haplotypes_UCSC.py
    │   ├── hisat2_extract_snps_haplotypes_VCF.py
    │   ├── hisat2_extract_splice_sites.py
    │   ├── hisat2-inspect
    │   ├── hisat2-inspect-l
    │   ├── hisat2-inspect-l-debug
    │   ├── hisat2-inspect-s
    │   ├── hisat2-inspect-s-debug
    │   ├── hisat2_simulate_reads.py
    │   ├── hisatgenotype_build_genome.py
    │   ├── hisatgenotype_extract_reads.py
    │   ├── hisatgenotype_extract_vars.py
    │   ├── hisatgenotype_hla_cyp.py
    │   ├── hisatgenotype_locus.py
    │   ├── hisatgenotype_modules
    │   │   ├── hisatgenotype_assembly_graph.py
    │   │   ├── hisatgenotype_convert_codis.py
    │   │   ├── hisatgenotype_extract_codis_data.py
    │   │   ├── hisatgenotype_extract_cyp_data.py
    │   │   ├── hisatgenotype_gene_typing.py
    │   │   ├── hisatgenotype_typing_common.py
    │   │   └── __init__.py
    │   ├── hisatgenotype.py
    │   ├── hisatgenotype_scripts
    │   │   ├── compare_HLA_Omixon.py
    │   │   ├── extract_Omixon_HLA.py
    │   │   ├── hisatgenotype_HLA_genotyping_PGs.py
    │   │   └── hisatgenotype_locus_samples.py
    │   ├── LICENSE
    │   ├── MANUAL
    │   ├── MANUAL.markdown
    │   ├── NEWS
    │   ├── scripts
    │   │   ├── convert_quals.pl
    │   │   ├── gen_2b_occ_lookup.pl
    │   │   ├── gen_occ_lookup.pl
    │   │   ├── gen_solqual_lookup.pl
    │   │   ├── infer_fraglen.pl
    │   │   ├── make_a_thaliana_tair.sh
    │   │   ├── make_bdgp6.sh
    │   │   ├── make_bdgp6_tran.sh
    │   │   ├── make_b_taurus_UMD3.sh
    │   │   ├── make_canFam2.sh
    │   │   ├── make_ce10.sh
    │   │   ├── make_dm6.sh
    │   │   ├── make_e_coli.sh
    │   │   ├── make_grch37.sh
    │   │   ├── make_grch37_snp.sh
    │   │   ├── make_grch37_snp_tran_ercc.sh
    │   │   ├── make_grch37_snp_tran.sh
    │   │   ├── make_grch37_tran.sh
    │   │   ├── make_grch38.sh
    │   │   ├── make_grch38_snp.sh
    │   │   ├── make_grch38_snp_tran_ercc.sh
    │   │   ├── make_grch38_snp_tran.sh
    │   │   ├── make_grch38_tran.sh
    │   │   ├── make_grcm38.sh
    │   │   ├── make_grcm38_snp.sh
    │   │   ├── make_grcm38_snp_tran.sh
    │   │   ├── make_grcm38_tran.sh
    │   │   ├── make_hg19.sh
    │   │   ├── make_hg38_allsnp.sh
    │   │   ├── make_hg38.sh
    │   │   ├── make_hg38_snp.sh
    │   │   ├── make_hg38_snp_tran.sh
    │   │   ├── make_mm10.sh
    │   │   ├── make_mm9.sh
    │   │   ├── make_r64.sh
    │   │   ├── make_r64_tran.sh
    │   │   ├── make_rn4.sh
    │   │   ├── make_rn6.sh
    │   │   ├── make_rnor6.sh
    │   │   ├── make_rnor6_tran.sh
    │   │   ├── make_sc3.sh
    │   │   ├── make_wbcel235.sh
    │   │   ├── make_wbcel235_tran.sh
    │   │   └── make_zm3_snp_tran_ercc.sh
    │   ├── TUTORIAL
    │   └── VERSION
    └── stringtie-1.3.4d.Linux_x86_64
        ├── LICENSE
        ├── README
        └── stringtie
```
