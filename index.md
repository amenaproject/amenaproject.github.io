### What is AMENA?

1. AMENA is a machine learning project that focuses on analyzing social media such as Twitter and News. Specifically, it is built for investigating political phenomena in Indonesia based on big data computation and the latest artificial intelligent approach. AMENA aims to provide accountable insight and information for government, policymakers, and society related to political events or the status quo in social media.
2. AMENA is a tool for analyzing and investigating public opinions on political developments in Indonesia through automatic text analysis.

Preliminary works (partially used as benchmark and knowledge base for this project) has been published in some international conferences, including:
1. Fajri Koto, and Gemala Y. Rahmaningtyas "InSet Lexicon: Evaluation of a Word List for Indonesian Sentiment Analysis in Microblogs". IEEE in the 21st International Conference on Asian Language Processing (IALP), Singapore, 2017. [[paper]](https://ieeexplore.ieee.org/abstract/document/8300625)
2. Fajri Koto, and Mirna Adriani. "HBE: Hashtag-Based Emotion Lexicons for Twitter Sentiment Analysis". ACM in The 6th Forum for Information Retrieval (FIRE 2015), Gandhinagar, India, December 2015 [[paper]](http://dl.acm.org/citation.cfm?id=2838718)
3. Fajri Koto, and Mirna Adriani. "A Comparative Study on Twitter Sentiment Analysis: Which Features are Good?". Springer in The 20th International Conference on Applications of Natural Language To Information Systems (NLDB 2015), Passau, Germany, June 2015 [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-19581-0_46)
4. Fajri Koto, and Mirna Adriani. "The Use of POS Sequence for Analyzing Sentence Pattern in Twitter Sentiment Analysis". IEEE in The 8th International Symposium on Mining and Web (MAW15), Gwangju, Korea (join with the 29th AINA Conference), March 2015 [[paper]](https://ieeexplore.ieee.org/abstract/document/7096234).

---

### What are the features of AMENA?

Currently, we have built three primary functions of AMENA. In the future, we are planning to enhance the model and features.
1. Crawler 
2. Analyzer: Network analysis and [Sentiment Analysis](https://en.wikipedia.org/wiki/Sentiment_analysis)
3. Data visualization

---

### How is AMENA constructed?

According to our knowledge, most of the machine learning systems in Indonesia (especially for analyzing text in the political domain) still use old-fashion approaches such as n-gram, lexicon-based technique, or traditional classification such as Naive Bayes, SVM, or regression. AMENA is different as it implements the state of the art of NLP for Bahasa Indonesia. Please refer to the recent [NLP lecture from Stanford](https://nlp.stanford.edu/~johnhew/public/14-seq2seq.pdf) to get some understanding about sequence-to-sequence model. In the future, we will enhance this architecture with pre-trained-network-models such as BERT (from Google) and GPT (from Open AI).

Currently, this is our neural architecture for classifying sentiment. Please keep in mind that we do it in two stages, as we involve neutral vs non-neutral, and postive vs negative prediction.


<img src="images/arch.jpg?raw=true"/>

---

### What has AMENA been used for?

AMENA has collaborated with [NextPolicy](https://nextpolicy.org/) on these following projects:

1. Analisis Pelantikan Kabinet / Menteri Jokowi (September-November 2019). Featured in [Republika](https://nasional.republika.co.id/berita/q1bk5x377/survei-ungkap-nadiem-dapat-perhatian-tertinggi-di-kabinet), [Jawapos](https://www.jawapos.com/nasional/21/11/2019/gebrakan-mendikbud-nadiem-makarim-paling-ditunggu-netizen/), [Tribunnews](https://m.tribunnews.com/images/regional/view/1823297/diskusi-kabinet-jokowi-dan-maruf-amin-di-mata-publik), [LineToday](https://today.line.me/id/pc/article/Survei+Next+Policy+Mendikbud+Raih+Perhatian+Tertinggi+Warganet-o3qQ2j), [Media Indonesia](https://m.mediaindonesia.com/amp/amp_detail/273078-survei-next-policy-mendikbud-raih-perhatian-tertinggi-warganet), [Tirto](https://www.beritasatu.com/politik/586662/next-policy-netizen-masih-tunggu-terobosan-nadiem-makarim), [BeritaSatu](https://www.beritasatu.com/politik/586662/next-policy-netizen-masih-tunggu-terobosan-nadiem-makarim), [Republika](https://www.republika.co.id/amp/q1bvi7320), [SindoNews](https://autotekno.sindonews.com/newsread/1461081/207/momentum-nadiem-makarim-jadi-paling-banyak-jadi-perhatian-milenial-1574329284).
2. Analisis 100 hari kepresidenan Jokowi (ongoing project, December 2019 on wards)

