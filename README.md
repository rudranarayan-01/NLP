# NLP 

## Tokenization (nltk)
  - sent_tokenize
  - word_tokenize
  - wordpunct_tokenize ( It simply separates punctuanions)
  - TreebankWordTokenizer ( It will not tokenize full stop)

## Steeming
  -  Porter Steemer
  -  RegexpStemmer
  -  Snowball Stemmer (gives better result than porterstemmer in most of the cases )

Using stemming is not a good practice while we working a project like chatbot or equivalent. So we use Lemmatization


## Lemmatization
 A Lemmatizer is cnsists of dictionary we can specify the POS(noun(n), verb(v), adverb(r), adjective(d))
  -  Wordnet Lemmatizer


## Text Processing and Stopwords
  - Used Stemming and Lemmatization in a paragraph and saw the results and find out that Lemmatization is gives better results

## Parts of speech tagging 
  -  a process that labels each word in a text with its grammatical category (pos_tag)

## Name Entity Recognition 
  - identifies and classifies entities like people, organizations, and locations within text, often utilizing Part-of-Speech (POS) tagging as a crucial preprocessing step (pos_tag.draw())

## Encoding 
  - One Hot Encoding
  - Bag Of Words
  - IF-IDF( Term Frequency - Inverse Doccument Frequency )
