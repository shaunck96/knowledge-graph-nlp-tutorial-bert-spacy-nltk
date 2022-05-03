# knowledge-graph-nlp-tutorial-bert-spacy-nltk

Table of Contents
Knowlege Graph (KG)
BERT
spaCy
NLTK

Introduction

1.1 What is Knowledge Graph?

1.2 Data Representation in Knowledge Graph?

1.3 Import Dependencies

1.4 Sentence Segmentation

1.5 Entities Extraction

1.6 Relations Extraction

1.7 Build Knowledge Graph

Conclusion


![](https://media-exp1.licdn.com/dms/image/C5622AQFSXoiAZtY6YA/feedshare-shrink_800-alternative/0?e=1602115200&v=beta&t=T06bS6puUTKlX7mWQ-fpRQz-BnO2b9Hv3zgFl3s0I9s)
Language is a method of communication with the help of which we can speak, read and write. For example, we think, we make decisions, plans and more in natural language; precisely, in words. However, the big question that confronts us in this AI era is that can we communicate in a similar manner with computers. In other words, can human beings communicate with computers in their natural language? It is a challenge for us to develop NLP applications because computers need structured data, but human speech is unstructured and often ambiguous in nature.

In this sense, we can say that Natural Language Processing (NLP) is the sub-field of Computer Science especially Artificial Intelligence (AI) that is concerned about enabling computers to understand and process human language. Technically, the main task of NLP would be to program computers for analyzing and processing huge amount of natural language data.

### History of NLP
We have divided the history of NLP into four phases. The phases have distinctive concerns and styles.

**First Phase (Machine Translation Phase) - Late 1940s to late 1960s**

The work done in this phase focused mainly on machine translation (MT). This phase was a period of enthusiasm and optimism.

Let us now see all that the first phase had in it −

* The research on NLP started in early 1950s after Booth & Richens’ investigation and Weaver’s memorandum on machine translation in 1949.
 
* 1954 was the year when a limited experiment on automatic translation from Russian to English demonstrated in the Georgetown-IBM experiment.
 
* In the same year, the publication of the journal MT (Machine Translation) started.
 
* The first international conference on Machine Translation (MT) was held in 1952 and second was held in 1956.
 
* In 1961, the work presented in Teddington International Conference on Machine Translation of Languages and Applied Language analysis was the high point of this phase.

**Second Phase (AI Influenced Phase) – Late 1960s to late 1970s**

In this phase, the work done was majorly related to world knowledge and on its role in the construction and manipulation of meaning representations. That is why, this phase is also called AI-flavored phase.

The phase had in it, the following −

* In early 1961, the work began on the problems of addressing and constructing data or knowledge base. This work was influenced by AI.
 
* In the same year, a BASEBALL question-answering system was also developed. The input to this system was restricted and the language processing involved was a simple one.
 
* A much advanced system was described in Minsky (1968). This system, when compared to the BASEBALL question-answering system, was recognized and provided for the need of inference on the knowledge base in interpreting and responding to language input.

**Third Phase (Grammatico-logical Phase) – Late 1970s to late 1980s**

This phase can be described as the grammatico-logical phase. Due to the failure of practical system building in last phase, the researchers moved towards the use of logic for knowledge representation and reasoning in AI.

The third phase had the following in it −

* The grammatico-logical approach, towards the end of decade, helped us with powerful general-purpose sentence processors like SRI’s Core Language Engine and Discourse Representation Theory, which offered a means of tackling more extended discourse.
 
* In this phase we got some practical resources & tools like parsers, e.g. Alvey Natural Language Tools along with more operational and commercial systems, e.g. for database query.
 
* The work on lexicon in 1980s also pointed in the direction of grammatico-logical approach.

**Fourth Phase (Lexical & Corpus Phase) – The 1990s**

We can describe this as a lexical & corpus phase. The phase had a lexicalized approach to grammar that appeared in late 1980s and became an increasing influence. There was a revolution in natural language processing in this decade with the introduction of machine learning algorithms for language processing.

### Study of Human Languages

Language is a crucial component for human lives and also the most fundamental aspect of our behavior. We can experience it in mainly two forms - written and spoken. In the written form, it is a way to pass our knowledge from one generation to the next. In the spoken form, it is the primary medium for human beings to coordinate with each other in their day-to-day behavior. Language is studied in various academic disciplines. Each discipline comes with its own set of problems and a set of solution to address those.

### Ambiguity and Uncertainty in Language

Ambiguity, generally used in natural language processing, can be referred as the ability of being understood in more than one way. In simple terms, we can say that ambiguity is the capability of being understood in more than one way. Natural language is very ambiguous. NLP has the following types of ambiguities −

**Lexical Ambiguity**

The ambiguity of a single word is called lexical ambiguity. For example, treating the word silver as a noun, an adjective, or a verb.

**Syntactic Ambiguity**

This kind of ambiguity occurs when a sentence is parsed in different ways. For example, the sentence “The man saw the girl with the telescope”. It is ambiguous whether the man saw the girl carrying a telescope or he saw her through his telescope.

**Semantic Ambiguity**

This kind of ambiguity occurs when the meaning of the words themselves can be misinterpreted. In other words, semantic ambiguity happens when a sentence contains an ambiguous word or phrase. For example, the sentence “The car hit the pole while it was moving” is having semantic ambiguity because the interpretations can be “The car, while moving, hit the pole” and “The car hit the pole while the pole was moving”.

**Anaphoric Ambiguity**

This kind of ambiguity arises due to the use of anaphora entities in discourse. For example, the horse ran up the hill. It was very steep. It soon got tired. Here, the anaphoric reference of “it” in two situations cause ambiguity.

**Pragmatic ambiguity**

Such kind of ambiguity refers to the situation where the context of a phrase gives it multiple interpretations. In simple words, we can say that pragmatic ambiguity arises when the statement is not specific. For example, the sentence “I like you too” can have multiple interpretations like I like you (just like you like me), I like you (just like someone else dose).

### NLP Phases
Following diagram shows the phases or logical steps in natural language processing −
![](https://www.tutorialspoint.com/natural_language_processing/images/phases_or_logical_steps.jpg)

**Morphological Processing**

It is the first phase of NLP. The purpose of this phase is to break chunks of language input into sets of tokens corresponding to paragraphs, sentences and words. For example, a word like “uneasy” can be broken into two sub-word tokens as “un-easy”.

**Syntax Analysis**

It is the second phase of NLP. The purpose of this phase is two folds: to check that a sentence is well formed or not and to break it up into a structure that shows the syntactic relationships between the different words. For example, the sentence like “The school goes to the boy” would be rejected by syntax analyzer or parser.

**Semantic Analysis**

It is the third phase of NLP. The purpose of this phase is to draw exact meaning, or you can say dictionary meaning from the text. The text is checked for meaningfulness. For example, semantic analyzer would reject a sentence like “Hot ice-cream”.

**Pragmatic Analysis**

It is the fourth phase of NLP. Pragmatic analysis simply fits the actual objects/events, which exist in a given context with object references obtained during the last phase (semantic analysis). For example, the sentence “Put the banana in the basket on the shelf” can have two semantic interpretations and pragmatic analyzer will choose between these two possibilities.
    
