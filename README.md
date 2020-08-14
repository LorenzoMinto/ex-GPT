# ex-GPT: An Extractive-Abstractive Summarization Framework with a Sentence Embeddings Twist

We propose a summarization pipeline to produce abstractive summaries of news articles. We first perform an extractive step at sentence level, in order to filter the most relevant sentences in the article. We use this extractive summary as conditioning to fine-tune a GPT- 2 model to perform a further abstractive step. Furthermore, we investigate on the shortcomings of the ROUGE metric and propose an alternative summarization evaluation metric and extractor model relying on sentence embeddings. We show that using sentence embeddings similarity measure in the extraction step captures richer latent content and can lead to improved ROUGE scores. Finally, we also show that our pipeline produces coherent and fluent end-to-end summaries.

This project was carried out as a part of the NLP course during my MSc in Machine Learning @UCL.
