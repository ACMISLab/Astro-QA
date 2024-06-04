<h1 align="center"> <img src="https://github.com/ACMISLab/AstroBench/blob/main/StarRipple.png" alt="AstroBench Logo" style="width: 100px; height: auto; vertical-align: middle; margin-right: 5px;"> AstroBench </h1>

The official repository of **AstroBench: A Evaluation Benchmark for Large Language Models in Astronomy**.
![image](https://github.com/ACMISLab/AstroBench/blob/main/overview.png)

## 🆕 News
- \[**June 2024**\] We have released the first version (v1) and are very excited to share our research and insights into astronomical macromodeling!

## Review Dataset Introduction
AstroBench is a benchmark by xxx ACMIS Labs for large language model generation capabilities in the field of astronomy. In this test, the Chinese large language models tested are required to provide accurate and relevant answers to 2709 different types of questions under five subject categories: astrophysics, celestial mechanics, astronomy, history of astronomy, and astronomical techniques and methods. We have designed a comprehensive scoring system, for non-calculated questions, each of the terminology and short answer questions has a standardized reference answer, which is scored using multiple criteria and then weighted and summed. For objective questions, we extract the final answer and then combine the scores using a difficulty factor.

The dataset includes the following fields:

ID,Question,Options

## Download papers and datasets
AstroBenc Paper **Link to be added**<br>
AstroBenc Download the test dataset https://github.com/ACMISLab/AstroBench/tree/main/data<br>
AstroBenc Automated evaluation address **Link to be added**<br>

## 💡 Prompt
以下是我们在论文中使用的提示。 也可以尝试自己设计的提示词！只需要在每个任务的python代码中更改提示，然后我们就可以看到结果。
![image](https://github.com/ACMISLab/AstroBench/blob/main/prompts.png)

## 📌 Evaluation Methodology
下载数据集后，请使用“题目prompt”列对应的提示词向模型提问，相关脚本文件在scripts目录下。 最终结果汇总于xlsx文件中增加每类题型相关的“回答”列，存放模型的回复。请注意题目的回答要与提示词、问题编号对应。 在收集到所有回答后，请将xlsx文件提交到评测网站 
**Link to be added**

您需要提交的xlsx文件应参照以下文件：
Submit test samples.xlsx

我们强烈建议对每一道题目进行五次不同的评估！

网站会自动计算分数，您可以选择是否将分数同步到排行榜。

## 🤗 Citation
If you find the code and testset are useful in your research, please consider citing
```
**References to be added**
```
## 🤗 Contact us
Jie Li: gs.lj23@gzu.edu.cn

Fuyong Zhao: gs.fyzhao22@gzu.edu.cn

## Star History
![Star History Chart](https://api.star-history.com/svg?repos=/ACMISLab/AstroBench&type=Date)

## License
The AstroBench dataset is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

