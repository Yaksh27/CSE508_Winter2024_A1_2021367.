# CSE508_Winter2024_A1_2021367.

Text Processing and Positional Index Project Report


Introduction
In this assignment, I've developed a Python program to handle text processing and create a positional index for efficient information retrieval. Below are the key components and functionalities of my project, outlined in a simple, student-friendly manner.

Key Components
NLTK Downloads: Initially, I downloaded necessary resources from the Natural Language Toolkit (NLTK), such as 'punkt' for tokenization and 'stopwords' for filtering common words.

Text Preprocessing:
Converted all text to lowercase for uniformity.
Tokenized text into words, removing punctuation and non-alphabetic characters.
Filtered out stopwords to focus on significant words.

Positional Index Creation:
Built using nested dictionaries to store word positions across documents.
Ensured it only processes .txt files to maintain focus on textual data.
Saving and Loading Index:

Utilized Python's pickle module for saving the positional index to a file and loading it back, making data retrieval efficient and reusable.

Functionality

Preprocessing Text:
The TextProcessor class handles text normalization, tokenization, and cleaning. This step is crucial for ensuring that the index only contains relevant words.


Creating the Positional Index:

The index maps words to their positions in each document, crucial for supporting precise phrase queries. It's implemented to efficiently handle large volumes of text.

Query Processing:
The system can process phrase queries, determining the exact sequence of words in documents. This functionality is essential for accurate search results.

Challenges and Solutions


Serialization of Lambda Functions: Encountered issues with serializing lambda functions for the positional index. Solved by using named functions for default dictionary values.
Handling Complex Queries: Devising a system to process combined boolean queries was challenging. Overcame this by implementing a robust parser and leveraging recursive strategies to evaluate query combinations.

Conclusion

This assignment encapsulates essential functionalities for text processing and indexing in Python, leveraging NLTK for preprocessing and custom logic for creating a positional index. It demonstrates practical skills in handling and querying large datasets, with a focus on efficiency and accuracy.

