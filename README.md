# 数据科学
好不容易终于结课了，这里是几位学长学姐的F3B通关指南，希望能够帮助到后面的学弟学妹们。

但是在开始这篇文档之前，大家可以看看往届的学长学姐们留下的珍贵资料和总结：[往届F3B总结](3A专业总结.pdf)

## F3B 李海鹏
### 选择数据科学的理由
1. 🎁赚钱多（国内大厂30w+），贴近机器学习，大数据，有良好的未来发展空间
2. 💪更加前沿（人工智能）和火爆（中国）
3. 🌈形象有趣，可以画出各种酷炫的图来表达自己的想法
### 课程介绍
[![NPM version](https://img.shields.io/badge/Niveau--1-%E7%BB%9F%E8%AE%A1%E5%AD%A6-red.svg)]: 非常重要的一门课，机器学习的基础，所有人必修，在课下需要自己多花时间学习理论知识和做更多的练习。课程分为一个projet和一个期末的QCM，projet是确定自己小组的研究主题，然后在学校范围内发放问卷调查，然后根据自己收集到的问卷做统计学分析，然后假设检验，最后获得结果。期末QCM难度不大但是我自己得到的分数奇低，所以建议大家好好做projet。

所有的相关资料可以在这个链接中找到：[Niveau-1](https://drive.google.com/drive/folders/1XSCo7Fqw8HM3oKVUPqPCtO3di1MLwh82?usp=sharing)

因为我自己很喜欢上网课所以在这里推荐学习：[![NPM version](https://img.shields.io/badge/cousera-Statistic%20with%20R-blue.svg)](https://www.coursera.org/specializations/statistics)，这门网课完美覆盖101E的所有重点，并且每一个章节后面都会有一个大约两小时的用`R`语言练习，既锻炼统计学能力，又为之后的niveau铺下基础。

[![NPM version](https://img.shields.io/badge/Niveau--2-%E6%95%B0%E6%8D%AE%E6%8C%96%E6%8E%98-red.svg)]: 重要而且有用的一门课，这堂课会将机器学习整个流程交给我们，比如：
* 输入阶段的数据可视化，数据清洗，特征工程，训练集验证集划分，
* 建模阶段的模型原理（监督方法：线性方法，SVM，决策树，随机森林，神经网络；非监督方法：K-means，聚类，PCA）
* 输出阶段的评价方法（Accuracy, Precision, Recall, F1-score），特征重要性，模型是否过拟合
课程分为选择一个线上的三人组队的竞赛，比如kaggle的竞赛，然后参与竞赛，最后比较获得的名次，和一个期末的QCM

相关资料：[Niveau-2](https://drive.google.com/drive/folders/17Of3oGdUtwQmFVtCt57XnwvEOfg42kBW?usp=sharing)

在这里同样推荐一门网课，吴恩达老师的机器学习：[![NPM version](https://img.shields.io/badge/cousera-Machine%20Learning-blue.svg)](https://www.coursera.org/learn/machine-learning)这是一门免费的课程，深入浅出，很大一部分从事机器学习的工程师都是从这个教学开始，虽然这门课推出的时间是2011年距离现在也已经有8年，但是它依然是最好的机器学习入门课程之一

[![NPM version](https://img.shields.io/badge/Niveau--3-%E5%A4%A7%E6%95%B0%E6%8D%AE-red.svg)]: 有点奇怪的一门课，百分之六十以上的时间都是Travail Personnal，老师在课堂上基本上没讲什么，第一方面需要每个小组决定一个自己的商业计划，然后做一次Presentation，第二方面会有几节Spark的课，基本上就是读官方文档，对于这门课大家可以参照一下陈力学长和吴梦颖学姐的指南。

相关资料: [Niveau-3](https://drive.google.com/drive/folders/1mrgyilV59J2i14oqaNWg-pPStsTDJ-7F?usp=sharing)

[![NPM version](https://img.shields.io/badge/Niveau--4-%E5%95%86%E4%B8%9A%E6%99%BA%E8%83%BD-red.svg)]：这是一门技术和商业混合的课，技术方面涉及数据仓库的设计，还有维度表，事实表的设计，商业方面会教一些敏捷开发的理论和技巧，和如何跟客户开会，怎么问出合适的问题来获得自己想要的信息。这门课比较烦因为每两周就会有一次QCM，然后会有一个大Projet，可以选择python或者传统软件实现，根据客户的需求设计出一个清晰明了的Dashboard，最后结束会有一个小的Forum。国内其实也有商业智能分析师这个职位，这个职位感觉更偏向于顶端一点，是整个数据科学的最终输出，所以感兴趣的同学可以多了解一下这个方面。另外这门课的老师比较认真严格，但是只要好好做他都会给一个好成绩，而且还有可能推荐毕业实习，这一方面还是很诱人的。这里是我们的projet的python实现版本，托管在github上面：[学生QCM管理系统](https://github.com/lhaippp/Dash_Student_Management_System)

相关资料: [Niveau-4](https://drive.google.com/drive/folders/1t6C7JNm7kYCtt32WVwNzLvujkKIexjEg?usp=sharing)

[![NPM version](https://img.shields.io/badge/Niveau--5-%E5%86%B3%E7%AD%96%E8%AE%BA-red.svg)]：比较有趣的一门课，特别是这门课的前半部分。前半部分要求我们读一篇论文，是关于港口的Node分布的最优解问题，然后先从线性规划的角度来解决这个问题，之后再用遗传算法来解决。后半段是关于风险分析的问题。这门课分为一个遗传算法的rapport和一个小projet的soutenance，总体来说比较轻松。另外有一点我想说的是，国内的人工智能其实感觉已经开始涉及最优解这个问题，从以前的传统的深度学习项目比如人脸识别，金融分析，自然语言处理，到现在很多大公司都已经开始做智慧仓库，智慧驾驶，这一些需要决策论的问题，所以我比较推荐大家选择这门课。遗传算法的jupyter可以在这里找到：[遗传算法](GA-Hub-Distribution.ipynb)

相关资料： [Niveau-5](https://drive.google.com/drive/folders/1shh2g__ZFqqgOS8UBqW8o4MSxm5fnOdx?usp=sharing)

[![NPM version](https://img.shields.io/badge/ProjetISA-SleepQuality-blue.svg)]：我的学期大projet，总结两个点：
1. 能跟认识的靠谱人组队最好，千万别作死。
2. 最好别选Sorin MOGA当导师，吗的水上天。

睡眠质量这个课题其实还挺不错的，前提是有人帮你入门，这个课题涉及医学和深度学习，所以如果能好好做应该是不错的。如果大家对这个课题感兴趣，推荐大家看看我的github，我托管了所有的代码和文档，希望能够帮助大家：[睡眠质量检测](https://github.com/lhaippp/Measuring-Sleep-Quality)

### 总结
时光飞逝，眨眼间一年半就过去了，总结我的TB时光，我感觉自己非常幸运，能够来到这个小渔村跟大家一起学习玩耍旅行。这里的大部分老师都很善良热心，rak味道真的不错，后海风光也很好。作为我的最后一段学生生涯，我给他打💯！
