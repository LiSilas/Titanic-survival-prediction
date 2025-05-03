```
项目简介

本项目使用逻辑回归和随机森林两种模型，分别对kaggle比赛Titanic - Machine Learning from Disaster进行生还率预测。

项目结构为：
Titanic_survival_prediction/
├── output/
│   ├── titanic_lr_submission.csv
│   ├── titanic_rf_submission.csv
├── README.md
├── Titanic_survival_prediction.ipynb

注意：由于kaggle中的文件路径与本地不同，如果想在本地运行该项目，请将Titanic_survival_prediction.ipynb中的数据读取路径改为“data/train.csv”与“data/test.csv”。
注意2：数据集我已删除，如若需要，请自行前往Kaggle下载数据集并解压在相应的位置。

项目说明：
该项目主要用于kaggle入门比赛及数据处理流程演示。其步骤如下：
1、导入必要库；
2、读取数据集并查看其属性；
3、处理缺失值，并对分类变量进行编码处理；
4、选择与生还率相关的特征；
5、使用逻辑回归和随机森林模型进行训练，并对随机森林进行交叉验证；
6、输出每个模型的预测结果并提交。

目的：展示了从数据处理到模型训练的完整机器学习项目流程，作为kaggle新手项目的参考
```
