# Mathematical-Graph-Final-Python-Project
mathematical graphs
# I think  A-star algorithm is huge overkill here. 

In this part we have done find_shortest_path, which returns: 
"shortest path between them has the minimum total weight
here they ask the opposite, just create a copy of the same graph and set weight values to (SOME_BIG_NUMBER-weight),  and run find_shortest_path.
#I think , to resolve question 4,we have to do all functions of graph class,  then
1) __add__(self, other) - make a copy of graph
2) change weights as I've wrote (you'll need to go over all pairs of nodes get weight and set it to (BIG_NUMBER - weigth) )
3) run find_shortest_path(self, frm_name, to_name) on a new graph.
