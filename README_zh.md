<h1 align="center"> <img src="https://github.com/ACMISLab/AstroBench/blob/main/StarRipple.png" alt="AstroBench Logo" style="width: 100px; height: auto; vertical-align: middle; margin-right: 5px;"> Astro-QA </h1>

**"Astro-QA: A Evaluation Benchmark for Large Language Models in Astronomy"** 官方存储库。
![image](https://github.com/ACMISLab/AstroBench/blob/main/overview.png)

## 🆕 新闻
- \[**2024 年 6 月**\] 我们发布了第一个版本(v1)，非常高兴分享我们对天文大模型的研究与见解！

## 评测数据集简介
Astro-QA是由xxx ACMIS实验室针对天文领域下大模型生成能力的测试基准。在此项测试中，受测的中文大语言模型需要对天体物理学、天体力学、天文学、天文学史、天文学技术和方法这五个科目类别下的2709道不同类型问题做出准确且相关的回答。 我们设计了一套综合的打分系统，对于非计算题，每一道名词解释题和简答题都有标准参考答案，采用多个标准打分然后加权求和。对于客观题目，我们会提取最终最终答案，然后通过难度系数进行综合打分。

数据集包括以下字段：

标号,题目文本,选项

## 论文及数据集下载
AstroBench论文 **待添加链接**<br>
AstroBench测试数据集下载地址 https://github.com/ACMISLab/Astro-QA/tree/main/data<br>
AstroBench自动化评测地址 **待添加链接**<br>

## 💡 提示词
以下是我们在论文中使用的提示。 也可以尝试自己设计的提示词！只需要在每个任务的python代码中更改提示，然后我们就可以看到结果。
![image](https://github.com/ACMISLab/AstroBench/blob/main/prompts.png)

## 📌 评测方法
下载数据集后，请使用“题目prompt”列对应的提示词向模型提问，相关脚本文件在scripts目录下。 最终结果汇总于xlsx文件中增加每类题型相关的“回答”列，存放模型的回复。请注意题目的回答要与提示词、问题编号对应。 在收集到所有回答后，请将xlsx文件提交到评测网站 
**待添加链接**

您需要提交的xlsx文件应参照以下文件：
Submit test samples.xlsx

我们强烈建议对每一道题目进行五次不同的评估！

网站会自动计算分数，您可以选择是否将分数同步到排行榜。

## 引用
如果您发现代码和测试集对您的研究有用，请考虑引用
```
@article{jieli2025astroqa,
  title={An astronomical question answering dataset for evaluating large language models},
  author={Jie Li, FuyongZhao, PanfengChen, JiafuXie, XiangruiZhang, Hui Li, MeiChen, YanhaoWang, MingZhu},
  journal={Scientific Data},
  year={2025},
  url={https://doi.org/10.1038/s41597-025-04613-9}
} 
```
## 🤗 联系我们
Jie Li: gs.lj23@gzu.edu.cn

Fuyong Zhao: gs.fyzhao22@gzu.edu.cn

## 使用许可证
Astro-QA 数据集的使用许可协议如下 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
