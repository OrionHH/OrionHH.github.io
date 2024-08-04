---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}


主要研究方向脑-机接口、神经电信号分析与处理、深度学习。此栏主要记录所做工作，方便后续梳理。

---

# 博士学位论文

博士期间主要围绕视觉型脑机接口展开研究，题目为“视觉型脑-机接口特征调制与增强关键技术研究-The key Technology of Feature Modulation and Enhancement for Visual Brain-Computer Interface”，下载链接请见[博士学位论文下载](https://www.researchgate.net/publication/371540188_boshixueweilunwen-Doctoral_Thesis-shijuexingnao-jijiekoutezhengdiaozhiyuzengqiangguanjianjishuyanjiu-The_key_Technology_of_Feature_Modulation_and_Enhancement_for_Visual_Brain-Computer_Interface)

> **博士学位论文摘要：**   
> <font size="2"><p style="text-indent:2em"></p>视觉型脑-机接口（Visual brain-computer interface, v-BCI）是依据大脑对外源性视觉刺激的响应，实现大脑与外界环境直接交互的通信或控制系统。由于v-BCI具有特征诱发稳定、信息传输速率（Information transfer rate, ITR）高等优势，在医疗健康、工业控制等领域展现出广阔的应用前景。然而，目前v-BCI研究仍存在指令集维度低、分类识别效果有待提高的问题和技术瓶颈，阻碍了其在多场景下的应用。为此，本文从v-BCI特征调制方法着手，利用光刺激调制脑电响应的方式扩增指令数量，利用磁刺激调制脑电响应的方式提升分类识别效果，探究增强脑电特征的关键技术，以提升v-BCI的系统性能。  
> <p style="text-indent:2em"></p>在光刺激调制脑电响应，即视觉刺激编码调制方面，针对v-BCI中指令数量和交互速率互相制约，限制大指令集高速率v-BCI技术发展的问题，本文研究了混合多址编码调制方法，通过混合多种特征信息增强脑电特征，实现了指令数量的扩增，并基于此搭建和测试开源平台，进行了应用开发。首先，设计基于时-频分多址的新型混合编码范式，提出新型并发混合脑电特征及提取策略，开发108指令的高速率BCI编解码方法，在国际上首次将BCI指令数量扩增至百量级。其次，探究v-BCI编码关键因素刺激间时间间隔（Inter-stimulus interval, ISI）对并发混合脑电特征及系统性能的影响，通过设计等间隔变化的ISI参数，寻找最优的编码方式，系统ITR可显著提升9.15%。上述工作表明，采用多址编码方法和混合多种特征信息的方式，可以有效扩增指令数量。然后，搭建在线BCI开源平台BrainOn，并依托此平台和上述工作基础，继续采用多址编码策略，设计混合三种特征信息的新型编码范式，开发216指令高速率脑-机信息输入系统，进一步扩增v-BCI指令数量的同时，成功对平台进行测试，系统在线平均ITR达302.83 bits/min，是迄今最大指令集的高速率非侵入式BCI系统。最后，基于上述研究，提出基于笔画的新型汉字书写策略，开发基于v-BCI的机械臂汉字书写应用，在线平均操控正确率为84.05%，实现了BCI信息输出由“拼”到“写”的转变。  
> <p style="text-indent:2em"></p>在磁刺激调制脑电响应方面，针对v-BCI分类识别效果有待提高的问题，本文从与人类日常生活密切相关的地球磁场着手，探究与地磁场强度等量级的环境弱磁场对大脑的调制作用，从人类是否可以感知弱磁场强度变化和如何应用于v-BCI研究两方面展开，寻找新型磁刺激调制方式，以提升系统分类效果。首先，将环境弱磁场强度以固定频率变化，采集和分析不同磁场环境下受试者睁眼静息态的脑电数据。结果发现，弱磁场强度变化会显著影响脑电振荡节律的功率谱密度和节律间的相位-幅值耦合程度，初步证明了人类大脑可以感知弱磁场强度的变化。在此基础上，开展弱磁场对v-BCI性能的影响研究，以实验当地（北京）的地磁场强度为基准，等倍数改变环境磁场强度，采集和分析不同磁场环境下受试者执行快速序列视觉呈现任务的脑电数据。结果显示，相比于当地磁场强度，环境磁场强度的改变可显著影响上述任务诱发的事件相关电位N200、P300成分幅值，显著提升脑电特征可分性和系统分类识别性能（≥1.57%）。上述结果表明，环境弱磁场可以作为一种新型的非侵入式神经调制方式，用于提高v-BCI系统性能，也可为开发大指令集高速率v-BCI系统提供新的技术路径。   
> <p style="text-indent:2em"></p>综上，本文在光刺激调制方面，设计新型多址编码调制范式，通过混合多维信息增强脑电特征，先后将BCI指令数量扩增至百量级和二百量级，搭建了在线BCI开源平台，实现了脑控机械臂的汉字书写应用。在磁刺激调制方面，发现环境弱磁场可作为一种新型神经调制手段，显著提升v-BCI系统分类识别效果。本文相关工作为脑电特征调制研究提供了新方法和新思路，为开发适用于多场景的高性能BCI系统提供了平台和技术支撑。</font>

> <font size="2"> 关键词：脑-机接口；脑电；特征调制；特征增强；混合编码；弱磁场调制；大指令集</font>





{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
