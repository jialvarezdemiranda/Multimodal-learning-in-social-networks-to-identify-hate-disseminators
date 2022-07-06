# Multimodal-learning-in-social-networks-to-identify-hate-disseminators

1) Authors
2) Abstract


## 1) Authors
José Ignacio Álvarez de Miranda Rodríguez
Javier Huertas Tato

## 2) Abstract
Currently, the detection of hate speech in online social networks is mainly based on textual
analysis, ignoring other sources of information such as images or connections between
network users. In this Final Degree Project, we combine Natural Language Processing
and graph theory to detect hateful disseminators in online social media. By combining
Transformer neural networks with graph attention networks (GATs), the classification
of these users should be more robust than using exclusively text or network topology
separately.
Two multimodal architectures are proposed to combine both information sources. In the
first one, the Transformer model generates a representation or embedding of the text that is
passed to the GAT model to obtain a prediction. In the second version of the architecture,
both Transformer and GAT provide an embedding that is combined to form a multimodal
representation of the information, from which the predictions are obtained.
To empirically test the performance of these systems, we rely on manually labeled
historical Twitter data, from which we have extracted a graph with connections between
users who retweet or mention each other. In this network, there are both hateful and
normal users, who have written a series of texts over time as well as personal descriptions.
The work carried out consists of a comparison between the performance of the models in
classifying the users of this network.
Experimentation has proven that the first architecture is not able to improve the quality
of the unimodal models, while with the second one F1 score values of around 0.7 are
achieved.
Keywords: Natural language processing, social networks, Twitter, graph theory, graph
attention network, Transformer, embeddings, hate dissemination, multimodal analysis.
