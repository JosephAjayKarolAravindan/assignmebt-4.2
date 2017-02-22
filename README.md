# assignmebt-4.2
QN 1:Write a Java program to list down all the files inside a directory and its sub-directories who
have last modified timestamp between the start_ts and end_ts passed as an argument. The
default value of start_ts is 0 and for end_ts is infinite.
In my program I have taken the path from root Directory and I accepted 2 arguments which takes Time Stamp in "yyyyMMddHHmmss" and them I used a remoteIterator to list all files recursively and I get Modified time of all files By "getModificationTime" and then passed it as a Date and convert these into Simple Date Format(yyyy-MM-dd HH:mm:ss) and convert it into Time Stamp and used TimeStamp.before and after to 
list all files having modified Time Stamp in this Range
O/P verification :I could retrieve the file which I actually put on Hdfs as Highlighted in O/p image
