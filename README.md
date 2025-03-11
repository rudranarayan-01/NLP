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

## Different Encoding 
 The process of converting text into a format that computers can understand. This is done by representing words as numbers or vectors. 
   - One Hot Encoding
   - Bag Of Words
      - Binary Bag Words ( 0, 1)
      - Normal Bag of Words ( Count will get updated based on frequency )
   - IF-IDF( Term Frequency - Inverse Doccument Frequency )

## Word Embeding 
   In NLP word embeding is a term used for the representation of words for text analysis, typically in the form of real valued vector that encodes the meaning of the word such that the words that are closer in the vector space are expected to be similar meaning.
   
   Word Embeding is of two types: 
     
      - Count or Frequency
         - One Hot Encoding
         - Bag of Words
         - IF_IDF
       
      - Deep Learning Training Model (Word2Vec)
          - CBOW ( Continous Bag of Words )
          - Skipgram


  
       
