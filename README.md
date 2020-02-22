# PythonTeaching (biology example problems)


## dilution_problem.ipynb
Problem to calculate dilutions.
Solutions are given in two version: using basic python and using numpy

### Skills:
Mathematical operators
Defining a variable
Lists in python
For loops
Printing to the screen, and formatted printing
Displaying graphics using matplotlib


## DNA_to_aa.ipynb
This problem takes a DNA sequence and transcribes it into an amino acid sequence.
Solutions are given in two version: using basic python and using python list comprehension

### Skills:
Lists in python
Definging a variable
For loops
If statements
String manipulation
Dictionaries in python
Printing to the screen


# Further Ideas from SBES colleagues

1. Calculating the length of genes/proteins from sequence data

2. Pattern matching in big data (e.g.  one data set is gene id and gene coordinates, and the second is gene id and description, and you create a third dataframe combining both).

3. Designing plate layout for qPCR analysis (i.e. 96 well plate, each plate must contain x y z) but be randomised. Then once the plate is run, a script to deconvolute the results.

4. Epidemic model (e.g. coronavirus, measles pre and post vaccination)

5. Motif detection on DNA. In a given DNA sequence, how often does a particular 2 bp, 5 bp, 10 bp motif occur? To add some complexity: A lot of motifs are also degenerated. For example, a transcription factor binding site can be CCWWWWWWGG, where W can be either A or T. It can be surprising that the motifs alone, because they are often relatively short, occur quite frequently on DNA just by chance. For example, the sequence TATA, an element of the promoter of many eukaryotic genes, occurs by chance every 256 bp if the four nucleotides occur at equal frequency. It thus has limited predictive value for where actual promoters are located.

6. Population growth models and plotting the results

7. Pattern formation using cellular automata? Relate it to morphogens etc. A good book that gives an example of the latter in Python https://www.apress.com/gp/book/9781484245224

8. Predator-prey models



# Code not intended to be a teaching example

## molecular_weight.ipynb

This code calculate the molecular weight of a molecule from its formula.
It involves regular expressions and is not intended for stage 1 teaching
