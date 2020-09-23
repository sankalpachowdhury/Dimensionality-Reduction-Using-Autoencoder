# Dimensionality-Reduction-Using-Autoencoder

* In this project the focus is reducing the dimensionality of data using autoencoder and comparative study with PCA.

* The sklearn Make_blob custom dataset is created, which consists of 20000 samples corresponfding having 50different dimesions correspond to 20 different clusters.

* The dataset is divided into Train(90%) and Test(10%) sets.

* The dimensionality of the data is reduced using PCA and Autoencoder based model, and corresponding clustering results of the dimensionally reduced data are plotted using scatter plot.

* The Autoencoder based model is much more efficient in Dimensionality reduction. Autoencoder architecture: 



* The PCA finds the linear relationship between feaures of the dataset, where the Autoencoder finds the non-linear relationship between data, thus it gives much more efficient result, as the combined feature is much more efficient to depict the combined effect of the dimensions.

* The details implementation of the code can be found in the collab [Notebook](https://github.com/sayan0506/Dimensionality-Reduction-Using-Autoencoder/blob/master/Dimensionality_Reduction_Using_Autoencoder.ipynb).

**Reference:**

1. [PCA reference](https://towardsdatascience.com/pca-using-python-scikit-learn-e653f8989e60)

2. [Autoencoder reference](https://towardsdatascience.com/autoencoders-made-simple-6f59e2ab37ef)

3. ["Reducing the Dimensionality of Data with Neural Networks" by G. E. Hinton and R. R. Salakhutdinov](https://www.cs.toronto.edu/~hinton/science.pdf).


**All the contents are made public, and all modifications, pull requests are welcome but please open issue and discuss before executing any major change in the repository.**


