# Exploring Gene Activation in Mouse Cells Using Chromatin Mapping

**By Liz Albertorio-Sáez, M.Sc. and Rebekah Picard, B.Sc.**

## Overview

In this hands-on activity, students will use real chromatin mapping data to compare gene activity in two types of mouse cells: **brain tissue** and **fibroblasts**. The focus is on a single, well-studied histone modification called **H3K4me3**, which marks the beginning of actively transcribed genes.

Students will use the **Integrative Genomics Viewer (IGV)**, a free genome browser tool, to visualize and interpret differences in gene regulation. By identifying where H3K4me3 peaks appear in each cell type, they will gain insight into how the same genome is read differently depending on cell function.

---

## What Is H3K4me3?

**H3K4me3** (histone H3 lysine 4 tri-methylation) is a **chemical tag** added to histone proteins after they are made. It is typically found at the **promoter regions** of active genes and helps the cell machinery recognize which genes to transcribe.

In genome browsers like IGV, H3K4me3 appears as **tall, narrow peaks** near the start of genes. These peaks indicate that a gene is **turned on** in that cell type.

---

## About the Cell Types

In this experiment, you will compare two samples:

- **Mouse Brain Cells**  
  These cells were isolated from whole mouse brain tissue and contain a mixture of neurons and glial cells. They represent genes commonly active in the brain.

- **NIH3T3 Fibroblasts**  
  NIH3T3 is a widely used mouse fibroblast cell line, originally derived from embryonic tissue. These cells are known for their fast growth and are often used in molecular biology.  
  Learn more here: [NIH3T3 Cell Line at ATCC](https://www.atcc.org/products/crl-1658)

Although both cell types share the same DNA, their **H3K4me3 patterns reveal differences in gene expression** based on their specific roles in the body.

---

## Getting Started with IGV

### Step-by-Step Setup

1. **Download IGV**  
   Visit [https://software.broadinstitute.org/software/igv](https://software.broadinstitute.org/software/igv) and install the version appropriate for your computer.
<img width="624" height="356" alt="Step 1" src="https://github.com/user-attachments/assets/cc2ea643-065e-4aae-9765-fe3a566121eb" />

2. **Launch IGV.**
   
   ![Untitled video](https://github.com/user-attachments/assets/a2cf6857-7d72-407b-b59b-d110eda4a3c0)

4. **Set the Genome to Mouse:**  
   Use the genome dropdown to select `Mouse (mm9)`. If mm9 is unavailable, `mm10` may be used, but ensure the data files match the version.

5. **Load Data Files:**  
   Drag and drop the `.bw` (BigWig) files for **H3K4me3 in brain** and **H3K4me3 in NIH3T3 fibroblasts** into the IGV browser.

6. **Organize the View:**
   - Use `Tracks → Fit Data to Window` for best viewing
   - Right-click the tracks and choose `Change Track Color` (suggested: green for H3K4me3)
   - Use the search bar to navigate to specific genes (see below)

---

## Genes to Explore: Brain vs Fibroblast Expression

Use the IGV search bar to investigate the following genes. Look for **H3K4me3 peaks near the promoter** (start) of each gene.

| Gene        | Function | Expected Pattern |
|-------------|----------|------------------|
| **Neurod6** | Brain-specific transcription factor | Strong peak in brain; absent in NIH3T3 |
| **Tubb3**   | Neuron-specific β3-tubulin protein | Present in brain; low or absent in NIH3T3 |
| **Rbfox3**  | Also known as NeuN; marker of mature neurons | Present in brain; absent in fibroblasts |
| **Map2**    | Microtubule-associated protein found in dendrites | Strong peak in brain; absent in fibroblasts |
| **Col1a1**  | Collagen gene expressed in connective tissue | Strong peak in NIH3T3; absent in brain |
| **Acta2**   | Smooth muscle actin gene; fibroblast marker | Moderate peak in NIH3T3; not in brain |
| **Gapdh**   | Housekeeping gene | Present in both samples |
| **Fos**     | Immediate early gene activated by stimuli | May appear in brain depending on activity state |

---

## Student Worksheet: Gene Expression in Mouse Cells

### Part 1: Setup and Observations

- What genome build are you using?  
- What color did you assign to the H3K4me3 tracks?  
- What does an H3K4me3 peak look like in IGV?

- Describe what H3K4me3 looks like at a gene that is **active**.  
- Describe what it looks like at a gene that is **inactive**.

---

### Part 2: Explore and Compare

Choose **three genes** from the list above. For each one, answer:

- Do you see a peak in the **brain** sample?  
- Do you see a peak in the **NIH3T3** sample?  
- What does this suggest about gene activity?  
- Does the observed pattern match what you know about the gene’s function?

---

### Part 3: Reflection

- What kinds of genes are turned on in brain cells?  
- What kinds of genes are turned on in fibroblasts?  
- Why do you think different genes are active in different cell types?  
- How do histone modifications like H3K4me3 help regulate these differences?  
- If you could compare another tissue, what would you choose and why?

---

## Key Vocabulary

| Term              | Definition |
|-------------------|------------|
| **H3K4me3**        | A chemical tag on histone H3 indicating active gene promoters |
| **Histone**        | Protein that DNA wraps around in chromatin |
| **Post-Translational Modification (PTM)** | A chemical change made to a protein after it is produced |
| **Promoter**       | DNA sequence at the start of a gene where transcription begins |
| **Gene Expression**| The process of turning on a gene to produce RNA or protein |
| **Fibroblast**     | A connective tissue cell that produces collagen and structural proteins |
| **Neuron**         | A brain cell that sends electrical and chemical signals |
| **IGV**            | A free genome browser used to view DNA and chromatin data |

---

