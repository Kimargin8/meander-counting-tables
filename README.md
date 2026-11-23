# Meander counting tables and proofs

**Iaroslav Argunov · Version 1.0.0 · 23 November 2026**

[Complete source, checks and data](meander-counting-tables-v1.0.0.zip) · [File checksums](SHA256SUMS) · [Licensing and sources](NOTICE.md)

## Papers and reproduction packages

| Paper | Verification material | Result |
| --- | --- | --- |
| [An exact census of semi-meander transfer states](layer-census.pdf) · [DOI](https://doi.org/10.5281/zenodo.24457230) | [Source, programs and data](layers.zip) | Exact boundary-state counts and two complete coefficient rows at orders 41 and 42. |
| [Meandric growth from local connectivity at a cut](window-bounds.pdf) · [DOI](https://doi.org/10.5281/zenodo.24457226) | [Source, programs and data](slices.zip) | Finite-window growth certificates and exact one-sided and two-sided acyclic slice counts through 43 and 44 crossings. |
| [Short-interval tests in open meanders](open-profiles.pdf) · [DOI](https://doi.org/10.5281/zenodo.24457227) | [Source, programs and data](profiles.zip) | Extremal placements of three-site tests and the integer lattice of short-arch indicators. |
| [Meandric systems without interval components](intervals.pdf) · [DOI](https://doi.org/10.5281/zenodo.24457228) | [Source, programs and data](intervals.zip) | Enumeration of systems without cluster cycles on a line, with every term through order 38. |

[Six-digon enumeration](six-digons.zip) contains two exact constructions for closed meanders with six digons. [All ten tables and their provenance](tables.zip) gives each table’s indices, counting conventions and prior sources.

## Enumeration tables

Files use two decimal integer columns, index and value. Physical sites are labelled. Ordinary connected open paths, acyclic systems allowing several paths, and semi-meanders with one bank fixed have distinct counting conventions.

| Table | Added terms or range supplied |
| --- | --- |
| [b046726.txt](b046726.txt) | Semi-meanders by component count, at indices 821–903 (orders 41 and 42). |
| [b046721.txt](b046721.txt) | Exactly 2 components, orders 41 and 42. |
| [b046722.txt](b046722.txt) | Exactly 3 components, orders 41 and 42. |
| [b046723.txt](b046723.txt) | Exactly 4 components, orders 41 and 42. |
| [b046724.txt](b046724.txt) | Exactly 5 components, orders 41 and 42. |
| [b046725.txt](b046725.txt) | Exactly 6 components, orders 41 and 42. |
| [b060089.txt](b060089.txt) | One-sided acyclic slices at 41–43 crossings. |
| [b060111.txt](b060111.txt) | Two-sided acyclic slices at 41–44 crossings. |
| [b301940.txt](b301940.txt) | Closed meanders with six digons, orders 36–60. |
| [meandric-systems-without-cluster-cycles.txt](meandric-systems-without-cluster-cycles.txt) | Systems without interval components, complete range 0–38. |

The five fixed-component columns repeat entries within the two new triangle rows. The four underlying existing tables have 115 additional positions altogether. The table headed by the object name has a provisional descriptive filename.

For a complete replay, extract the source archive, open the relevant directory and follow its README. In particular, the slices supplement distinguishes exact counts of acyclic systems from bounds for the growth rate of closed connected meanders. The profile paper states the all-order result for three windows and gives separate finite and eventual results for four windows.
