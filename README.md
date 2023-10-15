# Summary

1st version of the journalistic portion of Porttinari (which stands for “PORTuguese Treebank”), which shall be a large multigenre treebank for Portuguese ([Pardo et al., 2021](https://sol.sbc.org.br/index.php/stil/article/view/17778/17612)), following the "Universal Dependencies" international grammar framework ([de Marneffe et al., 2021](https://aclanthology.org/2021.cl-2.11/)).

# Introduction

1st version of the journalistic portion of Porttinari (which stands for “PORTuguese Treebank”), which shall be a large multigenre treebank for Portuguese ([Pardo et al., 2021](https://sol.sbc.org.br/index.php/stil/article/view/17778/17612)), following the "Universal Dependencies" international grammar framework ([de Marneffe et al., 2021](https://aclanthology.org/2021.cl-2.11/)). As reported by [Duran et al. (2023)](https://sol.sbc.org.br/index.php/stil/article/view/25443/25264), Porttinari is currently composed by three subcorpora with different characteristics and purposes:

* Porttinari-base, a corpus that is manually revised in detail to serve as gold standard (divided into training, development and test folds);

* Porttinari-check, a small corpus structurally similar to Porttinari-base to serve as testbed for additional and diversified evaluations and to illustrate the contrast between manual and automatic annotations;

* Porttinari-automatic, a very large corpus that was automatically annotated by a state of the art parser trained on Porttinari-base.

The texts in the treebank are from Folha de São Paulo newspaper, which are publicly available at Kaggle website. Overall, the journalistc portion of Porttinari includes 167,048 news articles, with 3,964,321 sentences and 94,646,080 tokens, which are distributed in the subcorpora as follows.

![subcorpora](https://github.com/UniversalDependencies/UD_Portuguese-Porttinari/assets/41649292/0eb597a6-4b41-49e6-b360-3afed709ad13)

UD_Portuguese-Porttinari is the UD release of Porttinari-base.

# Acknowledgments

This work was carried out at the Center for Artificial Intelligence of the University of São Paulo (C4AI - http://c4ai.inova.usp.br/), with support by the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and by the IBM Corporation. The project was also supported by the Ministry of Science, Technology, and Innovation, with resources of Law N. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published as Residence in TIC 13, DOU 01245.010222/2022-44.

## References

* Duran, M.S.; Lopes, L.; Nunes, M.G.V.; Pardo, T.A.S. (2023). The Dawn of the Porttinari Multigenre Treebank: Introducing its Journalistic Portion. In the Proceedings of the 14th Symposium in Information and Human Language Technology (STIL), pp. 115-124. September, 25-29. [pdf](https://sol.sbc.org.br/index.php/stil/article/view/25443/25264)

* Pardo, T.A.S.; Duran, M.S.; Lopes, L.; Di Felippo, A.; Roman, N.T.; Nunes, M.G.V. (2021). Porttinari - a large multi-genre treebank for brazilian portuguese. In the Proceedings of the XIII Symposium in Information and Human Language (STIL), pp. 1-10. November, 29 to December, 3. [pdf](https://sol.sbc.org.br/index.php/stil/article/view/17778/17612)

# Changelog

* 2023-11-15 v2.13
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.13
License: CC BY-SA 4.0
Includes text: yes
Genre: news
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Duran, Magali Sanches; Lopes, Lucelene; Nunes, Maria das Graças Volpe; Pardo, Thiago Alexandre Salgueiro
Contributing: elsewhere
Contact: elvis.desouza99@gmail.com
===============================================================================
</pre>
