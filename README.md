# neural-disaggregator

Implementations of NILM disaggegregators using Neural Networks, using [NILMTK](https://github.com/NILMTK/NILMTK) and Keras.

Most of the architectures are based on [Neural NILM: Deep Neural Networks Applied to Energy Disaggregation](https://arxiv.org/pdf/1507.06594.pdf) by Jack Kelly and William Knottenbelt.

The implemented models are:
- Denoising autoencoder (DAE) as mentioned in [Neural NILM](https://arxiv.org/pdf/1507.06594.pdf) (see [example](https://github.com/OdysseasKr/neural-disaggregator/blob/master/DAE/DAE-example.ipynb))
- Recurrent network with LSTM neurons as mentioned in [Neural NILM](https://arxiv.org/pdf/1507.06594.pdf) (see [example](https://github.com/OdysseasKr/neural-disaggregator/tree/master/RNN/RNN-example.ipynb))
- Recurrent network with GRU. A variation of the LSTM network in order to compare the two types of RNNs (see [example](https://github.com/OdysseasKr/neural-disaggregator/blob/master/GRU/GRU-example.ipynb))
- Recurrent network with "lookback" (LookbackGRU). A variation of the GRU network in that uses a window of data as input.
- Short Sequence to Point Network as mentioned in [paper](https://dl.acm.org/citation.cfm?id=3201011). Based on the architecture in [original paper](https://arxiv.org/abs/1612.09106) (see [example](https://github.com/OdysseasKr/neural-disaggregator/blob/master/ShortSeq2Point/ShortSeq2Point-example.ipynb))
