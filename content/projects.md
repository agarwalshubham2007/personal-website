+++
title = "Academic Projects"
slug = "projects"
+++

<hr>

##### Aligning English Sentences With AMR graphs using ILP

[CODE](https://github.com/agarwalshubham2007/AMR-Aligner-ILP)

* AMR: Semantic formalism to English natural language encoding meaning of a sentence in a rooted graph
* Idea of approach was predicting concepts invoked by words in a sentence is same as aligning words to those concepts
* Extracted linguistic background knowledge from sentences like lemma, part of speech, modals, named entities, question tokens
* Concepts in AMR split in nine categories. Learnt ILP rules for each category that invoke AMR concepts from sentence-AMR graph pairs in the training data
* Learnt ILP rules using open source system XHAIL deriving hypothesis in three steps : grounding, finding kernel, hypothesis generation
* Dataset consisted of 13050 AMR/English sentence pairs inclusive of 200 development and test pairs
* Performance of the aligner was measured using precision, recall and f-score measures on test dataset [P=0.971 | R=0.858 | F=0.91]

##### Semantic Search on Movie Database

[CODE](https://github.com/bhuvneshdev/NlpMovieDb)

* Created a text based system that predicts movie names on input user query
* Dataset of movie summaries text crawled from IMDB
* Proposed and implemented a semantic approach to find similarity between query and movie summary texts. Created a movie graph of events with Characters(nodes) and Events(edges)
* Used a semantic  K(knowledge)-parser to extract events from query and movie summaries
* Used multiple similarity scores to calculate similarity between input and movie graphs.} \item {Used NER similarity using Stanford CoreNLP, Term similarity using WS4J's PATH, LIN, LESK algorithms and Tf-IDF
* Used NLTK for NER detection and for name-co-reference unification of text
* Evaluated results using a hand prepared test dataset of 50 movies
