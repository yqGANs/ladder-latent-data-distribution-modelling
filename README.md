# ladder-latent-data-distribution-modelling
In this paper, we show that the performance of a learnt generative model is closely related to the model's ability to accurately represent the inferred \textbf{latent data distribution}, i.e. its topology and structural properties.  We propose LaDDer to achieve accurate modelling of the latent data distribution in a variational autoencoder framework and to facilitate better representation learning. The central idea of LaDDer is a meta-embedding concept, which uses multiple VAE models to learn an embedding of the embeddings, forming a ladder of encodings. We use a non-parametric mixture as the hyper prior for the innermost VAE and learn all the parameters in a unified variational framework. From extensive experiments, we show that our LaDDer model is able to accurately estimate complex latent distribution and results in improvement in the representation quality.
