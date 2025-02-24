**KMP Algorithm Implementation**
This project contains an implementation of the Knuth-Morris-Pratt (KMP) Algorithm for pattern searching in C++. The KMP algorithm efficiently finds occurrences of a pattern in a given text using the Longest Prefix Suffix (LPS) array to avoid redundant comparisons.

**Features**
Computes the LPS (Longest Prefix Suffix) array to optimize searching.
Searches for a given pattern in a text efficiently.
Outputs all occurrences of the pattern in the text.

**How It Works**
The computeLPSArray() function calculates the LPS array for the given pattern.
The KMPSearch() function uses the LPS array to search for the pattern in the text.
The main function defines a sample text and pattern, then calls the KMP search function to find occurrences.
