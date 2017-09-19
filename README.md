# Spatial Transformer Networks with IDSIA-like classifier for German Traffic Signs Dataset classification

![](https://raw.githubusercontent.com/dnkirill/stn_idsia_convnet/master/imgs/transformed_traffic_signs.png)

This repository introduces a TensorFlow-based implementation of STN + IDSIA classifier that is applied to [GTSRB (German Traffic Signs Recognition Benchmark)](http://benchmark.ini.rub.de/) dataset.

This repository provides the source code and the context for my blog post on Medium:
[https://medium.com/@kirilldaniluk/convnets-series-spatial-transformer-networks-cff47565ae81](https://medium.com/@kirilldaniluk/convnets-series-spatial-transformer-networks-cff47565ae81)

**The notebook with code: [STN_IDSIA_German_Traffic_Signs](stn_idsia_german_traffic_signs.ipynb)**

### STN Transformation Demos:

Grayscale:

![](https://raw.githubusercontent.com/dnkirill/stn_idsia_convnet/master/imgs/animation.gif)

Color:

![](https://raw.githubusercontent.com/dnkirill/stn_idsia_convnet/master/imgs/animation3.gif)

### Acknowledgements:
1. [Udacity Self-Driving Car Nanodegree](https://www.udacity.com/drive) for the inspiration and the inital idea for this project.
2. [TensorFlow STN Transformer implementation](https://github.com/tensorflow/models/blob/master/transformer/) which I use throughout this project.
3. [Moodstocks' Torch implementation of STN + IDSIA](https://github.com/Moodstocks/gtsrb.torch) for the solution and introduction to STNs.
4. Authors of the [original paper on spatial transformer paper](http://papers.nips.cc/paper/5854-spatial-transformer-networks.pdf).