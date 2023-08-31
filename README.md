# SVHack_Mendelian

## Please cite our work

### DOI:

# Introduction

## What's the problem?

Rare diseases, which are variably defined as having a prevalence of 5-80 per 100,000 people, are estimated to affect 3.5-5.9% of the global population (263-446 million) and approximately 72% of the rare diesease in Orphanet have a genetic etiology [https://pubmed.ncbi.nlm.nih.gov/31527858/]. Mendelian disorders, aka monogenic diseases, are undiagnosed by exome sequencing in ~50-75% of cases [https://www.nature.com/articles/ncomms15824]. A sizable portion of mendelian diseases are caused by SVs, (including complex SVs), but the extent of this is unclear [Schuy et al. 2022]. In the absence of reliable databases for phenotypically relevant SVs - like gnomAD or clinvar for SNVs - the interpretation of variants is often challenging.

In the case of a diseased child of healthy parents, all de-novo SVs are promising candidates for disease association and thus interesting to know. They can, in principle, be found via mendelian inconsistency analysis. In practice, this will yield false positives due to noise inherent in SV calling and merging. 

# What is <this software>?

<This software> is a QC framework tool that creates a local assembly of every novel SV candidate locus in each member of the trio to aid in confirming that the SV is indeed novel in the child.

# How to use <this software>

# Software Workflow Diagram

<img src="https://github.com/collaborativebioinformatics/SVHack_Mendelian/blob/jdh/SVHack_Mendelian_overview.drawio.png">

# Installing <this software> from Github

`git clone https://github.com/collaborativebioinformatics/SVHack_Mendelian.git`  

