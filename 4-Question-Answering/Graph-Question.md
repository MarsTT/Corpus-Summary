文章发表在 EMNLP 2016，本文详细阐述了 GraphQuestions 这个数据集的构造方法，强调这个数据集是富含特性的（Characteristic-rich）。

- 数据集特点：
	1. 基于 Freebase，有 5166 个问题，涉及 148 个不同领域；
	2. 从知识图谱中产生 Minimal Graph Queries，再将 Query 自动转换成规范化的问题；
	3. 由于 2，Logical Form 不需要人工标注，也不存在无法用 Logical Form 表示的问题；
	4. 使用人工标注的办法对问题进行 paraphrasing，使得每个问题有多种表述方式（答案不变），主要是 Entity-level Paraphrasing，也有 sentence-level；
	5. Characteristic-rich 指数据集提供了问题在下列维度的信息，使得研究者可以对问答系统进行细粒度的分析, 找到研究工作的前进方向：关系复杂度（Structure Complexity），普遍程度（Commonness），函数（Function），多重释义（Paraphrasing），答案候选数（Answer Cardinality）。