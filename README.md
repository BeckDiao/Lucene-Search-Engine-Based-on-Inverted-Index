# Lucene-Search-Engine-Based-on-Inverted-Index
1. Used inverted index,  an index data structure storing a mapping from content to its locations in a database file, to allow fast full text searches. 
2. Implemented Mapper Class for loading files, splitting words and filtering stopwords and Reducer Class for counting and  exporting the output, and ran on Docker.
3. Improved exactness of output by setting threshold to further filter low-occurrence outputs so that false positive reduced.
4. Chose StringTokenizer after testing StringTokenizer and String.split method because of better performance and 10% runtime speed improved.
5. Improved 20% efficiency by filtering stopwords(like "a", "the", etc.)  in Reducer Class because of work load decreased.
