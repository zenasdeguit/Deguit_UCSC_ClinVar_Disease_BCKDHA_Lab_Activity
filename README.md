# MSUD BCKDHA Mutation Analysis

## Project Overview

This project investigates **Maple Syrup Urine Disease (MSUD)** and the **BCKDHA** gene. The analysis examines a normal BCKDHA sequence, a documented disease-associated mutation, and a student-created artificial mutation.

The project used **NCBI, Galaxy, SeqKit Translate, UCSC Genome Browser, and ClinVar** to connect DNA sequence changes with predicted protein effects and genomic location.

---

# 1. Disease and Gene

## Maple Syrup Urine Disease (MSUD)

Maple Syrup Urine Disease is an inherited metabolic disorder that affects the breakdown of the branched-chain amino acids **leucine, isoleucine, and valine**. MSUD is inherited in an **autosomal recessive** pattern.

## BCKDHA

- **Gene:** BCKDHA
- **Chromosome:** 19
- **Location:** 19q13.2
- **Reference transcript:** NM_000709.4
- **Reference protein:** NP_000700.1
- **Protein:** 2-oxoisovalerate dehydrogenase subunit alpha

BCKDHA encodes the alpha subunit of the E1 component of the branched-chain alpha-ketoacid dehydrogenase complex.

---

# 2. Objectives

The project aimed to:

1. Obtain the BCKDHA wild-type CDS.
2. Translate the WT CDS into a protein sequence.
3. Analyze a documented BCKDHA mutation.
4. Create an artificial mutation.
5. Compare the resulting sequences and proteins.
6. Locate the documented variant using UCSC.
7. Examine ClinVar and conservation information.

---

# 3. Galaxy Sequence Analysis

## Wild-Type Sequence

The BCKDHA WT coding sequence was obtained from NCBI RefSeq.

| Feature | Result |
|---|---|
| Transcript | NM_000709.4 |
| Protein | NP_000700.1 |
| CDS length | 1,338 bp |
| Protein length | 445 aa |
| Reading frame | Frame 1 |
| Genetic code | Standard |

The WT CDS was translated using **SeqKit Translate** in Galaxy.

**WT protein:** `MSUD_protein.fasta`

---

## Documented Mutation

The documented BCKDHA mutation analyzed was:

**NM_000709.4:c.929C>G (p.Thr310Arg)**

The nucleotide substitution changes:

**ACA → AGA**

This results in:

**Thr310 → Arg310 (T310R)**

| Feature | Result |
|---|---|
| Mutation type | Missense |
| Nucleotide change | C → G |
| Codon change | ACA → AGA |
| Protein change | T310R |
| CDS length | 1,338 bp |
| Protein length | 445 aa |
| Frameshift | No |
| Premature stop | No |

**Documented mutant CDS:** `MSUD_BCKDHA_c929C_G_mutant.fasta`

**Documented mutant protein:** `MSUD_mutant_protein.fasta`

---

## Artificial Mutation

The student-created mutation was:

**c.303G>A**

The codon changes:

**AAG → AAA**

Both codons encode lysine (K), making this a **synonymous mutation**.

| Feature | Result |
|---|---|
| Nucleotide change | G → A |
| Codon change | AAG → AAA |
| Amino-acid change | K → K |
| Mutation type | Synonymous |
| Frameshift | No |
| Premature stop | No |
| Protein length | 445 aa |

**Artificial mutant CDS:** `MSUD_BCKDHA_artificial_c303G_A.fasta`

**Artificial mutant protein:** `MSUD_artificial_mutant_protein.fasta`

---

## Sequence Comparison

| Feature | WT | Documented Mutation | Artificial Mutation |
|---|---|---|---|
| CDS length | 1,338 bp | 1,338 bp | 1,338 bp |
| Protein length | 445 aa | 445 aa | 445 aa |
| Mutation | None | c.929C>G | c.303G>A |
| Codon change | — | ACA → AGA | AAG → AAA |
| Protein change | — | T310R | K → K |
| Mutation type | — | Missense | Synonymous |

The documented mutation changes one amino acid, while the artificial mutation does not change the predicted amino-acid sequence.

---

# 4. UCSC Genome Browser and ClinVar

## BCKDHA Gene Location

The BCKDHA gene was located in the **GRCh38/hg38** human genome assembly on chromosome 19 at approximately **chr19:41,397,818–41,425,002**.

### Figure 1. BCKDHA Gene Location

![Figure 1. BCKDHA gene location](Image/01_gene_location.png)

| Observation | Result |
|---|---|
| Gene | BCKDHA |
| Genome assembly | GRCh38/hg38 |
| Chromosome | Chromosome 19 |
| Cytogenetic location | 19q13.2 |
| Genomic coordinates | chr19:41,397,818–41,425,002 |
| DNA strand | Negative (-) |
| Approximate gene size | 27.2 kb |

**Description:** This figure shows the location of the **BCKDHA** gene in the human genome using the GRCh38/hg38 assembly. BCKDHA is located on chromosome 19 in the 19q13.2 region. The UCSC Genome Browser displays the genomic coordinates and gene annotation, allowing the physical position and approximate size of the gene to be examined.

---

## BCKDHA Gene Structure

The UCSC Genome Browser was used to examine the BCKDHA transcript and exon-intron structure.

### Figure 2. BCKDHA Exon-Intron and Transcript Structure

![Figure 2. BCKDHA gene structure](Image/02_gene_structure.png)

| Observation | Result |
|---|---|
| Gene | BCKDHA |
| Selected reference transcript | NM_000709.4 |
| Exons identified | 9 |
| Multiple transcripts visible | Yes |
| Exons | Shown as blocks/boxes in the gene models |
| Introns | Connecting regions between exon blocks |
| Relative intron length | Generally longer than the exon regions |

**Description:** This figure shows the exon-intron organization of **BCKDHA** using the UCSC gene annotation tracks. The selected BCKDHA transcript contains 9 identifiable exons, while several transcript models are visible in the browser. Exons are represented by blocks in the gene models, while the connecting regions represent introns. The introns generally appear longer than the exon regions. The activity requires choosing one transcript when counting exons and recording whether multiple transcripts are visible. :contentReference[oaicite:1]{index=1}

---

# 5. UCSC Annotation Tracks

The **ClinVar Short Nucleotide Variants <50bp** track and **UCSC 100 Vertebrates** conservation tracks were enabled.

## ClinVar Track

### Figure 3. ClinVar Variants in the BCKDHA Region

![Figure 3. ClinVar track](Image/03_ClinVar_track.png)

| Observation | Result |
|---|---|
| Gene annotation tracks | NCBI RefSeq / GENCODE |
| Clinical variant track | ClinVar Short Nucleotide Variants <50bp |
| ClinVar variant marks visible | Yes |
| Gene region examined | BCKDHA |
| Additional annotation | OMIM and other UCSC tracks |

**Description:** This figure shows the **ClinVar Short Nucleotide Variants <50bp** track together with the BCKDHA gene annotation. Multiple ClinVar-related variant marks are visible within or near the BCKDHA region. The track was used to examine reported clinical genetic variation in the region. The lab instructions emphasize selecting the specific disease-associated variant from ClinVar first rather than trying to identify it by visually guessing among many UCSC variant marks. :contentReference[oaicite:2]{index=2}

---

## Conservation Track

### Figure 4. BCKDHA Conservation Across Vertebrates

![Figure 4. BCKDHA conservation](Image/04_Conservation.png)

| Observation | Result |
|---|---|
| Conservation track | UCSC 100 Vertebrates |
| Conservation method | Basewise Conservation by PhyloP |
| Alignment track | Multiz Alignments of 100 Vertebrates |
| Species comparison | Multiple vertebrate species |
| Conservation pattern | Some regions show stronger conservation signals than others |
| Reference base at selected position | C |

**Description:** This figure shows the **UCSC 100 Vertebrates** conservation and multispecies alignment tracks across the BCKDHA region. The conservation track allows sequence positions to be compared across multiple vertebrate species. Some regions show stronger conservation signals than others. Strong conservation can suggest that a sequence has biological importance because similar sequence has been retained across species, although conservation alone does not prove that a particular variant causes disease. The activity specifically instructs students to report what they observe rather than assuming that all exons must be highly conserved. :contentReference[oaicite:3]{index=3}

---

# 6. Selected ClinVar Variant

The selected variant was:

**NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg)**

### Figure 5. NCBI ClinVar Record for BCKDHA c.929C>G

![Figure 5. ClinVar record](Image/04_ClinVar_Record.png)

| Observation | Result |
|---|---|
| Gene | BCKDHA |
| Variant | NM_000709.4:c.929C>G |
| Protein change | NP_000700.1:p.Thr310Arg |
| ClinVar Variation ID | 2381 |
| VCV accession | VCV000002381.14 |
| Chromosome | chr19 |
| GRCh38 position | 41,422,704 |
| Molecular consequence | Missense |
| Clinical significance | Pathogenic/Likely pathogenic |
| Associated condition | Maple Syrup Urine Disease (MSUD) |

**Description:** This figure shows the selected **NCBI ClinVar** record for **NM_000709.4(BCKDHA):c.929C>G (p.Thr310Arg)**. The record provides the variant identifier, HGVS descriptions, genomic position, protein consequence, and reported clinical significance. The variant is described as a missense change because the nucleotide substitution results in an amino-acid change from threonine to arginine at position 310. The activity requires the ClinVar record to document the gene, HGVS description, identifier, genomic position, associated disease, clinical significance, review status if shown, and record URL. :contentReference[oaicite:4]{index=4}

**ClinVar:**  
https://www.ncbi.nlm.nih.gov/clinvar/variation/2381/

---

# 7. Locating the Variant in UCSC

The ClinVar variant was located in UCSC using the GRCh38 position:

**chr19:41,422,704**

### Figure 6. BCKDHA c.929C>G Located in UCSC

![Figure 6. BCKDHA c.929C>G in UCSC](Image/05_variant_in_UCSC.png)

| Observation | Result |
|---|---|
| Genome assembly | GRCh38/hg38 |
| Chromosome | chr19 |
| Genomic position | chr19:41,422,704 |
| Gene | BCKDHA |
| Transcript shown | NM_000709.4 |
| Protein position | T310 |
| Variant | c.929C>G |
| ClinVar track | Visible |
| Conservation track | Visible |
| Gene model | Visible |

**Description:** This figure shows the selected ClinVar variant at **GRCh38 chr19:41,422,704** in the UCSC Genome Browser. The BCKDHA gene model is visible together with the ClinVar and conservation tracks, allowing the selected position to be compared with the annotated gene structure. The genomic position corresponds to the coding variant **c.929C>G**, which is annotated in ClinVar as the protein change **p.Thr310Arg**. The activity requires Screenshot 5 to show the selected variant together with the gene model so that its position relative to the gene structure can be examined. :contentReference[oaicite:5]{index=5}

---

# 8. Interpretation

### a. Where is the variant located relative to the gene?

The selected variant is located within the genomic region of the **BCKDHA** gene on chromosome 19 at GRCh38 position **chr19:41,422,704**.

### b. Is it in an exon, intron, UTR, splice region, or another region?

The variant corresponds to coding position **c.929** of the BCKDHA transcript and is associated with the protein change **p.Thr310Arg**. Therefore, the variant is located in the coding portion of the transcript.

### c. Is it likely in a coding or non-coding region?

The variant is in a **coding region** because the ClinVar record provides the protein consequence **p.Thr310Arg** and identifies the molecular consequence as missense.

### d. Based on its location and ClinVar information, how might the variant affect the gene or gene product?

The c.929C>G substitution changes the codon from **ACA to AGA**, resulting in the replacement of threonine with arginine at amino-acid position 310. The predicted protein remains 445 amino acids long, but the amino-acid substitution could affect the structure, stability, interactions, or activity of the BCKDHA protein.

### e. What additional evidence would be needed before concluding that the variant causes disease?

Additional evidence such as clinical observations, family segregation data, population-frequency information, functional experiments, and biochemical studies would help determine the biological and clinical effect of the variant.

The lab specifically requires these five interpretation questions and states that if a region cannot be determined confidently from the browser view, it should be reported as uncertain rather than guessed. :contentReference[oaicite:6]{index=6}

---

# 9. Short Reflection

### 1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?

UCSC showed the physical organization of BCKDHA, including its genomic location, transcript structure, clinical variants, and conservation across species. These details are not obvious from simply reading about the biological function of the gene.

### 2. Why is knowing the exact genomic location of a disease-associated variant useful?

The exact genomic location allows a variant to be connected to a specific gene, transcript, and genomic feature. It also makes it possible to compare the variant with clinical annotations and conservation information.

### 3. What is one limitation of predicting a variant's effect only from its genomic location?

Genomic location alone cannot show exactly how a variant affects protein structure or biological activity. Functional and clinical evidence are needed to determine the actual effect of a variant.

### 4. What was the most interesting feature you observed about your assigned gene?

One interesting feature was being able to view the BCKDHA gene structure together with ClinVar and conservation information in the same browser. This made it possible to connect a specific nucleotide variant with its genomic location and predicted protein consequence.

---

# 10. Conclusion

The analysis demonstrated how a DNA mutation can be followed from its genomic location to its predicted protein consequence.

The documented **BCKDHA c.929C>G** variant changes **ACA to AGA**, producing the predicted **T310R** amino-acid substitution. The artificial **c.303G>A** mutation changes **AAG to AAA** but remains synonymous because both codons encode lysine.

The UCSC Genome Browser and ClinVar provided genomic and clinical context for the documented variant, while Galaxy and SeqKit were used to analyze the sequence and predicted protein consequences.

---

# 11. Galaxy History

**Galaxy History:** `Deguit_MSUD_BCKDHA_Mutation_Lab`

| File | Purpose |
|---|---|
| `MSUD_CDS.fasta.txt` | WT BCKDHA CDS |
| `MSUD_protein.fasta` | WT protein |
| `MSUD_BCKDHA_c929C_G_mutant.fasta` | Documented mutant CDS |
| `MSUD_mutant_protein.fasta` | Documented mutant protein |
| `MSUD_BCKDHA_artificial_c303G_A.fasta` | Artificial mutant CDS |
| `MSUD_artificial_mutant_protein.fasta` | Artificial mutant protein |

---

# 12. References and Links

- **UCSC Genome Browser**  
  https://genome.ucsc.edu/

- **NCBI BCKDHA Gene**  
  https://www.ncbi.nlm.nih.gov/gene/593

- **NCBI ClinVar — Selected Variant**  
  https://www.ncbi.nlm.nih.gov/clinvar/variation/2381/

- **MedlinePlus Genetics — BCKDHA**  
  https://medlineplus.gov/genetics/gene/bckdha/

- **MedlinePlus Genetics — Maple Syrup Urine Disease**  
  https://medlineplus.gov/genetics/condition/maple-syrup-urine-disease/

- **GeneReviews — Maple Syrup Urine Disease**  
  https://www.ncbi.nlm.nih.gov/books/NBK1319/

---

