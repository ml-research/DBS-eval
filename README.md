# DBS-eval 
This repository contains a corpus of PYRAMID annotations from three to four manual summaries of ten topics carried out by three annotators from the field of computational linguistics and linguistics. Each topic contains four to 16 documents per cluster. The annotations are based on the manual summaries created for the DBS corpus published by Benikova et al. (2016) (https://github.com/AIPHES/DBS).

### The Corpus
The manual summaries from the pyramids in DBS-eval as well as source documents and several other automatic summaries can be found in the DBS corpus in https://github.com/AIPHES/DBS.
Included in the `Pyramids` folder are pyramids (.pyr files) for ten topics by three annotators.
Included in the `Automatic_summaries` folder are the automatic summaries, which were evaluated against these PYRAMID files.
Included in the `Pans` folder are the .pan files from each annotator for each automatic summary, which was evaluated against the pyramids.
The filenames contain the topic ID (1-10), the topic name and except for .pyr files the name of the summary system (lex, lsa, mz, text). The .pyr and .pan files also contain the ID of the annotator (a1, a2, a3).


Contact person: Christopher Tauchmann, tauchmann@cs.tu-darmstadt.de

https://ml-research.github.io/


Don't hesitate to send an e-mail or report an issue, if something is broken (and it shouldn't be) or if you have further questions.


# License

* The PYRAMID annotations (.pyr and .pan files) and the automatic summaries are licensed under the [Creative Commons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. See LICENSE.txt for detailed information.
* The original content from DBS keeps its [original license](https://github.com/AIPHES/DBS/blob/master/LICENSE.txt).
