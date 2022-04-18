# FODBMS_END-TERM_PROJECT_GEPHI

A social network of LastFM users which was collected from the public API in March 2020. Nodes are LastFM users from Asian countries and edges are mutual follower relationships between them. 
The vertex features are extracted based on the artists liked by the users. The task related to the graph is multinomial node classification - one has to predict the location of users. This target 
feature was derived from the country field for each user.                                                                
<img width="505" alt="image" src="https://user-images.githubusercontent.com/93238926/163675708-3d66dc6f-6436-4bdf-8fe3-c5aa6c4ca6d2.png">
![image](https://user-images.githubusercontent.com/93238926/163675924-8421a7ed-5f6e-464c-b741-d9ac0325dbb2.png)

LastFM social network Algorithms used - Fruchterman Reingold, Force Atlas 2, Measures of centrality like betweenness, and modularity was also calculated.

![image](https://user-images.githubusercontent.com/93238926/163675928-84003875-ed17-43db-b8cd-ef4755321936.png)
Ques 1: What are important entities from different POVs?
Ans 1: The importance of a particular node can be decided through degree and betweenness.
Nodes with labels 7237, 3450,524, 5101, and many more are important as these have more than 100 connections which we found using the degree range filter.

Ques 2: How many communities exist within the network?
Ans2: A total of 24 communities exist. From which Magneta, Green, Black, Blue & Orange dominate the most.

Ques 3: Why a community is different from other communities?
Ans 3: For finding why a community is different from other communities we combine 2 filters of modularity class & topology.
These are the insights where we used the data laboratory in Gephi.

Ques3. Examine the relationship of nodes within and outside communities.

Ans3.
The relationship between the top 5 dominating communities is very strong as it is visible and other communities do not have that strong relationship.

Ques 4. What are the important insights?

Ans 4. Few of the nodes that had more than 100 connections were not connected with each other.

