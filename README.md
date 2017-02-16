1.	Explain what is a cluster and what is a hadoop cluster?
Cluster is a system which consists of many servers and other supportive hardware which work together as single system and enable high availability and high processing capability.
Hadoop Cluster 
Hadoop cluster consist of master daemon called as name node and Resource Manager (in Hadoop 2.X) both the master daemons are one in number. The other machines in cluster are slave daemons these are many in number and are the commodity machines which are low in cost and are not reliable. Hence the many copies of the data in from of blocks are kept in more than on slave daemon so that data reliability is removed by replication of the data. Different slave daemons are Data node for HDFS and node manager for map reduce.(Already Mentioned in assignment 2.2)







2) What is meant by a Rack and explain the rack arrangement in a Hadoop cluster?
Rack is group of around 40 to 50 nodes which are physically placed together which are connected to the same network with help of the switch. 
Hadoop rack awareness is arrangement for the betterment of the traffic while reading or  writing the files in disk .Hadoop rack awareness  is important as it gives the shorter path to different nodes as transmitting data between two nodes in same rack would be much easier than that of the in the other node this can be done with help of rack awareness.
