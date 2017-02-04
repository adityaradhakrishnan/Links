### 5P-Seq Protocol
Adapted from [Pelechano *et al. Nat Protoc.* 2016 **11**:359-76](https://www.ncbi.nlm.nih.gov/pubmed/?term=genome-wide+quantification+of+5'-phosphorylated)<br />
By Aditya Radhakrishnan (Current Version: February 4th, 2017)

This protocol is used to generate 5P-Seq sequencing libraries by enriching for mRNA species containing a 5' Phosphate group, which is a sign of 5' exonucleolytic cleavage by Xrn1. This protocol can also be used to quickly generate mRNA-Seq libraries without using gels, by using purely a magnetic (SPRI bead) based purification.<sup>1</sup>

**Table of Contents**

1. [Preparing total RNA from yeast](#preparing-total-rna-from-yeast)
2. [Preparing randomly fragmented samples for mRNA-Seq](#preparing-randomly-fragmented-samples-for-mrna-seq)
3. [Citations](#citations)

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

Given that random fragmentation leads to 5'-OH ends, we use a T4 PNK reaction to rephosphorylate ends of the fragments so that they can ligate to the 5P-Seq Linker.

#### Citations

<sup>1</sup> [Fisher *et al. Genome Biol* 2011 **12**:12:R1](https://www.ncbi.nlm.nih.gov/pubmed/21205303)

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
