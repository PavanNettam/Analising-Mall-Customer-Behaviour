# Analising-Mall-Customer-Behaviour
Mall Customer Behavior is been classified into clusters for better marketing techniques with K-Means++ clustering.

<h2>Dataset Description</h2>
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

<h2>Elbow Method</h2>
The optimal number of clusters is choosen by ploting the elbow graph.
<br>
<img width="447" alt="Elbow_Method" src="https://user-images.githubusercontent.com/79460453/154484664-c23a9a96-26cd-413b-b1f5-a589e5098d4a.png">
Choice of number of clusters:<br>
After the number of clusters exceed 5, wcss droping rate reduces significantly.<br>
Thus we choose n_clusters=5 to train the model

<h2>Visualizing the clusters</h2>
<img width="430" alt="Cluster" src="https://user-images.githubusercontent.com/79460453/154485215-578ffaed-4505-4c28-a1b6-321bdfbf3cd2.png">

<h2>Classing a new customer into a cluster</h2>
New customer with Annual income = 80 K$ and spending score of 15 is analised:<br>
<img width="430" alt="New_Customer" src="https://user-images.githubusercontent.com/79460453/154485493-a4583bfe-bd8f-4cb9-bd7e-6258b71f5a63.png">

<h2>Conclusions</h2>
<ul>
<li>The Green cluster contains the customers  who earn more and spend more, thus brand new variety of products can be advertesed for such customers.</li>
<li>The Blue cluster are contains the customers who earn more but spend less, thus these customres must be attracted with sophisticated marketing techniques.</li>
<li>The Black cluster contains the customers who earn less but spend more, thus we shall not target such customers anymore.</li>
<li>The Red and the Pink clustes contains the customes who does not deserve light, as they are in right position in the graph.</li>
</ul>
