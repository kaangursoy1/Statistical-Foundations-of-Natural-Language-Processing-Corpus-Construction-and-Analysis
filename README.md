# Statistical-Foundations-of-Natural-Language-Processing-Corpus-Construction-and-Analysis
# Overview
This project aims to explore fundamental statistical laws in natural language processing (NLP) by constructing and analyzing a custom corpus from literature. It involves a comprehensive study of word distributions, tokenization, stop-word removal, and the relationship between word types and token sizes in different texts. The primary focus is to investigate and confirm Zipf's Law and other statistical patterns in text corpora. Additionally, it explores the potential of clustering texts based on author or literary genre using these statistical insights.

# Dataset
Source: The Project Gutenberg eBooks (http://www.gutenberg.org/)
Corpus Composition:
3 authors, 3 books each: A total of 9 books from three different authors, selected for their sizable content (over 1MB).
3 genres, 3 books each: An additional set of 9 books from three different literary genres, ensuring a broad representation of text types.
# Preprocessing:
All books were cleaned of metadata, tokenized, converted to lowercase, and stripped of punctuation.
Stop-word removal was applied to create two versions of each text (with and without stop-words), resulting in a total of 36 text versions.
# Methodology
# Corpus Construction:

Texts were selected based on authorship and genre, ensuring the removal of Project Gutenberg metadata and unreadable characters.
Implemented tokenization and stop-word removal using standard English stop-word lists.
Two corpus versions were generated: one with stop-words and one without.
# Vocabulary Analysis:

Created vocabulary files with word types and frequencies for each book, before and after stop-word removal.
Plotted Zipf’s Law curves for three authors, observing word frequency distributions and validating the Zipfian pattern.
# Type-Token Relationship:

Analyzed the relationship between token size and vocabulary size in each author’s corpus.
Plotted both normal and log-log curves to observe text behavior and identified the relationship as Heaps' Law.
# Clustering Potential:

Investigated simple clustering methodologies to group books by author or genre using statistical patterns derived from word distributions and token-type relations.
# Results
# Zipf’s Law:

The Zipfian distribution was observed in most author corpora, confirming the expected statistical behavior in natural language corpora.
Consistency was found in the Zipfian patterns across authors, though variations existed in the slopes of word frequency curves.
# Type-Token Relationship:

The analysis confirmed Heaps' Law, where vocabulary size grows sub-linearly with token size, as indicated by a growth rate less than one.
Both linear and log-log plots highlighted this behavior, with a clear distinction between corpora before and after stop-word removal.
# Impact of Stop-word Removal:

Removing stop-words led to sharper slopes in the log-log type-token curves, indicating a clearer growth trend in vocabulary size.
However, the overall distribution patterns remained consistent, suggesting minimal impact on the core statistical properties of the texts.
# Clustering Feasibility:

Preliminary clustering results showed potential for grouping texts based on author or genre using type-token ratios and word frequency distributions.
Expanding the analysis to five authors indicated increased complexity but retained clustering viability.

# Conclusion
This project demonstrates the statistical properties of natural language corpora, confirming both Zipf's and Heaps' Laws. It also highlights the potential of basic statistical analysis for clustering texts based on authorship or genre. The results show that statistical NLP can be effective even without advanced NLP libraries.
