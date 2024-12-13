# SymptoNet-Network
A Project in Network Analysis leveraging NLP techniques to build a Network of Medical Conditions with links representing diseases with similar symptoms.


The " SymptoNet " project addresses the misdiagnosis problem by constructing a disease network based on shared symptoms, moving away from traditional bipartite graph models. By using web scraping techniques, data on symptoms and diseases were collected from Wikipedia, and a network, SymptoNet, was created using cosine similarity measures to establish edges based on symptom semantic similarity. The network comprises 935 nodes and 65,610 edges, demonstrating a dense interconnectivity with a clustering coefficient of 0.6148 and positive assortativity. The network’s visualization in Gephi revealed key patterns of symptom overlap and highlighted central diseases with high betweenness centrality, indicating their potential role in misdiagnosis. The analysis showed a modular network structure with significant implications for understanding disease
interrelationships and improving diagnostic accuracy.

![image](https://github.com/user-attachments/assets/c7bca0f1-a4e2-4167-8953-f6779f92230a)
Here, we see the entire network, presenting a clear overview. In this network visualization of SymptoNet, observable patterns appear from the complex
web of disease interconnections, showcasing shared symptoms and suggesting potential underlying biological relationships. Patterns within Clusters: The clustering of diseases reveals an interesting symmetry of symptomatology. For example, the red cluster is densely populated and tightly knit, possibly indicating a set of diseases with a high degree of symptom overlap, such as systemic or core body afflictions. In contrast, other
clusters, like the one highlighted in yellow, suggest diseases with more specific and localized symptoms, potentially representing less commonly associated conditions or more specialized disease categories.


![image](https://github.com/user-attachments/assets/eac73e1a-370f-4f30-9105-30ce980e11c1)
This showcases the details of one of the modules, representing cardiovascular and respiratory diseases clustered by Gephi. The larger nodes, like ”pneumonia,” ”coronary artery disease,” and ”dilated cardiomyopathy,” are prominent, indicating these conditions have symptoms that overlap
with many other diseases within this category, highlighting their central role in cardiopulmonary and systemic symptomatology.

![image](https://github.com/user-attachments/assets/d069c4b5-8f75-4a4c-8df3-4314d5747d01)
The clustering coefficient for the medical condition network is notably high at 0.6296, suggesting a pronounced propensity for local clustering compared to the Erdos-Renyi network, which exhibits a relatively low clustering coefficient of 0.1576. This indicates that the real-world network is more likely to form tightly knit groups, suggesting that interconnected nodes—representing medical conditions—are likely to cluster together, potentially indicating related conditions or comorbidities.


