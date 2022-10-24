
Perform a link/edge prediction using Colab </br>
 
I used Cora dataset (paper = node, citation = link/edge), to predict connection between targeted nodes.  </br>

By using random forest classifier, I got accuray of 0.72 </br>
Colab Link: https://colab.research.google.com/drive/12yOvQKk6q718osYJbxeZreirguMXShL9 </br>

-------------------------------------------------------------------------</br>
On the second try (file: link_prediction), I used antoher GNN model, GraphSAGE (with Convelutional layers). </br>
In this exercise, I split data to positive and negative samples for prediction. I used GraphSAGE for graph embedding. One of the mian difference between GCN and Graphsage is the aggregation function (AGG), which was the mean aggregator in GCN. After we convert graph to computable format, we can find similarity score between edges. The dataset is same. </br>
The AUC is about 0.87.
</br>
Colab Link: https://colab.research.google.com/drive/1lmmSfDMhlq1Q1-c1YeuG7ngNyz9HjQ8y

