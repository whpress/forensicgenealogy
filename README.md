# forensicgenealogy

This repository contains data and other files associated with the paper

### Likelihood Models for Forensic Genealogy

by William H. Press and John Hawkins

The paper is at [http://arxiv.org/abs/2010.02985](http://arxiv.org/abs/2010.02985) .  A copy of the PDF is also
in this repository.  The paper's abstract follows:

## Abstract

In the idealized Morgan model of crossover, we study the probability
distributions of shared DNA (identical by descent) between
individuals having a wide range of relationships (not just lineal
descendants), especially cases for which previous work produces
inaccurate results.Using Monte Carlo simulation, we show that a
particular, complicated functional form with just one continuous
fitted parameter accurately approximates the distributions in all
cases tried.Analysis of that functional form shows that it is
close to a normal distribution, not in shared fraction $f$, but in the
square-root of $f$.We describe a multivariate normal model in this
variable for use as a practical framework for several general tasks in
forensic genealogy that are currently done by less-accurate and less
well-founded methods.

## Files in this repository

- File {\em SupplementalTable1.tsv} (7KB) Values $k_1$, $k_2$, $\alpha$,
$D_{KS}$, $D_{KL}$, $D^\prime_{KL}$ for the fitted models of 96
relationships in the files {\em dependsdata_*_23.txt}.  Table 1 in
the main text gave a representative selection.

- File {\em SupplementalTable2.xlsx} (17 KB):  Coefficients of correlation
$r$ for 173 pairs of relationships drawn from {\em bigrun_data.out}, above.
Table 2 in the main text gave a representative selection.

- Files {\em dependsdata_*_23.txt} (each about 50 MB):
Centimorgans of common DNA for one million Monte Carlo simulations
of the relationships (and also descendants $\le 9$ times removed)
for lineal descendant, 1st cousin, 2nd cousin, 3rd cousin, double
1st cousin, nephew, half 1st cousin, half 2nd cousin, half third
cousin, and half nephew.

- File {\em bigrun_data.out} (470 MB): Centimorgans of common DNA for
one million Monte Carlo simulations among all pairs of descendants to
five generations of siblings and half-siblings.  Stored as zip file broken
into two pieces.  Can be reconstituted with 7-zip (e.g.).


