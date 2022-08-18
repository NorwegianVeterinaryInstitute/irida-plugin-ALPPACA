# irida-plugin-ALPPACA

Input: Multi Fasta file 

### Step 1: ParSnp
Using harvest toools convert "xmfa" to "fasta"
Output: parsnp_alignement.fasta file (aligned multi fasta file) 
parsnpALIGNER.LOG/PARSNP_results.txt 

### Step 2:identify the recombinent areas 
Input: parsnp_alignement.fasta file (aligned multi fasta file)
Output: *filtered_polymorphic_sites.fasta (not filtered out but noted)
*per_branch_statistics.csv 

### Step 3: Masking the recombinant areas (Mask the recom area by N)
Input: ParSP multifastaalignmennt file
All the output files from Gubbins
Output: MASKRC_Masked_alignment.ALN

### (Optional) Step 4: SNP-dists
 
### Step 5: SNPSites - removes noninformatics segments and also % of nucleotides 
### Step 6: IQTree
Input: MASKRC_Masked_alignment.ALN and % of nucleotides 





