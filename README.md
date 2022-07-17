# Big-Data-Digital-Assignment

Word Count with two input files


# Hadoop_Map-Reduce word count:
Hadoop Map reduce word count program displays the count of each word in a specified text file. The implementation of Word Count java program is done in HDFS.
Following are the commands need to follow in order to run the hadoop mapreduce wordcount program for specific input text file: 

1)To Put the input files in a directory created in hadoop: --> hadoop fs -put C:/file1.txt /word_count --> hadoop fs -put C:/file2.txt /word_count

2)To Check the content of the specified input file: --> hadoop dfs -cat /word_count/file1.txt --> hadoop dfs -cat /word_count/file2.txt

3)To run the jar file: -->hadoop jar C:/hadoop-3.3.0/share/hadoop/mapreduce/hadoop-mapreduce-examples-3.3.0.jar wordcount /word_count /outputs

4)To display the final counts of each words present in the input file: hadoop fs -cat /outputs/*
