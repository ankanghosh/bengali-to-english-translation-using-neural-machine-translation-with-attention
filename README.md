# bengali-to-english-translation-using-neural-machine-translation-with-attention
Bengali-to-English text translation using Neural Machine Translation (NMT) with attention.

# About the project
Bengali-to-English text translation using Neural Machine Translation with attention.
This is a Google Colab notebook for implementing Bengali-to-English text translation using NMT with attention. The work uses a language dataset provided by [Anki](http://www.manythings.org/anki/). The data is first cleaned, normalized, and preprocessed. An encoder with a Bidirectional Recurrent Neural Network (RNN), a decoder with a unidirectional RNN, with both of the RNNs implemented using Gated Recurrent Units (GRUs), and cross-attention is used to implement the model for the Bengali-to-English text translation. Training is performed using a TPU or Tensor Processing Unit. With an accuracy of about 65%, the performance of the model can be considered average. However, this is a quick and dirty implementation and there is definitely a decent scope for improvement.

It is important to note that this work is adapted directly from TensorFlow's tutorial on ["Neural machine translation with attention"](https://www.tensorflow.org/text/tutorials/nmt_with_attention) that shows how to use sequence-to-sequence or seq2seq models for Spanish-to-English text translation. The content (text, images, and code) from the original TensorFlow tutorial has been reused in most parts. The Colab notebook for this project specifies all of the modifications made in this Bengali-to-English text translation tutorial, as compared to TensorFlow's original Spanish-to-English text translation tutorial.

# Tools Used
Tools and libraries used in this project include TensorFlow, TensorFlow Text, Keras, typing, Einops, NumPy, scikit-learn, and Matplotlib.

# Who can benefit from the project?
Anyone can use the project to get started with the basics of text translation using TensorFlow.

# Getting Started
Anyone interested in getting started with Machine Learning, Deep Learning, or Natural Language Processing, specifically, text translation between language pairs using TensorFlow, RNNs / GRUs, and attention, can clone or download the project to get started.

# References
I have leveraged ChatGPT for guidance in terms of some concepts and to clarify doubts, both theoretical and code-based. However, I did not use ChatGPT to generate code. The most important points of reference for the project are as follows.
TensorFlow tutorial using NMT with attention for Spanish-to-English text translation. Link [here](https://www.tensorflow.org/text/tutorials/nmt_with_attention).

# Additional Notes
1. The dataset is available [here](http://www.manythings.org/anki/). If the dataset is taken down in the future, please feel free to reach out to me at ankanatwork@gmail.com if you would like to learn more about the data. However, I may not be able to share the dataset with you due to licensing restrictions.
2. The project is a basic one in nature and is not currently being maintained.
3. [Here](https://researchguy.in/bengali-to-english-translation-using-neural-machine-translation-with-attention/) is the blog post covering this work.

