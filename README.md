<div align="right">
  语言:
    🇨🇳
  <a title="英语" href="./README.en.md">🇺🇸</a>
  <!-- <a title="俄语" href="../ru/README.md">🇷🇺</a> -->
</div>

 <div align="center"><a title="" href="git@github.com:ZJCV/ZCls.git"><img align="center" src="./imgs/ZCls.png"></a></div>

<p align="center">
  «ZCls»是一个分类模型基准代码库
<br>
<br>
  <a href="https://github.com/RichardLitt/standard-readme"><img src="https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square"></a>
  <a href="https://conventionalcommits.org"><img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg"></a>
  <a href="http://commitizen.github.io/cz-cli/"><img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg"></a>
</p>

## 内容列表

- [内容列表](#内容列表)
- [背景](#背景)
- [主要维护人员](#主要维护人员)
- [致谢](#致谢)
- [参与贡献方式](#参与贡献方式)
- [许可证](#许可证)

## 背景

为了进一步提高算法性能，通常需要对已有模型进行改进，不可避免的就涉及到代码重构。创建本仓库，一方面作为新的模型/优化方法的`CodeBase`，另一方面也记录下自定义模型与已有实现（比如`Torchvision Models`）之间的比较

## 主要维护人员

* zhujian - *Initial work* - [zjykzj](https://github.com/zjykzj)

## 致谢

```
@misc{fan2020pyslowfast,
  author =       {Haoqi Fan and Yanghao Li and Bo Xiong and Wan-Yen Lo and
                  Christoph Feichtenhofer},
  title =        {PySlowFast},
  howpublished = {\url{https://github.com/facebookresearch/slowfast}},
  year =         {2020}
}

@misc{cao2019gcnet,
      title={GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond}, 
      author={Yue Cao and Jiarui Xu and Stephen Lin and Fangyun Wei and Han Hu},
      year={2019},
      eprint={1904.11492},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{sandler2019mobilenetv2,
      title={MobileNetV2: Inverted Residuals and Linear Bottlenecks}, 
      author={Mark Sandler and Andrew Howard and Menglong Zhu and Andrey Zhmoginov and Liang-Chieh Chen},
      year={2019},
      eprint={1801.04381},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{hu2019squeezeandexcitation,
      title={Squeeze-and-Excitation Networks}, 
      author={Jie Hu and Li Shen and Samuel Albanie and Gang Sun and Enhua Wu},
      year={2019},
      eprint={1709.01507},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{wu2018group,
      title={Group Normalization}, 
      author={Yuxin Wu and Kaiming He},
      year={2018},
      eprint={1803.08494},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{wang2018nonlocal,
      title={Non-local Neural Networks}, 
      author={Xiaolong Wang and Ross Girshick and Abhinav Gupta and Kaiming He},
      year={2018},
      eprint={1711.07971},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{micikevicius2018mixed,
      title={Mixed Precision Training}, 
      author={Paulius Micikevicius and Sharan Narang and Jonah Alben and Gregory Diamos and Erich Elsen and David Garcia and Boris Ginsburg and Michael Houston and Oleksii Kuchaiev and Ganesh Venkatesh and Hao Wu},
      year={2018},
      eprint={1710.03740},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}

@misc{goyal2018accurate,
      title={Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour}, 
      author={Priya Goyal and Piotr Dollár and Ross Girshick and Pieter Noordhuis and Lukasz Wesolowski and Aapo Kyrola and Andrew Tulloch and Yangqing Jia and Kaiming He},
      year={2018},
      eprint={1706.02677},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{howard2017mobilenets,
      title={MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications}, 
      author={Andrew G. Howard and Menglong Zhu and Bo Chen and Dmitry Kalenichenko and Weijun Wang and Tobias Weyand and Marco Andreetto and Hartwig Adam},
      year={2017},
      eprint={1704.04861},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{he2015deep,
      title={Deep Residual Learning for Image Recognition}, 
      author={Kaiming He and Xiangyu Zhang and Shaoqing Ren and Jian Sun},
      year={2015},
      eprint={1512.03385},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{szegedy2015rethinking,
      title={Rethinking the Inception Architecture for Computer Vision}, 
      author={Christian Szegedy and Vincent Vanhoucke and Sergey Ioffe and Jonathon Shlens and Zbigniew Wojna},
      year={2015},
      eprint={1512.00567},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## 参与贡献方式

欢迎任何人的参与！打开[issue](https://github.com/zjykzj/ZCls/issues)或提交合并请求。

注意:

* `GIT`提交，请遵守[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/)规范
* 语义版本化，请遵守[Semantic Versioning 2.0.0](https://semver.org)规范
* `README`编写，请遵守[standard-readme](https://github.com/RichardLitt/standard-readme)规范

## 许可证

[Apache License 2.0](LICENSE) © 2020 zjykzj