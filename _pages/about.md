---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
carousels:
  - images: 
    - image: /images/sliders/202401_HNNU_Winter.jpg
      title: "HNNU in Winter"
    - image: /images/sliders/202306_Lushan.jpg
      title: "在庐山"
    - image: /images/sliders/202412_AsiaCarto.jpg
      title: "AsiaCarto24"
    - image: /images/sliders/202411_InClass.jpg
      title: "InClass"
    - image: /images/sliders/202301_JingweiBuilding.jpg
      title: "Jingwei Building"
    - image: /images/sliders/201801_at ETH.jpg
      title: "ETH"
---

<style>
.main-content {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

.sliderBar {
  flex: 4;

  border-radius: 8px;

}

.sliderText {
  flex: 5;
  background-color: #fff;
  border-radius: 8px;
  padding-top:1rem;
}

.carousel__holder {
  width: 100%;
  height: 90%;
}

@media (max-width:768px){
  .main-content{
    flex-direction:column;
  }
  .sliderBar{
    max-width:100%;
    order:0;
  }
  .sliderText{
    order:1;
  }
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 👨‍🏫 简介 {#Intro}
廖华，博士，副教授，硕士研究生导师，湖南师范大学“世承人才计划”青年优秀人才，国际地图协会(ICA)地理信息可视化认知专业委员会(CogVis)共同主席(Co-Chair)，湖南省测绘地理信息学会交通水利电力测绘地理信息技术专业委员会委员。主要研究方向为地理空间认知、空间导航视觉认知、智能地理信息人机交互。近年来在 IJGIS、CEUS、CaGIS、地理学报等期刊发表学术论文30余篇。主持国家自然科学基金、湖南省自然科学基金项目等多项课题，曾获地理信息科技进步奖一等奖(5/5)，湖南师范大学第24届青年教师课堂教学竞赛二等奖、百优教学设计，第十一届、十二届、十三届全国大学生GIS应用技能大赛“优秀指导老师”等多项荣誉。

<!-- 
{% include carousel.html height="50" unit="%" duration="5" number="1" %}

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In class</div><img src='images/in class.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**讲授课程**

- 数据结构（本科课程，第4学期，地理信息科学）
- 计算机图形学（本科课程，第5学期，地理信息科学）
- 地图学（本科课程，第2学期，地理科学）
- 专题地图编绘（本科课程，第5学期，地理科学）
- 地理空间认知理论与方法（本科课程，第6学期，地理信息科学）
- 遥感与大数据应用（硕士课程，第1学期，人文地理）

**研究方向**

- 基于眼动跟踪的地理空间认知、导航视觉认知、智能地理信息人机交互

**硕士研究生招生专业**

- 学硕：地图学与地理信息系统
- 专硕：资源与环境（测绘方向）
</div>

</div>

-->

<div class="main-content">
  <div class="sliderBar">
    {% include carousel.html height="50" unit="%" duration="5" number="1" %}
  </div>
  <div class='sliderText' markdown="1">


**讲授课程**

- 数据结构（本科课程，第4学期，地理信息科学）
- 计算机图形学（本科课程，第5学期，地理信息科学）
- 地图学（本科课程，第2学期，地理科学）
- 专题地图编绘（本科课程，第5学期，地理科学）
- 地理空间认知理论与方法（本科课程，第6学期，地理信息科学）
- 遥感与大数据应用（硕士课程，第1学期，人文地理）

**研究方向**

- 基于眼动跟踪的地理空间认知、导航视觉认知、智能地理信息人机交互

**硕士研究生招生专业**

- 学硕：地图学与地理信息系统
- 专硕：资源与环境（测绘方向）
</div>
</div>

# 📖 教育经历 {#education} 
- *2014.09 - 2019.06*, 北京师范大学地理科学学部, 地图学与地理信息系统，理学博士
- *2017.01 - 2018.01*，奥地利维也纳科技大学大地测量与地理信息学院，联合培养博士生
- *2011.09 - 2014.06*, 北京师范大学地理科学学部, 地图学与地理信息系统，理学硕士
- *2007.09 - 2011.06*, 湖南师范大学地理资源与环境科学学院, 地理信息系统，理学学士

# 🔥 承担课题 {#Wow}
- *2024 - 2026*, 湖南师范大学教学改革项目，大数据背景下地理信息科学专业学生的空间能力评估与培养研究，在研，*主持*
- *2024 - 2017*, 国家自然科学基金，面上项目，视觉注意驱动的自适应地图交互模型与方法，在研，*主持*
- *2021 - 2023*, 国家自然科学基金，青年项目，虚拟环境与真实环境下的行人地图导航视觉行为模式研究，结题，*主持*
- *2021 - 2023*, 湖南省自然科学基金，青年项目，基于眼动控制的地图交互算法研究，结题，*主持*
- *2020 - 2022*, 湖南省教育厅，优秀青年项目，面向空间认知的行人地图导航行为模式挖掘，结题，*主持*
- *2023 - 2026*, 国家自然科学基金, 重点项目, 地理空间类脑智能导航基础理论与方法，在研，参与
- *2019 - 2022*, 国家自然科学基金, 面上项目, 基于眼动跟踪的行人地图导航行为模式识别与预测方法研究，结题，参与
- *2017 - 2021*, 国家重点研发计划项目，地理大数据挖掘与时空模式发现，结题，参与
- *2015 - 2018*, 国家自然科学基金, 面上项目, 基于视觉注意与眼动跟踪的地图认知计算模型与方法研究，结题，参与
- *2010 - 2024*, 国家科技支撑项目，周边地缘环境信息建模与安全评估关键技术研究，结题，参与

# 👨🏻‍🎓 研究生 {#postgraduate}
- *在读* 孟晋华 卢柏言 谭思思 周越 刘灿
- *已毕业* 赵文迪 张昌博 

# 🎖 指导获奖 {#awards} 
- *2024.11* 刘更好, 边家欣, 邢华芬, 陈科仰. 第十三届全国大学生GIS应用技能大赛, 特等奖.
- *2024.11* 边家欣, 陈科仰, 邢华芬, 刘更好, 周鑫. 湖南第七届大学生测绘综合技能大赛GIS应用赛, 一等奖. 
- *2024.09* 吴名. 2024年全国大学生测绘学科创新创业智能大赛（测绘程序设计比赛非专业组）, 二等奖.  
- *2023.09* 李昌哲. 2023年全国大学生测绘学科创新创业智能大赛（测绘程序设计比赛非专业组）, 一等奖. 
- *2022.07* 孙铭悦, 陈铭臻. 2022年全国大学生测绘学科创新创业智能大赛（测绘程序设计比赛非专业组）, 二等奖. 
- *2020.11* 疫苗下的“傲慢与偏见”, 2020易智瑞杯中国大学生GIS软件开发竞赛·地图故事组, 优胜奖.
- *2019.03* 刘茹, 易嘉慧, 杨敏, 欧阳睿, 胡成凤. 湖南省村级土地利用规划编制软件, 大学生创新训练项目（省级）, 已结题. 

# 💬 学术交流 {#talks} 
- *2024.08*, 第六十三届欧洲区域科学协会年会, How Does the COVID-19 Pandemic Affect Employment Outcomes Differently for College Graduates with Diverse Characteristics (oral), 葡萄牙特尔塞拉. （交流学习）. 
- *2023.10*, 第十五届中日韩地理学联合年会, Impact of Clan Culture on the Spatial Heterogeneity of Betrothal Gifts in China (oral), 韩国首尔. （交流学习）. 
- *2019.08*, Goldschmidt2019, 西班牙巴塞罗那. （学习×2）. 
- *2018.09*, 第八届亚洲区域科学会议, 韩国济州. （主要是学习） 

# 📝 期刊论文 {#publication} 
- [30] <b>廖华*</b>, 孟晋华, 赵文迪, 董卫华. (2025). 真实环境下行人导航认知负担度量的瞳孔指标适用性检验, 测绘科学, 50(2):57-66. (in press)
- [29] Griffin, A., Reichenbacher, T., <b>Liao, H.</b>, Wang, W., Cao, Y. (2024). Cognitive issues of mobile map design and use. *Journal of Location Based Services*, [https://doi.org/10.1080/17489725.2024.2371288](https://doi.org/10.1080/17489725.2024.2371288).
- [28] Zhang, C., <b>Liao, H.*</b>, & Meng, J. (2025). Evaluating the performance of gaze interaction for map target selection. *Cartography and Geographic Information Science*, 52(1):82-102. [https://doi.org/10.1080/15230406.2024.2335331](https://doi.org/10.1080/15230406.2024.2335331).
- [27] Zhang, C., <b>Liao, H.*</b>, Huang, Y., & Dong, W. (2023). Evaluating the Usability of a Gaze-Adaptive Approach for Identifying and Comparing Raster Values between Multilayers. *ISPRS International Journal of Geo-Information*, 12(10), 412. [https://doi.org/10.3390/ijgi12100412](https://doi.org/10.3390/ijgi12100412).
- [26] <b>Liao, H.</b>, Dong, W. & Zhan, Z. (2022). Identifying Map Users with Eye Movement Data from Map-Based Spatial Tasks: User Privacy Concerns. *Cartography and Geographic Information Science*, 49(1), 50-69. doi: [https://doi.org/10.1080/15230406.2021.1980435](https://doi.org/10.1080/15230406.2021.1980435).
- [25] <b>Liao, H.</b>, Zhang, C., Zhao, W. & Dong, W. (2022). Toward Gaze-Based Map Interactions: Determining the Dwell Time and Buffer Size for the Gaze-Based Selection of Map Features. *ISPRS International Journal of Geo-Information*,11(2), 127. doi: [https://doi.org/10.3390/ijgi11020127](https://doi.org/10.3390/ijgi11020127).
- [24] <b>Liao, H.</b>, Zhao, W., Zhang, C. & Dong, W. (2022). Exploring Eye Movement Biometrics in Real-World Activities: A Case Study of Wayfinding. *Sensors*, 22(8), 2949. doi: [https://doi.org/10.3390/s22082949](https://doi.org/10.3390/s22082949).
- [23] <b>Liao, H.</b>, Zhao, W., Zhang, C., Dong, W. & Huang, H. (2022). Detecting Individuals’ Spatial Familiarity with Urban Environments Using Eye Movement Data. *Computers, Environment and Urban Systems*, 93, 1-12. doi: [https://doi.org/10.1016/j.compenvurbsys.2022.101758](https://doi.org/10.1016/j.compenvurbsys.2022.101758).
- [22] Dong, W., <b>Liao, H. *</b>, Liu, B., Zhan, Z., Liu, H., Meng, L. & Liu, Y. (2020). Comparing pedestrians' gaze behavior in desktop and in real environments. *Cartography and Geographic Information Science*, 47(5), 432–451. doi: [https://doi.org/10.1080/15230406.2020.1762513](https://doi.org/10.1080/15230406.2020.1762513).
- [21] <b>Liao, H.</b>, Dong, W., Huang, H., Gartner, G. & Liu, H. (2019). Inferring user tasks in pedestrian navigation from eye movement data in real-world environments. *International Journal of Geographical Information Science*,33(4), 739–763. doi: [https://doi.org/10.1080/13658816.2018.1482554](https://doi.org/10.1080/13658816.2018.1482554).
- [20] <b>Liao, H.</b>, Wang, X., Dong, W. & Meng, L. (2019). Measuring the influence of map label density on perceived complexity: A user study using eye tracking. *Cartography and Geographic Information Science*, 46(3), 210–227. doi: [https://doi.org/10.1080/15230406.2018.1434016](https://doi.org/10.1080/15230406.2018.1434016).
- [19] <b>Liao, H.</b> & Dong, W. (2017). An exploratory study investigating gender effects on using 3D maps for spatial orientation in wayfinding. *ISPRS International Journal of Geo-Information*, 6(3), 1-19. doi: [https://doi.org/10.3390/ijgi6030060](https://doi.org/10.3390/ijgi6030060).
- [18] <b>Liao, H.</b>, Dong, W., Peng, C. & Liu, H. (2017). Exploring differences of visual attention in pedestrian navigation when using 2D maps and 3D geo-browsers. *Cartography and Geographic Information Science*, 44(6), 474-490. doi: [https://doi.org/10.1080/15230406.2016.1174886](https://doi.org/10.1080/15230406.2016.1174886).
- [17] <b>Liao, H.</b>, Dong, W., Liu, H. & Ge, Y. (2015). Towards Measuring and Visualizing Sustainable National Power—A Case Study of China and Neighboring Countries. *ISPRS International Journal of Geo-Information*, 4(3), 1672-1692. doi: [https://doi.org/10.3390/ijgi4031672](https://doi.org/10.3390/ijgi4031672).
- [16] He, B., Dong, W., <b>Liao, H.</b>, Ying, Q., Shi, B., Liu, J. & Wang, Y. (2023). A geospatial image based eye movement dataset for cartography and GIS. *Cartography and Geographic Information Science*, 1-16. doi: [https://doi.org/10.1080/15230406.2022.2153172](https://doi.org/10.1080/15230406.2022.2153172).
- [15] Dong, W., Qin, T., Yang, T., <b>Liao, H.</b>, Liu, B., Meng, L. & Liu, Y. (2022). Wayfinding Behavior and Spatial Knowledge Acquisition: Are They the Same in Virtual Reality and in Real-World Environments? *Annals of the American Association of Geographers*, 112(1), 226-246. doi: [https://doi.org/10.1080/24694452.2021.1894088](https://doi.org/10.1080/24694452.2021.1894088).
- [14] Dong, W., Yang, T., <b>Liao, H.</b> & Meng, L. (2020). How does map use differ in virtual reality and desktop-based environments? *International Journal of Digital Earth*, 13(12), 1484-1503. doi: [https://doi.org/10.1080/17538947.2020.1731617](https://doi.org/10.1080/17538947.2020.1731617).
- [13] Dong, W., Zhan, Z., <b>Liao, H.</b>, Meng, L. & Liu, J. (2020). Assessing Similarities and Differences between Males and Females in Visual Behaviors in Spatial Orientation Tasks. *ISPRS International Journal of Geo-Information*, 9(2), 115. doi: [https://doi.org/10.3390/ijgi9020115](https://doi.org/10.3390/ijgi9020115).
- [12] Dong, W., Qin, T., <b>Liao, H.</b>, Liu, Y. & Liu, J. (2020). Comparing the roles of landmark visual salience and semantic salience in visual guidance during indoor wayfinding. *Cartography and Geographic Information Science*, 47(3), 229-243. doi: [https://doi.org/10.1080/15230406.2019.1697965](https://doi.org/10.1080/15230406.2019.1697965).
- [11] Wang, C., Chen, Y., Zheng, S. & <b>Liao, H.</b> (2018). Gender and Age Differences in Using Indoor Maps for Wayfinding in Real Environments. *ISPRS International Journal of Geo-Information*, 8(1), 11. doi: [https://doi.org/10.3390/ijgi8010011](https://doi.org/10.3390/ijgi8010011).
- [10] Liu, Z., Anderson, B., Yan, K., Dong, W., <b>Liao, H.</b> & Shi, P. (2017). Global and regional changes in exposure to extreme heat and the relative contributions of climate and population change. *Scientific Reports*, 7, 43909. doi: [https://doi.org/10.1038/srep43909](https://doi.org/10.1038/srep43909).
- [9] Dong, W., Zhang, S., <b>Liao, H.</b>, Liu, Z., Li, Z. & Yang, X. (2016). Assessing the effectiveness and efficiency of map colour for colour Impairments using an eye-tracking approach. *The Cartographic Journal*, 53(2), 166-176. doi: [https://doi.org/10.1179/1743277413Y.0000000053](https://doi.org/10.1179/1743277413Y.0000000053).
- [8] Dong, W., Li, X., Wang, P., <b>Liao, H.</b>, Wang, X., & Wang, Q. (2015) The Effects of Weather Factors on Hand, Foot and Mouth Disease in Beijing. *Scientific Reports*. DOI: [https://doi.org/10.1038/srep19247](https://doi.org/10.1038/srep19247).
- [7] Chen, J., Dong, W., Li, R., <b>Liao, H.</b>, & Cheng Y. (2015) A GIS Perspective for Borderlands Modelling and Understanding: Challenges and a Research Agenda. *ISPRS International Journal of Geo-Information*, 6, 661-676. DOI: [https://doi.org/10.3390/ijgi4020661](https://doi.org/10.3390/ijgi4020661).
- [6] Dong, W., Liu, Z., <b>Liao, H.</b>, Tang, Q. & Li, X.e. (2015). New climate and socio-economic scenarios for assessing global human health challenges due to heat risk. *Climatic Change*, 130, 505-518. doi: [https://doi.org/10.1007/s10584-015-1372-8](https://doi.org/10.1007/s10584-015-1372-8).
- [5] Dong, W., Z. Liu, L. Zhang, Q. Tang, <b>H. Liao</b> & X. e. Li (2014) Assessing Heat Health Risk for Sustainability in Beijing’s Urban Heat Island. *Sustainability*, 6, 7334-7357. DOI: [https://doi.org/10.3390/su6107334](https://doi.org/10.3390/su6107334).
- [4] Dong, W., <b>Liao, H.</b>, Xu, F., Liu, Z., & Zhang, S. (2014). Using eye tracking to evaluate the usability of animated maps. *Science China Earth Sciences*, 57(3): 512-522. DOI: [https://doi.org/10.1007/s11430-013-4685-3](https://doi.org/10.1007/s11430-013-4685-3).
- [3] Dong, W., <b>Liao, H.</b>, Roth, R.E., & Wang, S. (2014). Eye-tracking to Explore Potential of Enhanced Imagery Basemaps in Web Mapping. *The Cartographic Journal*, 51(4): 313-329. DOI: [https://doi.org/10.1179/1743277413Y.0000000071](https://doi.org/10.1179/1743277413Y.0000000071).
- [2] 董卫华, <b>廖华*</b>, 詹智成, 刘兵, 王圣凯 & 杨天宇 (2019). 2008年以来地图学眼动与视觉认知研究新进展. 地理学报, 74(3), 599-614. doi: [https://doi.org/10.11821/dlxb201903015](https://doi.org/10.11821/dlxb201903015).
- [1] 周秋文, 杨胜天, <b>廖华</b>, 马龙生, 韦小茶 & 颜红 (2016). 地缘环境单元划分方法及实例研究. 世界地理研究, 25(4), 58-66. Doi: [https://doi.org/10.3969/j.issn.1004-9479.2016.04.007](https://doi.org/10.3969/j.issn.1004-9479.2016.04.007).



<script defer src="https://cn.vercount.one/js"></script>
<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?6f4a6579643562aeebf8bcf02017b627";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>

{% include text-expand.html %}
