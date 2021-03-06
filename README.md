# Chatbot_CN  (www.chatbotcn.com)

#### 项目介绍(Chatbot_CN)
该项目的目的为实现闲聊的聊天机器人，目前的领域主要针对金融领域

项目共分为六个模块：

    Chatbot_CN       存放项目的整理配置文件
    Chatbot_Data     存放项目的数据文件以及模型训练文件
    Chatbot_Doc      存放项目的参考文献等文档文件
    Chatbot_Model    项目的模型实现
    Chatbot_KG       知识图谱实现
    Chatbot_Web      页面展示

#### 安装教程

    1、项目的依赖包请参考Chatbot_CN根目录下的requirement.txt文件。
    2、导入sql文件到mysql
    3、导入数据到Neo4J

#### 项目结构图

```
Chatbot_CN
├───Chatbot_CN  主要存放项目主体的配置文件
│   ├───data (内部实验数据)
│   │   ├───Attention-Based-BiLSTM-relation-extraction
│   │   ├───Info-extra
│   │   ├───lecture_2
│   │   ├───NRE
│   │   ├───pos-tagging
│   │   ├───QA
│   │   └───Relation_extraction
│   ├───example
│   │   ├───Attention-Based-BiLSTM-relation-extraction
│   │   ├───glove
│   │   ├───Info-extra
│   │   ├───lecture_1
│   │   ├───lecture_2
│   │   ├───lecture_3
│   │   ├───lecture_4
│   │   ├───NER
│   │   ├───NLP
│   │   ├───NRE
│   │   ├───POS-tagging
│   │   ├───Relation Extraction
│   │   ├───RL
│   │   ├───Sequence_labeling
│   │   ├───Synonyms
│   │   ├───syntactic
│   │   └───Syntactic_Parsing
│   ├───jieba_dict
│   ├───log
│   ├───QuestionAnswering
│   ├───RuleMatcher
│   ├───task_modules
│   ├───util
│   └───Validation
├───Chatbot_Data 主要存放数据文件及训练好的模型
├───Chatbot_Doc  主要存放一些文档，paper，笔记等文档文件
│   ├───cs224n
│   ├───note
│   ├───paper   （paper目录）
│   │   ├───Attention
│   │   ├───Co-reference Resolution
│   │   ├───DeepDive
│   │   ├───Dialogue System
│   │   ├───Distant-Supervision
│   │   ├───Entity Alignment
│   │   ├───Entity Disambiguation
│   │   ├───Entity Linking
│   │   ├───Info-Extra
│   │   │   ├───entity extraction
│   │   │   ├───event extraction
│   │   │   ├───relation extraction
│   │   │   └───terminology extraction
│   │   ├───Intent Detection
│   │   ├───kg    知识图谱
│   │   ├───KG Embeddings
│   │   ├───Knowledge Base Completion
│   │   ├───mulDialogue
│   │   ├───NER
│   │   ├───NLG
│   │   ├───nlp
│   │   ├───NLU
│   │   ├───Pinyin2Chinese
│   │   ├───QA
│   │   ├───Representation-Learning
│   │   ├───RL           强化学习
│   │   ├───RL In Dialogue
│   │   ├───Semantic Parsing
│   │   ├───Semantic Role Labeling
│   │   ├───Sentiment-Analyse
│   │   ├───Seq2Seq
│   │   ├───Shortest Dependency Path
│   │   ├───Slot Filling
│   │   ├───Syntax parsing
│   │   ├───Textual Entailment
│   │   ├───WordRepresentation
│   │   └───因果推断
│   ├───pic
│   ├───小象Chatbot课件
│   └───知识图谱课件
├───Chatbot_KG   知识图谱
├───Chatbot_Model   整个项目的模型实现
└───output

```

#### 有关paper代码复现请关注另一个开源项目：
https://github.com/charlesXu86/PAPER-In-CODE

#### 博客 ：https://blog.csdn.net/Q_S_Y_Q

#### QQ群： [聊天机器人开发实战](点击链接加入群聊【聊天机器人开发实战】：https://jq.qq.com/?_wv=1027&k=5ypCd1S) (718607564)

#### 微信公众号： 聊天机器人开发实战

#### 域名：www.chatbotcn.com (目前尚未部署)

#### 说明
持续更新中。。。

License(s)
----------
Various licenses apply. Please refer to the LICENSE and NOTICE files for more
detailed information.