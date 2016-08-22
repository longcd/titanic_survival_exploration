## 预测泰坦尼克号乘客幸存率

### 安装要求
这个项目要求使用 **Python 3.5.2** 以及安装下列python库

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装和运行 [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html#optional-for-experienced-python-developers-installing-jupyter-with-pip)。

推荐安装 [Anaconda](https://www.continuum.io/downloads)，一个包含了项目需要的所有库和软件的 Python 发行版本。[这里](https://classroom.udacity.com/nanodegrees/nd002/parts/0021345403/modules/317671873575460/lessons/5430778793/concepts/54140889150923)介绍了如何安装Anaconda。

### 代码

事例代码在 `titanic_survival_exploration_cn.ipynb` 文件中，辅助代码在 `titanic_visualizations.py` 文件中。

### 运行

在命令行中，确保当前目录为 `titanic_survival_exploration/` 文件夹的最顶层（目录包含本 README 文件），运行下列命令：

```bash
$ jupyter notebook titanic_survival_exploration.ipynb
```

这会启动 Jupyter Notebook 把项目文件打开在你的浏览器中。

对jupyter不熟悉的同学可以看一下这个链接：

- [为什么使用jupyter？](https://www.zhihu.com/question/37490497)

### 数据

这个项目的数据包含在 `titanic_data.csv` 文件中。文件包含下列特征：

- **Survived**：是否存活（0代表否，1代表是）
- **Pclass**：社会阶级（1代表上层阶级，2代表中层阶级，3代表底层阶级）
- **Name**：船上乘客的名字
- **Sex**：船上乘客的性别
- **Age**：船上乘客的年龄（可能存在 `NaN`）
- **SibSp**：乘客在船上的兄弟姐妹和配偶的数量
- **Parch**：乘客在船上的父母以及小孩的数量
- **Ticket**：乘客船票的编号
- **Fare**：乘客为船票支付的费用
- **Cabin**：乘客所在船舱的编号（可能存在 `NaN`）
- **Embarked**：乘客上船的港口（C 代表从 Cherbourg 登船，Q 代表从 Queenstown 登船，S 代表从 Southampton 登船）
