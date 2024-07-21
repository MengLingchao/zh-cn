---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


孟令超，对外经济贸易大学中国金融学院助理教授。博士毕业于北京大学经济学院。我的研究兴趣包括资产定价，文本分析，机器学习，行为金融，资产配置，宏观政策与宏观预测。我的研究聚焦于充分运用文本分析与机器学习等前沿方法，测度情绪、预期等重要主观变量，建模时变性、非线性等理论特征和典型事实，解决资产定价、组合配置、宏观政策分析与宏观经济预测等重要问题。

我的研究兴趣包括: 
- 资产定价
- 文本分析
- 机器学习
- 行为金融
- 资产配置
- 宏观政策与宏观预测

<span class='anchor' id='-lwfb'></span>
# 论文发表

## 英文发表
---

- **Forecasting Inflation Using Economic Narratives**, `Journal of Business & Economic Statistics`, 2024, with Yongmiao Hong, [Fuwei Jiang](https://fuweijiang.weebly.com/), Bowen Xue
  - **Abstract:** We use economic narratives to forecast inflation with a large news corpus and machine learning algorithms. The economic narratives from the full text content of over 880,000 Wall Street Journal articles are decomposed into multiple time series representing interpretable news topics, which are then used to predict inflation. The results indicate that narrative-based forecasts are more accurate than the benchmarks, especially during recession periods. Narrative-based forecasts perform better in long-run forecasting and provide incremental predictive information even after controlling macroeconomic big data. In particular, information about inflation expectations and prices of specific goods embedded in narratives contributes to their predictive power. Overall, we provide a novel representation of economic narratives and document the important role of economic narratives in inflation forecasting.
  - [`Article Link`](https://www.tandfonline.com/doi/full/10.1080/07350015.2024.2347619?src=exp-la)
- **Certainty of Uncertainty for Asset Pricing**, `Journal of Empirical Finance`, 2024, with [Fuwei Jiang](https://fuweijiang.weebly.com/), Jie Kang
  - **Abstract**: Uncertainty is known to be crucial in asset pricing, yet evidence from a comprehensive analysis of various uncertainty measures remains sparse. By machine learning, we construct a novel economic uncertainty index derived from a heterogeneous range of uncertainty measures and investigate its predictability of stock returns. Our composite uncertainty index exhibits robust in- and out-of-sample predictability of stock market returns over the one- to 12-month horizon. The predictive power stems from the volatility-orthogonal components of individual uncertainty measures and becomes more pronounced during high uncertainty and high sentiment periods. The predictability of our economic uncertainty index aligns with theoretical frameworks linking uncertainty to future investment, cash flows, and market expectations.
  - [`Article Link`](https://www.sciencedirect.com/science/article/pii/S0927539824000367)





## 中文发表
---
- **深度学习、文本情绪与金融市场：兼论“人工智能+金融”的逻辑**. `管理世界`，2024，与 [姜富伟](https://fuweijiang.weebly.com/)，刘雨旻 合作
  -  **摘要**：“人工智能+”行动是发展新质生产力的重要途径，其在金融领域的应用有助于金融强国建设。本文创新性地融合结构化金融市场数据和非结构化金融文本大数据，并结合中国特色金融市场的独特特征，训练了一个更适用于我国金融领域的中文金融大语言模型，并开展金融市场情绪测度和资产价格风险预测。研究发现，与传统字典法相比，使用中文金融大语言模型构建的大模型情绪在金融市场回报预测方面表现显著更佳。大模型情绪对很多宏观经济变量也有显著预测能力，能够捕捉非理性情绪冲击对宏观经济基本面的影响。大模型情绪在经济下行和极端风险事件期间的预测效果更强，契合了金融理论中非理性情绪对金融市场和宏观经济会产生非对称与非线性影响的结果。综上，本研究展现了“人工智能+”行动在我国金融领域应用落地的潜在技术路径和理论逻辑。
- **媒体文本情绪与股票回报预测**. `经济学（季刊）`，2021，与 [姜富伟](https://fuweijiang.weebly.com/), [唐国豪](https://jt.hnu.edu.cn/info/1167/6086.htm) 合作
  - **摘要**：本文在 Loughran and MacDonald (2011) 词典的基础上通过人工筛选和 word2vec 算法扩充，构建了一个更新更全面的中 文金融情感词典。我们使用该情感词典计算我国财经媒体文本情绪指标，发现媒体文本情绪可以更准确地衡量我国股市投资者情绪的变化，对我国股票回报有显著的样本内和样本外预测能力。媒体文本情绪对一些重要的宏观经济指标也有显著的预测能力，具有重要的学术和实践应用价值。
- **防风险背景下的金融稳定沟通：基于银行系统性风险的视角**. `世界经济`，2024，与 [姜富伟](https://fuweijiang.weebly.com/)，李梦如 合作  
  - **摘要**：防范系统性金融风险对于维护金融和经济稳定安全至关重要。本文从中国人民银行网站收集了2010至2020年所有金融稳定沟通文本，然后使用情感词典法构建金融稳定沟通指数，并基于A股上市商业银行数据，研究金融稳定沟通防范银行系统性风险的效果。本文发现正面的沟通会导致银行系统性风险下降，作用机制为：正面沟通一方面可以引导和协调存款人预期，避免银行挤兑发生，有利于降低银行的流动性风险；另一方面可以稳定金融市场，提高借款企业偿债能力，有利于降低银行的信用风险。此外，正面沟通还可以减弱银行间的风险传染，然而当正面沟通超出一定临界值后可能会提高系统性风险。本文研究凸显了加强预期管理的重要性，对于央行借助以金融稳定沟通为代表的预期管理政策工具防范系统性风险具有参考价值。

<span class='anchor' id='-xshy'></span>
# 学术会议
## 参与会议
- **2024**：第五届中国宏观经济学者论坛（北京），2024 China International Conference in Finance（CICF，北京）
- **2023**：中国金融学年会（优秀论文奖）、中国金融工程年会（济南）、中国金融学科年会（北京）、中国经济学年会（广州）、2023 CFRI & CIRF Joint Conference (Research Excellence Award)、中国金融科技学术年会（成都）、《计量经济学报》“大数据计量经济学理论与应用”研讨会（广州）、环亚太青年计量学者（YEAP）会议（上海）、PKU-NUS 数量金融与经济学国际学术会议（深圳）、中国青年经济学家联谊会（YES）（上海）、《金融学季刊》论坛（广州）等
- **2022**：中国金融工程学年会（线上）、计量经济学者论坛（线上）、中国金融科技学术年会（线上）
- **2021**： 中国经济学年会、应用经济学高端前沿论坛（优秀论文奖）

## 会议获奖
1. 2023年10月，中国金融学年会嘉实基金资产定价最佳论文（2篇）
2. 2023年10月，中国金融学年会最佳论文三等奖
3. 2023年7月，第十七届中国经济增长与周期高峰论坛优秀论文
4. 2023年7月，China Finance Review International & China International Risk Forum Joint Conference， Sinofin CCER Database Research Excellence Award
5. 2023年11月，第七届全国金融学博士生学术论坛优秀论文二等奖
6. 2021年12月，第四届应用经济学高端前沿论坛优秀论文


