## What's in here?

This repository contains additional information regarding the results in Shulgina & Eddy (2021). This includes:

- For the ambiguous translation of CUG in _Saccharomycopsis_ and _Ascoidea_, alignments of tRNA<sub>CAG</sub> sequences
- For all five bacterial clades using new codon reassignments, alignments of relevant tRNAs and alignments of BUSCO genes containing the reassigned codon at conserved positions
- For the four new CGA/CGG reassignments, an in-depth analysis of each clade. This includes a write-up summarizing the evidence supporting each reassignment, containing some results such as tRNA phylogenetic trees that were not included in the paper. These analyses may include additional outgroup species not featured in the paper; however, the species numberings that are shared should be consistent. 

The supplemental files directly associated with the paper can be found in `paper_supplemental_files`.

## Repository contents

#### `yeast_CUG`: Yeast CUG results
- `saccharomycopsis_ascoidea_cag_ser_alignment.sto`: Stockholm alignment of tRNA<sup>Ser</sup><sub>CAG</sub> sequences in _Saccharomycopsis_ and _Ascoidea_ genomes
- `saccharomycopsis_ascoidea_cag_leu_alignment.sto`: Stockholm alignment of tRNA<sup>Leu</sup><sub>CAG</sub> sequences in _Saccharomycopsis_ and _Ascoidea_ genomes

#### `Bacilli_AGG_Met`: Bacilli AGG Arg&#8594;Met reassignment
- `Bacilli_AGG_Met_genomes_info.xlsx`: Excel spreadsheet of info on reassigned and close outgroup genomes
- `Bacilli_AGG_Met_tRNA_alignment.sto`: Stockholm alignment of Arg and Met tRNAs from reassigned clade and outgroups
- `Bacilli_AGG_Met_uridylate_kinase_alignment.sto`: Stockholm alignment of uridylate kinase sequences
- `Bacilli_AGG_tRNA_syntenic_regions.pdf`: visualization of genomic context surrounding the tRNA<sub>CAG</sub> in reassigned and outgroup genomes 

#### `Peptacetobacter_CGG_Gln`: _Peptacetobacter_ CGG Arg&#8594;Gln reassignment 
- `Peptacetobacter_CGG_Gln_analysis.pdf`: A detailed write-up about the _Peptacetobacter_ CGG Arg&#8594;Gln reassignment
- `Peptacetobacter_CGG_Gln_genomes_info.xlsx`: Excel spreadsheet of info on reassigned and close outgroup genomes
- `Peptacetobacter_CGG_Gln_tRNA_alignment.sto`: Stockholm alignment of Arg and Gln tRNAs from reassigned clade and outgroups
- `Peptacetobacter_CGG_Gln_POG091H022D_alignment.sto`: Stockholm alignment of BUSCO POG091H022D
- `Peptacetobacter_CGG_Gln_POG091H01H6_alignment.sto`: Stockholm alignment of BUSCO POG091H01H6
- `Peptacetobacter_CGG_Gln_POG091H0124_alignment.sto`: Stockholm alignment of BUSCO POG091H0124
- `Peptacetobacter_CGG_Gln_POG091H00IF_alignment.sto`: Stockholm alignment of BUSCO POG091H00IF


#### `Bacilli_CGG_Trp`: Bacilli CGG Arg&#8594;Trp reassignment  
- `Bacilli_CGG_Trp_analysis.pdf`: A detailed write-up about the Bacilli CGG Arg&#8594;Trp reassignment  
- `Bacilli_CGG_Trp_genomes_info.xlsx`: Excel spreadsheet of info on reassigned and close outgroup genomes
- `Bacilli_CGG_Trp_tRNA_alignment.sto`: Stockholm alignment of Arg and Trp tRNAs from reassigned clade and outgroups
- `Bacilli_CGG_Trp_POG091H02IX_alignment.sto`: Stockholm alignment of BUSCO POG091H02IX
- `Bacilli_CGG_Trp_POG091H024G_alignment.sto`: Stockholm alignment of BUSCO POG091H024G
- `Bacilli_CGG_Trp_POG091H01RS_alignment.sto`: Stockholm alignment of BUSCO POG091H01RS
- `Bacilli_CGG_Trp_POG091H01PM_alignment.sto`: Stockholm alignment of BUSCO POG091H01PM
- `Bacilli_CGG_Trp_POG091H01G9_alignment.sto`: Stockholm alignment of BUSCO POG091H01G9

#### `Anaerococcus_CGG_Trp`: _Anaerococcus_ CGG Arg&#8594;Trp reassignment 
- `Anaerococcus_CGG_Trp_analysis.pdf`: A detailed write-up about the _Anaerococcus_ CGG Arg&#8594;Trp reassignment 
- `Anaerococcus_CGG_Trp_genomes_info.xlsx`: Excel spreadsheet of info on reassigned and close outgroup genomes
- `Anaerococcus_CGG_Trp_tRNA_alignment.sto`: Stockholm alignment of Arg and Trp tRNAs from reassigned clade and outgroups
- `Anaerococcus_CGG_Trp_POG091H024G_alignment.sto`: Stockholm alignment of BUSCO POG091H024G

#### `Absconditabacteria_CGA_CGG_Trp`: Absconditabacteria CGA & CGG Arg&#8594;Trp reassignment 
- `Absconditabacteria_CGA_CGG_Trp_analysis.pdf`: A detailed write-up about the Absconditabacteria CGA & CGG Arg&#8594;Trp reassignment 
- `Absconditabacteria_CGA_CGG_Trp_genomes_info.xlsx`: Excel spreadsheet of info on reassigned and close outgroup genomes
- `Absconditabacteria_CGA_CGG_Trp_tRNA_alignment.sto`: Stockholm alignment of Arg and Trp tRNAs from reassigned clade and outgroups
- `Absconditabacteria_CGA_CGG_Trp_POG091H02K5_alignment.sto`: Stockholm alignment of BUSCO POG091H02K5
- `Absconditabacteria_CGA_CGG_Trp_POG091H01WE_alignment.sto`: Stockholm alignment of BUSCO POG091H01WE
- `Absconditabacteria_CGA_CGG_Trp_POG091H0131_alignment.sto`: Stockholm alignment of BUSCO POG091H0131
- `Absconditabacteria_CGA_CGG_Trp_POG091H00BZ_alignment.sto`: Stockholm alignment of BUSCO POG091H00BZ

#### `paper_supplemental_files`: Supplemental files from Shulginna & Eddy (2021)
- `SupplFile1_summary_inference_all_assemblies.csv`: From a screen of >250,000 bacterial and archaeal genomes, a list of all analyzed genome assemblies with the inferred genetic code, inclusion in dereplicated dataset, and number of expected, unexpected, and uninferred codon inferences.
- `SupplFile2_summary_spreadsheet_all_candidate_novel_codes.xls`: List of all candidate new codon reassignments, with additional information.
- `Fig2_SourceData_yeast_phylogenetic_groupings.xls`: Table of all analyzed yeast genomes with phylogenetic grouping and Codetta CUG inference
- `Fig3_SourceData_Bacilli_AGG_Met_genomes_info.xlsx`: For the AGG$\rightarrow$Met reassignment, a table of genome accessions, Codetta AGG inference, tRNA gene presence, codon usage, and genome GC content for reassigned and outgroup genomes.
- `Fig4_SourceData_CGA_CGG_reassignments_genome_info.xlsx`: For each of the CGA/CGG reassignments, a table of genome accessions, Codetta CGA/CGG inference, tRNA gene presence, codon usage, and genome GC content for the reassigned clade and outgroup species. Includes fewer outgroup species than equivalent file in each above directories about each reassignment.

