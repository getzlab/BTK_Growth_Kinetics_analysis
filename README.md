# BTK_Growth_Kinetics_analysis

Standalone Cell Population calculation (compatible with python 3)



The -w flag should provide a measure of tumor burden, with one value per input sample maf in clustering. When ommited, stable tumor burden is assumed.
The -t flag should provide relative time for spacing the samples. When omitted, equal spacing is assumed.

python ./PhylogicNDT.py CellPopulation -i Indiv_ID -sif Patient.sif  -m mutation_ccf_file -c cluster_ccf_file --tree_number correct_tree_number
