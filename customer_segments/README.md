# Creating Customer Segments 

## Overview 
Reviewed unstructured data to understand the patterns and natural categories that the data fits into. Used multiple algorithms and both empirically and theoretically compared and contrasted their results. Made predictions about the natural categories of multiple types in a dataset, then checked these predictions against the result of unsupervised analysis. 

**Keywords**: clustering, pca, feature selection, k means, gaussian mixture model 

## Libraries 
This project was done using **Python 3.5** and the following Python libraries: 

- Numpy 
- Pandas 
- Matplotlib 
- Scikit-Learn 

## Data  
The dataset is a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers). 

**Features** 

- `Fresh`: annual spending (m.u.) on fresh products 
- `Milk`: annual spending (m.u.) on milk products  
- `Grocery`: annual spending (m.u.) on grocery products 
- `Frozen`: annual spending (m.u.) on frozen products 
- `Detergents_Paper`: annual spending (m.u.) on detergents and paper products 
- `Delicatessen`: annual spending (m.u.) on and delicatessen products 
- `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal) 
- `Region`: {Lisnon - 1, Oporto - 2, or Other - 3} (Nominal) 