# MSUD BCKDHA Mutation Analysis

## Project Overview

This repository contains the sequence-analysis work for the Cell and Molecular Biology Laboratory activities involving **Maple Syrup Urine Disease (MSUD)** and the **BCKDHA** gene.

The project examines the normal BCKDHA coding sequence, a documented disease-associated mutation, and a student-created artificial mutation. The sequence analysis was performed using **NCBI**, **Galaxy**, **SeqKit Translate**, the **UCSC Genome Browser**, and **NCBI ClinVar**.

The main goal of the activity was to connect a DNA sequence change to its predicted protein consequence and to examine where a clinically reported variant is located in the human genome.

---

# 1. Assigned Gene and Disease

## Maple Syrup Urine Disease (MSUD)

Maple Syrup Urine Disease (MSUD) is an inherited metabolic disorder associated with impaired breakdown of the branched-chain amino acids **leucine, isoleucine, and valine**. Their metabolites can accumulate in the body and may affect the nervous system.

MSUD is inherited in an **autosomal recessive** pattern.

## BCKDHA

- **Official gene symbol:** BCKDHA
- **Full gene/protein description:** 2-oxoisovalerate dehydrogenase subunit alpha, mitochondrial isoform 1 precursor
- **Chromosome:** 19
- **Cytogenetic location:** 19q13.2
- **Reference transcript:** NM_000709.4
- **Reference protein:** NP_000700.1
- **Genome assembly used for UCSC:** GRCh38/hg38

BCKDHA encodes the alpha subunit of the E1 component of the branched-chain alpha-ketoacid dehydrogenase (BCKD) complex. This mitochondrial enzyme complex is involved in the metabolism of branched-chain amino acids.

---

# 2. UCSC Gene Location

The **UCSC Genome Browser** was used to locate BCKDHA in the human genome.

### Genome Browser Information

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| Genome assembly | GRCh38/hg38 |
| Chromosome | chr19 |
| Cytogenetic region | 19q13.2 |
| Approximate genomic coordinates | chr19:41,397,818–41,425,002 |
| Approximate gene size | 27.2 kb |
| Strand | Negative (-) |

The BCKDHA gene was located on chromosome 19 in the 19q13.2 region. The gene spans approximately 27 kb in the GRCh38 assembly.


---

# 3. Exons, Introns, and Transcripts

The UCSC Genome Browser was used to examine the structure of the BCKDHA gene.

The **NCBI RefSeq** and **GENCODE** annotation tracks showed multiple transcript representations of BCKDHA. Different horizontal gene models can represent different transcripts or isoforms.

For the selected BCKDHA transcript, **NM_000709.4**, the gene structure contains **9 identifiable exons**.

### Observations

- Multiple BCKDHA transcript models are visible in UCSC.
- Exons are represented as blocks or boxes.
- Introns are represented by connecting lines between exon regions.
- The intronic regions are generally much longer than the exon regions.
- Different transcripts can have differences in exon boundaries or transcript structure.

### Exon vs. Intron

An **exon** is a region of a gene that is retained in the mature RNA transcript. In protein-coding genes, coding portions of exons contain the information used to determine the amino-acid sequence.

An **intron** is a region located between exons that is removed from the pre-mRNA during RNA processing. Introns therefore separate the exon regions in the genomic sequence.


---

# 4. UCSC Annotation Tracks

After locating BCKDHA, additional annotation tracks were enabled in the UCSC Genome Browser.

The main tracks examined were:

- GENCODE
- NCBI RefSeq
- ClinVar Short Nucleotide Variants <50bp
- OMIM Alleles
- OMIM Genes
- GTEx gene expression
- UCSC 100 Vertebrates conservation
- Multiz Alignments of 100 Vertebrates

## ClinVar Track

The **ClinVar Short Nucleotide Variants <50bp** track was enabled to display clinically reported small variants in the genomic region.

ClinVar-related variant marks were visible within the BCKDHA region. Because many variants can occur in a gene, the specific disease-associated variant was selected first from NCBI ClinVar and was then located in UCSC using its genomic coordinate.

## Conservation Track

The **UCSC 100 Vertebrates** conservation track was also enabled.

The browser displayed a **100 vertebrates Basewise Conservation by PhyloP** track and a **Multiz Alignments of 100 Vertebrates** track. The conservation signal varied across the displayed region, indicating that some positions are more conserved across species than others.

The selected variant position is within a region where the reference base is shown as **C** in the conservation/alignment view.

Strong conservation can suggest that a sequence region has been maintained across species because it may have an important biological function. However, conservation alone does not prove that a particular variant causes disease.


---

# 5. Selected ClinVar Variant

One clinically reported BCKDHA variant was selected from **NCBI ClinVar**.

### Selected Variant

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| HGVS cDNA description | NM_000709.4:c.929C>G |
| Protein change | NP_000700.1:p.Thr310Arg |
| Short protein notation | p.Thr310Arg (T310R) |
| Variant type | Single nucleotide variant |
| Molecular consequence | Missense |
| ClinVar Variation ID | 2381 |
| VCV accession shown in record | VCV000002381.14 |
| Chromosome | chr19 |
| GRCh38 genomic position | 41,422,704 |
| GRCh38 genomic HGVS | NC_000019.10:g.41422704C>G |
| Clinical significance | Pathogenic/Likely pathogenic |
| Associated disease | Maple Syrup Urine Disease (MSUD) |

The ClinVar record identifies the nucleotide substitution as **c.929C>G** and the resulting amino-acid substitution as **p.Thr310Arg**.

The variant is a missense variant because a single nucleotide substitution changes the encoded amino acid.

### Mutation Interpretation

The coding change can be represented as:

**c.929C>G**

This changes the codon:

**ACA → AGA**

The codon change results in:

**Thr (T) → Arg (R)**

Therefore, the predicted protein-level change is:

**p.Thr310Arg (T310R)**

The substitution does not change the overall number of nucleotides in the CDS and does not create a frameshift.


### ClinVar Record Link

NCBI ClinVar:

https://www.ncbi.nlm.nih.gov/clinvar/variation/2381/

---

# 6. Locating the Variant in UCSC

The selected ClinVar variant was then located in the UCSC Genome Browser using the GRCh38 genomic coordinate:

**chr19:41,422,704**

The UCSC search was performed using the variant position so that the exact nucleotide could be examined in relation to the BCKDHA gene model.

The browser displayed:

**chr19:41,422,704–41,422,704**

The BCKDHA transcript and the variant position were visible together. The browser also showed the ClinVar-related track, RefSeq/GENCODE annotations, and the conservation tracks.

The position corresponds to the region associated with **T310** in the BCKDHA transcript. This is consistent with the ClinVar HGVS description **c.929C>G (p.Thr310Arg)**.

Based on the transcript annotation and the amino-acid designation, the variant is located in the **coding portion of the BCKDHA transcript** rather than an intronic region.


---

# 7. Interpretation

## Where is the variant located relative to the gene?

The selected variant is located within the genomic region occupied by the **BCKDHA** gene on chromosome 19. In GRCh38, the variant is located at **chr19:41,422,704**.

## Is the variant in an exon, intron, UTR, or another region?

The variant corresponds to the coding position **c.929** of the BCKDHA transcript and produces the protein substitution **p.Thr310Arg**. Therefore, it is associated with the coding portion of the transcript rather than an intronic region.

## Is the variant likely in a coding or non-coding region?

The variant is in a **coding region** because the ClinVar record provides a protein consequence, **p.Thr310Arg**, and identifies it as a missense variant.

## How might the variant affect the gene or gene product?

The c.929C>G substitution changes the codon from **ACA to AGA**, replacing threonine with arginine at amino-acid position 310. Although the overall predicted protein length remains 445 amino acids, changing one amino acid can potentially influence protein structure, stability, interactions, or activity depending on the position and properties of the substituted residues.

ClinVar provides clinical classification information for this variant, but genomic location and computational sequence analysis alone do not establish the complete biological mechanism.

## What additional evidence is needed before concluding that the variant causes disease?

Additional evidence can include clinical observations, segregation studies, population-frequency data, functional experiments, protein studies, and other independent genetic or biochemical evidence. These types of evidence help determine whether the sequence change actually affects BCKDHA function and contributes to the MSUD phenotype.

---

# 8. UCSC and ClinVar Activity Summary

The UCSC Genome Browser and NCBI ClinVar provided complementary information.

UCSC was used to examine the physical genomic location, gene structure, transcripts, clinical variant tracks, and conservation across species. ClinVar was used to identify the selected clinically reported variant and obtain its HGVS description, genomic position, protein consequence, and clinical classification.

The two resources were connected by using the GRCh38 coordinate from ClinVar to return to the exact position in UCSC.

The overall relationship can be summarized as:

**BCKDHA gene → c.929C>G nucleotide change → ACA→AGA codon change → p.Thr310Arg protein change → possible effect on BCKDHA function**

---

# 9. Short Reflection

## 1. What did UCSC show about your gene that was not obvious from simply reading about its function?

UCSC showed the physical organization of the BCKDHA gene in the human genome, including its chromosome location, exon-intron structure, and multiple transcript models. It also showed clinical variant information and conservation across many vertebrate species, which cannot be understood from gene function alone.

## 2. Why is knowing the exact genomic location of a disease-associated variant useful?

Knowing the exact genomic location makes it possible to connect a variant to a specific gene, transcript, exon, and coding region. It also allows the variant to be compared with genome annotations, conservation information, and other known variants.

## 3. What is one limitation of predicting a variant's effect only from its genomic location?

Genomic location alone does not show exactly how a variant changes protein structure or biological activity. A variant may be located in a coding region but have a small effect, while other variants can affect gene expression or RNA processing without changing the protein sequence.

## 4. What was the most interesting feature you observed about your assigned gene?

One interesting feature was that the UCSC Genome Browser showed several BCKDHA transcript models and allowed the gene structure to be examined at the same time as clinical variant and conservation information. It was also useful to see how the exact ClinVar variant could be connected to a specific position within the BCKDHA gene.

---

# 10. Galaxy Sequence Analysis

The WT BCKDHA coding sequence was obtained from **NCBI RefSeq** and used as the reference sequence for the Galaxy analysis.

### WT Sequence Information

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| Reference transcript | NM_000709.4 |
| Reference protein | NP_000700.1 |
| Sequence type | Coding DNA sequence (CDS) |
| CDS length | 1,338 bp |
| Organism | *Homo sapiens* |
| Start codon | ATG |
| Stop codon | TGA |
| Reading frame | Frame 1 |

The original WT CDS was kept unchanged and used as the reference for the mutation analysis.

---

# 11. WT Translation

The WT BCKDHA CDS was translated using **SeqKit Translate** in Galaxy.

### Translation Settings

- Genetic code: Standard
- Reading frame: Frame 1
- Translate initial codon to M: Yes

### Results

- CDS length: **1,338 bp**
- Predicted protein length: **445 amino acids**
- Start codon: **ATG**
- Stop codon: **TGA**
- First 10 amino acids: `MAVAIAAARV`
- Last 10 amino acids: `EHYPLDHFDK`

**Output:** `MSUD_protein.fasta`

---

# 12. Documented Mutation

The documented BCKDHA mutation analyzed in the Galaxy sequence experiment was:

**NM_000709.4:c.929C>G (p.Thr310Arg)**

### Mutation Details

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| Reference transcript | NM_000709.4 |
| Reference protein | NP_000700.1 |
| Nucleotide change | C → G at c.929 |
| Codon change | ACA → AGA |
| Amino-acid change | Thr310 → Arg310 (T310R) |
| Mutation type | Missense |
| Nucleotides affected | 1 bp |
| CDS length | 1,338 bp |
| Predicted protein length | 445 aa |
| Frameshift | No |
| Premature stop | No |

The documented mutation was introduced into a copy of the WT CDS so that the original WT sequence remained unchanged.

**Documented mutant CDS:** `MSUD_BCKDHA_c929C_G_mutant.fasta`

---

# 13. Documented Mutant Translation

The documented mutant CDS was translated using the same SeqKit Translate settings as the WT sequence.

### Results

- Mutant CDS length: **1,338 bp**
- Predicted mutant protein length: **445 aa**
- Amino-acid change: **T310 → R310**
- Premature stop codon: **Absent**
- Reading-frame change: **None**

The WT and documented mutant proteins therefore have the same overall length, with the predicted difference being the **T310R substitution**.

**Output:** `MSUD_mutant_protein.fasta`

---

# 14. Artificial Mutation

A student-created artificial single-nucleotide substitution was introduced into a copy of the WT BCKDHA CDS.

**Artificial mutation: c.303G>A**

The nucleotide change converted:

**AAG → AAA**

Both codons encode lysine (K), so the artificial mutation was predicted to be **synonymous**.

### Artificial Mutation Information

| Feature | Result |
|---|---|
| Gene | BCKDHA |
| Reference transcript | NM_000709.4 |
| Mutation type | Single-nucleotide substitution |
| Nucleotide position | c.303 |
| Nucleotide change | G → A |
| Codon change | AAG → AAA |
| Predicted amino-acid change | K → K |
| Predicted mutation type | Synonymous |
| Predicted frameshift | No |
| Predicted premature stop | No |
| Predicted protein length | 445 aa |

**Artificial mutant CDS:** `MSUD_BCKDHA_artificial_c303G_A.fasta`

---

# 15. Artificial Mutant Translation

The artificial mutant CDS was translated using the same SeqKit Translate settings.

**Output:** `MSUD_artificial_mutant_protein.fasta`

### Results

- CDS length: **1,338 bp**
- Predicted protein length: **445 aa**
- Amino-acid substitution: **None**
- Reading-frame change: **None**
- Premature stop codon: **No**

The artificial mutation did not change the predicted amino-acid sequence because both **AAG** and **AAA** encode lysine.

---

# 16. WT Versus Mutant Protein Comparison

| Feature | WT | Documented Mutation | Artificial Mutation |
|---|---|---|---|
| CDS length | 1,338 bp | 1,338 bp | 1,338 bp |
| Protein length | 445 aa | 445 aa | 445 aa |
| Mutation | None | c.929C>G | c.303G>A |
| Codon change | ACA | ACA → AGA | AAG → AAA |
| Mutation type | N/A | Missense | Synonymous |
| Reading frame changed? | No | No | No |
| Premature stop? | No | No | No |
| Amino acids affected | None | T310 → R310 | None |
| Predicted protein-length change | None | None | None |

The documented and artificial mutations are both single-nucleotide substitutions, but they have different predicted protein-level consequences.

The documented **c.929C>G** substitution changes **ACA to AGA**, resulting in the amino-acid substitution **T310R**.

The artificial **c.303G>A** substitution changes **AAG to AAA**, but both codons encode lysine. Therefore, no amino-acid change is predicted for the artificial mutation.

---

# 17. Molecular Interpretation

The documented **c.929C>G** variant changes one nucleotide in the BCKDHA coding sequence and produces the predicted **Thr310Arg** substitution.

The computational analysis shows that the mutation does not change the length of the coding sequence, does not shift the reading frame, and does not introduce a premature stop codon. Instead, its predicted protein-level effect is a single amino-acid substitution.

Because BCKDHA encodes a component of the BCKD complex, changes that reduce normal BCKD complex function can interfere with the metabolism of branched-chain amino acids.

The computational workflow establishes the sequence-level relationship:

**DNA substitution → codon change → amino-acid substitution**

However, computational sequence analysis alone cannot demonstrate the complete biochemical or clinical effect of the mutation. Experimental and clinical evidence are needed to establish effects on protein stability, complex assembly, enzyme activity, and disease phenotype.

---

# 18. Galaxy History

### Galaxy History

`Deguit_MSUD_BCKDHA_Mutation_Lab`

### Relevant Files

| File | Filename | Purpose |
|---|---|---|
| File 1 | `MSUD_CDS.fasta.txt` | WT BCKDHA CDS |
| File 3 | `MSUD_protein.fasta` | Predicted WT protein |
| File 5 | `MSUD_BCKDHA_c929C_G_mutant.fasta` | Documented mutant CDS |
| File 6 | `MSUD_mutant_protein.fasta` | Predicted documented mutant protein |
| File 7 | `MSUD_BCKDHA_artificial_c303G_A.fasta` | Student-created artificial mutant CDS |
| File 8 | `MSUD_artificial_mutant_protein.fasta` | Predicted artificial mutant protein |

File 4 was an intermediate working copy and was deleted after the documented mutant sequence was produced.

---

# 19. Reproducibility

The overall workflow was:

1. Obtain the BCKDHA WT CDS from NCBI RefSeq.
2. Preserve the original WT sequence.
3. Upload the WT CDS to Galaxy.
4. Translate the WT CDS using SeqKit Translate.
5. Create a copy of the WT sequence for the documented mutation.
6. Introduce the documented c.929C>G substitution.
7. Translate the documented mutant CDS.
8. Compare the WT and documented mutant sequences.
9. Create a separate artificial mutation from the WT sequence.
10. Translate the artificial mutant CDS.
11. Compare the WT, documented mutant, and artificial mutant proteins.
12. Use UCSC Genome Browser to examine the BCKDHA genomic region.
13. Enable ClinVar and conservation tracks.
14. Identify the documented variant in NCBI ClinVar.
15. Return to UCSC using the GRCh38 genomic coordinate.
16. Interpret the variant in relation to the BCKDHA gene structure.
17. Document the findings and limitations.

---

# 20. Required Screenshots

The repository contains the following UCSC and ClinVar evidence:

| Screenshot | Description |
|---|---|
| `01_gene_location.png` | BCKDHA gene location in UCSC |
| `02_gene_structure.png` | BCKDHA exon-intron structure |
| `03_tracks.png` | UCSC ClinVar and conservation tracks |
| `04_ClinVar_Record.png` | Selected BCKDHA ClinVar record |
| `05_variant_in_UCSC.png` | Selected variant located in UCSC |

---

# 21. Conclusion

This analysis connected the BCKDHA gene, a clinically reported nucleotide variant, and its predicted protein consequence using several bioinformatics resources.

The UCSC Genome Browser showed the physical location and structure of BCKDHA, including transcript models, clinical variant annotations, and conservation information. NCBI ClinVar provided the clinical record for **NM_000709.4:c.929C>G (p.Thr310Arg)** and allowed the variant to be connected to its genomic coordinate.

The Galaxy analysis showed that the documented mutation changes one nucleotide and produces a predicted amino-acid substitution without changing the protein length or reading frame. In contrast, the artificial mutation was synonymous and did not change the predicted amino-acid sequence.

Overall, the activity demonstrated how a nucleotide-level change can be followed through the sequence-analysis workflow:

**Gene → genomic position → nucleotide change → codon change → protein consequence → possible biological effect**

---

# 22. References and Links

### UCSC Genome Browser

UCSC Genome Browser:  
https://genome.ucsc.edu/

UCSC Genome Browser Tutorials:  
https://genome.ucsc.edu/docs/tutorials/

UCSC Genome Browser 101 Tutorial:  
https://genome.ucsc.edu/docs/tutorials/gb101.html

### NCBI

NCBI BCKDHA Gene:  
https://www.ncbi.nlm.nih.gov/gene/593

NCBI ClinVar:  
https://www.ncbi.nlm.nih.gov/clinvar/

Selected ClinVar Variant — Variation ID 2381:  
https://www.ncbi.nlm.nih.gov/clinvar/variation/2381/

### Disease Information

MedlinePlus Genetics — BCKDHA:  
https://medlineplus.gov/genetics/gene/bckdha/

MedlinePlus Genetics — Maple Syrup Urine Disease:  
https://medlineplus.gov/genetics/condition/maple-syrup-urine-disease/

GeneReviews — Maple Syrup Urine Disease:  
https://www.ncbi.nlm.nih.gov/books/NBK1319/

---

# 23. Final Submission Checklist

- [x] GitHub repository
- [x] README.md
- [x] Assigned gene: BCKDHA
- [x] Associated disease: Maple Syrup Urine Disease (MSUD)
- [x] WT CDS
- [x] WT protein
- [x] Documented mutant CDS
- [x] Documented mutant protein
- [x] Artificial mutant CDS
- [x] Artificial mutant protein
- [x] WT-mutant comparison/alignment
- [x] UCSC gene location evidence
- [x] UCSC gene structure evidence
- [x] UCSC ClinVar/conservation evidence
- [x] NCBI ClinVar record evidence
- [x] Selected variant located back in UCSC
- [x] Interpretation questions
- [x] Reflection questions
- [x] References and links
- [x] Galaxy history evidence

---

## Galaxy History

Galaxy history used for the sequence analysis:

`Deguit_MSUD_BCKDHA_Mutation_Lab`
