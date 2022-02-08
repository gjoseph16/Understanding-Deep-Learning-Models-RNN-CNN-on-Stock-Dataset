# Understanding-Deep-Learning-Models-RNN-CNN-on-Stock-Dataset
Deep learning practitioners regard recurrent architectures as the default starting point for sequence modeling tasks. Convolutional networks, however, have been applied to sequences for decades,in speech recognition etc. While there have been multiple thorough evaluations of RNN architectures on representative sequence modeling tasks, we are not aware of a similarly thorough comparison of convolutional and recurrent approaches to sequence modeling. My study on these architectures showed how do the CNN and RNN perform on our stock dataset and why is CNN better than RNN. Evaluated models: Feedforward, LSTM, 2D CNN, 3D CNN, TCN

### Recent works:
- Combining the desirable aspects of RNN and CNN architectures
- Convolutional LSTM¹, Quasi-RNN model⁶, dilated RNN⁷
- Multiple thorough evaluations of RNN architectures on representative sequence modeling tasks⁸

Current paper:
Focussed on a comparison of generic convolutional (TCN)² and recurrent architectures (LSTM and GRU)²

### Code:

src/DL on Stock Data

### Comparison and explanation:

File 'PPT_DL on Stock Data'

### 5 Stock datasets: 

Folder 'Dataset'

### Conclusion:

The experimental results indicated that TCN models substantially was outperformed by 2D_CNN but performed better than Feedforward and LSTM.
A simple convolutional architecture is more effective across sequence modeling on stock data than recurrent architectures.

