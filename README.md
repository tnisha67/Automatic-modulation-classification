# Automatic-modulation-classification
## Abstract: 
Neural networks have received a lot of attention in the recent years due to its superior performance in classifying data with
complex structure. In this project, the feasibility and effectiveness of applying deep learning algorithms for automatic recognition of
modulation type of the received signals is investigated. The test results show that statistical features extracted from input signal data
significantly improve the performance of artificial neural networks (ANNs). Nonetheless, convolutional neural networks (CNNs)
have proven to achieve performance that outperforms the expert-based approaches. Moreover, in order to reduce the training
time, principal component analysis (PCA) method is applied to decrease the dimension of the training data set. Finally, the
relationship between reducing the dimension of training data set and loss in classification accuracy is investigated by identifying
the representative SNR values for both ANN and CNN architectures.

## Conclusion:
In this work, we proposed using fast deep learning algorithms to differentiate between 11 different modulation types, with
high classification accuracy over a wide range of SNR values. ANN and CNN architecture networks were studied in a variety
of settings. The results demonstrate that compared to the well known expert feature based ANNs, CNNs are work quite well in
low levels. Hence for robust classification at low SNR, CNNs are a preferred choice to rely on. One major challenge on using
CNN is the long training time. This creates a bottleneck towards the feasibility of applying such algorithms in real-time, where
online training is needed to adapt the network architecture to changing environmental conditions. As a result, both ANN and
CNN can be implemented and trained to provide good performance, the option, however, is dependent on the specifications
of the classifier and other constraints.
