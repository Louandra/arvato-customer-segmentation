# arvato-customer-segmentation

## Motivation
The aim of the project is to enable a mail-order company selling organic products to acquire customers more efficiently by using a targeted approach. Using the provided demographics data of the population and the company's customer base, we need to match the attributes of the wider population to those of the customers in order to figure out which are potential clients for the mail order company.

## Libraries
- Pandas
- SciKit-Learn
- UMAP
- DBSCAN

## File in repository
Arvato Project Notebook - Jupyter notebook containing project code.

## Data
The data used in the project was provided by Arvato and Udacity

## Results
- Clustering model: The chosen clustering model produced 5 clusters where the customer base was overrepresented in custers 0 and 2.
- Prediction model: A GBM model was used. The final prediction model produced a recall of 0.22 and and a accuracy of 0.83.

The results are detailed in this blog post: https://medium.com/@a.louandra/udacity-arvato-customer-segmentation-fed89156afe7

## Future work
Other model tuning and feature engineering approaches need to be attempted in order to improve the results

## Acknowledgements
- Bertelsmann/Arvato
- https://umap-learn.readthedocs.io/en/latest/clustering.html
- https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html
- https://stats.stackexchange.com/questions/22569/pca-and-proportion-of-variance-explained

  


