# Context
-----------
On this marketplace, sellers post photos and descriptions of items for buyers. Currently, sellers manually assign categories to their products, which is often unreliable due to human error. Given the small volume of items now, scaling up will require automating the category assignment process to streamline the experience for both sellers and buyers.

In this study, we need to evaluate the feasibility of building an automatic product classification engine using both the text and image data from product listings. The objective is to improve the user experience by automating the assignment of product categories.

# Tech used
--------------

* NLP : Bag-of-words, TF-IDF, Word2Vec, BERT
* Computer vision  : VGG16, data augmentation
* Dimensionality reduction: 2D projection for category clustering visualization
* Clustering validation: Category similarity analysis through clustering

