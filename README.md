# indonesian-NLP-resources
Data NLP for bahasa indonesia (last update 20 sep 2020)

# Sentences Dataset
1. [leipzig indonesian sentence collectoin](http://wortschatz.uni-leipzig.de/en/download) news articles, web articles, wikipedia data from 2008-2016
1. [wn-msa.sourceforge.net](https://sourceforge.net/p/wn-msa/tab/HEAD/tree/trunk/) Wordnet Bahasa
1. [Quran](http://tanzil.net/trans/id.indonesian) indonesian quran translation (id.muntakhab, id.jalalayn, id.indonesian)
1. [Kompas online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/kompas.zip).
   This corpus contains [Kompas online](http://www.kompas.com/) news articles from 2001-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [Tempo online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/tempo.zip).
   This corpus contains [Tempo online](https://www.tempo.co/) news articles from 2000-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [corpus-frog-storytelling](https://github.com/davidmoeljadi/corpus-frog-storytelling) spoken text story telling
1. [TED-Multilingual-Parallel-Corpus](https://raw.githubusercontent.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus/master/Monolingual_data/Indonesian.txt) Monolingual_data/Indonesian
1. [Opus](http://opus.nlpl.eu/) Opus NLPL
1. [Sealang](http://sealang.net/indonesia/) Sealang dataset

# Word reference (kemdikbud) [link](https://kbbi.kemdikbud.go.id/Beranda/Statistik)
1. Entri Dasar : 50.668 (45,02 %)
1. Kata Turunan : 26.835 (23,85 %)
1. Gabungan Kata : 31.492 (27,98 %)
1. Peribahasa : 2.054 (1,83 %)
1. Kiasan : 269 (0,24 %)
1. Ungkapan : 1.131 (1,00 %)
1. Varian : 89 (0,08 %)
1. Entri Total : 112.538 (100,00 %)
1. Makna Total : 131.533
1. Contoh Total : 30.010
1. Kategori Total : 234
1. Makna Per Entri : 1,169
1. Contoh Per Makna : 0,228

# Words dataset ([PUEBI word type](https://puebi.readthedocs.io/en/latest/kata/) )
1. word class => [word noun](https://github.com/kirralabs/Indonesian-Word-Tagged/blob/master/resources/word-noun.txt)(18647), [word verb](https://github.com/kirralabs/Indonesian-Word-Tagged/blob/master/resources/word-verb.txt)(39070) = 57717 words
1. word type => [rootword](https://github.com/kirralabs/Indonesian-Word-Tagged/blob/master/resources/word-root.txt)(41409), [derivative word](https://github.com/kirralabs/Indonesian-Word-Tagged/blob/master/resources/word-affix.txt)(24913), [compound words](), [Figure of speech](), [proverb](), [expression]() = 66322 words
1. Word root => [source#1.1](https://github.com/sastrawi/sastrawi/blob/master/data/kata-dasar.txt) : sastrawi 29932 words ; [source#1.2](https://github.com/sastrawi/sastrawi/blob/master/data/kata-dasar.original.txt) : sastrawi 30342 words ; [source#2](https://github.com/agusmakmun/SentiStrengthID/blob/master/id_dict/rootword.txt) : SentiStrengthID 27979 words ; [source#3](https://github.com/prasastoadi/serangkai/blob/master/serangkai/kamus/data/kamus-kata-dasar.csv) : serangkai 30342 words
1. [Word spaCy](https://github.com/explosion/spaCy/tree/master/spacy/lang/id) : id
1. [word](https://github.com/prasastoadi/serangkai/tree/master/serangkai/kamus/data) : serangkai
1. [Word name](https://github.com/dominictarr/random-name) : random-name
1. [Word Indo name](https://github.com/seuriously/genderprediction/blob/master/namatraining.txt) : genderprediction
1. [Word Wiktionary](https://id.wiktionary.org/wiki) : word id
1. word compound => 
   * [source#1](https://github.com/panggi/pujangga/blob/master/resource/tokenizer/compositewords.txt) : 71 words
   * [source#2](https://puebi.readthedocs.io/en/latest/kata/gabungan-kata/) : puebi
1. Word Acronims => 
   * [source#1](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/acronym.txt) : 4085 words ; 
   * [source#2](https://github.com/panggi/pujangga/blob/master/resource/netagger/contextualfeature/ptit.txt) : 70 words
1. Word Negative => 
   * [source#1.1](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/negatif_ta2.txt) : 3829 words ; [source#1.2](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/negative_keyword.txt) : 3523 words ; [source#1.3](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/negative_add.txt) : 154 words ; 
   * [source#2](https://github.com/masdevid/ID-OpinionWords/blob/master/negative.txt) : ID-OpinionWords 2402 words
   * [source#3](https://github.com/riochr17/Analisis-Sentimen-ID/blob/master/data/negatif.txt) : 3523 words
   * [source#4](https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection/blob/master/abusive.csv) : 126 words
1. Word Positive => 
   * [source#1.1](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/positif_ta2.txt) : 1678 words ; [source#1.2](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/positive_add.txt) : 40 words ; [source#1.3](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/positive_keyword.txt) : 1293 words ; 
   * [source#2](https://github.com/masdevid/ID-OpinionWords/blob/master/positive.txt) : 1182 words
   * [source#3](https://github.com/riochr17/Analisis-Sentimen-ID/blob/master/data/positif.txt) : 1293 words
1. Word Slang => 
   * [source#1](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/kbba.txt) : 1319 words ; 
   * [source#2](https://github.com/agusmakmun/SentiStrengthID/blob/master/id_dict/slangword.txt) : 286 words ; 
   * [source#3](https://github.com/panggi/pujangga/blob/master/resource/formalization/formalizationDict.txt) : 1147 words
   * [source#4](https://github.com/abhimantramb/elang/blob/master/word2vec/utils/swear-words.txt) : 62 words
   * [source#4](https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection/blob/master/new_kamusalay.csv) : 15167 words
1. Stopwords => 
   * [source#1](https://github.com/explosion/spaCy/blob/master/spacy/lang/id/stop_words.py) : spacy data ; 
   * [source#2](https://github.com/yasirutomo/python-sentianalysis-id/blob/master/data/feature_list/stopwordsID.txt) : 759 words ; 
   * [source#3](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/stopword.txt) : 399 words ;
   * [source#4](https://github.com/abhimantramb/elang/tree/master/word2vec/utils/stopwords-list) : 759+329+124+126 words
1. Emoticon => 
   * [source#1](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/emoticon.txt) : 252 ; 
   * [source#2](https://github.com/jolicode/emoji-search/blob/master/synonyms/cldr-emoji-annotation-synonyms-id.txt) : 3018 ; 
   * [source#3](https://github.com/agusmakmun/SentiStrengthID/blob/master/id_dict/emoticon.txt) : 123
1. Name Entity => 
   * [source#1](https://github.com/kata-ai/kawat/blob/master/semantic/country-capitals.txt) : [Place] country
   * [source#1](https://github.com/edwardsamuel/Wilayah-Administratif-Indonesia) : [Place] Wilayah-Administratif-Indonesia (provinces, villages, districts, regencies)
   * [source#2](https://github.com/pentagonal/Indonesia-Postal-Code) : [Place] Indonesia-Postal-Code  (provinces, cities, subdistricts, urbans)
   * [source#3](https://github.com/abhimantramb/elang/blob/master/word2vec/utils/indonesian-region.txt) : [Place] indonesian-region
   * [source#3](https://github.com/seuriously/genderprediction/blob/master/namatraining.txt) : [Person] gender prediction
   * [source#4](https://github.com/dominictarr/random-name/blob/master/names.txt) : [Person] random name
   * [source#5](https://github.com/panggi/pujangga/blob/master/resource/netagger/contextualfeature/ppre.txt) : [Person] title of name
   * [source#6](https://github.com/panggi/pujangga/blob/master/resource/netagger/contextualfeature/psuf.txt) : [Person] degree
   * [source#7](https://github.com/panggi/pujangga/blob/master/resource/reference/opre.txt) : [Org] institution
   
# Tagged dataset
1. NER =>
   * [source#1](https://github.com/yohanesgultom/nlp-experiments) : yohanesgultom/nlp-experiments 1700 sentences
   * [source#2](https://github.com/yusufsyaifudin/indonesia-ner) : yusufsyaifudin/indonesia-ner 1835 sentences
1. POS-TAG
   * [POS-TAG](https://github.com/famrashel/idn-tagged-corpus) : famrashel/idn-tagged-corpus
   * [POS-TAG](https://github.com/pebbie/pebahasa/blob/master/resource/Corpus.crp) : pebbie/pebahasa ~600 sentence
   * [POS-TAG Parser](https://github.com/UniversalDependencies/UD_Indonesian-GSD) : UniversalDependencies/UD_Indonesian-GSD ~4477 sentence 
1. Sentimen => 
   * [source#1](https://github.com/riochr17/Analisis-Sentimen-ID/blob/master/data/training_all_random.csv) : 1506 sentences ; 
   * [source#2](https://github.com/agusmakmun/SentiStrengthID/blob/master/id_dict/sentimentword.txt) : Sentiment word with strenght agusmakmun/SentiStrengthID 1573 (range : -5 until 5 ) ; 
   * [source#3](https://github.com/fajri91/InSet) : Sentiment with weight fajri91/InSet -> separate word list with weight of the strength (range : -5 until 5 ). 6610 negative words and 3619 positive words
1. [panl10n](http://www.panl10n.net/english/OutputsIndonesia2.htm) Pan Localization
1. [Acronyms](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/acronym.txt) : ramaprakoso/analisis-sentimen 4085 words

# Parallel corpus Eng-Ind
1. [parallel-corpora-en-id](https://github.com/prasastoadi/parallel-corpora-en-id/)
1. [Indonesian-English-Bilingual-Corpus](https://github.com/desmond86/Indonesian-English-Bilingual-Corpus)
1. [TALPCo](https://github.com/matbahasa/TALPCo)
1. [opus](http://opus.nlpl.eu/)
1. [Multi-Wiki](https://github.com/nguyenlab/Multi-Wiki)

# Sentence Analyzer 
1. [MALINDO_Morph](https://github.com/matbahasa/MALINDO_Morph)
1. [morphind](http://septinalarasati.com/morphind/)
1. [INDRA](https://github.com/davidmoeljadi/INDRA)
1. [pujangga](https://github.com/panggi/pujangga) : An interface for InaNLP and Deeplearning4j's Word2Vec for Indonesian (Bahasa Indonesia) in the form of REST API.
1. [id-multi-label-hate-speech-and-abusive-language-detection](https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection) : Here we provide our dataset for multi-label hate speech and abusive language detection in the Indonesian Twitter.
1. [kawat](https://github.com/kata-ai/kawat) : A Word Analogy Task Dataset for Indonesian

# Crawler Data
1. [Crawler](https://github.com/harryandriyan/warta-scrap) Indonesian news portal
