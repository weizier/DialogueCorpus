### 单轮
[insuranceQA](https://github.com/shuzi/insuranceQA)保险行业的问答对。

[中文InsuranceQA](https://github.com/Samurais/insuranceqa-corpus-zh)中文版的insuranceQA.分为“问答语料”和“问答对语料”，前者是insuranceQA直接翻译的结果，后者是基于问答语料，又做了分词和去标去停，添加label。所以，"问答对语料"可以直接对接机器学习任务。如果对于数据格式不满意或者对分词效果不满意，可以直接对"问答语料"使用其他方法进行处理，获得可以用于训练模型的数据。

[Maluuba新闻问答数据集](https://datasets.maluuba.com/NewsQA)：基于CNN新闻报道的1.2万对问答。

[Quora问答对](https://data.quora.com/First-Quora-Dataset-Release-Question-Pairs)：Quora发布的首个数据集，包含副本/语义相似度标签。

[CMU问答数据集](https://www.cs.cmu.edu/~ark/QA-data/)：用维基百科文章人工生成的事实型问答对，配有难度评级。

[儿童图书测试](http://www.thespermwhale.com/jaseweston/babi/CBTest.tgz)：从古腾堡计划提供的儿童图书中提取问答对（问题 + 上下文、答案）作为基线，可以用于问题回答（阅读理解）和事实型查询。

[SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)：斯坦福问答数据集——用途广泛的问题回答及阅读理解数据集，每项问题的答案都是一段文本。

[白鹭时代中文问答语料](https://github.com/Samurais/egret-wenda-corpus)
<br>由白鹭时代官方论坛问答板块10,000+ 问题中，选择被标注了“最佳答案”的纪录汇总而成。人工review raw data，给每一个问题，一个可以接受的答案。目前，语料库只包含2907个问答。([备份](./egret-wenda-corpus.zip))

[WebQA](https://pan.baidu.com/s/1pLXEYtd)，提取密码为：6fbf. 从百度知道中抽取到的问答对语料，由论文[“Dataset and Neural Recurrent Sequence Labeling Model for Open-Domain Factoid Question Answering”](https://arxiv.org/abs/1607.06275)中提出。

### 多轮
[豆瓣多轮ResponseSelection](https://github.com/MarkWuNLP/MultiTurnResponseSelection)，豆瓣的多轮问答选择数据集。

[Maluuba目标导向对话](https://datasets.maluuba.com/Frames)：程序型会话数据集，对话旨在完成一项任务或决策，常用于聊天机器人。

[bAbi](https://research.fb.com/projects/babi/)：来自Facebook人工智能研究所（FAIR）的综合型阅读理解及问答数据集。

[dgk_shooter_min.conv.zip](https://github.com/rustch3n/dgk_lost_conv)
<br>中文电影对白语料，噪音比较大，许多对白问答关系没有对应好

[The NUS SMS Corpus](https://github.com/kite1988/nus-sms-corpus)
<br>包含中文和英文短信息语料，据说是世界最大公开的短消息语料

[ChatterBot中文基本聊天语料](https://github.com/gunthercox/chatterbot-corpus/tree/master/chatterbot_corpus/data)
<br>ChatterBot聊天引擎提供的一点基本中文聊天语料，量很少，但质量比较高

[Datasets for Natural Language Processing](https://github.com/karthikncode/nlp-datasets)
<br>这是他人收集的自然语言处理相关数据集，主要包含Question Answering，Dialogue Systems， Goal-Oriented Dialogue Systems三部分，都是英文文本。可以使用机器翻译为中文，供中文对话使用

[小黄鸡](https://github.com/rustch3n/dgk_lost_conv/tree/master/results)
<br>据传这就是小黄鸡的语料：xiaohuangji50w_fenciA.conv.zip （已分词） 和 xiaohuangji50w_nofenci.conv.zip （未分词）

[Chat corpus repository](https://github.com/Marsan-Ma/chat_corpus)
<br>chat corpus collection from various open sources
<br>包括：开放字幕、英文电影字幕、中文歌词、英文推文