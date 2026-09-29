# Maple Syrup Urine Disease (MSUD) – BCKDHA Gene Analysis

**Name:** Deguit, Zenas Charis C.
**Assigned Gene:** BCKDHA  
**Associated Disease:** Maple Syrup Urine Disease (MSUD)  
**Genome Assembly:** GRCh38/hg38  

---

# Project Overview

This activity investigated the **BCKDHA gene**, which is associated with **Maple Syrup Urine Disease (MSUD)**. The analysis used the UCSC Genome Browser and NCBI ClinVar to examine the genomic location, gene structure, conservation, and a disease-associated variant.

The activity also included sequence analysis using Galaxy to examine the wild-type BCKDHA coding sequence, protein sequence, a documented disease-associated mutation, and an artificial synonymous mutation.

---

# Disease and Gene Background

## Maple Syrup Urine Disease (MSUD)

Maple Syrup Urine Disease (MSUD) is an inherited metabolic disorder caused by impaired breakdown of the branched-chain amino acids **leucine, isoleucine, and valine**. The disorder is associated with pathogenic variants affecting genes that encode components of the branched-chain alpha-keto acid dehydrogenase complex.

The assigned gene for this activity is **BCKDHA**, which encodes the E1 alpha subunit of the branched-chain alpha-keto acid dehydrogenase complex.

---

# Objectives

The objectives of this activity were to:

1. Locate the BCKDHA gene in the UCSC Genome Browser.
2. Record the chromosome, genomic coordinates, strand, genome assembly, and approximate gene size.
3. Examine the exon, intron, and transcript structure of BCKDHA.
4. Examine additional UCSC tracks, including ClinVar and conservation information.
5. Select a BCKDHA variant from NCBI ClinVar.
6. Record the variant's HGVS description, genomic position, clinical significance, and associated disease.
7. Locate the selected variant back in the UCSC Genome Browser.
8. Interpret the location of the variant relative to the BCKDHA gene structure.
9. Reflect on what genomic browser and ClinVar information added to the analysis.
10. Perform sequence analysis of the BCKDHA wild-type and mutant sequences using Galaxy.

---

# PART A. GitHub Activity Record

This GitHub repository contains the screenshots, observations, sequence files, Galaxy evidence, and written answers for the BCKDHA/MSUD bioinformatics activity.

The screenshots are stored in the `Image/` folder.

---

# PART B. Locate the BCKDHA Gene in UCSC

## Gene Location

The BCKDHA gene was located using the **UCSC Genome Browser** with the human **GRCh38/hg38** genome assembly.

### Required Information

| Item | Record |
|---|---|
| **a. Official gene symbol** | BCKDHA |
| **b. Full gene name** | Branched chain keto acid dehydrogenase E1 subunit alpha |
| **c. Chromosome** | Chromosome 19 |
| **d. Genome assembly used** | GRCh38/hg38 |
| **e. Genomic coordinates shown in UCSC** | Approximately chr19:41,397,818–41,425,002 |
| **f. DNA strand** | Negative (-) strand |
| **g. Approximate gene size** | Approximately 27.2 kb |

### Required Proof – Screenshot 1

![Figure 1 – BCKDHA Gene Location in UCSC](Image/01_gene_location.png)

**Figure 1. BCKDHA gene location in the UCSC Genome Browser.**

### Description

The UCSC Genome Browser shows the location of the BCKDHA gene on chromosome 19 using the GRCh38/hg38 genome assembly. The gene is located on the negative strand and spans approximately 27.2 kb based on the displayed genomic coordinates.

---

# PART C. Understand the Gene Structure: Exons, Introns, and Transcripts

## BCKDHA Gene Structure

The BCKDHA gene structure was examined using the gene annotation track in UCSC. The gene model shows exon boxes connected by intronic regions. Multiple transcript models are also visible.

For the exon count, the selected BCKDHA transcript contains **9 identifiable exons**.

### Required Information

| Question | Answer |
|---|---|
| **a. Number of exons identified in the selected transcript** | 9 exons |
| **b. Were multiple transcripts/isoforms visible?** | Yes. Multiple transcript models were visible in the UCSC gene annotation track. |
| **c. What is the difference between an exon and an intron?** | Exons are regions retained in the mature RNA after RNA processing, while introns are intervening regions that are removed during RNA splicing. |
| **d. Were the introns generally longer or shorter than the exons?** | The introns generally appeared longer than the exon regions in the displayed BCKDHA gene structure. |

### Required Proof – Screenshot 2

![Figure 2 – BCKDHA Gene Structure](Image/02_gene_structure.png)

**Figure 2. BCKDHA exon, intron, and transcript structure in the UCSC Genome Browser.**

### Description

The UCSC gene model displays BCKDHA as a series of exon blocks connected by intronic regions. Several transcript models can be seen, showing that the same gene can have different transcript structures. In the selected transcript, 9 exons can be identified, while the connecting intronic regions are generally longer than the exon blocks.

---

# PART D. Turn On and Examine Genome Browser Tracks

Additional tracks were examined in the UCSC Genome Browser to provide information beyond the basic gene annotation. The **ClinVar Short Nucleotide Variants** track and the **100 Vertebrates Conservation** tracks were enabled.

## Required Information

### a. Which gene annotation track did you use?

I used the **NCBI RefSeq Genes** annotation track to view the BCKDHA gene model and its genomic structure.

### b. Were ClinVar-related variant marks visible within or near your gene?

Yes. ClinVar-related variant marks were visible within and near the BCKDHA gene region. These marks represent reported variants at genomic positions.

### c. Were some regions more conserved than others?

Yes. The conservation track showed that some regions had stronger conservation signals than others. Conservation was therefore not uniform across the entire BCKDHA genomic region.

### d. Did conserved regions correspond mainly to exons, introns, both, or another region?

The stronger conservation signals were mainly associated with **exonic/coding regions**, although conserved sequence can also occur in non-coding regions.

### e. In 2–3 sentences, explain why strong conservation can suggest biological importance.

Strong conservation means that a DNA sequence has remained similar across different species over evolutionary time. This can suggest that the region has an important biological function because functionally important sequences may be less tolerant of sequence changes.

---

## Required Proof – Screenshot 3

![Figure 3 – BCKDHA with ClinVar Track](Image/03_ClinVar_track.png)

**Figure 3. BCKDHA shown with an additional ClinVar-related track in the UCSC Genome Browser.**

### Additional Conservation Evidence

![Figure 4 – BCKDHA Conservation Track](Image/04_Conservation.png)

**Figure 4. BCKDHA region with the UCSC 100 Vertebrates conservation tracks.**

### Description

The additional UCSC tracks provided information about genomic variation and evolutionary conservation. The ClinVar-related track showed reported variant marks within or near the BCKDHA region. The conservation track showed differences in conservation strength across the gene region, with stronger conservation generally observed around exonic/coding portions.

---

# PART E. Select One Variant in NCBI ClinVar

The selected BCKDHA variant was examined using the NCBI ClinVar database.

## Selected Variant

**NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg)**

### Required Information

| Question | Answer |
|---|---|
| **a. Gene** | BCKDHA |
| **b. Variant name/HGVS description** | NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg) |
| **c. rsID or ClinVar Variation ID/VCV accession** | ClinVar Variation ID: 2381; VCV000002381.14 |
| **d. Chromosome and genomic position** | GRCh38: chr19:41,422,704 |
| **e. Associated condition/disease** | Maple Syrup Urine Disease (MSUD) |
| **f. Clinical significance exactly as reported by ClinVar** | Pathogenic/Likely pathogenic |
| **g. Review status, if shown** | The record displayed multiple submitted classifications contributing to the clinical significance. |
| **h. ClinVar record URL** | https://www.ncbi.nlm.nih.gov/clinvar/variation/2381/ |

### Variant Consequence

The selected variant is a **missense variant** that changes the BCKDHA coding sequence from **C to G at c.929**. This changes the codon from **ACA to AGA**, resulting in an amino acid substitution from **threonine (Thr/T) to arginine (Arg/R) at position 310**.

### Required Proof – Screenshot 4

![Figure 5 – ClinVar Variant Record](Image/04_ClinVar_Record.png)

**Figure 5. NCBI ClinVar record for BCKDHA c.929C>G (p.Thr310Arg).**

### Description

The ClinVar record identifies the selected variant as NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg). The record provides the genomic position, protein consequence, associated disease, and clinical significance. The variant is reported with a Pathogenic/Likely pathogenic classification in the displayed record.

---

# PART F. Find the Selected Variant Back in UCSC

The selected ClinVar variant was located again in the UCSC Genome Browser using its genomic position.

## Variant Used

**ClinVar Variation ID:** 2381  
**HGVS:** NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg)  
**GRCh38 genomic position:** chr19:41,422,704

## Required Information

### a. Where is the variant located relative to your gene?

The variant is located within the genomic region of the **BCKDHA gene** on chromosome 19.

### b. Is it in an exon, intron, UTR, splice region, or another region?

The variant is located in an **exonic coding region** of the BCKDHA gene based on the displayed gene annotation and the corresponding coding sequence annotation.

### c. Is it likely in a coding or non-coding region based on the displayed annotations?

It is in a **coding region**. This is consistent with the HGVS protein consequence **p.Thr310Arg**, which describes an amino acid substitution.

### d. Based on its location and ClinVar information, briefly explain how the variant might affect the gene or gene product.

Because the variant changes a coding nucleotide and results in a threonine-to-arginine amino acid substitution, it can alter the BCKDHA protein sequence. The ClinVar record reports the variant with a Pathogenic/Likely pathogenic classification, providing clinical evidence associated with the variant.

### e. What additional evidence would be needed before concluding that the variant causes disease?

Additional evidence could include functional studies showing the effect of the amino acid substitution on BCKDHA protein function, population frequency data, segregation information from affected families, and additional clinical or experimental evidence.

### Required Proof – Screenshot 5

![Figure 6 – Selected Variant in UCSC](Image/05_variant_in_UCSC.png)

**Figure 6. Selected BCKDHA variant located in the UCSC Genome Browser.**

### Description

The selected variant was located in UCSC using the genomic coordinate obtained from the ClinVar record. The browser view allows the variant position to be compared with the BCKDHA gene model and its annotated regions. The position is consistent with the coding variant identified in the ClinVar record.

---

# GALAXY SEQUENCE ANALYSIS

The sequence portion of the activity was performed using the Galaxy platform. The analysis focused on the BCKDHA reference sequence and the effects of documented and artificial mutations.

## Wild-Type BCKDHA Sequence

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| RefSeq transcript | NM_000709.4 |
| RefSeq protein | NP_000700.1 |
| CDS length | 1,338 bp |
| Protein length | 445 amino acids |
| Reading frame | Frame 1 |
| Genetic code | Standard |

The wild-type BCKDHA coding sequence was translated using Galaxy/SeqKit. Translation produced a protein sequence of 445 amino acids.

---

# Documented Disease-Associated Mutation

## BCKDHA c.929C>G (p.Thr310Arg)

The documented disease-associated variant analyzed in Galaxy was:

**c.929C>G (p.Thr310Arg)**

The nucleotide substitution changes the coding sequence from **C to G** at position 929. At the affected codon, **ACA** changes to **AGA**, resulting in an amino acid substitution from **threonine (T)** to **arginine (R)** at position 310.

### Expected Molecular Effect

| Feature | Result |
|---|---|
| DNA change | c.929C>G |
| Codon change | ACA → AGA |
| Amino acid change | Thr → Arg |
| Protein position | 310 |
| Mutation type | Missense |
| Frameshift | No |
| Premature stop | No |
| Expected protein length | 445 aa |

Because this is a single-nucleotide substitution, it does not shift the reading frame. The protein remains 445 amino acids long, but one amino acid is changed.

---

# Artificial Synonymous Mutation

An artificial mutation was also introduced to compare the effect of a synonymous nucleotide change.

**Artificial mutation:** c.303G>A

This changes the codon from **AAG to AAA**, but both codons encode lysine (K).

| Feature | Result |
|---|---|
| DNA change | c.303G>A |
| Codon change | AAG → AAA |
| Amino acid change | K → K |
| Mutation type | Synonymous |
| Frameshift | No |
| Premature stop | No |
| Expected protein length | 445 aa |

Because both AAG and AAA encode lysine, the artificial nucleotide substitution does not change the amino acid sequence.

---

# Galaxy Files

The following files were produced during the sequence analysis:

| File | Description |
|---|---|
| `MSUD_CDS.fasta.txt` | Wild-type BCKDHA CDS |
| `MSUD_protein.fasta` | Wild-type BCKDHA protein |
| `MSUD_BCKDHA_c929C_G_mutant.fasta` | Documented c.929C>G mutant CDS |
| `MSUD_mutant_protein.fasta` | Protein sequence containing the documented mutation |
| `MSUD_BCKDHA_artificial_c303G_A.fasta` | Artificial synonymous mutant CDS |
| `MSUD_artificial_mutant_protein.fasta` | Protein sequence from the artificial mutant |

---

# Sequence Comparison

The documented mutation c.929C>G produces a protein-level change from threonine to arginine at position 310. In contrast, the artificial c.303G>A substitution changes one nucleotide without changing the encoded amino acid.

The comparison demonstrates the difference between a **missense mutation**, which changes the amino acid sequence, and a **synonymous mutation**, which changes the DNA sequence but preserves the encoded amino acid.

---

# PART G. Short Reflection

## 1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?

UCSC showed the physical genomic organization of BCKDHA, including its chromosome location, genomic coordinates, exon and intron structure, transcript models, ClinVar variants, and conservation patterns. This provided a visual representation of the gene that cannot be obtained simply from reading a description of its biological function.

## 2. Why is knowing the exact genomic location of a disease-associated variant useful?

Knowing the exact genomic location makes it possible to connect a variant to a specific gene and genomic feature. It also allows the variant to be compared with exon boundaries, coding regions, UTRs, introns, and other genomic annotations.

## 3. What is one limitation of predicting a variant's effect only from its genomic location?

Genomic location alone does not provide enough information to determine the complete biological effect of a variant. Additional evidence such as protein-level consequences, functional studies, population data, clinical observations, and genetic segregation may be needed.

## 4. What was the most interesting feature you observed about your assigned gene?

One interesting feature was that the BCKDHA gene spans a relatively large genomic region while containing multiple exons and transcript models. It was also interesting to observe ClinVar variant marks and conservation information directly within the same genomic region.

---

# Conclusion

The UCSC Genome Browser provided a visual representation of the BCKDHA gene on chromosome 19, including its genomic coordinates, strand, exon and intron organization, transcript models, clinical variant information, and evolutionary conservation.

The ClinVar analysis identified **NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg)** as the selected disease-associated variant. The variant produces a missense amino acid substitution in the BCKDHA protein.

The Galaxy sequence analysis further demonstrated how a nucleotide substitution can affect a protein sequence. The documented c.929C>G mutation changes the amino acid at position 310, whereas the artificial c.303G>A mutation is synonymous and does not change the encoded amino acid.

Together, the UCSC Genome Browser, ClinVar, and Galaxy analyses provided complementary information about the genomic location, sequence, variation, and potential biological significance of BCKDHA variants.

---

# Galaxy History

The Galaxy workflow and sequence analysis were performed in the following Galaxy history:

**Deguit_MSUD_BCKDHA_Mutation_Lab**

The Galaxy history provides evidence for the sequence extraction, translation, mutation generation, and sequence comparison steps.

---

# References

1. National Center for Biotechnology Information (NCBI). **ClinVar: NCBI's database of genomic variation and its relationship to human health.**  
   https://www.ncbi.nlm.nih.gov/clinvar/

2. UCSC Genome Browser. **UCSC Genome Browser.**  
   https://genome.ucsc.edu/

3. National Center for Biotechnology Information (NCBI). **BCKDHA – Branched chain keto acid dehydrogenase E1 subunit alpha.**  
   https://www.ncbi.nlm.nih.gov/gene/593

4. National Center for Biotechnology Information (NCBI). **RefSeq: Reference Sequence Database.**  
   https://www.ncbi.nlm.nih.gov/refseq/

5. Galaxy Project. **Galaxy: An open, web-based platform for accessible, reproducible, and transparent computational research.**  
   https://galaxyproject.org/

6. GeneReviews. **Maple Syrup Urine Disease.**  
   https://www.ncbi.nlm.nih.gov/books/

