# COI DNA Barcoding and Sequence Similarity Analysis

## Overview

This project explores DNA barcoding concepts using mitochondrial COI (Cytochrome Oxidase I) sequences retrieved from NCBI.

The analysis focuses on comparing DNA sequences across species and evaluating genetic similarity through computational methods using Python and Biopython.

## Background

DNA barcoding is a molecular identification method that uses short genetic markers to distinguish species.

In animals, the mitochondrial COI gene is one of the most widely used markers for species identification, biodiversity studies, and evolutionary research.

## Objectives

* Retrieve biological sequences from NCBI.
* Compare DNA sequences across species.
* Calculate pairwise sequence similarity.
* Visualize genetic relationships.
* Explore bioinformatics workflows using Python.

## Technologies Used

* Python
* Biopython
* Pandas
* NumPy
* Matplotlib
* SciPy
* NCBI Entrez

## Methodology

### 1. Sequence Retrieval

COI sequences were obtained from the NCBI database using accession numbers and the Entrez module from Biopython.

### 2. Pairwise Similarity Analysis

DNA sequences were compared nucleotide by nucleotide to calculate the percentage of matching positions between species.

### 3. Similarity Matrix

The similarity values were organized into a matrix using Pandas for comparative analysis.

### 4. Data Visualization

A heatmap was generated to visualize sequence similarity patterns among species.

### 5. Hierarchical Clustering

Sequence similarity values were converted into genetic distances and used to perform hierarchical clustering.

The resulting dendrogram provides a simplified visualization of relationships among the analyzed species.

## Example Outputs

### Similarity Matrix

| Species   | Species A | Species B | Species C |
| --------- | --------- | --------- | --------- |
| Species A | 100       | ...       | ...       |
| Species B | ...       | 100       | ...       |
| Species C | ...       | ...       | 100       |

### Visualizations

* Similarity Heatmap
* Hierarchical Clustering Dendrogram

## Learning Outcomes

Through this project I learned how to:

* Retrieve biological sequence data from NCBI.
* Work with mitochondrial DNA sequences.
* Apply DNA barcoding concepts.
* Calculate sequence similarity.
* Visualize biological relationships using clustering techniques.
* Combine bioinformatics and data science tools in Python.

## Future Improvements

* Analyze additional species.
* Automate sequence retrieval using species names.
* Incorporate larger COI datasets.
* Build phylogenetic trees using specialized bioinformatics methods.

## Author

**Valeria Solís**

Biologist | Data Analyst | Aspiring Bioinformatician 🧬
