Here is the overview of the code. 

In the file 6000D_project_KG_construction.ipynb, it uses the data of .csv files to construct a knowledge graph with neo4j database, which includes nodes and edges. Then it will generate the basic idea to build a csv file for the GNN input.

In the file 6000D_project_Node_Classification.ipynb, it uses the Cora dataset, a citation network among papers to make the node classification to classify each publication into one of seven classes. Each publication is represented by a bag-of-words vector. It uses MLP and GNN model for comparison.

In the file 6000D_project_Link_prediction.ipynb, it uses the knowledge graph which has built before and use GNN model to predict whether the random 2 company nodes in the graph have relationship and which kind of relationship they have. 