# ExteriorIdeals
A Macaulay2 package for working with ideals over an exterior algebra.

Introduction
===================
Let K be a field, V a K-vector space with basis {e_1, ...,e_n}, and E the exterior algebra of V. We introduce a Macaulay2 package that allows one to deal with classes of monomial ideals in E.

- More precisely, we implement some algorithms in order to easily compute stable, strongly stable and lexsegment ideals in E.
- Moreover, an algorithm to check whether an (n+1)-tuple (1, h_1, ..., h_n) (h_1 <= n= dim_K V) of nonnegative integers is the Hilbert function of a graded K-algebra of the form E/I, with I graded ideal of E, is given.
- In particular, if H_(E/I) is the Hilbert function of a graded K-algebra E/I, the package is able to construct the unique lexsegment ideal I^lex such that H_(E/I) = H_(E/I^lex).
