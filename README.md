# Word_Composition
my git repo with eclipse
Introduction
This Java program is designed to find the longest compound word from a list of words in a given input file. It uses a Trie data structure to efficiently identify compound words and determine the longest and second longest compound words.

Prerequisites
Before running the program, make sure you have the following prerequisites:

Java Development Kit (JDK) installed on your system.
Getting Started
Clone or download this repository to your local machine.

Open a command-line terminal and navigate to the directory containing the Java source files (Solution.java and Trie.java).

A Trie is a tree-like data structure used for efficiently storing and searching for strings. It is particularly useful for tasks like autocompletion, spell checking, and prefix matching. The core components of this implementation are the TrieNode class and the Trie class.

Trie Class
The Trie class serves as the root of the Trie data structure. It has the following key methods:

insert(String word): Inserts a word into the Trie. contains(String word): Checks if a word exists in the Trie. getPrefixes(String word): Retrieves all prefixes of a given word.

Usage
To use this Trie implementation, follow these steps:

Create a Trie object using Trie trie = new Trie();. Insert words into the Trie using the insert(String word) method. Check if a word exists in the Trie using the contains(String word) method. Obtain all prefixes of a word using the getPrefixes(String word) method.

Deployment
To deploy this project run

    character: The character associated with the node.
    children: A HashMap that maps characters to their corresponding child nodes.
    isTerminal: A boolean flag indicating whether the current node represents the end of a valid word.
Badges
Add badges from somewhere like: shields.io

MIT License GPLv3 License AGPL License

Appendix
Any additional information goes here
