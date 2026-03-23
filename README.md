# 决策树分类 - [你的作业题目]

## 📌 问题背景
> We can also use the decision tree classifier to analyze the dataset in Q4. From the decision tree, we can easily understand which features are more important in the prediction.
 (a) For maximum depth= 2, 4, 6 (for MATLAB, take MaxNumSplits= 3, 15, 63 correspondingly), draw the decision trees and calculate their accuracy score. (Again, ensure that random_state=42 in your classifier)
 (b) By directly inspecting the tree with depth = 2, can you determine which two features are the most important in the prediction? Why? 

本项目的目标是使用决策树算法对 Q4 内的数据进行分类，找出depth = 2 时的最重要特征。

## 📊 数据集
**文件**：`hw4.csv`
-**训练集样本数**: 274
-**测试集样本数**: 118
- **数据来源**：课程作业

## 🔧 技术栈
- Python 3.x
- pandas, numpy（数据处理）
- scikit-learn（决策树模型）
- matplotlib（可视化）
