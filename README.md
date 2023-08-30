# Standalone Cell Population calculation (compatible with python 3)

The -sif flag should provide a sif file
The -m flag should provide a mutation ccf file from the clustering result
The -c flag should provide a cluster ccf file from the clustering result
The --tree number should provide the most likely tree number from PhylogicNDT output 

python ./PhylogicNDT.py CellPopulation -i Indiv_ID -sif Patient.sif  -m mutation_ccf_file -c cluster_ccf_file --tree_number correct_tree_number
