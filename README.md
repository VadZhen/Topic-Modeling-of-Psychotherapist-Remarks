# Topic-Modeling-of-Psychotherapist-Remarks

[Project.](https://github.com/VadZhen/Topic-Modeling-of-Psychotherapist-Remarks/blob/main/GITHUB_Classic_modern_Eng_sessions(BertTopic)_(United_model).ipynb) |
[Article.](https://github.com/VadZhen/Topic-Modeling-of-Psychotherapist-Remarks/blob/main/fpsyt-3-1608163.pdf)

**Description of the project:** This project applies BERTopic, a topic modeling technique, to two corpora of psychotherapist remarks—one from a classical approach and one from a modern approach. The goal is to analyze the differences in topics between the two sets of remarks within a psychotherapeutic context. 

**Data:** The primary source material consisted of publicly available recordings of psychotherapeutic sessions posted on YouTube. In addition, textual transcripts of Carl Rogers' sessions were used. The materials were divided into two datasets: sessions conducted by classical and by modern therapists. The sample of classical psychotherapeutic sessions includes 25 transcripts and recordings, while the sample of modern sessions comprises 97 ones. Classical therapists are represented by session transcripts and recordings of the founders of therapeutic schools – Carl Rogers, Fritz Perls, and Albert Ellis – while modern therapists are represented by recordings of 37 unique practitioners. The samples of classical and modern psychotherapeutic sessions involved 22 and 66 unique clients, respectively.

**Purporse** is to conduct and compare topic modeling of therapeutic sessions between modern and classical therapists

**Methods**: The BERTopic text data topic modeling library was used in the research process. Pre-trained embeddings from the Sentence-Transformer model 'paraphrase-multilingual-MiniLM-L12-v2' were used to create a vector space. UMAP (Uniform Manifold Approximation and Projection) method was applied to reduce the vector space's dimensionality, and HDBSCAN (Hierarchical Density-Based Spatial Clustering of Applications with Noise) was used to cluster the data. The topic representation of the clusters was made using BERTopic's built-in c-TF-IDF method for assessing the importance of words within the context of document clusters, and its optimization was primarily achieved through the use of large language models like GPT.

**Tasks:**
- Perform preprocessing of the therapeutic session corpora, differentiating between modern and classical therapists.
- Construct a vector space from the processed corpora.
- Implement dimensionality reduction on the vector space.
- Conduct clustering analysis on the resulting vector space.
- Generate topic representations.
- Assess and optimize the identified topic structures within therapeutic sessions from modern and classical therapists.
- Compare the topic structures derived from the therapeutic sessions.

**Coclusion:** This study was conducted to analyze the topics of therapist remarks within a psychotherapeutic context. For this purpose, BERTopic, a powerful ML-based topic modeling technique, was applied to distinguish topics from unstructured dialogue of therapists with their clients within psychotherapy sessions. Topic modeling with a meticulous iterative process of optimizing topic structure based on expert assessment was applied to corpora of therapist remarks from both classical and modern therapeutic approaches, yielding 43 and 46 distinct topics, respectively. Analysis of semantic proximity within these topic sets identified prominent themes in the discourse of both therapist groups, likely reflecting core client concerns. These key topics include fear, anger, anxiety, familial and peer relationships, as well as issues related to development, self-esteem, and other psychological challenges.

**Detailed information about the study, including its motivation, methodology, and results, has been published in the prestigious scientific journal [Frontiers in Psychiatry](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2025.1608163/full):**

Vanin A, Bolshev V and Panfilova A (2025) Psychotherapist remarks’ ML classifier: insights from LLM and topic modeling application. Front. Psychiatry 16:1608163. doi: 10.3389/fpsyt.2025.1608163
