

Trp53cor1 KO vs WT (Male_leg)
======================================







This file shows the wt-v-ko comparison for Trp53cor1. 

Cuff overview:


```
## CuffSet instance with:
## 	 2 samples
## 	 26754 genes
## 	 77524 isoforms
## 	 0 TSS
## 	 23066 CDS
## 	 0 promoters
## 	 0 splicing
## 	 19954 relCDS
```

# QC

## Dispersion

Dispersion plot for genes in cuff:
(Overdispersion can lead to innacurate quants)

![plot of chunk dispersion](figure/dispersion-1.png) 

## Cross-replicate variability (fpkmSCVplot)
Differences in CV 2 can result in lower numbers of differentially expressed genes due to a higher degree of variability between replicate fpkm estimates.

Genes:

![plot of chunk CV_genes](figure/CV_genes-1.png) 

Isoforms: 

![plot of chunk cv_iso](figure/cv_iso-1.png) 

## MvA plot

![plot of chunk MvA](figure/MvA-1.png) 
   
### MvA plot counts

![plot of chunk MvA_counts](figure/MvA_counts-1.png) 

## Scatterplot matrix

![plot of chunk scatterplot](figure/scatterplot-1.png) 

## Distributions

### Boxplots

Boxplot (genes)

![plot of chunk boxplot_genes](figure/boxplot_genes-1.png) 

Boxplot (genes, replicates)

![plot of chunk boxplot_genes_replicates](figure/boxplot_genes_replicates-1.png) 

Boxplot (isoforms)

![plot of chunk boxplot_isoforms](figure/boxplot_isoforms-1.png) 

Boxplot (isoforms, replicates)

![plot of chunk boxplot_isoforms_replicates](figure/boxplot_isoforms_replicates-1.png) 

### Density

Density (genes)

![plot of chunk density](figure/density-1.png) 

Density (genes, replicates)

![plot of chunk density_w_replicates](figure/density_w_replicates-1.png) 


## Clustering

### Replicate Clusters

![plot of chunk replicate_clusters](figure/replicate_clusters-1.png) 

```
## NULL
```

### PCA (genes)

![plot of chunk PCA](figure/PCA-1.png) 

### MDS (genes)

![plot of chunk MDS](figure/MDS-1.png) 





# KO assessment

## Endogenous lncRNA expression

![plot of chunk lincp21](figure/lincp21-1.png) 

![plot of chunk lacZ](figure/lacZ-1.png) 

## Digital Genotyping (LacZ vs Endogenous lncRNA and Sex)

Eif2s3y is a y-expressed gene, Xist is an x-expressed gene 
Expression plot (endogenous linc, lacZ, Y-expressed gene):

![plot of chunk Digital_Genotyping](figure/Digital_Genotyping-1.png) 

Expression heatmap:

![plot of chunk digital_geno_heatmap](figure/digital_geno_heatmap-1.png) 

### Track visualization 

![plot of chunk track_vis](figure/track_vis-1.png) 

# Differential Analysis

## Differential Genes 



There are 89 significantly differentially expressed genes. They are:

<!-- html table generated in R 3.0.2 by xtable 1.7-3 package -->
<!-- Thu Apr  2 16:52:07 2015 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> geneAnnot$gene_short_name </TH>  </TR>
  <TR> <TD align="right"> 1 </TD> <TD> Cdh1 </TD> </TR>
  <TR> <TD align="right"> 2 </TD> <TD> Sox9 </TD> </TR>
  <TR> <TD align="right"> 3 </TD> <TD> Hspb1 </TD> </TR>
  <TR> <TD align="right"> 4 </TD> <TD> Ihh </TD> </TR>
  <TR> <TD align="right"> 5 </TD> <TD> Gltp </TD> </TR>
  <TR> <TD align="right"> 6 </TD> <TD> Matn4 </TD> </TR>
  <TR> <TD align="right"> 7 </TD> <TD> Acsl1 </TD> </TR>
  <TR> <TD align="right"> 8 </TD> <TD> Krt10 </TD> </TR>
  <TR> <TD align="right"> 9 </TD> <TD> Perp </TD> </TR>
  <TR> <TD align="right"> 10 </TD> <TD> Aim1 </TD> </TR>
  <TR> <TD align="right"> 11 </TD> <TD> Grhl1 </TD> </TR>
  <TR> <TD align="right"> 12 </TD> <TD> Krt19 </TD> </TR>
  <TR> <TD align="right"> 13 </TD> <TD> Hapln1 </TD> </TR>
  <TR> <TD align="right"> 14 </TD> <TD> Scel </TD> </TR>
  <TR> <TD align="right"> 15 </TD> <TD> Tgm1 </TD> </TR>
  <TR> <TD align="right"> 16 </TD> <TD> Cma1 </TD> </TR>
  <TR> <TD align="right"> 17 </TD> <TD> Sept3 </TD> </TR>
  <TR> <TD align="right"> 18 </TD> <TD> Endou </TD> </TR>
  <TR> <TD align="right"> 19 </TD> <TD> Col2a1 </TD> </TR>
  <TR> <TD align="right"> 20 </TD> <TD> Cldn1 </TD> </TR>
  <TR> <TD align="right"> 21 </TD> <TD> Cdkn1a </TD> </TR>
  <TR> <TD align="right"> 22 </TD> <TD> Glo1 </TD> </TR>
  <TR> <TD align="right"> 23 </TD> <TD> Tpsab1 </TD> </TR>
  <TR> <TD align="right"> 24 </TD> <TD> Anxa1 </TD> </TR>
  <TR> <TD align="right"> 25 </TD> <TD> Gldc </TD> </TR>
  <TR> <TD align="right"> 26 </TD> <TD> Ovol1 </TD> </TR>
  <TR> <TD align="right"> 27 </TD> <TD> Col9a1 </TD> </TR>
  <TR> <TD align="right"> 28 </TD> <TD> Pkp1 </TD> </TR>
  <TR> <TD align="right"> 29 </TD> <TD> Hdc </TD> </TR>
  <TR> <TD align="right"> 30 </TD> <TD> Tgm3 </TD> </TR>
  <TR> <TD align="right"> 31 </TD> <TD> Fabp5 </TD> </TR>
  <TR> <TD align="right"> 32 </TD> <TD> Col9a3 </TD> </TR>
  <TR> <TD align="right"> 33 </TD> <TD> Them5 </TD> </TR>
  <TR> <TD align="right"> 34 </TD> <TD> Aqp3 </TD> </TR>
  <TR> <TD align="right"> 35 </TD> <TD> Pla2g2f </TD> </TR>
  <TR> <TD align="right"> 36 </TD> <TD> Spp1 </TD> </TR>
  <TR> <TD align="right"> 37 </TD> <TD> Ibsp </TD> </TR>
  <TR> <TD align="right"> 38 </TD> <TD> Dmp1 </TD> </TR>
  <TR> <TD align="right"> 39 </TD> <TD> Ckm </TD> </TR>
  <TR> <TD align="right"> 40 </TD> <TD> Acan </TD> </TR>
  <TR> <TD align="right"> 41 </TD> <TD> Tnmd </TD> </TR>
  <TR> <TD align="right"> 42 </TD> <TD> Wwp2 </TD> </TR>
  <TR> <TD align="right"> 43 </TD> <TD> Trim29 </TD> </TR>
  <TR> <TD align="right"> 44 </TD> <TD> Elovl4 </TD> </TR>
  <TR> <TD align="right"> 45 </TD> <TD> Asprv1 </TD> </TR>
  <TR> <TD align="right"> 46 </TD> <TD> Tpsb2 </TD> </TR>
  <TR> <TD align="right"> 47 </TD> <TD> Evpl </TD> </TR>
  <TR> <TD align="right"> 48 </TD> <TD> Gdf5 </TD> </TR>
  <TR> <TD align="right"> 49 </TD> <TD> Ppl </TD> </TR>
  <TR> <TD align="right"> 50 </TD> <TD> Matn1 </TD> </TR>
  <TR> <TD align="right"> 51 </TD> <TD> BC006965 </TD> </TR>
  <TR> <TD align="right"> 52 </TD> <TD> Abca9 </TD> </TR>
  <TR> <TD align="right"> 53 </TD> <TD> S100a14 </TD> </TR>
  <TR> <TD align="right"> 54 </TD> <TD> Dsc1 </TD> </TR>
  <TR> <TD align="right"> 55 </TD> <TD> Krt1 </TD> </TR>
  <TR> <TD align="right"> 56 </TD> <TD> Sfn </TD> </TR>
  <TR> <TD align="right"> 57 </TD> <TD> Rpsa-ps10 </TD> </TR>
  <TR> <TD align="right"> 58 </TD> <TD> Fgfbp1 </TD> </TR>
  <TR> <TD align="right"> 59 </TD> <TD> Upk1b </TD> </TR>
  <TR> <TD align="right"> 60 </TD> <TD> Abca12 </TD> </TR>
  <TR> <TD align="right"> 61 </TD> <TD> Tacstd2 </TD> </TR>
  <TR> <TD align="right"> 62 </TD> <TD> Hbb-y </TD> </TR>
  <TR> <TD align="right"> 63 </TD> <TD> Lgals7 </TD> </TR>
  <TR> <TD align="right"> 64 </TD> <TD> Krt15 </TD> </TR>
  <TR> <TD align="right"> 65 </TD> <TD> Dsp </TD> </TR>
  <TR> <TD align="right"> 66 </TD> <TD> Hba-x </TD> </TR>
  <TR> <TD align="right"> 67 </TD> <TD> Myh8 </TD> </TR>
  <TR> <TD align="right"> 68 </TD> <TD> Hmga2 </TD> </TR>
  <TR> <TD align="right"> 69 </TD> <TD> Lypd3 </TD> </TR>
  <TR> <TD align="right"> 70 </TD> <TD> Krt4 </TD> </TR>
  <TR> <TD align="right"> 71 </TD> <TD> Dsc3 </TD> </TR>
  <TR> <TD align="right"> 72 </TD> <TD> Unc5c </TD> </TR>
  <TR> <TD align="right"> 73 </TD> <TD> Dmkn </TD> </TR>
  <TR> <TD align="right"> 74 </TD> <TD> Cytl1 </TD> </TR>
  <TR> <TD align="right"> 75 </TD> <TD> Rpl9-ps6 </TD> </TR>
  <TR> <TD align="right"> 76 </TD> <TD> Krt77 </TD> </TR>
  <TR> <TD align="right"> 77 </TD> <TD> Nnat </TD> </TR>
  <TR> <TD align="right"> 78 </TD> <TD> Dsg1a </TD> </TR>
  <TR> <TD align="right"> 79 </TD> <TD> Gm10275 </TD> </TR>
  <TR> <TD align="right"> 80 </TD> <TD> Hba-a1 </TD> </TR>
  <TR> <TD align="right"> 81 </TD> <TD> Krtdap </TD> </TR>
  <TR> <TD align="right"> 82 </TD> <TD> Dnm3os </TD> </TR>
  <TR> <TD align="right"> 83 </TD> <TD> Hmga1-rs1 </TD> </TR>
  <TR> <TD align="right"> 84 </TD> <TD> Trp53cor1 </TD> </TR>
  <TR> <TD align="right"> 85 </TD> <TD> Gm15500 </TD> </TR>
  <TR> <TD align="right"> 86 </TD> <TD> Rps2-ps10 </TD> </TR>
  <TR> <TD align="right"> 87 </TD> <TD> Gm9825 </TD> </TR>
  <TR> <TD align="right"> 88 </TD> <TD> Gm26924 </TD> </TR>
  <TR> <TD align="right"> 89 </TD> <TD> LacZ </TD> </TR>
   </TABLE>
![plot of chunk sigdiffGenetable](figure/sigdiffGenetable-1.png) 

Expression heatmap of sigGenes

![plot of chunk sigExpression heatmap](figure/sigExpression heatmap-1.png) 

Foldchange heatmap of sigGenes 

![plot of chunk DEgenes_FC_Heatmap](figure/DEgenes_FC_Heatmap-1.png) 



Now, look at genes that are detectably expressed (FPKM>0.5, yes I know it should be 1), and log2foldchange>2 in any direction: 88 genes

![plot of chunk expressed_and_changing](figure/expressed_and_changing-1.png) 



Now, those that are expressed, changing and called sig: 12 genes 

![plot of chunk expressed_and_changing_andSIG](figure/expressed_and_changing_andSIG-1.png) 

### Expression-level/significance relationship

Scatter plot of significant genes only:

![plot of chunk expression-sig_relationship](figure/expression-sig_relationship-1.png) 

Volcano Plot

![plot of chunk volcano](figure/volcano-1.png) 

Volcano plot with significant genes only:

![plot of chunk sig_volcano](figure/sig_volcano-1.png) 

### Differential Isoforms between conditions

Per isoform difference between conditions:

![plot of chunk diff_iso](figure/diff_iso-1.png) 

```
## Error in getGenes(cuff, isoformSigIDs, level = "isoforms"): unused argument (level = "isoforms")
```

These isoforms are:


```
## Error in as.data.frame(isoAnnot$gene_short_name): error in evaluating the argument 'x' in selecting a method for function 'as.data.frame': Error: object 'isoAnnot' not found
```

DE isoform heatmap


```
## Error in csHeatmap(isoformSigGenes, cluster = "both", replicates = T, : error in evaluating the argument 'object' in selecting a method for function 'csHeatmap': Error: object 'isoformSigGenes' not found
```

Isoform foldchange heatmap by isoform:


```
## Error in csFoldChangeHeatmap(isoforms(isoformSigGenes), "WT", replicates = TRUE, : error in evaluating the argument 'object' in selecting a method for function 'csFoldChangeHeatmap': Error in isoforms(isoformSigGenes) : 
##   error in evaluating the argument 'object' in selecting a method for function 'isoforms': Error: object 'isoformSigGenes' not found
```

# Gene/Pathway Analysis

## GSEA

Enrichment and zscores are calculated based on expression in KO vs WT (fpkmKO/fpkmWT), so genes that are down regulated in KO are shown in blue, while upregulation is shown in red. 

KO/WT
Blue = down in KO
Red = Up in KO





Biocarta enrichment: 

![plot of chunk print_GSEA_biocarta](figure/print_GSEA_biocarta-1.png) 

Biocarta zscore: 

![plot of chunk gsea_zscore_biocarta](figure/gsea_zscore_biocarta-1.png) 

Reactome enrichment:


```
## Error in x_ordered[1:50, ]: subscript out of bounds
```

![plot of chunk print_GSEA_reactome](figure/print_GSEA_reactome-1.png) 

Reactome zscore: 


```
## Error in x_ordered[1:50, ]: subscript out of bounds
```

![plot of chunk gsea_zscore_reactome](figure/gsea_zscore_reactome-1.png) 

Kegg enrichment: 

![plot of chunk gsea_enrichment_kegg](figure/gsea_enrichment_kegg-1.png) 

Kegg zscore: 

![plot of chunk gsea_zscore_kegg](figure/gsea_zscore_kegg-1.png) 


p53 enrichment: 

![plot of chunk gsea_enrichment_p53](figure/gsea_enrichment_p53-1.png) 

p53 zscore: 

![plot of chunk gsea_zscore_p53](figure/gsea_zscore_p53-1.png) 

Oncogene enrichment: 

![plot of chunk gsea_enrich_onco](figure/gsea_enrich_onco-1.png) 

Oncogene zscore:

![plot of chunk gsea_zscore_onco](figure/gsea_zscore_onco-1.png) 


Jacks enrichment
![plot of chunk jacks_enrich](figure/jacks_enrich-1.png) 


Jacks zscore

![plot of chunk jacks_zscore](figure/jacks_zscore-1.png) 


All enrichment 



There are 842 categories enriched (p<0.0001). They are:


```
## Error in x_ordered[1:500, ]: subscript out of bounds
```

![plot of chunk gsea_enrich_fig](figure/gsea_enrich_fig-1.png) 

ALL zscore:


```
## Error in x_ordered[1:500, ]: subscript out of bounds
```

![plot of chunk gsea_zscore_fig](figure/gsea_zscore_fig-1.png) 

## GO enrichment 
Cluster profiler used to call enichments of significantly differentially regulated genes that map to Entrez IDs. 





![plot of chunk GO_figures](figure/GO_figures-1.png) ![plot of chunk GO_figures](figure/GO_figures-2.png) ![plot of chunk GO_figures](figure/GO_figures-3.png) 

```
## Error in plot.window(...): need finite 'xlim' values
```

![plot of chunk GO_figures](figure/GO_figures-4.png) 

# Cis vs Trans (locally)

log2 Foldchange and test statistic are calculated with the ratio of fpkm(KO)/fpkm(WT), thus the test_stat is positive if a gene is higher in the KO and negative if a gene has lower expression in the KO





The pvalue for genes significantly regulated in a region this size  is: 0.052 

![plot of chunk cisreg_image](figure/cisreg_image-1.png) 

# Notes

## Samples used are:
<!-- html table generated in R 3.0.2 by xtable 1.7-3 package -->
<!-- Thu Apr  2 18:57:27 2015 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> 11 </TH>  </TR>
  <TR> <TD align="right"> 1 </TD> <TD> JR878 </TD> </TR>
  <TR> <TD align="right"> 2 </TD> <TD> JR881 </TD> </TR>
  <TR> <TD align="right"> 3 </TD> <TD> JR883 </TD> </TR>
  <TR> <TD align="right"> 4 </TD> <TD> lincp21_Leg_KO4 </TD> </TR>
   </TABLE>

## Replicates
<!-- html table generated in R 3.0.2 by xtable 1.7-3 package -->
<!-- Thu Apr  2 18:57:27 2015 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> file </TH> <TH> sample_name </TH> <TH> replicate </TH> <TH> rep_name </TH> <TH> total_mass </TH> <TH> norm_mass </TH> <TH> internal_scale </TH> <TH> external_scale </TH>  </TR>
  <TR> <TD align="right"> 1 </TD> <TD> /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR878/abundances.cxb </TD> <TD> WT </TD> <TD align="right">   0 </TD> <TD> WT_0 </TD> <TD align="right"> 48224900.00 </TD> <TD align="right"> 38745900.00 </TD> <TD align="right"> 1.22 </TD> <TD align="right"> 1.00 </TD> </TR>
  <TR> <TD align="right"> 2 </TD> <TD> /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR881/abundances.cxb </TD> <TD> WT </TD> <TD align="right">   1 </TD> <TD> WT_1 </TD> <TD align="right"> 43230900.00 </TD> <TD align="right"> 38745900.00 </TD> <TD align="right"> 1.11 </TD> <TD align="right"> 1.00 </TD> </TR>
  <TR> <TD align="right"> 3 </TD> <TD> /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR883/abundances.cxb </TD> <TD> Trp53cor1 </TD> <TD align="right">   0 </TD> <TD> Trp53cor1_0 </TD> <TD align="right"> 53017900.00 </TD> <TD align="right"> 38745900.00 </TD> <TD align="right"> 1.37 </TD> <TD align="right"> 1.00 </TD> </TR>
  <TR> <TD align="right"> 4 </TD> <TD> /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/lincp21_Leg_KO4/abundances.cxb </TD> <TD> Trp53cor1 </TD> <TD align="right">   1 </TD> <TD> Trp53cor1_1 </TD> <TD align="right"> 20607100.00 </TD> <TD align="right"> 38745900.00 </TD> <TD align="right"> 0.55 </TD> <TD align="right"> 1.00 </TD> </TR>
   </TABLE>

## Session Info

```
## R version 3.0.2 (2013-09-25)
## Platform: x86_64-unknown-linux-gnu (64-bit)
## 
## locale:
##  [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
##  [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
##  [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
##  [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
##  [9] LC_ADDRESS=C               LC_TELEPHONE=C            
## [11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       
## 
## attached base packages:
## [1] grid      parallel  methods   stats     graphics  grDevices utils    
## [8] datasets  base     
## 
## other attached packages:
##  [1] plyr_1.8.1                         
##  [2] stringr_0.6.2                      
##  [3] seqbias_1.10.0                     
##  [4] BSgenome.Mmusculus.UCSC.mm10_1.3.19
##  [5] BSgenome_1.30.0                    
##  [6] Biostrings_2.30.1                  
##  [7] GO.db_2.10.1                       
##  [8] org.Mm.eg.db_2.10.1                
##  [9] clusterProfiler_1.13.1             
## [10] DOSE_2.0.0                         
## [11] ReactomePA_1.6.1                   
## [12] AnnotationDbi_1.24.0               
## [13] Biobase_2.22.0                     
## [14] mgcv_1.8-2                         
## [15] nlme_3.1-117                       
## [16] RMySQL_0.9-3                       
## [17] RColorBrewer_1.0-5                 
## [18] gridExtra_0.9.1                    
## [19] gtable_0.1.2                       
## [20] marray_1.40.0                      
## [21] gplots_2.14.2                      
## [22] GSA_1.03                           
## [23] limma_3.18.13                      
## [24] xtable_1.7-3                       
## [25] cummeRbund_2.7.2                   
## [26] Gviz_1.6.0                         
## [27] rtracklayer_1.22.7                 
## [28] GenomicRanges_1.14.4               
## [29] XVector_0.2.0                      
## [30] IRanges_1.20.7                     
## [31] fastcluster_1.1.13                 
## [32] reshape2_1.4                       
## [33] ggplot2_1.0.0                      
## [34] RSQLite_0.11.4                     
## [35] DBI_0.3.1                          
## [36] BiocGenerics_0.8.0                 
## [37] knitr_1.7                          
## 
## loaded via a namespace (and not attached):
##  [1] biomaRt_2.18.0         biovizBase_1.10.8      bitops_1.0-6          
##  [4] caTools_1.17.1         cluster_1.15.2         colorspace_1.2-4      
##  [7] dichromat_2.0-0        digest_0.6.4           DO.db_2.7             
## [10] evaluate_0.5.5         formatR_1.0            Formula_1.1-2         
## [13] gdata_2.13.3           GenomicFeatures_1.14.5 GOSemSim_1.20.3       
## [16] graph_1.40.1           graphite_1.8.1         gtools_3.4.1          
## [19] Hmisc_3.14-4           igraph_0.7.1           KEGG.db_2.10.1        
## [22] KernSmooth_2.23-12     labeling_0.2           lattice_0.20-29       
## [25] latticeExtra_0.6-26    MASS_7.3-33            Matrix_1.1-4          
## [28] munsell_0.4.2          org.Hs.eg.db_2.10.1    proto_0.3-10          
## [31] qvalue_1.36.0          Rcpp_0.11.3            RCurl_1.95-4.3        
## [34] reactome.db_1.46.1     Rsamtools_1.14.3       scales_0.2.4          
## [37] splines_3.0.2          stats4_3.0.2           survival_2.37-7       
## [40] tcltk_3.0.2            tools_3.0.2            XML_3.98-1.1          
## [43] zlibbioc_1.8.0
```

## Run Info

```
##           param
## 1      cmd_line
## 2       version
## 3  SVN_revision
## 4 boost_version
## 5        genome
##                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                value
## 1 cuffdiff -p 10 -L WT,Trp53cor1 -o /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/diff/Trp53cor1_E14.5_Leg_male /n/rinn_data1/seq/lgoff/Projects/BrainMap/data/annotation/mm10_gencode_vM2_with_lncRNAs_and_LacZ.gtf /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR878/abundances.cxb,/n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR881/abundances.cxb /n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/JR883/abundances.cxb,/n/rinn_data1/users/agroff/seq/OtherMice/Diana/lincP21/quants/lincp21_Leg_KO4/abundances.cxb 
## 2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              2.2.1
## 3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               4237
## 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             104700
## 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               mm10
```
