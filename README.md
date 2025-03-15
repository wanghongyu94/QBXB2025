## 《基于词向量网络的科研主题演化分析：语义漂移过程的揭示》LIS数据集

    数据来源：Web of Science (SSCI)
    年份范围：2011-2020
    数量：38,932条

## 附录A：词向量网络与共词网络的比较案例分析

- 在“Social Media”的结果中，其他几个高共现词相较于“Bibliometrics”等其他标签词而言，均与“Social Media”具有更高的GloVe相似度，而Word2Vec相似度的波动性较大。说明不论在共词网络还是基于GloVe的学科领域词向量网络中，这些词汇都会被划分至标签词“Social Media”的同一个主题聚类中。而对于“China”而言，其跟“Social Media”共现次数较高，主要是由于不少研究以中国的社交媒体平台及数据为研究对象，但在学科领域词向量网络中，其与“Academic Library”这一标签的语义相似度更高。这可能是因为共词网络仅考虑了2016年的词间共现情况，而学科领域词向量网络是结合了2011-2016年数据训练的结果，表明在这六年的研究积累下，“China”与“Academic Library”有更近的语义距离。

- 在“Bibliometrics”的结果中，除“University”外，其他高共现词均与“Bibliometrics”具有更高的GloVe相似度，这些词汇中包括文献计量的常用分析方法或路径如引文分析（Citation Analysis）、科学计量（Scientometrics）和社交网络分析（Social Network Analysis），还包括文献计量的目的和结果如研究评价（Research Evaluation）等，因而这些词与“Bibliometrics”除具有较高的共现次数外，也具有较高的语义相似度，不论在共词网络还是学科领域词向量网络中，很大概率都会和“Bibliometrics”处在同一个主题聚类中。对高校的科研产出进行文献计量进而分析领域的核心研究机构或是进行大学排名是文献计量的一个重要研究方向，因而“University”与“Bibliometrics”的共现次数较高。但在语义层面，“University”与另一个标签词“Academic Library”更高，这可能与学术图书馆研究的重要分支大学图书馆（University Library）研究有一定的关联，这也在一定程度上体现了学科领域词向量网络与共词网络的差异。

- 在“Qualitative”的结果中，除“Research”外，其余高共现词与标签词“Qualitative”的语义相似度均大于其他标签词。这是因为访谈是质性研究的常用分析方法，而人际关系和卫生保健则是质性研究的重要研究对象，因而这些词汇不仅与“Qualitative”有较高的共现次数，其语义距离也较近。而对于“Research”而言，分析2016年的原始数据可以发现，在不少质性研究中“Qualitative”和“Research”均作为关键词出现，这一方面是由于研究者的个人选择，另一方面也不排除原始数据中存在着一些书写错误，从而导致“Research”与“Qualitative”的共现次数较高。但从语义层面来看，“Research”与另一标签词“Knowledge Management”的语义相似度更高，即，通过多年的语料数据积累，能够在一定程度上减少关键词质量的不足所产生的误差。

- 在“Knowledge Management”的结果中，除调研（Survey）外，其他与知识及知识管理流程密切相关的高共现的特征关键词均与“Knowledge Management”有更高的语义相似度，表明了学科领域词向量网络和共词网络在领域关键概念上的一致性。而“Survey”是一种信息科学与图书馆学领域的常用分析手段和方法，在不同的研究领域和主题下都有应用，对于2016年的数据而言，“Knowledge Management”与“Survey”共现次数较高，但是通过2011-2016这六年的研究积累下，相较于“Knowledge Management”而言“Survey”与“Academic Library”有更近的语义距离。

- 与“Academic Library”共现次数最高的词汇包括信息素养（Information Literacy）、高等教育（Higher Education）、开放获取（Open Access）、用户研究（User Study）和大学图书馆（University Library），这些高共现词中包括学术图书馆的重要子领域，也包括学术图书馆的研究对象和问题，这些词汇与标签词“Academic Library”的语义相似度大于其他标签词也符合学科领域中对于学术图书馆领域的认知，表明学科领域词向量网络和共词网络作为文本内容层面的科学知识网络均能在一定程度上反应学科领域的知识结构。
