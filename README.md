# The List Spectrum of Product Classes

## Abstract

How many predictions per example are necessary to learn several classification tasks simultaneously? For a class $\mathcal H$, let $K(\mathcal H)$ be the least list size that makes realizable PAC learning possible. Hanneke, Moran, and Waknine asked for $K(\mathcal H_1\otimes\mathcal H_2)$, leaving a gap between $(K(\mathcal H_1)-1)(K(\mathcal H_2)-1)$ and $K(\mathcal H_1)K(\mathcal H_2)$.

We close the gap and determine a stronger risk spectrum. For nonempty classes with finite $k_j=K(\mathcal H_j)$, set $M=\prod_j k_j$. If a learner may output $L$ tuple labels, then its optimal worst-case expected realizable error converges to

$$\left(1-\frac{L}{M}\right)_+.$$

Consequently, $K(\bigotimes_j\mathcal H_j)=\prod_jK(\mathcal H_j)$. The result is quantitative at every sample size. Its lower bound is a strong direct-product inequality in terms of the factor learning curves.

The proof turns infinite list-DS pseudo-cubes into explicit finite Bayes experiments. On an unseen coordinate, the posterior contains $k_j$ competing labels. A difference of adjacent Bayes list risks lower bounds the $k_j$-th posterior mass. Under independent products, these masses multiply, while a list of size $L$ omits at least $M-L$ cells of the top-posterior grid. This posterior order-statistic argument also shows that optimal weak multiclass accuracies multiply. We complement the list theorem with an exact fixed-marginal tensorization under standard minimax regularity and dimension-dependent rates for uniform and agnostic product learning.

## Contributions

- We determine the complete asymptotic list-risk spectrum of a finite Cartesian product and prove the finite-sample strong direct-product inequality.
- We resolve the minimal-list-size question exactly, including heterogeneous factors and infinite list numbers, and deduce multiplicativity of optimal weak PAC accuracy.
- We prove a fixed-marginal Bayes and minimax tensorization theorem for all-coordinate zero-one loss.
- We derive product-class rates from graph, DS, and Natarajan dimensions, while identifying the low-dimensional exceptions exposed by the latest agnostic separation.

## Keywords

list, spectrum, product, classes, many, predictions, example, necessary, learn

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
