# Differential Privacy

Differential privacy (DP in short) is a mathematical-rigorous definition of privacy that can be applied to a wide-class of algorithms in machine learning. The main motivation of DP is to make meaningful privacy-preserving guarantees for individuals whose personal information might be in a dataset. A chief goal in DP is to provide secure datasets or learning algorithms which allow to extract meaningful information about a population without compromising the information of the members of the dataset. In a sense, one wants to offer a learning algorithm which is *robust* or *stable* under small changes in the membership status of individuals in a dataset. 

DP is still in its early years and in this repository we study a promising approach: **Private Aggregation of Teacher Ensembles (PATE)**. We explain the main concepts behind this strategy as well as the basic concepts of DP in the notebook `basics.ipynb`. As a case of study we compare the implementation of PATE in the MNIST and Fashion MNIST databases in the notebooks `dp_mnist.ipynb` and  `dp_fashion_mnist.ipynb`.

