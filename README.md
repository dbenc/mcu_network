# Acquaintance Network of the Marvel Cinematic Universe

The goal of this project is to obtain the acquaintance network of the characters in the MCU and calculate some basic characteristics in SQL, thus each task should be carried out in SQL, unless stated otherwise. To visualize the results you can use Python, gnuplot or any software of your choice. Make publication quality plots: Title, marked axes, legend if needed etc.. Use comments in your code to explain important steppes, so if you opened your project six months from now you should still understand what's going on. Explain in a report what you did, and what do you think it means based on the plots you've created and your network science knowledge. Provide sources if necessary.

Consider two characters to be connected if they have at least one line in the same movie. The database doesn't contain whether two characters talk to each other when they say their lines, so this is a slight simplification. The resulting network should be unweighted and undirected.

Tasks:

1. Download the database from [Kaggle](https://www.kaggle.com/pdunton/marvel-cinematic-universe-dialogue).

2. Load relevant tables into your database for creating a character network. Preprocess/clean tables as needed before this task in your chosen environment. Assign each character a UUID.

3. Create the link list of the acquaintance network! You can use any environment to calculate permutations if you prefer not to do it in SQL.

4. Visualize the network you've obtained! Nodes with more links should be bigger and labeled according to the characters they represent. Who are the most well-connected nodes in this network? Are they the main characters of the MCU?

5. Calculate the degree distribution and the average degree of the network. Visualize the results! What does the shape of the distribution tell you about this particular network?

6. Calculate the clustering coefficient for each node, obtain the average clustering, and also calculate the global clustering coefficient! Visualize the results! How does the distribution look like? How does the average clustering compare to the global clustering?

7. Measure the degree correlation function of the network! Visualize the results! What does this tell you about the assortativity of the network?

![full_marvel_net](https://github.com/dbenc/mcu_network/assets/40838667/6259e081-199b-47e6-b707-6b73c7643dc1)
