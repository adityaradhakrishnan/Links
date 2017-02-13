### 5P-Seq Protocol
Adapted from [Pelechano *et al. Nat Protoc.* 2016 **11**:359-76](https://www.ncbi.nlm.nih.gov/pubmed/?term=genome-wide+quantification+of+5'-phosphorylated)<br />
By Aditya Radhakrishnan (Current Version: February 12th, 2017)

This protocol is used to generate 5P-Seq sequencing libraries by enriching for mRNA species containing a 5' Phosphate group, which is a sign of 5' exonucleolytic cleavage by Xrn1. This protocol can also be used to quickly generate mRNA-Seq libraries without using gels, by using purely a magnetic (SPRI bead) based purification.<sup>1</sup>

**Table of Contents**

1. [Preparing total RNA from yeast](#preparing-total-rna-from-yeast)
2. [Preparing randomly fragmented samples for mRNA-Seq](#preparing-randomly-fragmented-samples-for-mrna-seq)
3. [Single-stranded RNA ligation](#single-stranded-rna-ligation)
4. [Depletion of rRNA molecules](#depletion-of-rrna-molecules)
5. [Fragmentation of mRNA](#fragmentation-of-mrna)
6. [Reverse transcription](#reverse-transcription)
7. [Second-strand synthesis by PCR](#second-strand-synthesis-by-pcr)
8. [Sample enrichment by streptavidin selection](#sample-enrichment by streptavidin selection)
9. [A-tailing DNA fragments](#a-tailing-dna-fragments)
10. [Common adapter ligation](#common-adapter-ligation)
11. [Library PCR amplification](#library-pcr-amplification)
12. [Library size selection](#library-size-selection)
13. [Bioinformatics analysis](#bioinformatics-analysis)
14. [Citations](#citations)

#### Preparing total RNA from yeast

1) Start with at least 25 ug of total mRNA and use Turbo DNase to remove any DNA that may persist in your total mRNA. While I've found that this is largely unnecessary following acid phenol extraction (DNA precipitates and migrates to the organic phase at low pH), it may be useful to address any contamination issues early. Further, this treatment often leads to minimal loss of mRNA.

2) Set up the following reaction and incubate samples at 37 <sup></sup>C for 30 minutes.

| Reagent                                  | Amount  |
|------------------------------------------|---------|
| Total RNA                                | > 25 ug |
| TURBO DNase Buffer (10x)                 | 5 uL    |
| TURBO DNase Enzyme (2 U uL<sup>-1</sup>) | 2 uL    |
| SUPERase•In (20 U uL<sup>-1</sup>)       | 1 uL    |
| H<sub>2</sub>O                           | to 50 uL|

3) Add 5 uL of TURBO DNase inactivation reagent, mix, and incubate samples for 5 minutes at room temperature.
4) Centrifuge samples at 16,000 x*g* for 2 minutes and recover the supernatant

#### Preparing randomly fragmented samples for mRNA-Seq

To generate a control mRNA library, we can randomly fragment molecules and use 5'-phosphate selection to carry through mRNA which should be representative of the transcriptome. However, given that random fragmentation leads to 5'-OH ends, we use a T4 PNK reaction to rephosphorylate ends of the fragments so that they can ligate to the 5P-Seq Linker.

1) Start by taking one-fifth of the RNA from the previous step and dilute to 25 uL. To this sample, add 25 uL of [2x RNA fragmentation buffer](#2x-rna-fragmentation-buffer). 

Note: While the original protocol suggests using a fragmentation buffer consisting of tris acetate, magnesium acetate, and potassium acetate, the buffer here has been used previously in mRNA-seq sample prep in the lab profiling protocol and appears to work equally well.

2) Incubate the sample at 80 <sup>o</sup>C for five minutes, then place on ice.

3) Purify the sample using 2x volumes of AmpPure XP beads.


#### Single-stranded RNA ligation

#### Depletion of rRNA molecules

#### Fragmentation of mRNA

#### Reverse trancription

#### Second-strand synthesis by PCR

#### Sample enrichment by streptavidin selection

#### A-tailing DNA fragments

#### Common adapter ligation

#### Common adapter ligation

#### Library PCR amplification

#### Library size selection

#### Bioinformatics analysis

#### Citations

<sup>1</sup> [Fisher *et al. Genome Biol* 2011 **12**:12:R1](https://www.ncbi.nlm.nih.gov/pubmed/21205303)

#### 2X RNA Fragmentation Buffer
* 0.15 mL of 100 mM Na<sub>2</sub>CO<sub>3</sub>
* 1.10 mL of 100 mM NaHCO<sub>3</sub>
* 2 mM EDTA
* pH the solution to 9.2

#### Oligo-(dT)<sub>25</sub> Dynabeads Binding Buffer

* 20 mM Tris-Hcl (pH 7.5)
* 1 M LiCl
* 2 mM EDTA

#### Oligo-(dT)<sub>25</sub> Dynabeads Wash Buffer

* 10 mM Tris-Hcl (pH 7.5)
* 150 mM LiCl
* 1 mM EDTA

#### Streptavidin M-280 Beads Bind and Wash Buffer

* 5 mM Tris-HCl (pH 7.5)
* 0.5 mM EDTA
* 1 M NaCl
