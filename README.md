# NLPDataSet
大家好，我是刘聪NLP。

本项目为本人收集并整理的一些数据集，目前包括中文摘要数据集、中文片段抽取式阅读理解数据集（QA）、中文文本相似度数据集和中文NER数据集。

希望大家可以多多转发、多多start。

## UpDate 06.16.2022
* 从网上收集数据，将CMeEE数据集、IMCS21_task1数据集、CCKS2017_task2数据集、CCKS2018_task1数据集、CCKS2019_task1数据集、CLUENER2020数据集、MSRA数据集、NLPCC2018_task4数据集、CCFBDCI数据集、MMC数据集、WanChuang数据集、PeopleDairy1998数据集、PeopleDairy2004数据集、GAIIC2022_task2数据集、WeiBo数据集、ECommerce数据集、FinanceSina数据集、BoSon数据集、Resume数据集、Bank数据集和FNED数据集等21个数据集进行整理清洗，构建一个较完善的中文NER数据集。
* 数据集清洗时，仅进行了简单地规则清洗，并将格式进行了统一化，标签为“BIO”。
* 处理后数据集详细信息，见[数据集描述]()。
* 数据集由[NJUST-TB](https://github.com/Swag-tb)一起整理。

| 数据   | 原始数据/项目地址   |  原始数据描述 |
| ------  | ------ | ------  |
| CMeEE数据集 | [地址](http://www.cips-chip.org.cn/2021/CBLUE) |  中文医疗信息处理挑战榜CBLUE中医学实体识别数据集 |
| IMCS21_task1数据集 | [地址](http://www.fudan-disc.com/sharedtask/imcs21/index.html?spm=5176.12282016.0.0.140e6d92ypyW1r) |  CCL2021第一届智能对话诊疗评测比赛命名实体识别数据集 |
| CCKS2017_task2数据集 | [地址](https://www.biendata.xyz/competition/CCKS2017_2/) |  CCKS2017面向电子病历的命名实体识别数据集  |
| CCKS2018_task1数据集 | [地址](https://www.biendata.xyz/competition/CCKS2018_1/) |  CCKS2018面向中文电子病历的命名实体识别数据集  |
| CCKS2019_task1数据集 | [地址](http://openkg.cn/dataset/yidu-s4k) |  CCKS2019面向中文电子病历的命名实体识别数据集  |
| CLUENER数据集 | [地址](https://github.com/CLUEbenchmark/CLUENER2020) |  CLUENER2020数据集  |
| MSRA数据集 | [地址](https://www.msra.cn/) |  MSRA微软亚洲研究院开源命名实体识别数据集  |
| NLPCC2018_task4数据集 | [地址](http://tcci.ccf.org.cn/conference/2018/taskdata.php) |  任务型对话系统数据数据集  |
| CCFBDCI数据集 | [地址](https://www.datafountain.cn/competitions/510) |  中文命名实体识别算法鲁棒性评测数据集  |
| MMC数据集 | [地址](https://tianchi.aliyun.com/competition/entrance/231687/information) |  瑞金医院MMC人工智能辅助构建知识图谱大赛数据集  |
| WanChuang数据集 | [地址](https://tianchi.aliyun.com/competition/entrance/531827/introduction) |  "万创杯”中医药天池大数据竞赛—智慧中医药应用创新挑战赛数据集  |
| PeopleDairy1998数据集 | [地址]() |  人民日报1998数据集  |
| PeopleDairy2004数据集 | [地址]() |  人民日报2004数据集  |
| GAIIC2022_task2数据集 | [地址](https://www.heywhale.com/home/competition/620b34ed28270b0017b823ad/content/2) |  2022全球人工智能技术创新大赛-商品标题实体识别数据集  |
| WeiBo数据集 | [地址](https://github.com/hltcoe/golden-horse) |  社交媒体中文命名实体识别数据集  |
| ECommerce数据集 | [地址](https://github.com/allanj/ner_incomplete_annotation) |  面向电商的命名实体识别数据集  |
| FinanceSina数据集 | [地址](https://github.com/jiesutd/LatticeLSTM) |  新浪财经爬取中文命名实体识别数据集  |
| BoSon数据集 | [地址](https://github.com/bosondata) |  玻森中文命名实体识别数据集  |
| Resume数据集 | [地址](https://github.com/jiesutd/LatticeLSTM/tree/master/ResumeNER) |  中国股市上市公司高管的简历  |
| Bank数据集 | [地址](https://www.heywhale.com/mw/dataset/617969ec768f3b0017862990/file) |  银行借贷数据数据集  |
| FNED数据集 | [地址](https://www.datafountain.cn/competitions/561/datasets) |  高鲁棒性要求下的领域事件检测数据集  |

清洗及格式转换后的数据，下载链接如下：[百度云](https://pan.baidu.com/s/19u7koJdlZiox-0fGQoZ2cA)
<br>提取码：cfv8

## UpDate 01.06.2022
* 从网上收集数据，将DIAC2019、CCKS2018_Task3、LCQMC、AFQMC、GAIIC2021_Task3、THS2021、CHIP2019、SOHU_2021、COVID19、PAWSX、XF2021、Chinese-MNLI、Chinese-SNLI、Chinese-STS-B、OCNLI、PKU Paraphrase Bank等16个数据集进行整理清洗，构建一个较完善的中文文本匹配数据集。
* 数据集清洗主要包括：针对4个NLI数据集进行标签转换，STS-B数据集进行分数过滤，PKU复述数据集仅生成正标签。
* 处理后数据集详细信息，见[数据集描述](https://zhuanlan.zhihu.com/p/454173790)。
* 增加CINLID词语级匹配数据集。

| 数据   | 原始数据/项目地址   |  原始数据描述 |
| ------  | ------ | ------  |
| DIAC2019 | [地址](https://www.biendata.xyz/competition/2019diac/)  |  基于Adversarial Attack的问题等价性判别比赛数据集  |
| CCKS2018_Task3 | [地址](https://www.biendata.xyz/competition/CCKS2018_3/)  |  CCKS 2018 微众银行智能客服问句匹配大赛  |
| LCQMC | [地址](https://aclanthology.org/C18-1166.pdf)  |  哈工大发表的一个中文问答匹配数据集  |
| AFQMC | [地址](https://tianchi.aliyun.com/dataset/dataDetail?dataId=106411)  |  蚂蚁金融语义相似度数据集  |
| GAIIC2021_Task3 | [地址](https://tianchi.aliyun.com/competition/entrance/531851/information)  |  小布助手对话短文本语义匹配比赛数据集  |
| THS2021 | [地址](http://contest.aicubes.cn/#/detail?topicId=23)  |  同花顺2021人工智能大赛-跨领域迁移的文本语义匹配数据集  |
| CHIP2019 | [地址](https://www.biendata.xyz/competition/chip2019/)  |  平安医疗科技疾病问答迁移学习比赛数据集  |
| SOHU_2021 | [地址](https://www.biendata.xyz/competition/sohu_2021/)  |  2021搜狐校园文本匹配算法大赛数据集  |
| COVID19 | [地址](https://tianchi.aliyun.com/competition/entrance/231776/introduction)  |  “公益AI之星”挑战赛-新冠疫情相似句对判定大赛数据集  |
| PAWSX | [地址](https://github.com/google-research-datasets/paws)  |  多语言释义识别对抗性数据集  |
| XF2021 | [地址](https://challenge.xfyun.cn/topic/info?type=chinese-question-similarity)  |  讯飞赛题—中文问题相似度挑战赛数据集  |
| Chinese-MNLI | [地址](https://github.com/pluto-junzeng/CNSD)  |  中文MNLI数据集  |
| Chinese-SNLI | [地址](https://github.com/pluto-junzeng/CNSD)  |  中文SNLI数据集  |
| Chinese-STS-B | [地址](https://github.com/pluto-junzeng/CNSD)  |  中文SNLI数据集  |
| OCNLI | [地址](https://github.com/CLUEbenchmark/OCNLI)  |  原生中文自然语言推理数据集，是第一个非翻译的、使用原生汉语的大型中文自然语言推理数据集。  |
| PKU | [地址](https://github.com/pkucoli/PKU-Paraphrase-Bank)  |  句级中文文本复述语料库  |
| CINLID | [地址](https://mp.weixin.qq.com/s/oCwwkOtamf1rmIch7SjJug)  |  中文成语语义推理数据集  |

清洗及格式转换后的数据，下载链接如下：[百度云](https://pan.baidu.com/s/1V-WHrZoDcSw1QEA9NDg9UQ)
<br>提取码：rt6f


## UpDate 08.03.2021
* 从网上收集数据，将DRCD、cmrc2018、chinese-squad、中医数据集、法研杯2019、莱斯杯机器阅读理解、疫情QA、WebQA、Dureader等9个数据集进行整理清洗，构建一个较完善的中文片段抽取式阅读理解数据集。
* 数据集清洗时，仅进行了简单地规则清洗，并将格式进行了统一化。
* 处理后数据集详细信息，见[数据集描述](https://zhuanlan.zhihu.com/p/395788175)

| 数据   | 原始数据/项目地址   |  原始数据描述 |
| ------  | ------ | ------  |
| DRCD | [地址](https://github.com/DRCKnowledgeTeam/DRCD)  | 台达阅读理解资料集 Delta Reading Comprehension Dataset (DRCD) 属于通用领域繁体中文机器阅读理解资料集。  本资料集期望成为适用于迁移学习之标准中文阅读理解资料集。  本资料集从2,108篇维基条目中整理出10,014篇段落，并从段落中标注出30,000多个问题   |
| cmrc2018 | [地址](https://hfl-rc.com/cmrc2018/)  | 第二届“讯飞杯”中文机器阅读理解评测 |
| chinese-squad | [地址](https://github.com/pluto-junzeng/ChineseSquad)  | 中文机器阅读理解数据集，本数据集通过机器翻译加人工校正的方式从原始Squad转换而来，其中包括V1.1 和V2.0。由于部分翻译无法找到原文中的答案（短答案翻译和文档翻译有出入），故数据量对比原始英文版SQuAD 有所减少。  |
| 中医数据集 | [地址](https://tianchi.aliyun.com/competition/entrance/531826/introduction)  |  本次标注数据源来自中医药领域文本，包括【黄帝内经翻译版】、【名医百科中医篇】、【中成药用药卷】、【慢性病养生保健科普知识】四个主要来源，共标注 13000对（问题、文档、答案），来源于5000篇文档，每篇文档由人工标注产生1～4对(问题, 答案)对。 | 
| 法研杯2019 | [地址](http://cail.cipsc.org.cn:2019/)  | 裁判文书中包含了丰富的案件信息，比如时间、地点、人物关系等等，通过机器智能化地阅读理解裁判文书，可以更快速、便捷地辅助法官、律师以及普通大众获取所需信息。本任务是首次基于中文裁判文书的阅读理解比赛，属于篇章片段抽取型阅读理解比赛（Span-Extraction Machine Reading Comprehension）。  | 
| 莱斯杯机器阅读理解 | [地址](https://www.heywhale.com/home/competition/5d142d8cbb14e6002c04e14a)  | 本次竞赛将提供面向军事应用场景的大规模中文阅读理解数据集，围绕多文档机器阅读理解进行竞赛，涉及理解、推理等复杂技术。每个问题对应五篇候选文章，问题与篇章中的答案证据句间存在较大的语法与句式变化。需要在多篇章定位与深度理解的基础上，从存在干扰项的多篇文章中搜寻出最优答案，更富挑战性的是问题的答案可能需要结合至少两篇文章的相关内容，进行关联推断才能够准确得出。 | 
| 疫情QA | [地址](https://www.datafountain.cn/competitions/424/datasets)  | 任务将提供以疫情为主的政策数据集、用户问题以及标注好的答案片段，参赛者可自行通过对政策数据的分析、处理和组织，利用训练数据集训练智能问答算法，并在测试数据集上进行评测，评测指标为最终返回答案的准确性。 | 
| WebQA | [地址](https://kexue.fm/archives/4338)  | 百度利用百度知道和其他资源，构建了一个这样的一个数据集，称为WebQA | 
| Dureader | [地址](http://ai.baidu.com/broad/download?dataset=dureader)  | 百度整理出来的阅读理解数据集，问题和文档均来自于百度搜索和百度知道，而答案是人工手动生成的，因此数据集更加切合真实场景。 |
 
清洗及格式转换后的数据，下载链接如下：[百度云](https://pan.baidu.com/s/1Q_ti7S7jQy7GN-ZjmZOYpg)
<br>提取码：02ta


## UpDate 01.02.2021
* 从网上收集数据，将清华新闻数据、搜狗新闻数据等新闻数据集，以及开源的一些摘要数据进行整理清洗，构建一个较完善的中文摘要数据集。
* 数据集清洗时，仅进行了简单地规则清洗。例如：清洗htlm标记、去除多余空字符、去除图片标记等。
* 处理后数据集详细信息，见[数据集描述](https://zhuanlan.zhihu.com/p/341398288)

| 数据   | 原始数据/项目地址   |  处理后文件下载地址 |
| ------  | ------ | ------  |
| 清华新闻数据 | [地址](http://thuctc.thunlp.org/)  | [百度云盘](https://pan.baidu.com/s/1a-CUtTc5xQFB9_EJaxDklA) 提取码： vhol |
| 搜狗新闻数据 | [地址](https://www.sogou.com/labs/resource/cs.php)  | [百度云盘](https://pan.baidu.com/s/1vgfa5gnIHTYpoYptuHo6gQ) 提取码：ode6 |
| nlpcc2017摘要数据 | [地址](http://tcci.ccf.org.cn/conference/2017/taskdata.php)  | [百度云盘](https://pan.baidu.com/s/1v7QFJ3hl_ALb2DEEq0umRQ) 提取码：e0zq  |
| csl摘要数据 | [地址](https://github.com/P01son6415/CSL)  | [百度云盘](https://pan.baidu.com/s/1qrzhsWq8SGQ1-W8VizSY9w) 提取码：0qot  | 
| 教育培训行业摘要数据 | [地址](https://github.com/wonderfulsuccess/chinese_abstractive_corpus)  | [百度云盘](https://pan.baidu.com/s/1sjOkp8LKGVmY6h0QXl5m7g) 提取码：kjz3  | 
| lcsts摘要数据 | [地址](http://icrc.hitsz.edu.cn/Article/show/139.html)  | [百度云盘](https://pan.baidu.com/s/1J2NcMfxpGGG_BG1Wx0lHGA) 提取码：bzov | 
| 神策杯2018摘要数据 | [地址](https://js.dclab.run/v2/cmptDetail.html?id=242)  | [百度云盘](https://pan.baidu.com/s/1WFimCGk6y-nfSdPRbCrV8Q) 提取码：6f4f | 
| 万方摘要数据 | [地址](https://github.com/EachenKuang/wanfangSpider)  | [百度云盘](https://pan.baidu.com/s/1RFNFagKnxf2JKnjwBDecPA) 提取码： p69g| 
| 微信公众号摘要数据 | [地址](https://github.com/nonamestreet/weixin_public_corpus)  | [百度云盘](https://pan.baidu.com/s/1OBn8kyZEsUeiV_kw4OJYnQ) 提取码： 5has| 
| 微博数据 | [地址](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg)  | [百度云盘](https://pan.baidu.com/s/1-OxrZRm_Q7ejfU-mtngBWg) 提取码： 85t5|
| news2016zh新闻数据 | [地址](https://github.com/brightmart/nlp_chinese_corpus)  | [百度云盘](https://pan.baidu.com/s/1S3YhetbEZuSfYbfSLeRfSg) 提取码： qsj1 |  

数据集集合：[百度云盘](https://pan.baidu.com/s/1ibPTRTgXn8FfVf6DgVFWfA) 提取码： 7am8 

## 声明
本项目中整理的所有数据集，仅能用于学术研究，请勿用于商业。