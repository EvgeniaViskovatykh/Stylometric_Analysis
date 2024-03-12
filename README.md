### Stylometric_Analysis Project ##
Stylometric analysis of the novel "David Copperfield" by Charles Dickens.

## Introduction:
Stylometric analysis is a method for studying the linguistic style of written texts. It is often employed in authorship attribution and literary analysis. In this report, we conducted a stylometric analysis of Charles Dickens's novel David Copperfield.

## Methodology:

# Data Collection: 
The text of "David Copperfield" was obtained from Project Gutenberg, a digital library of public domain texts.
# Data Preprocessing:
The text was tokenized into words using the NLTK library.
Punctuation marks and stop words were removed to focus on content words.
Part-of-speech tagging was performed to identify different syntactic patterns.
# Feature Extraction:
Word frequencies were calculated to identify the most common words in the text.
Sentence lengths were analyzed to understand the structure and complexity of the text.
The type-token ratio (TTR) was calculated to measure vocabulary richness.
Syntactic patterns were examined by analyzing the frequency of different parts of speech.
# Readability Measures:
The Flesch Reading Ease Score and Flesch-Kincaid Grade Level were computed to assess the text's readability.

## Results:

# Most Common Words: 
Analysis of word frequencies revealed that words like "said" and "little" had 2942 and 1057 occurrences, respectively.
# Sentence Length: 
The average sentence length is 26.53 words.
# Vocabulary Richness: 
The type-token ratio (TTR) is 0.055537, suggesting moderate vocabulary richness.
# Syntactic Patterns: 
Examining syntactic patterns showed that Nouns (17921) and Prepositions or subordinating Conjunctions (16523) were the text's most common parts of speech.
# Readability Measures: 
The Flesch Reading Ease Score is 69.11. The Flesch-Kincaid Grade Level is 8.3 (aprox. for 8th graders of US school)

## Conclusion:
The stylometric analysis of "David Copperfield" provided insights into Charles Dickens's writing style and the novel's linguistic characteristics. The results highlighted the frequent use of certain words, the complexity of sentence structures, and the text's readability. Further analysis and comparison with other works by Charles Dickens or contemporary authors could yield additional insights into the author's style and literary influences.

## Code:
The code used for this analysis involved data preprocessing, feature extraction, and calculation of readability measures using Python libraries such as NLTK and textstat. Specific functions were written to tokenize the text, remove punctuation and stop words, perform part-of-speech tagging, and calculate various stylometric features. The code was modularized and encapsulated within functions to facilitate readability, reusability, and ease of analysis. All the results are visualised. Code can be adjusted accordingly to linguistics goals.
