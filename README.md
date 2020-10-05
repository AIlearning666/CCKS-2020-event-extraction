# CCKS 2020：面向金融领域的小样本跨类迁移事件抽取


## 任务描述

在金融领域，事件抽取是一项十分重要的任务，也是自然语言处理领域一项比较复杂的任务，而小样本下的事件抽取模型在落地应用中也极为需要。本任务需要从金融领域新闻资讯句子中，抽取事件知识（包括事件类型、触发词和事件元素），并将大样本下训练的模型跨类迁移到小样本的其他事件类型上。
 
其中，事件类型分为两类，初始事件类型限定为：质押、股份股权转让、投资、起诉和减持，需要迁移的事件类型为：收购、担保、中标、签署合同和判决，每个事件类型都有其对应的事件框架，需要抽取出每个事件对应的事件元素 。即给出一段句子级新闻资讯文本，针对该文本需要判断其所属的事件类型，抽取该事件的各个事件元素。

## 方法

### MRC




## 示例数据：

### 输入：

刚刚，A公司发布情报通告，称已于2019年10月28日向广州知识产权法院就B公司涉嫌滥用市场支配地位等相关事宜提起诉讼，并于2019年11月4日得到受理。

### 输出：

事件类型：起诉
触发词：诉讼
原告（公司）：A公司
被告（公司）：B公司
起诉日期：2019年10月28日


### 数据来源:
https://www.biendata.xyz/competition/ccks_2020_3/data/
