# Hadoop-MapReduce - Average Word Length

MapReduce code which calculates average word length, aggregating results by first letter. This repository includes the Driver, Mapper, and Reducer. Also included in this repository is a txt file with the local and Hadoop script commands necessary to compile the java code, combine into a jar file, and submit the project to hadoop.

This MapReduce code could be used on any HDFS directory. I used it on a sample of Shakespeare's works provided by Cloudera. I included the Reducer's output as a csv file, showing key-value format. 

Links
--------------------
Java Files: https://github.com/BethHilbert/Hadoop-AverageWordLength/tree/master/averagewordlength/stubs

Hadoop Script Commands: https://github.com/BethHilbert/Hadoop-AverageWordLength/blob/master/Hadoop%20Script%20Commands

CSV output from Shakespeare: https://github.com/BethHilbert/Hadoop-AverageWordLength/blob/master/averagewordlengthoutput.csv