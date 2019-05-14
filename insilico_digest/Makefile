
#name of the fasta file 
#the fasta file should have .fa extension
#give the name without extension
#for example if the input fasta is Test.fa the NAME variable shoudl be Test
NAME  := Test

#enzyme details of rare cutter here (SbFI)
ENZYME_1    := SbFI
CUT_1       := CCTGCAGG
NICKPOS_1   := 2


#Enzyme details of common cutter
ENZYME_2    := MseI
CUT_2       := TTAA
NICKPOS_2   := 1

#seek distance for clusters
#The distance to look from a rare cutter site until a common cutter site is found
WINLEN      := 500

include ./Pipeline.mk


