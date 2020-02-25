# Graph-Analytics

Graph theory has been around for quite some time and we are seeing majority of the optimization problems now a days use graph theory as a base - dijkstra's algorithm etc.

And this is now slowing moving into the analytics space as well. Many inddustries are starting to utilize graph theory for a variety of analytics problems.

We concetrated on one area where we saw a huge potential - Organizational Network Analysis(or as people like to call it - HR Analytics).

We wanted to understand the inherent relationships within a company and how to construct as network of employees which can be leveraged for a variety of requirements like - Identifying the most influencing person, identifying the most effective team, identifying the weakest links between the clients and the internal teams etc.

Since company data is very confidential and is very difficult to get hold of we used the data that is on par with employee details - our MSBA program whatsapp group chat.

We defined a node as a member and defined the edge as a relationship, which is established between members by defining a condition - there is a relationship between 2 members if their messages are within a gap of 5 - considered as the 2nd memeber replied to the first member.

We added demographic level attributes to the node and defined strength of the edge(relationship) based on how many times we have see these 2 set of members interated or replied to each others message.
