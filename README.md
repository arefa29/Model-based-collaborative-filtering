# Model based collaborative filtering

<h3 style="color:#FA5F55;">Using Singular Value Decomposition (SVD) </h3>
<h1 ></h1>

Memory-based recommendation systems are not always as fast and scalable as we would like them to be and are memory intensive, especially in the context of actual systems that generate real-time recommendations on the basis of very large datasets. To achieve these goals, model-based recommendation systems are used.

Model-based recommendation systems involve building a model based on the dataset of ratings. In other words, we extract some information from the dataset, and use that as a "model" to make recommendations without having to use the complete dataset every time. This approach offers the benefits of both speed and scalability.

This Jupyter notebook contains a simple implementation of Model based system using SVD.
