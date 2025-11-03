## Comparing two Plant-CARE outputs

PlantCARE is a database of plant cis-acting regulatory elements and a tool for finding them in promoter sequences.

https://bioinformatics.psb.ugent.be/webtools/plantcare/html/

If we have two different variants of the promoter sequence for the same gene, it can be difficult to identify any differences in the lists of predicted regulatory elements in each variant.
This notebook contains Python code that compares two lists of regulatory elements. An alignment of the two promoter sequences must be provided as input, along with the output table files that should be renamed as sequences names in alignment (see example files).
The results of the comparison can be visualized using a special function in the code.


![image](<Differential Elements 60-160.svg>)


