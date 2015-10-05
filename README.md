# giab_FAQ
This repository contains FAQs (Frequently Asked Questions) for the Genome in a Bottle Consortium
************************************************************************************************

1. If I have data or analyses from GIAB samples, how can I submit data to GIAB ftp site?<br />
   <sub>If you have data or analysis results to be submitted to GIAB ftp site, please contact Justin Zook (Justin.Zook@nist.gov) and Chunlin Xiao (xiao2@ncbi.nlm.nih.gov). An instruction will be sent to you regarding how to set up an uploading account.</sub><br />

2. Where can I find the latest sequence data, alignment data, analysis results by analysis group for the GIAB project?<br />
   <sub>All the data from the GIAB project are under ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data. The data are being organized by the individual trio (or sample) first, then by sequencing platforms.  For a list of raw sequence files (eg fastq, fasta, hdf5, xsq, bnx format) or alignment files (eg bams, or xmap/cmap format) to download for your own analysis, you can go the repository of "giab_data_indexes" (https://github.com/genome-in-a-bottle/giab_data_indexes) to find the index file of interest with the particular sequencing platform.

   <sub>The "analysis" folder under each trio (or sample) contains analysis results submitted by the analysis group with the sub-folder names consisting of: (1). the name of the analyzer or submitter, (2). sequencing technology or dataset(s), (3). type of variant to be analyzed, (4). analysis tool being used, and (5). date that serves as "version".</sub><br />
   
3. Where can I find high-confidence variant calls and bed files from the GIAB project?<br />
   <sub>The latest release and old versions are always under: ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/release/</sub><br />
   
4. Why do you have both high-confidence vcf and bed files?<br />
   <sub>The vcf files describe high-confidence variant calls, and the bed file describe high-confidence regions.  If you wish to assess false positive rates, then you must use the bed file.  Any variant calls you find in the high-confidence regions that are not in the high-confidence vcf are putative false positives.</sub><br />

5. What tool should I use to compare my SNP and small indel calls to the GIAB high-confidence calls?<br />
   <sub>The Global Alliance for Genomics and Health Benchmarking Team is currently developing standardized definitions for performance metrics and tools to calculate these metrics, including around complex variants that can have multiple correct representations in vcf.  Three tools are currently being actively developed by the team:<br />
      vcfeval from Real Time Genomics (http://realtimegenomics.com/products/rtg-core-non-commercial/)<br />
      hap.py from Illumina (https://github.com/sequencing/hap.py)<br />
      vgraph from Kevin Jacobs (https://github.com/bioinformed/vgraph)</sub><br />

6. Can I access GIAB data from Amazon cloud?<br />
   <sub>Yes. All the GIAB data has been mirrored into Amazon S3, and the bucket name is s3://giab.</sub><br />

7. How can I get updates about new data, analyses, and conference calls of the GIAB Analysis Team?<br />
   <sub>Sign up for our GIAB Analysis Team google group at https://groups.google.com/forum/#!forum/giab-analysis-team.  You can also sign up for general GIAB emails (e.g., workshop announcements) at https://groups.google.com/forum/#!forum/genome-in-a-bottle. </sub><br />
