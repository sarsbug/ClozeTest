# ClozeTest

简介

完形填空问题作为英语试题中常见的问题，常常难倒广大考生。随着自然语言处理技术的发展，其适用范围也从传统的机器翻译，拓展到各个领域，如知识问答、机器人聊天、阅读理解等等。在这里，我将用在课上学到的自然语言处理的知识，一步一步地使用机器学习技术去尝试解答完形填空的问题。从最基础的方案入手，不断改进模型，每一步都会阐述详细的实验思想、步骤、所遇到的问题、解决方案等等一系列问题。

内容介绍

1.模型1.0 计算所要填的词与其前N-1个词的概率

2.模型2.0 计算所要填的词与其周围N-1范围多个词组的概率

3.模型3.0 将句子分块，然后计算分块词组概率并加上模型2.0所算的概率
