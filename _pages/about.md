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
- [30] <b>廖华*</b>,孟晋华,赵文迪,董卫华. 测绘科学，2025，50(2):57-66. (in press)
- 孙字祥,胡涛,李超民,杨凤玲,<b>周楷淳*</b>.湘江流域农村居民点时空演变特征及影响因素研究[J].水土保持研究,2024,31(06):344-353.DOI:10.13869/j.cnki.rswc.2024.06.043.
- 杨妍,于成,傅安洲,孙字祥,周楷淳*.城市三维形态空间分异格局对大气污染时空分布响应研究——以长沙市为例[J].湖南师范大学自然科学学报,2024,47(02):12-21.
- Zhou K, Fu A, Xiao C, et al. [Understanding Idle Land Using Local Environmental Characteristics: A Case Study of Liuyang, China[J]](https://www.mdpi.com/2071-1050/15/8/6663). Sustainability, 2023, 15(8): 6663.
- Li J, Xie B, Gao C, Zhou K, et al. [Impacts of natural and human factors on water-related ecosystem services in the Dongting Lake Basin[J](https://www.sciencedirect.com/science/article/abs/pii/S0959652622029833). Journal of Cleaner Production, 2022, 370: 133400.
- Li J, Zhou K, Xie B, et al. [Impact of landscape pattern change on water-related ecosystem services: Comprehensive analysis based on heterogeneity perspective[J]](https://www.sciencedirect.com/science/article/pii/S1470160X21010372). Ecological Indicators, 2021, 133: 108372.
- 李晓青,徐修桥,谢炳庚,刘茹,周楷淳*.喀斯特地区农村居民点对石漠化演变的影响[J].经济地理,2020,40(10):154-163.DOI:10.15957/j.cnki.jjdl.2020.10.018.
- Zhou K, Hu C, Zhang H, et al. [Why do we hardly see people with visual impairments in the street? A case study of Changsha, China[J]](https://www.sciencedirect.com/science/article/pii/S0143622818311172). Applied geography, 2019, 110: 102043.

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
