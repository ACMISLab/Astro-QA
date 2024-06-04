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
Below are the prompts we use in our papers. You can also try your own designed prompts! Just change the prompts in the python code for each task and then we can see the results.
![image](https://github.com/ACMISLab/AstroBench/blob/main/prompts.png)

## 📌 Evaluation Methodology
After downloading the dataset, please ask the model questions using the prompts corresponding to the “Question Prompt” column, the relevant scripts are located in the scripts directory. The final results will be summarized in an xlsx file with an “Answer” column for each type of question to store the model's responses. Please note that the responses to the questions should correspond to the prompts and question numbers. Once all responses have been collected, please submit the xlsx file to the review site. 
**Link to be added**

The xlsx file you need to submit should refer to the following document:
Submit test samples.xlsx

We strongly recommend five different assessments for each question!

The site calculates scores automatically and you can choose whether or not to synchronize your scores to the leaderboard.

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

