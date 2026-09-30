# Mapreduce_word_frequently


A simple Python implementation of the MapReduce paradigm using the mrjob library to calculate word frequency from text files.

MapReduce Word Frequency Counter
This project demonstrates how to perform a word frequency analysis on text data using the MapReduce programming model in Python with the mrjob library.

Features
Mapper: Splits input text into individual words and counts occurrences.
Combiner & Reducer: Efficiently aggregates counts for each unique word.
Case Insensitive: Converts all words to lowercase to ensure accurate frequency counts.
