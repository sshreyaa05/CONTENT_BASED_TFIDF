### Building a Content-Based Recommender System Using Discriminative Keywords and Gini Index/Entropy

### Overview:
This project focuses on developing a content-based recommender system using hypothetical datasets to identify discriminative keywords from documents. The goal is to apply measures such as the Gini Index and Entropy to determine the most relevant keywords for recommendation, based on their frequency distribution across documents. The project utilizes two datasets:
1. A small dataset with 8 documents and 10 keywords, each having ratings of 0, 1, and 2.
2. A larger dataset with 25 documents and 75 keywords, where ratings range from 0 to 3.
The project involves calculating the Gini Index and Entropy for the respective datasets to identify the most discriminative keywords, then computing the Term Frequency (TF) for these keywords across the documents.

### Result:
1. Dataset 1 (8 Documents, 10 Keywords, Ratings 0, 1, 2): The Gini Index was calculated for each keyword to assess how well it discriminates between documents based on its frequency. After calculating the Gini Index for all keywords, the 5 most discriminative keywords were selected. The term-frequency for these keywords was then computed, revealing the most significant terms per document for recommendation purposes.

2. Dataset 2 (25 Documents, 75 Keywords, Ratings 0, 1, 2, 3): In the larger dataset, the Entropy measure was used to determine the keywords that provide the most information gain, as Entropy accounts for the distribution of the keyword ratings across the documents. The 10 most discriminative keywords were identified, and the Term Frequency for these keywords was computed, allowing the creation of a content-based recommender system that could suggest documents with similar keyword profiles to users.

### Conclusion:
By leveraging the Gini Index in the first dataset and Entropy in the second dataset, we were able to extract the most discriminative keywords for each scenario. The use of Term Frequency (TF) allowed us to understand the distribution of these keywords in the documents, providing the foundation for a content-based recommender system. The results demonstrated that both keyword selection methods were effective in determining relevant content, with Entropy offering a more nuanced approach for handling the larger dataset. This recommender system can be scaled for larger, more complex datasets, offering personalized content suggestions based on document similarities.



