# Sequence Labeling

### WSJ-PTB

- 词性标注/命名实体识别 数据集
	- https://www.zhihu.com/question/52756127
- 国内可用免费语料库
	- http://www.cnblogs.com/mo-wang/p/4444858.html
- 一个中文的标注语料库。可用于训练HMM模型。
	- https://github.com/liwenzhu/corpusZh
- 可以提供给题主两份相对较新的中文分词语料
	- 第一份是SIGHAN的汉语处理评测的Bakeoff语料，从03年起首次进行评测，评测的内容针对汉语分词的准确性和合理性，形成Bakeoff 2005评测集，包含简、繁体中文的训练集和测试集，训练集有四个，单句量在1.5W~8W+。内容比较偏向于书面语。后面05 07年分别对中文命名实体识别和词性标注给出了评测。Bakeoff 2005中文分词熟语料传送门：Second International Chinese Word Segmentation Bakeoff
	- 第二份语料来自GitHub作者liwenzhu，于14年发布于GitHub，总词汇量在7400W+，可以用于训练很多模型例如Max Entropy、CRF、HMM......，优点是这份语料在分词基础上还做了词性标注，至于准确性还有待考究。传送门：liwenzhu/corpusZh
- zh seg
	- http://sighan.cs.uchicago.edu/bakeoff2005/
		- icwb2
			- http://sighan.cs.uchicago.edu/bakeoff2005/data/icwb2-data.rar