# Graph Analytics
# One of the many things that graphs can be used for is performing grid & network quality of service 
* identifying weakness in power/water grids, transportation networks, preventing cybercrime, etc.
* Optimizing routes in the airlines and retail industries

![screen shot 2018-09-20 at 4 28 50 pm](https://user-images.githubusercontent.com/31625655/45845156-58a33a80-bcf2-11e8-8bcd-1eb3cc67dce7.png)

# When Can Graph Analysis Be Used?
# All the time.

* To address relationship-based problems(travel, security, social media hierarchies)
* To represent networks of communication and data organization within a company
* To identify clusters of communities

![image](https://user-images.githubusercontent.com/31625655/45844885-a10e2880-bcf1-11e8-948e-05ffe09a1b00.png)

Meet-Up is a social media platform that offers membership software to enable their users create events on a common platform. The relationship derived from this platform are the members who attend or create meetups and is ideal for graphical analysis. The data set retrieved was on Meet-up data in Nashville, TN.

![image](https://user-images.githubusercontent.com/31625655/45844913-aec3ae00-bcf1-11e8-9635-2907e09bea06.png)

![image](https://user-images.githubusercontent.com/31625655/45844932-b5522580-bcf1-11e8-836e-c476e9217ee6.png)

It lists the nodes or discrete entities as well as the connection between those entities through edges. There are two sets of data: graph data which shows the edges between nodes and meta data which shows a list of all the nodes themselves. They should also have corresponding id’s for all nodes used in the graph data. Since every node has a unique id, we wanted to be able to see the connectivity between different members of groups. We developed a graph using Gephi, an open source network analysis visualization tool, and only imported selected data (group edges and meta groups). Group edges gives data to enable construct a group to group graph (node to node), whereas meta groups contains information on each group such as name and category. The weight indicates the strength of a connection between two nodes thus two groups can be connected and have a weight of 1, if there is 1 common member for each group or 2 if there are 2 members found in both groups. In order to link the file for group edges, we had to create a source id and target id so it could be easily displayed graphically. Visualizing this data not only allowed us to see how many individuals belonged to different groups but also how many groups existed within Nashville, and how many have similar members. We also observed how several nodes are directly connected to each other and this highlights the stability and strength of the network system. Another important thing to note was the dysconnectivity amongst the nodes- not all nodes in the graph are connected to each other. 


Graph analytics is very powerful in uncovering valuable insights about data, optimize processes and improve financial opportunities. As a data analyst, the goal is to not only uncover correlations and patterns within data but to be able to make effective data-driven decisions from the insights. Graph analytics supports the ability to add new data sources and develop new relationships within the data in order to answer arising queries. 

# (Visual developed in Gephi from Nashville Meetup Data, retrieved from Kaggle)
