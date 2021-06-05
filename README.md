# Lemmatizing medieval French with Pie & RNNTagger

This repository contains a couple of notebooks created to easily generate a langague model for Pie and RNNTagger for tagging and lemmatizing medieval French with no prior local installation and fastened training. Any training dataset can be used if the language-specific parameters are properly configured for each tool's parameters file. Also, it includes the possibility of tagging files from our Drive with the generated models.


# Short description of the task

We've trained a model for medieval French with RNNTagger and Pie in order to tag a number of texts with the <a href="http://bfm.ens-lyon.fr/IMG/pdf/Cattex2009_manuel_2.0.pdf">Cattex09 </a> morphosyntactic labels. Two different corpora are used for training : 
- BFMGOLDLEM corpus, fully annotated in parts of speech (UD and Cattex POS tags) including a number of morphological labels. The lemmas in this corpus were previously standarized in a <a href="https://github.com/CristinaGHolgado/Lemmatisation_AncienFran-ais">previous work</a>. This corpus consists of 431,144 tokens distributed in 20 texts (36.1MB).
- BFMGOLD corpus, where only a small number of texts include all lemmas. It contains 1,187,061 tokens distributed in 42 texts (75.4MB).

A complete description can be found <a href="https://gitlab.huma-num.fr/lemmatisation-fro/bfm-lem/-/blob/master/doc/description_nlppie_rnntagger.pdf"> here </a> [French]
