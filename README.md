# miRMOD
miRNA modification prediction tool
http://bioinfo.icgeb.res.in/miRMOD/

miRMOD is the cross-platform standalone GUI/CLI tool to identify and analyze non templated nucleotide additions and trimming
at both the termini of the miRNA sequences in NGS data. It provides useful statistics like kinds of miRNA modifications and
its frequencies, differential miRNA-modified miRNA abundance and frequencies of the modified bases found in each of the
modifications. miRMOD also analyzes differences in miRNA target interactions. This kind of detailed analysis helps understand
global as well as micro level miRNA modifications in NGS datasets. miRMOD provides user-friendly graphical representations
to visualize miRNA modifications and target predictions in different formats to facilitate HT data analysis even on your laptop .
miRMOD is also available in command line version to reach broad range of users.

Applications :
  1. Predicts modified miRNAs (5' and/or 3' non-templated nucleotide additions and trimming) .
  2. Percentage of occurence of each modified sequence in the dataset.
  3. Any miRNA to miRNA conversion as a result of trimming.
  4. miRNA score table to present its relative tendency to get modified.
  5. Determination of target binding alteration due to modification using RNAhybrid.
  6. Determine novel targets for modified miRNAs.

  Required input files:
  1. Mature miRNA(s) sequences (fasta format) for which modifcation(s) has to be identified.
  2. Small RNA sequencing reads processed using "Prepare_input" program (packaged with miRMOD).
  3. Bowtie alignment file generated using file prepared in 2. and reference genome/pre-miRNAs.
  4. Target sequence file (fasta format,optional).

  For more information about miRMOD please read manual.
