---
date: '2'
title: 'Face-Recognition'
cover: './demo.jpg'
github: 'https://github.com/05rs/Face-Recognition'
# external: 'https://github.com/05rs/Face-Recognition'
tech:
  - Python
  - OpenCv
  - DLIB
  - TensoFlow
---

End to End Face-Recognition follows the approach\
described in [[1]](https://arxiv.org/abs/1503.03832) with modifications inspired by the\
OpenFace project.

Keras is used for implementing the CNN, Dlib and\
OpenCV for aligning faces on input images.

Semi-hard triplet loss and online semi-hard triplet\
 generator are used for further fine-tuning.

Face recognition performance is evaluated on a small\
subset of the LFW dataset which you can replace with\
your own custom dataset\

e.g. with images of your family and friends if you want to\
further experiment with the notebook.

• Got 97% F1 score & 99.5% accuracy after fine-tuning\
on LFW sub dataset.
