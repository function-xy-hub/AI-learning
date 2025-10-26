# 第一阶段：基础能力入门

建立对于计算机视觉和深度学习领域的基础能力，包括编程、理论知识和科研素养。

## 1.代码基本功

- 优先学习Python基础教程（可参考电子书和 [B站教程](https://www.bilibili.com/))，因为Python是当前AI方向的主流编程语言。
- 如果不熟悉Linux，建议学习 [Linux基础教程](https://www.runoob.com/linux/linux-tutorial.html)。在连接服务器时通常使用Linux系统，与Windows的图形化界面不同，需要掌握一些基本命令。（这个短期内不是重点，用到什么搜什么就行）
- 代码编辑器：VS code，Pycharm。可以在网上搜索如何配置python环境以及在编辑器中运行代码。
- github coplit，AI代码工具，之前在群里也有提到过，针对基础的代码可以迅速生成，可以作为插件集成在上述两个编辑器中。此外，Deepseek，Chatgpt，qwen，豆包等大模型都具备一定的代码理解和生成能力。

## 2.深度学习的基本原理和代码功底

- 观看 [吴恩达的深度学习视频](https://www.bilibili.com/video/BV11H4y1F7uH/?spm_id_from=333.788.videopod.episodes&vd_source=061ef1aa7e4f9fa18405ca80a7d52416)，有些公式可以跟着推导一下。
- 学习 [李沐深度学习系列课程](https://courses.d2l.ai/zh-v2/)，配套源码和安装包可在 [GitHub仓库](https://github.com/d2l-ai/d2l-zh) 获取。
- 学习 [PyTorch 官方文档](https://docs.pytorch.org/tutorials/) 提供的教程和示例。同时，推荐 [小土堆的PyTorch教程](https://space.bilibili.com/1567748478) （适合快速上手）。此外还有一些 [电子书](https://github.com/TingsongYu/PyTorch-Tutorial-2nd) 可供参考。

## 3.科研基础

- 文献检索：学会在 [arXiv](https://arxiv.org/) 和 [Google Scholar](https://scholar.google.com/schhp?hl=en) 上搜索英文论文。
- 代码库：主流代码开源仓库为 [GitHub](https://github.com/)。
- 学术认知：AI ⽅向发展迅速，每年论⽂投稿量都在翻倍增加。论⽂可投稿于会议或期刊。计算机视觉三⼤会议（CVPR、ICCV、ECCV）、⼈⼯智能领域顶级会议（NeurIPS、ICML、ICLR）以及顶级期刊（IEEE TPAMI、IEEE TIP、IJCV）均为AI领域经典与⾼阶论⽂的主要发表平台。

# 第二阶段：前沿知识进阶

最快的学习方式就是阅读论文。建议每篇论⽂先通过知乎、CSDN等平台的中⽂解析快速理解其核⼼思想和贡献，建⽴初步认知后再回归英⽂原⽂，仔细品味作者的表述与细节。初期可能会觉得晦涩难懂，但只要坚持阅读，随着知识量和阅读量的积累，理解会逐步加深。
推荐观看 [李沐老师的论文讲解系列](https://www.bilibili.com/video/BV1H44y1t75x/?spm_id_from=333.337.search-card.all.click&vd_source=fe7d6890ef2f992c9e769a8520b9a51d)，帮助快速入门论文解读。

## 1.核心网络架构（经典图像分类模型）

以下是计算机视觉领域最具代表性的经典网络架构：

 - 1. [AlexNet](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
 - 2. [VGGNet](https://arxiv.org/pdf/1409.1556)
 - 3. [GoogLeNet](https://arxiv.org/abs/1409.4842)
 - 4. [ResNet](https://arxiv.org/abs/1512.03385)
 - 5. [MobileNets](https://arxiv.og/abs/1704.04861)，[MobileNetV2](https://arxiv.org/abs/1801.04381)
 - 6. [Transformer](https://arxiv.org/abs/1706.03762)：Transformer 是⽬前⼈⼯智能领域最为核⼼的技术架构，⼏乎所有⼤模型的技术基座都基于此。推荐阅读 [这篇知乎博客](https://zhuanlan.zhihu.com/p/340149804)，重点了解 Transformer 与 CNN 的区别，并动⼿实现 Attention机制。Attention 机制是当前⼏乎所有模型的基础。
 - 7. [Vision Transformer (ViT)](https://arxiv.org/abs/2010.11929) （论文：[An Image is Worth 16✖16 Words：Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)）：VIT是目前视觉大模型的基础，把Transformer机制引入图像领域，结合[这篇知乎解析](https://zhuanlan.zhihu.com/p/308301901)深入理解。