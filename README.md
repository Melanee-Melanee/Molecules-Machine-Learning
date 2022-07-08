# Molecules-Machine-Learning



This notebook is taken from:

https://www.kaggle.com/code/firuzjuraev/molecules-machine-learning/notebook

![molecule](https://user-images.githubusercontent.com/74653444/177920837-84a2b529-3c6e-4b51-88f4-223f36ed9608.png)


</br>

</br>


What is SMILES?

SMILES (Simplified Molecular Input Line Entry System)

This is the simplest way to reflect a molecule. The idea behind is to use simple line notations for chemical formulas that are based on some rules. Atoms of chemical elements are represented by chemical symbols in capital letter, hydrogen is usually ignored. Single bonds are not displayed; for double, triple and quadruple bonds we shall use '=', '#', '$' respectively. Atoms that are bonded must stand nearby. Ring structures are written by breaking each ring at an arbitrary point (although some choices will lead to a more legible SMILES than others) to make a 'straight non-ring' structure (as if it wasn't a ring) and adding numerical ring closure labels to show connectivity between non-adjacent atoms. Aromacity is commonly illustrated by writing the constituent B, C, N, O, P and S atoms in lower-case forms b, c, n, o, p and s, respectively. To represent side chains of atomic gpoups branches are used.

 Library for working with SMILES:
 
 rdkit - https://www.rdkit.org/
