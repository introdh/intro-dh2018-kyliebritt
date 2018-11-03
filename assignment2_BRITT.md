# Network Analysis: Polish Jews in Positions of Power, 1944-1956 

## Data:

In early postwar Poland, it was not uncommon for Jews to be appointed to high positions of power. Stalin himself even appointed some Jews to run some essential departments. I wondered if there were any patterns to the organizations that Polish Jews ran, and how a Network Analysis could elucidate the relationships of those organizations and their leaders. 
My nodes represent different officials of Jewish heritage, and they are connected by edges which represent a shared organization. For this analysis, I counted a "shared organization" as a group in which both people held leadership positions. 

There are only nine figures represented in my analysis, but up to six edges connecting a single leader. By analyzing the structure of a network, I intend to suggest some trends about Polish Jews in leadership positions. 

## Analysis:

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_degrees.JPG "Degrees")

The above image shows the degree values of my nodes, and visually spaces each node and shows the edges. It is clear that some people are connected to only one or two others, but that some have many connections within this data set. It is likely that Jews in positions of power were aware of other Jews within their network, and I would be interested in researching further to explore the ways they may have communicated or leaned on each other for support. 

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_eigen.JPG “Eigen”)

The eigen function represents the influence of a node within its relationships to the nodes around it (similarly, an Eigenfunction in Quantum Mechanics is a function that describes all physical characteristics of a system and therefore holds all influential data within it). Jozef Rozanski, given an eigen value of 1, is highly connected and is related to other nodes with many connections. His connections have made him the “most influential” by the standards of this function, and may elucidate information about his influence within this network of Jewish leaders. 

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_close.JPG “Close”)

The closeness measurement shows here the average distance of a node to all other nodes. This can indicate a node’s centrality and may, in some cases, be related to spatial distance as well. There is no evidence that this data set could represent physical space, but those who have higher close values (ie are farther away) may hold positions in departments or organizations that are close to or far away from the majority of the other leaders in the network. Those located on the “outskirts” of this network may not work as closely with those with lower close values, as it may be more difficult to “travel” the relational distance between organizations and their leaders. 

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_between.JPG“Between”)

The between measurement shows the length of the shortest path that can be drawn without passing through an edge. This is a good representation of how easily the nodes are connection. The people represented by the red dots are clearly on the “outskirts” of the network, and therefore have the least “betweenness.” It is interesting to note that the only woman featured in this network has a between factor of 0. While Helena Wolinska-Brus may be more central in other networks of Jewish leaders, it is notable that based on my easily compiled data (from Wikipedia, the only source that would even give me this many Jewish leaders), she is located outside of, rather than between most nodes in the network. This may illuminate some understandings of gender as intersecting with Jewish ethnicity during the early postwar period in Poland. 

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_cluster.JPG “Cluster”)

The version of this network organized by cluster illustrates more specific “communities” within this network of Jews in positions of power. By understanding the data and visualizing the relationships, it is easy to see that the communities are structured based on the organizations in which multiple people held office. 

In the first network below, the NKVD (The People's Commissariat for Internal Affairs) is highly represented in one cluster, while the Politburo (leadership of the Polish United Workers’ Party), is represented by another cluster.

The second network below shows other organizations represented by the clusters, such as the State and Public Security Services. 

![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_quality%201.JPG “Quality #1”)
![alt text](https://github.com/introdh/intro-dh2018-kyliebritt/blob/master/images/britt_quality%202.JPG “Quality #2”)

Though it is important to admit I can’t produce any conclusions from this much research and such a small network, I can make conjectures about trends and patterns I could look for in an expansion of this research. 

The widespread appointment of Jews to positions of power within the Polish Communist Party and government (run by Soviets at the time) is surprising. Most Poles not directly involved in Communism and still reeling from the effects of WWII were not pleased with the new government, including Jews. Many Polish Jews were discouraged by the indifference and participation of ethnic Poles during the Holocaust. They were also disillusioned by the Soviets, who refused to admit that the Holocaust was a uniquely Jewish tragedy, claiming that the Jewish victims were “martyrs” for the Communist cause. In this way, it was surprising to me that many Jews accepted appointments to the highest positions in the Communist system. 

The disproportionate amount of Jews in power (who were overly representing in highly ranked positions) may have contributed to stereotypes of Jews. Some ethnic Poles saw Jews as money-grabbing, power-hungry, and selfish, and seeing Jewish leaders guiding the unpopular Communist party did not rub Poles the right way.

Other interesting conclusions or discoveries I could explore in the analysis include looking for other similarities between the people represented in my network besides ethnicity and status in an organization. For example, were most subjects in this network educated in a certain way? Were they from the same region? How were they affected by Soviet involvement in WWII? To look into these questions, I would have to expand on the dataset and learn more about the context in which these Jewish leaders were appointed to powerful positions.

## Limits & Benefits of Network Analysis:

Network analysis offers a way to visualize relationships and draw conclusions from a new way of representing data. The fundamentals of networks include nodes (the stuff to be connected) and edges (the connections). Where an analysis can really occur is in the novel way that those relationships are laid out, and may illuminate conclusions never before understood. 

In a network, the data can consist of multiple node types, such as authors and books, organizations and people, or cities and states.(Weingart, JDH, 2011)  These bimodal networks can illustrate the relationships between types of things, but can also lead to false conclusions or connections that appear to be true based on the sheer proximity when placed into a network together. 

There are different types of edges as well, which can represent different types of relationships, or be weighted to indicate the frequency or importance of a connection. Specific edge types can demonstrate how nodes are connected in a variety of ways, though it is important to have a fundamental understanding of the data used before comparing relationships that have no reason for comparison. 

Networking as a method of analysis can be compounded with other methods, such as with topic modeling. In his blog post “Topic Modeling and Networking,” Scott Weingart explains the ways topics of articles have been mapped to place them in a network of articles covering similar topics, which can be used to explore the trends of popular publications and research. (Weingart, personal blog, 2011) Network analysis can also be applied to spatial analyses to look into the ways in which a network is mapped over space. Not only can a network be used as a map, it can be applied to geographic space. In this way, network analysis and spatial mapping can be useful in multiple applications. (Weingart, personal blog, 2011)a

### Nodes & Edges Data

[Edges](https://docs.google.com/spreadsheets/d/16BiejTQ-EBtY1rNgLK5xjJhpWWgbjpkKEYVnLwB2eus/edit)

[Nodes](https://docs.google.com/spreadsheets/d/1GrqyD47xRuzlvX565bXSklmP95Mb3vl6Tr_Trl1GrVs/edit#gid=0)
