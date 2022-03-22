# Interpreting Class Conditional GANs with Channel Awareness

![image](./docs/assets/teaser.jpg)
**Figure:** Novel applications enabled by interpreting class conditional GANs, including (1) single-channel image editing, (2) category hybridization, (3) fine-grained semantic segmentation, and (4) category-wise synthesis performance evaluation.

> **Interpreting Class Conditional GANs with Channel Awareness** <br>
> Yingqing He, Zhiyi Zhang, Jiapeng Zhu, Yujun Shen, Qifeng Chen <br>
> *arXiv preprint arXiv:2203.11173*

[[Paper](https://arxiv.org/abs/2203.11173)]
[[Project Page](https://yingqinghe.github.io/interclassgan)]

This work targets understanding how a class conditional GAN manages to unify the synthesis of various classes. For this purpose, we take a close look at the widely used class-conditional batch normalization (CCBN) layer, and observe that, followed by the ReLU activation, CCBN helps distribute the categorical information to feature channels. That says, for a particular channel, it makes varying contribution to synthesizing different categories. Thanks to such an interpretation, we investigate the potential of class conditional GANs in four novel applications, including (1) single-channel image editing, (2) category hybridization, (3) fine-grained semantic segmentation, and (4) category-wise synthesis performance evaluation. Qualitative results can be found at our [project page](https://yingqinghe.github.io/interclassgan).

## Code Coming Soon

## BibTeX

```bibtex
@article{he2022interpreting,
  title   = {Interpreting Class Conditional GANs with Channel Awareness},
  author  = {He, Yingqing and Zhang, Zhiyi and Zhu, Jiapeng and Shen, Yujun and Chen, Qifeng},
  article = {arXiv preprint arXiv:2203.11173},
  year    = {2022}
}
```
