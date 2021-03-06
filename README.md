###### Bioinformatic pipeline for processing Sequence Capture data for Phylogenetics  
# seqcap_processor

  

***
  
  
#### Check the [Wiki-page](https://github.com/AntonelliLab/seqcap_processor/wiki) for a detailed work-flow!!
This software package constitutes an automated workflow for processing and analyzing of Illumina read data. The workflow was developed within a phylogenetic project concerning different genera of palms (Arecaceae), using the standardized probe-set as described in Heyduk et al. (2015).  

These scripts can also be applied to other Illumina datasets based on different probe sets, yet specific parameters for qualtiy filtering, adapter trimming and assembly of contigs may have to fitted to the specific dataset. The enclosed wiki-page explains the complete workflow, aimed at users with no prior Illumina experience. No advanced bioinformatic skills are required for carrying out this protocol.  All scripts are written in python2.7 and in some cases have to be run with that specific python version for proper functioning!

Some scripts are modified versions of the scripts from the [Phyluce pipeline](https://github.com/faircloth-lab/phyluce) by Braint Faircloth (in those cases you find the license agreement at the beginning of the script), which is aimed at the processing of UCE data for Vertebrates. To honour some of the ingenious ideas belonging to Brant Faricloth for efficiently scripted NGS read processing, and the generous sharing of all is code as open-source, we ask you to cite his Phyluce pipeline (Faircloth et al. 2015) alongside with ours, when using these scripts.  
  
The scripts require the following programs to be installed. Just click on the name of the program to open the download link:  
- [Trimmomatic] (http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/Trimmomatic-Src-0.33.zip)
- [Trinity] (https://github.com/trinityrnaseq/trinityrnaseq/archive/1e099546fa81cc6bdf410a898527f9a1efc4c748.zip)
- [Sqlite3] (https://www.sqlite.org/2015/sqlite-shell-linux-x86-3081101.zip)
- [Samtools] (http://downloads.sourceforge.net/project/samtools/samtools/0.1.19/samtools-0.1.19.tar.bz2?r=&ts=1443908667&use_mir     ror=vorboss)  
  
For additional functions:
- [CLC Genomics Workbench] (http://www.clcbio.com/products/download-trial/?productName=CLC+Genomics+Workbench&productVersion=8.5     &productID=1637&rand=251767810)  
- EMBOSS (ftp://emboss.open-bio.org/pub/EMBOSS/old/6.3.1/EMBOSS-6.3.1.tar.gz)  
- [Picard] (https://github.com/broadinstitute/picard/zipball/master)  
- [Seqtk] (https://github.com/lh3/seqtk/archive/master.zip)

####References:
Heyduk, K., Trapnell, D. W., Barrett, C. F., & Leebens-Mack, J. (2015). Phylogenomic analyses of species relationships in the       genus Sabal (Arecaceae) using targeted sequence capture. Biological Journal of the Linnean Society.

Faircloth BC. 2015. PHYLUCE is a software package for the analysis of conserved genomic loci. bioRxiv. doi: 10.1101/027904.
