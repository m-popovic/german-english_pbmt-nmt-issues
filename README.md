The files contain parts of the wmt16 news test data from the German-to-English and English-to-German translation tasks.

The files *issues.tsv contain tab-separated:
- original source language (not translated by humnans)
- segment number in the original wmt16 test file
- source sentence
- NMT translation output (Sennrich, Haddow, and Birch. "Edinburgh Neural Machine Translation Systems for WMT16", Proceedings of the 1st Conference on Machine Translation (WMT 2016), Berlin, Germany, August 2016.)
- PBMT translation output (Williams, Sennrich, Nadejde, Huck, Haddow, and Bojar. "Edinburgh’s Statistical Machine Translation Systems for WMT16", Proceedings of the 1st Conference on Machine Translation (WMT 2016), Berlin, Germany, August 2016.)
- reference translation
- language related issues for the NMT translation
- langugae related issues for the PBMT translation


The files *ranks.tsv contain tab-separated:
- segment number in the original wmt16 test file
- relative rank of the NMT translation
- relative rank of the PBMT translation

If you use any part of this corpus, please cite the following paper:

Maja Popović, "Comparing language related issues for NMT and PBMT between German and English", The 20th Annual Conference of the European Association for Machine Translation (EAMT-17), Prague, Czech Republic, May 2017 
