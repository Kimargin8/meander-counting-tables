# Meander counts, first bridges and growth bounds

Iaroslav Argunov · 24 November 2026

| Work | Record | Files |
| --- | --- | --- |
| First-bridge parity and open meander numbers modulo four | [Zenodo, v1.0.0](https://doi.org/10.5281/zenodo.24516878) | [Paper](first-bridge-parity.pdf) · [Source, data and verification programs](first-bridge-parity.zip) · [A259974 positions 421–506](A259974-additions-421-506.txt) |
| Parity contraction and finite-window bounds for meandric words | [Zenodo, v1.1.0](https://doi.org/10.5281/zenodo.24516866) | [Paper](parity-window-bounds.pdf) · [Source and integer certificates](parity-window-bounds.zip) |
| Endpoint intervals and the prediction of open meander numbers | [Zenodo, v1.0.0](https://doi.org/10.5281/zenodo.24516884) | [Paper](open-meander-endpoint-intervals.pdf) · [Source and exact interval checks](open-meander-endpoint-intervals.zip) |
| The number of open meanders with 64 crossings | [Zenodo dataset, v1.0.0](https://doi.org/10.5281/zenodo.24516880) | [Numerical result](open-meanders-64.json) · [Weighted contributions and reconstruction](open-meanders-64.zip) |

The first-bridge paper proves a parity law for the number of configurations with the first bridge at a prescribed position. The data extend the 420-entry first-bridge table by 86 positions at 41–44 crossings. The supplement identifies 16 of those entries that also follow from existing formulas and tables. The independent residue calculation covers every even size through 98 crossings. [Earlier first-bridge table](https://oeis.org/A259974)

The finite-window paper continues the direct-window study. At width 16 the certified upper bound for the growth constant of connected plane meanders is 12.643867, rounded upward. The verification covers 620,537,812 integer inequalities. The first paper and its computational supplement retain their original version-specific identifier. [Direct-window study, v1.0.0](https://doi.org/10.5281/zenodo.24457226)

The endpoint paper records the interval for 64 crossings calculated from earlier terms. The subsequent exact value is **411162873752534667276292731379**. The dataset reconstructs this integer from measured upper-connectivity contributions, checks coverage and divisibility, and compares with the interval and the residue modulo four. The two assemblies share the underlying upper-connectivity computation. The paper also gives five updated intervals through 74 crossings.

The same dataset includes 16 marked-ear contributions and 64 squared-degree contributions at the preceding even size. They give **37235308802393747632970627778** at 62 crossings by division of their respective sums by 64 and 62. The previously published 60-crossing value **3383262281572596355695881934** is due to Vladimir Osipov. [Osipov's preprint, p. 13](https://doi.org/10.5281/zenodo.22773575)

The verification programs are distributed under MIT. The original papers and independent authored materials are distributed under CC BY 4.0. The archived OEIS inputs and the tables adapted from them, including the extension of A259974, carry CC BY-SA 4.0 and the source attributions listed in each package. [OEIS terms](https://oeis.org/wiki/The_OEIS_End-User_License_Agreement) · [File checksums](SHA256SUMS-2026-11-24.txt)
