---
layout: post
---

# Data representation in Process Mining

## Survey and Benchmark on Trace Encoding Methods

Paper published at the [EAAI](https://www.sciencedirect.com/science/article/pii/S0952197623012125) journal.

In order to guide researchers and practitioners to choose the right algorithm according to their goals, we proposed new evaluation metrics and performed an extensive experimental evaluation to serve as a benchmark.
The metrics cover what we believe is essential for encoding in PM: expressivity of the encoded data, scalability w.r.t. the event log cardinality, correlation between performances of the encoding algorithm performance and the PM task, and domain agnosticism regarding PM tasks.
The benchmark focuses on the anomaly detection task and assesses 27 encoding methods through hundreds of event logs. We discuss future directions based on our findings. Therefore, we also expect the proposals and insights presented in our work can be leveraged for other PM tasks.

![Encoding Survey](/assets/img/posts/encoding/encoding.jpeg)
![Encoding Survey](/assets/img/posts/encoding/download.png)


---

## Enhancing Predictive Process Monitoring with Time-Related Feature Engineering

Accepted at the [CAiSE'24](https://link.springer.com/chapter/10.1007/978-3-031-61057-8_5) conference.

Predictive process monitoring plays a critical role in process mining by predicting the dynamics of ongoing processes. Recent trends employ deep learning techniques that use event sequences to make highly accurate predictions. However, this focus often overshadows the significant advantages of lightweight, transparent algorithms. This study explores the potential of traditional regression algorithms, namely kNN, SVM, and RF, enhanced by event time feature engineering. We integrate existing and novel time-related features to augment these algorithms and compare their performance against the well-known LSTM network. Our results show that these enhanced lightweight models not only compete with LSTM in terms of predictive accuracy but also excel in scenarios requiring online, real-time decision-making and explanation. Furthermore, despite incorporating additional feature extraction processes, these algorithms maintain superior computational efficiency compared to their deep learning counterparts, making them more viable for time-critical and resource-constrained environments.

![Feature engineering](/assets/img/posts/encoding/engineering_pipeline.png)


[back](/)
