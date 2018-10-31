# protein-sequence-kernel

# Comparing Protein Sequences using String Kernels 

By: Munir Nur and Zaid Al Rakabi

Program implemented in C++ to test how similar protein sequences are using the BL62 matrix and kernel method for comparing sequences developed by Smale et al. For further information on how the algorithm works and how we tested it read our paper: Comparing Protein Sequences using String Kernels. This is a work in progress.

	(note: may need to run on a *nix based computers for accurate distance floating-point computation)

To compile:
	type "g++ kernel.cpp" into the command line


To run:
	type "./a.out bl62.txt 0.01 sequences/(sequence 1 filename) sequences/(sequence 2 filename)" into the command line
	
	(0.01 is our tested beta-value, for our unweighted String Kernel)

