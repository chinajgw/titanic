Titanic乘客遇难分析
==
本案例基于Kaggle上的Titanic数据集，对此数据集进行初步探索，通过可视化观察自变量分布以及自变量与因变量关系分布，并进行特征处理、建模分析及模型评估等建模操作。

### 运行:
1.在pycharm上创建一个project,将Titanic.py与数据集test.csv，titanic_train.csv放置project下。

2.安装所需的依赖项pip install -r requirements.txt。

#### 依赖项:
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Seaborn](https://pypi.org/project/seaborn/)

#### 分析步骤

#### 数据预分析处理
* 初步探索数据
* 缺失值处理
* 使用 Matplotlib 通过可视化探索数据

#### 数据分析
* 分析特征变量与目标变量的关系
* 通过多次分析建立 Logit Regression 模型
* 建立RandomForestClassifier

#### 模型评估和预测
* 用十折交叉验证对两种模型评估
* 选取Logit Regression做预测
