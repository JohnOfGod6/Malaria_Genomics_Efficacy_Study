#  Malaria Genomics and Therapeutic Efficacy Study

This project investigates malaria treatment efficacy using Deep Targeted Amplicon Sequencing (AmpSeq), genetic diversity analysis, and infection classification with R and DADA2.

##  Folder Structure

- `report/`: Final RMarkdown (`.Rmd`) and rendered PDF report
- `data/`: Mutation data for cpmp gene (MalariaGEN)
- `scripts/`: Bioinformatics pipelines and analysis code

##  Project Objectives

1. **Design polymorphic marker panels** from MalariaGEN data.
2. **Visualize mutation frequency and heterozygosity** to identify a 300-nucleotide marker.
3. **Align and call haplotypes** using patient samples at Day 0 and Day X.
4. **Classify infections** as recrudescence or new using 2/3 and 3/3 rules.
5. **Estimate treatment efficacy** and provide policy recommendations.

## Tools & Technologies

- **R & RMarkdown**
- **IGV Browser** for visualizing BAM alignments
- **DADA2** package for haplotype inference
- Data from: [https://www.malariagen.net](https://www.malariagen.net)

## 📈 Key Outcomes

- Identified polymorphic regions in `cpmp` gene (~180025–180325 bp)
- Determined MOI = 3 for sample
- Estimated treatment efficacy:
  - 2/3 rule: **20%**
  - 3/3 rule: **45%**

## Recommendations

- Conduct further regional surveillance
- Investigate drug resistance markers
- Strengthen infection classification pipelines

 
