# BE-schemes
Compute the associated graded algebra and Schur functors to obtain an equivariant basis for Buchsbaum-Eisenbud varieties of complexes
---
This will compute the associated graded algebra in terms of Schur functors of a Buchsbaum-Eisenbud variety of complexes
in order to obtain an equivariant basis for the varieties. This equivariance can be used in the construction of 
equivariant neural networks compatable with current methods for constructing group rquivariant neural networks. The performance
of this new method (as a possible additional set of features) is untested, but it is hoped to improve accuracy and efficency. 
This may also prove useful in a geometric complexity theory context related to the [Honeycomb Model of GL(n)](https://github.com/The-Singularity-Research/Schur-Shor). See [Macaulay2](http://www2.macaulay2.com/Macaulay2/doc/Macaulay2-1.17/share/doc/Macaulay2/MonomialAlgebras/html/index.html), 
the [paper](https://arxiv.org/abs/1110.3653) and the [paper](https://arxiv.org/abs/1106.0774) for an explanation of how the structure sheaf for
representation schemes of surface algebras can be regarded as a semigroup ring with standard monomial theory and how they can be decomposed
into associated graded algebras by Schur functors. 

## Decomposition of Monomial Ideas
---
The decomposition of monomial ideas and standard monomial theory is explained in the following articles

1. [SEMI-INVARIANTS FOR GENTLE STRING ALGEBRAS]()
2. 
3. 

These can be implemented in Macaulay2 in order to decompose the structure sheaf of a representation scheme of surface algebra into standard monomials and corresponding Schur functors giving an equivariant basis for the associated graded alegbra. This equivariant basis can be used as additional feature in a group equivariant neural network where the symmetry group is the full general linear group $\mathbf{GL}(n)$. Since the methods are independent of the field of coefficients and the methods works and is defined over the integers $\mathbb{Z}$, this provides the ability to extend such neural network architectures to arbitrary coefficients rings/fields. This could be useful for studying $p$-adic AdS/CFT and string theory, quantum computing circuits that model the AdS/CFT correspondence, and other $p$-adic and ring theoretic sensitive phenomena. 
