# Sections

Framing: I'm using computational and theoretical approaches to interrogate the problem of how particle shape leads to different emergent behavior in actively driven, colloidal-scale systems.

0. [x] Acknowledgements (1 page)
0. [ ] Abstract (1 page)
1. [ ] Motivation / Introduction (Just a few pages)
2. [ ] Background (23 pages) - theoretical background, could think about as a review article of the field
3. [ ] Model systems (11 pages)
4. [ ] Methods used (31 pages)
5. [ ] Individual project papers
6. [ ] Appendix: Peer mentor paper? Can I include this?


# Outlining various sections.
Background
1. Theories for describing active phase separation: MIPS, balancing of time scales, Redner
2. Theories looking at thermodynamics in active systems (Brady)
3. What "active shapes" are in biology / synthetically developed
4. Development of percolation theories (site/bond/continuum; random/explosive/other; analogies to phase transitions)


Projects:
1. Active matter- one-particle type systems
2. Binary active matter-- how particles interact to enable novel states
3. Percolation analogies and active systems
4. Peer mentor program

I think I want to have all the bibliographies at the end, though.

References:
* [How to have separate bibliographies for each chapter](https://en.wikibooks.org/wiki/LaTeX/Bibliographies_with_biblatex_and_biber#Bibliographies_per_Section_or_Chapter)-- but tbh I might just want a big one instead

Separate bibliographies for each chapter:
```
\usepackage[backend=biber,defernumbers=true,refsection=section]{biblatex}
\addbibresource{biblatex-examples.bib}
\begin{document}
\section{Aster}
\cite{ctan,sigfridsson} and some text
\printbibliography[heading=subbibliography]
```

Adding multiple `.bib` files, as I am likely to do.
```
\usepackage{biblatex}
\addbibresource{lauraPhd2016.bib}
\addbibresource{lauraPhd2016_2.bib}
```
