# Twi Corpus: A Massively Twi-to-Handful Languages Parallel Bible Corpus 
We detailed the modeling of a massively parallel Bible corpus based on Twi, a common Ghanaian language to a handful of languages. We discussed some of the common issues we encountered in obtaining, processing, converting, and formatting the corpus and the latent desire for success in NLP. We stored the sentence aligned data in various files based on the Twi to the selected language pairs with a tab-delimited separation. Verses with the same line number in a line pair are mappings of each other. It is often challenging to learn what a "clean" corpus looks like in lower-resource situations, especially where the target corpus is the only sample of the language's parallel text. We, therefore, performed unsupervised measurements on each sentence pair. We engage the squared Mahalanobis distances that predicted parallelism on the dataset. Eventually, we perform a statistical analysis of the corpora collected based on selected text categorization models for text classification by leveraging vector embedding (like Word2vec). Finally, we trained the Twi vocabs for a 2D representation. Similar words find their vectors closer by engaging t-Distributed Stochastic Neighbor embedding (t-SNE).. 
##### Refer to dataset/split

## The Akan Language also known as Twi
Is a spoken language in the southern and central part of Ghana by several people, mainly of the Akan tribe. It is the biggest of about 18 major tribes in Ghana and forms about 70% of the Ghanaian population as a first and second language [1]. Twi is a common name for two former literary dialects of the Akan language; Asante (Ashanti) and Akuapem, which are mutually intelligible. There are about 9 million Twi speakers, mainly originating from the Ashanti Region [2] and about a total of 17–18 million Ghanaians as either first or second Twi language speakers. The Twi alphabet contains 22 letters as shown in table 1. Letters C, J, V, and Z are also used, but only in loanwords [1]. 
__________________________________________________
             ### THE TWI ALPHABET
__________________________________________________
#### Majuscule forms (uppercase or capital letters)

## A	B	D	E	Ɛ	F	G	H	I	K	L	M	N	O	Ɔ	P	R	S	T	U	W	Y

#### Minuscule forms (lowercase or small letters)

## a	b	d	e	ɛ	f	g	h	i	k	l	m	n	o	ɔ	p	r	s	t	u	w	y


## Reference
#### [1] https://en.wikipedia.org/wiki/Akan_language
#### [2] https://www.amesall.rutgers.edu/languages/128-akan-twi
