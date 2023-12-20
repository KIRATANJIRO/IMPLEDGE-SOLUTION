Program Overview:
Trie Implementation: The program defines classes for TrieNode and Trie. The Trie is utilized to efficiently store and search for words.
Functions:
insert: Inserts words into the Trie.
search: Searches for words in the Trie.
isCompoundWord: Determines if a word can be formed by concatenating two other words in the input list.
Other utility functions to find compound words and their lengths.
Main Function:
Reads input from two different files (input_01.txt and Input_02.txt).
Constructs a Trie with words from each file.
Identifies the longest and second-longest compound words from the words in each file.
Measures the time taken to process each file.
Summary:
The program performs the following steps:

Initialization:
Reads words from two input files.
Constructs a Trie data structure.
Trie Operations:
Inserts words into the Trie for each file.
Searches for the longest and second-longest compound words in each set of words using Trie operations.
Time Measurement:
Measures the time taken to process each file using the chrono library.
Output:
Displays the longest and second-longest compound words found in each file.
Displays the time taken to process each file in milliseconds.
