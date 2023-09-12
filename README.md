# KnowledgeDAO
供AI训练的中文数据集（持续更新。。。）

为了推进中文AI的发展，促进AI技术公开化、国际化，我们成立了知识岛（KnowledgeDAO)项目，希望借助大家的力量推进中文AI数据集的建设。

数据、算法和算力，是AI发展的三大基石，其中数据的质量对模型最终性能至关重要。然而，从Hugging Face上的模型数据集数量来看，5W多的数据集中，英语的占比超过90%，优质中文数据少之又少。

OpenAI完成数据集的收集花费了巨大成本，以至于需要从微软集资。我们无力承担如此巨大的开销，于是需要各位有志于筹建开放获取语料，并有一定技术基础的网友们献上自己的力量。

如果您有意向参与此项目，我们将不胜感激。

# 知识岛目前的数据集
1、餐饮行业：

a、餐饮行业8000问，来源：2022年和2023年餐饮行业报告与行业白皮书，由chatGPT 3.5负责整理总结，共8204条问答对，1.3M的tokens总数（680k汉字总数）

2、百度知道，来源：百度知道的帖子（2017年的数据整理），共211741条问答对，1.3M的tokens总数（680k汉字总数），42M的tokens总数（21M汉字总数），由于训练数据超过git的文件上限（25mb），因此可在hugging face上查看：https://huggingface.co/datasets/LIUshu123/knowledgeDAO/tree/main/WebQA

Update:由于Hugging Face目前无法访问，百度知道的数据集放到百度网盘下载，链接：https://pan.baidu.com/s/1jQvo9iLqdPFJo01A3iZjSg?pwd=4u5t，解压密码为知识岛QQ群号。

3、Alpaca中文数据集：使用SeamlessM4T + Kaggle线上部署的方式翻译，并未人工进行校正，token总数7.8M（汉字数：3930639）。感谢项目切分的英文数据集：https://github.com/hikariming/alpaca_chinese_dataset/tree/main/

# 知识岛项目参与方式
QQ群：916663510

知识岛社区文档： https://docs.qq.com/aio/DVXZ6d3V6T2lYaENP?p=0Tv6BON3xXocBIBQ629PMO。

Dodo平台：https://imdodo.com/s/209426?inv=4RL32  （主要看中了dodo类似于discord的在线语音功能以及积分系统，可以用来量化成员的贡献）

Hugging Face: https://huggingface.co/datasets/LIUshu123/knowledgeDAO

# 知识岛需要的人
作为知识岛的发起者，很惭愧我不是专业的技术人员，只会简单的代码（不懂的请教项目上的大神以及GPT），因此，知识岛需要的人：

1、愿意分享行业经验的伙伴，共同参与AI行业专家的模型训练；

2、拥有IT技术的伙伴，为社区的发展添砖加瓦；

3、想要参与社区运营的伙伴，为社区稳步发展保驾护航；

4、天使投资者，看好知识岛，为知识岛的建设提供资金支持；

5、热心的参与者，参与知识岛社群规则建立，为社区的良性发展出谋划策。

# 训练效果

ChatGPT3.5 + LangChain + 餐饮行业8000问之后的训练效果（上面是原生的GPT3.5，下面是加上了餐饮行业8000问的效果）
![Weixin Image_20230814133553](https://github.com/shuliu586/KnowledgeDAO/assets/78126220/deca2c2f-479a-4b88-97a4-3f21a814eff8)
