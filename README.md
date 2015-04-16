# fastalang
This is the gedit langauge definition xml file for FASTA sequence format. This is modified (almost completely remade) from another FASTA definition file by Thomas Krahn (2010).

### Modifications include
1) Using standard mapping definitions rather than defining colors used by alignment viewers

2) Removing colors for individual bases to permit using both protein and nucleotide sequences indifferently

3) Defining colors for protein stops, gaps, and irregular characters

4) Use with multiple different FASTA extensions, .fa, .fasta, .faa

5) X is defined as the only univerally unwanted letter, as N can be asparagine in protein sequences

In the future one could implement flagging letters that are neither amino acids or ambiguous bases. Non-amino acid letters are BZJOUX, sort of like the French word for jewel. BZJ are used to double up for certain pairs while OU are non-canonical amino acids pyrrolysine selenocysteine. This leaves only X, so the utility is questionable. For nucleotides, the letters are EFIJLOPQYX, of which EFIJLPQY are amino acids, leaving O and X.
