- Data re-scaling:
It is important to use techniques which normalize our data, some machine learning models such as linear regression may depend on the values of the adjusted dimensions. So Log scaling, min-max, AB re-normalization, standard deviations to the mean, etc must be considered.


- Dimensional reduction:

Principle component analysis (PCA) is the best *linear* technique (a basis-change) to reduce the number of components. 

![[PCA_visual.png]]

It consists of analyzing the [[Covariance]] of many variables and defining new dimensions as linear combinations of previous features:
$$ cov(x,y)=\sum_{n}{( x_{n}-x_{mean}) \left( y_{n}-y_{mean} \right)}$$