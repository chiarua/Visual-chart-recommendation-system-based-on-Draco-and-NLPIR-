# Visualization-explore-procession-based-on-Draco-and-NLPIR
2023.7大创项目及小学期实习：可视化图形推荐（探索）系统（Draco部分）
项目尚在开发，仅作代码仓之用

### 项目背景

本项目以 [Draco2](https://dig.cmu.edu/draco2/) 为基础，意在尽我们所能降低利用Draco可视化推荐算法的门槛，构建一个开箱即用的工具，为用户提供更多样的数据可视化样式参考。

### 项目说明

面对大量繁杂的数据，清晰而规范的图表能最好反映数据的特征、趋势与数据之间的关系。而当数据被第一次获取时，研究者往往只能先理解数据，发现特征，再人工制作图表，将数据特征更好呈现给他人。

假如我们能调转这一过程，利用[推荐算法](https://ieeexplore.ieee.org/abstract/document/8440847)读取数据，生成最合理、最规范的可视化结果，让可视化图表先于对数据的理解出现，那么算法生成的可视化图表，便能成为初步理解数据的助力。

#### 使用说明

市面上丰富的图表绘制工具足以让有明确设计（我需要一张柱状图，其中x轴为天气，y轴为平均降水量）的用户方便地完成图表制作，而本项目针对的是通过可视化进行数据探索（我想看看天气和其它数据的关联）的情况。

在此基础上，Draco得到验证的可视化推荐算法，保证了生成图表的质量与信息量，进一步地，保证了这一可视化图形生成系统，达到前文项目说明所描述的目标。

#### 使用流程

下载并安装依赖库

用你的ide打开app.py

在终端输入`streamlit run app.py`

点浏览器页面左上角出现的`>`就可以啦

#### 输入规范

在上传数据源的csv文件时，请注意，您的数据源如果在表头使用了大写字母（建议只使用小写英文字母），或者在数据中出现了特殊符号，那么在图表渲染时可能会报错，只需修改可疑的特殊符号即可。

在输入栏中，您可以用中文输入您的需求，但是如果您有想要关注的表头信息，请用它在数据源中的英文名称来描述它（我想看看weather和其它数据的关联）。

##### 如有其它使用问题，请提交issue。

##### 希望这一差强人意的小工具，能为你认识数据的过程带来一点点助力。
