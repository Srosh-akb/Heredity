# Heredity
AI assessing the likelihood of a person having a particular genetic trait.

## Instructions
1. Download this repository to your device.
2. Open a terminal or command prompt.
3. Navigate to the directory where you downloaded the repository.
4. Run the file with Python 3 using the following command, changing which family in the csv file
```bash
python heredity.py family0.csv
```
5. Watch the AI create probability districutions for gene and trait presence

## Background
Mutated versions of the GJB2 gene are one of the leading causes of hearing impairment in newborns. Every child inherits one copy of the GJB2 gene from each of their parents. 
Depending on the number of genes present in a parent the child has a varying likelihood of inheriting both genes, causing a hearing impairment.

This programme sets up this problem as a Bayesian Network where variables represent either the number of genes present (0, 1, 2) or whether the trait is present (yes, no).

This AI programme shows the importance and applicability of AI in medicinal situations, providing doctors with more information to make informed decisions.
