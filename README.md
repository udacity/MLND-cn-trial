# 机器学习工程师纳米学位（试学班）
## 项目0：预测你的下一道世界料理

### 准备工作

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [Pandas](https://pandas.pydata.org/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [nltk](https://www.nltk.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装一个软件，以运行和编辑 [.ipynb](http://jupyter.org/) 文件。

优达学城推荐学生安装 [Anaconda](https://www.continuum.io/downloads)，这是一个常用的 Python 集成编译环境，且已包含了本项目中所需的全部函数库。

### 代码

代码的模版已经在 `PredictYourCuisine.ipynb` 文件中给出。你还会用到[菜系数据集](https://www.kaggle.com/c/whats-cooking/data)来完成这个项目。我们已经为你提供了一部分代码，但还有些功能需要你来实现才能以完成这个项目。

### 运行

在终端或命令行窗口中，选定 `MLND-cn-trial/` 的目录下（包含此README文件），运行下方的命令：

```jupyter notebook PredictYourCuisine.ipynb```

这样就能够启动 Jupyter notebook 软件，并在你的浏览器中打开文件。

### 数据

此项目的数据集来自[Kaggle What's Cooking](https://www.kaggle.com/c/whats-cooking/data) 竞赛。共 39774/9944 个训练和测试数据点，涵盖了中国菜、越南菜、法国菜等的信息。

**特征**

1. `id`: 数据编号，例如“24717”
2. `cuisine`: 菜名，例如“Indian”
3. `ingredients`: 此菜所包含的原料，例如["tumeric", "vegetable stock", ...] 

**目标变量**

`cuisine`: 菜名