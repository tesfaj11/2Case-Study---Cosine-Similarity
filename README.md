# 2Case-Study---Cosine-Similarity

Cosine Similarity Case Study
Objective
The main goal of this case study was to practice calculating cosine similarity between samples in a dataset. We used cosine similarity to compare records numerically and visually understand how similar they are to one another. This concept is especially helpful for tasks like record matching or NLP (natural language processing), where it's important to measure how closely related two items are.

What I Did
Loaded a dataset of 2,000 records with X, Y, and Z features.

Normalized the data so that the values are on the same scale before computing similarity.

Used cosine_similarity() from scikit-learn to compute a 2,000 x 2,000 similarity matrix.

Visualized the similarity matrix using a heatmap to see how samples compared to each other.

Focused on plotting just the first 100 samples for clearer interpretation.

