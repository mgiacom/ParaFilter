# ParaFilter
A script to filter paralogs. 

This script parses gene tree files built on each orthrogroups .
It first discerns the nature of the paralogy relationships between the sequences. If monophyletics (i.e. In-Paralogs), it keeps the one/ones with the shortest branch length. If not monophyletic (Out-Paralogs), it discards all the sequences. It then create new fasta files with these sequences removed.

