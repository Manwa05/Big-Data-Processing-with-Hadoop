# Big-Data-Processing-with-Hadoop

•	Implemented a simple word count program using MapReduce on 3 text files stored in HDFS.
•	Generated the top 10 occurring tri-grams in the input files by replacing the keywords in the input with '$' using MapReduce program. A global mapper was created to take the output of all local reducers which was then passed to a global reducer that combined the tri-grams and incremented their counts.
•	Created an inverted index of all the words occurring in the input files using MapReduce. Words and the corresponding list of filenames in which they appear was given as the output.
•	Performed a relational join on 2 text files using MapReduce. The input text files were joined on the primary key constraint.
•	Implemented the K-nearest neighbor algorithm using MapReduce of Hadoop. The mapper program was used to output the distances and the labels associated with them to the reducer which in turn sorted the distances according to the K-neighbors and predicted their class label. 

Language used: Python 
Frameworks used: Hadoop
