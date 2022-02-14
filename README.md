Keyword extraction is tasked with the automatic identification of terms that best describe the subject of a document.
Keywords are the terms that represent the most relevant information contained in the document.
Methods for automatic keyword extraction can be supervised, semi-supervised, or unsupervised.
There are various ways to extract keywords from text like by using Count Vectoriser , TF-IDF , LDA but the problem with all those approaches are these approaches have nothing to do with the 
Semantic relationship between words and text document they give words/ keywords importance based on their occurance in the document.

What is semantic relationship?
Semantic relationships are the associations that there exist between the meanings of words (semantic relationships at word level),
between the meanings of phrases, or between the meanings of sentences (semantic relationships at phrase or sentence level).

In this project --
I used Senntence Transformers to calculate Semantic relationships between words and the sentence .
In this keywords are extracted based on how closely each keyword is representing the sentence .
for example :-

text = "Video: Students Stopped At Second Karnataka College Over Hijab"

keywordsextracted = [('karnataka college', 0.473552405834198),
 ('over hijab', 0.4525412321090698),
 ('hijab', 0.44046491384506226),
 ('students stopped', 0.4034881293773651),
 ('karnataka', 0.400024950504303)]
 
We can see that how close are  each keywords is to the document .

This is very simple to use since we will use the knowledge and understanding of pre-built models.
We don't have to traing anything from scratch and also they are very good in understanding text data .
Give It a try .
Thanks ! 
