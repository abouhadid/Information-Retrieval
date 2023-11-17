# Information-Retrieval
#### Advanced Natural Language Processing module @ AALTO University
----------------------------------------------

Yassine ABOU HADID

----------------------------------------------
An ongoing challenge in news consumption is the prevalence of redundancy, where identical news stories are reported by different sources. This repetition not only leads to information overload but also diminishes the diversity of perspectives available to readers. Exploring ways to streamline and curate news content to minimize redundancy could enhance the efficiency and variety of news consumption experiences.

In this context, this project aims to explore and compare 2 approaches:
* Unsupervised ML approach: treating the information retrieval problem as a clustering problem,
* Graph based approach: if we build a graph network to connect all the titles together, the major news must be the nodes with the highest degree all we need to do is to use a traversal algorithm to get these nodes.
----------------------------------------------

**DATA:**
The data are news headlines scrapped from different mainstream websites including BBC, Reuters, Al Jazeera..

----------------------------------------------

**GRAPH CONSTRUCTION:**
Construct Graph as follows: vertices are titles indices and edges are the number of common words between titles (if ≠ 0)
