https://www.nature.com/articles/s41586-021-03819-2


Highly accurate protein structure prediction with AlphaFold

Proteins are essential to life and understanding their structure can help us understand the functions they perform. The alpha is a deep novel neural network architecture to predict the 3D proetin structure computationally. It uses physical, evolutionary and geomteric constraints of protein strcutures that can predict a protein structure highly accurately

The alpha fold directly predicts the 3D coordinates of all heavy atoms for a given protein using the primary amino acid sequence and aligned sequences of homologues as inputs
 The trunk called the Evoform in which the repeated neural network produce an (No of sequences * No of residues) array that presesnts MSA and (No of residues * No of residue ) array that represents residue pairs.

The network comrpises two stages: 
First stage: The trunk called the Evoform in which the repeated neural network produce an (No of sequences * No of residues) array that presesnts MSA and (No of residues * No of residue ) array that represents residue pairs. The operation operates on a concrete 3D backbone structure, prioritizes back bone such that side chains are highly and constrained and peptides are not. Next they generate inavriant point attention (a geometry of 3D positions) and assign key value pairing with 3D points that are produced in local frame of each residue such that the final value is invariant to global rotations and translations.
Predictions of side-chain χ angles as well as the final, per-residue accuracy of the structure (pLDDT) are computed with small per-residue networks on the final activations at the end of the network.
The resulting Nframes × Natoms distances are penalized with a clamped L1 loss. This creates a strong bias for atoms to be correct relative to the local frame of each residue and hence correct with respect to its side-chain interactions, as well as providing the main source of chirality for AlphaFold
They use supervised learning technique
to train to enhance accuracy

To test the network, they trained a seperate structure module and ran the 48 evoformer blocks in the network which provided trajectory of 192 intermediate strcutures. The resulting trajectories are smooth and indicating alphafold makes constant incremental improvements to the structure until it no longer can improve. Alphafold functions far more efficiently compared to other algorithms from a limited data in the PDB and also is able to cope with the complexity and variety of structural data.

PS: I might be wrong with my understanding of how the evoform is working but I'm still trying to understand the concept in depth.