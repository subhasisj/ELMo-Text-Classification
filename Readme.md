# Sentiment Classification using ELMo Embeddings

Followed a blog to create bi-LSTM model that that takes ELMo embeddings as inputs.
-   Trained it on GPU. 
-   Used Cached tools to fasten the process of getting embeddings.
-   Saved_model format does not work with tf hub models using Lambda layer. (Have to check further)
-   __note-to-self__: when using TF hub models, have to disable eager execution and default behavior
