# MILNET in TensorFlow Keras
MILNET implementation in TensorFlow Keras. This is a machine learning model for sentiment classification.



### Model

The model is MILNET described in _Stefanos Angelidis and Mirella Lapata, Multiple Instance Learning Networks for Fine-Grained Sentiment Analysis_. The model features the following points.

- Multi instance learning on sentence level or EDU level
- Segment features extracted by convolutional layers with different kernel sizes
- Attention weights generated by GRU layer
- Segment level classification and merged by attention weights