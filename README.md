## Graph Analytics
# Graph Analytics

A strong analysis that makes complex data more simplified. According to IBM, Graph analytics also known as network analysis, is an interesting new area for analytics workloads (Ferguson, 2016). It is essentially used to leverage graph structures in an effort to visualize the relationships that exist between the people or devices in a network (Big Data 03 ppt, 2018).

# One of the many things that graphs can be used for is performing grid & network quality of service 
* identifying weakness in power/water grids, transportation networks, preventing cybercrime, etc.
* Optimizing routes in the airlines and retail industries



Graph theory can be applied in various aspects of engineering, social, and biological sciences and are often used to show the relationships amongst discrete objects which are defined as nodes also known as vertices in mathematical context) and connected by lines or paths known as edges. Nodes can either be individuals or affinity groups such as Facebook groups.  Through this we are able to understand the topology of the network or the relationships that exists between variables. There are four main types of graph analysis that are commonly used which include path analysis, connectivity analysis, community analysis and centrality analysis. Path analysis can be used to optimize route delays on ride share apps by assessing the shortest distance between two nodes on a graph. Connectivity analysis shows the weakness in networks whereas centrality analysis shows the influential people that exist on a social network through ranking algorithms such as Instagram influencers. Our paper is based on data on community analysis, used to locate different interacting groups on a social media platform. (Ferguson, 2016).



Meet-Up is a social media platform that offers membership software to enable their users create events on a common platform. The relationship derived from this platform are the members who attend or create meetups and is ideal for graphical analysis. The data set retrieved was on Meet-up data in Nashville, TN.

![image](https://user-images.githubusercontent.com/31625655/45844885-a10e2880-bcf1-11e8-948e-05ffe09a1b00.png)


It lists the nodes or discrete entities as well as the connection between those entities through edges. There are two sets of data: graph data which shows the edges between nodes and meta data which shows a list of all the nodes themselves. They should also have corresponding id’s for all nodes used in the graph data. Since every node has a unique id, we wanted to be able to see the connectivity between different members of groups. We developed a graph using Gephi, an open source network analysis visualization tool, and only imported selected data (group edges and meta groups). Group edges gives data to enable construct a group to group graph (node to node), whereas meta groups contains information on each group such as name and category. The weight indicates the strength of a connection between two nodes thus two groups can be connected and have a weight of 1, if there is 1 common member for each group or 2 if there are 2 members found in both groups. In order to link the file for group edges, we had to create a source id and target id so it could be easily displayed graphically. Visualizing this data not only allowed us to see how many individuals belonged to different groups but also how many groups existed within Nashville, and how many have similar members. We also observed how several nodes are directly connected to each other and this highlights the stability and strength of the network system. Another important thing to note was the dysconnectivity amongst the nodes- not all nodes in the graph are connected to each other. 


Graph analytics is very powerful in uncovering valuable insights about data, optimize processes and improve financial opportunities. As a data analyst, the goal is to not only uncover correlations and patterns within data but to be able to make effective data-driven decisions from the insights. Graph analytics supports the ability to add new data sources and develop new relationships within the data in order to answer arising queries. 
