# Feature-Engineering-with-Text

Messages sent  through social media and email has become a popular communication channel and has caused a rise in messaging threats such as spam, phishing or malware as well as other threats. 

The language used in messages usually can contain informal words such as misspellings, slang, lexical variants and inconsistent punctuation, contractions, phonetic substitutions or emoticons. Spammers are aware of these peculiarities and generate messages that are very similar to ham by using creative variants of the original content in order to avoid fingerprinting. 

Text normalisation techniques deal with out-of-vocabulary words (OOV) by replacing these variants with canonical ones. The text normalization process based on the exception dictionaries of TENOR in order to substitute the most common English shortenings and lexical variants.

Structure of a usual Spam filter

The information contained in a message is divided into the header (fields containing general information on the message, such as the subject, sender and recipient) and body (the actual contents of the message). Before the available information can be used by a classifier in a filter, appropriate pre-processing pipeline are required:
•	Tokenization
•	Lower casing
•	Stopword removal
•	Stemming
•	Transformmation (TFIDFVectorizer)


Text Pre-Processing Pipeline¶
 Text pre-processing pipeline will include (but not limited to):
•	tokenization
•	lowercasing
•	stop word removal
•	stemming

Spam filtering model has been developed based on Bayesian algorithm and enhanced spam detection techniques filter both text and image based email messages.
