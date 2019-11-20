# ParaFilter

A script to filter paralogs. 

Given a tree file and the corresponding sequence alignment, the script first discerns the nature of the paralogy relationships between the sequences. If monophyletics (i.e. In-Paralogs), it keeps the one/ones with the shortest branch length. If not monophyletic (Out-Paralogs), it discards all.
