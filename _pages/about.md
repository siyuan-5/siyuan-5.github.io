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

Hi, I’m Siyuan Wu, I’m a junior student at <img src='images/HUST.png' style='width: 1.2em;'> [Huazhong University of Science and Technology](https://english.hust.edu.cn/). I have the privilege of being a visiting student to LAIR, where I work with Prof. Lichao Sun at Lehigh University and Prof.Yao Wan at HUST.
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->



# 💡 Research Interest

- LLM-based Agents: tool usage, efficiency and utility.
- Trustworthy AI: safety, truthfulness, fairness, robustness, privacy and machine ethics of AI model.
- LLM4Code: code intelligence,apply LLMs to solve code-relevant tasks.

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 [HonestLLM](https://arxiv.org/abs/2406.00380) has been accepted by NeurIPS 2024! Congratulations to [Chujie](https://flossiee.github.io/) and [Yue](https://howiehwong.github.io/) !
- *2024.05*: &nbsp;🎉🎉 [TrustLLM](https://trustllmbenchmark.github.io/TrustLLM-Website/) has been accepted by ICML 2024! Congratulations to [Yue](https://howiehwong.github.io/)!
- *2024.01*: &nbsp;🎉🎉 [MetaTool](https://arxiv.org/abs/2310.03128) has been accepted by ICLR 2024! Congratulations to [Yue](https://howiehwong.github.io/)!


# 📝 Publications 




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/UniGen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

![ICLR 2025](https://img.shields.io/badge/ICLR-2025-ff9671) **UniGen: Unified Synthetic Dataset Generation via Large Language Models** 
 
[[PDF]](https://arxiv.org/abs/2406.18966) [[Github]](https://github.com/HowieHwong/UniGen) [[Website]](https://unigen-framework.github.io/)

**Siyuan Wu** \*, Yue Huang \*, Chujie Gao, Dongping Chen, Qihui Zhang, Yao Wan, Tianyi Zhou, Chaowei Xiao, Jianfeng Gao, Xiangliang Zhang, Lichao Sun


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/HonestLLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


![NeurIPS 2024](https://img.shields.io/badge/NeurIPS-2024-228B22) **The Best of Both Worlds*: Toward an Honest and Helpful Large Language Model**
[[PDF]](https://arxiv.org/abs/2406.00380)

Chujie Gao \*, **Siyuan Wu** \*, Yue Huang\*, Dongping Chen \*,Qihui Zhang \*, Zhengyan Fu, Yao Wan, Lichao Sun, Xiangliang Zhang

[**Code**](https://github.com/Flossiee/HonestyLLM) [![](https://img.shields.io/github/stars/Flossiee/HonestyLLM)](https://github.com/Flossiee/HonestyLLM)
[![Website](https://img.shields.io/badge/Website-%F0%9F%8C%8D-blue)](https://honestllm.github.io/)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/trustllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

![ICML 2024](https://img.shields.io/badge/ICML-2024-A84111) [TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/abs/2401.05561)

Yue Huang \*, Lichao Sun \*, Haoran Wang\*, **Siyuan Wu** \*, Qihui Zhang \*, Chujie Gao \*, Yixin Huang, Wenhan Lyu , Yixuan Zhang, Xiner Li, Zhengliang Liu, Yixin Liu, Yijue Wang, Zhikun Zhang, Bhavya Kailkhura, Caiming Xiong, et al. (*: major contribution)


[**Toolkit & Code**](https://github.com/HowieHwong/TrustLLM) [![](https://img.shields.io/github/stars/HowieHwong/TrustLLM)](https://github.com/HowieHwong/TrustLLM)
[![ibm](https://img.shields.io/badge/Invited%20Talk-IBM%20Research-blue)](https://research.ibm.com/)
[![huggingface](https://img.shields.io/badge/huggingface-Daily%20Paper-yellow)]()
[![report](https://img.shields.io/badge/Reported%20By-机器之心-brown)](https://mp.weixin.qq.com/s/iah6Wz0VsMsJx_wCtgirBw) 
[![Website](https://img.shields.io/badge/Website-%F0%9F%8C%8D-blue)](https://trustllmbenchmark.github.io/TrustLLM-Website/)
[![Dataset](https://img.shields.io/badge/Dataset-%F0%9F%92%BE-green)](https://huggingface.co/datasets/TrustLLM/TrustLLM-dataset)
[![Data Map](https://img.shields.io/badge/Data%20Map-%F0%9F%8D%9F-orange)](https://atlas.nomic.ai/map/f64e87d3-c769-4a90-b15d-9dc833acc8ba/8e9d7045-503b-4ba0-bc64-7201cb7aacee?xs=-16.14086&xf=-1.88776&ys=-7.54937&yf=3.88213)
[![Leaderboard](https://img.shields.io/badge/Leaderboard-%F0%9F%9A%80-brightgreen)](https://trustllmbenchmark.github.io/TrustLLM-Website/leaderboard.html)
[![Toolkit Document](https://img.shields.io/badge/Toolkit%20Document-%F0%9F%93%9A-blueviolet)](https://howiehwong.github.io/TrustLLM/)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/GUI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

![ICLR 2025](https://img.shields.io/badge/ICLR-2025-ff9671) **GUI-World: A Dataset for GUI-oriented Multimodal LLM-based Agents** [[PDF]](https://arxiv.org/abs/2406.10819) [[Github]](https://github.com/Dongping-Chen/GUI-World) [[Website]](https://gui-world.github.io)

Dongping Chen \*, Yue Huang \*, **Siyuan Wu** \*, Jingyu Tang \*, Liuyi Chen, Yilin Bai, Zhigang He, Chenlong Wang, Huichi Zhou, Yiqiang Li, Tianshuo Zhou, Yue Yu, Chujie Gao, Qihui Zhang, Yi Gui, Zhen Li, Yao Wan, Pan Zhou, Jianfeng Gao, Lichao Sun

</div>
</div>


<div class='paper-box'><div class='paper-box-image'>
<div>
<div class="badge">ICLR 2024</div>
<img src='images/metatool_00.png' alt="sym" width="100%">
</div>
</div>
<div class='paper-box-text' markdown="1">

![ICLR 2024](https://img.shields.io/badge/ICLR-2024-7740bd) **MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use**
[PDF](https://arxiv.org/abs/2310.03128)

Yue Huang, Jiawen Shi, Yuan Li, Chenrui Fan, **Siyuan Wu**, Qihui Zhang, Yixin Liu, Pan Zhou, Yao Wan, Neil Zhenqiang Gong, Lichao Sun

[**Code**](https://github.com/HowieHwong/MetaTool) [![](https://img.shields.io/github/stars/HowieHwong/MetaTool)](https://github.com/HowieHwong/MetaTool)

</div>
</div>



<div class='paper-box-text' markdown="1">

![WWW 2025](https://img.shields.io/badge/WWW-2025-4682B4) **WebCode2M: A Real-World Dataset for Code Generation from Webpage Designs**

Yi Gui, Zhen Li, Yao Wan, Yemin Shi, Hongyu Zhang, Yi Su, Bohua Chen, Dongping Chen, **Siyuan Wu**, Xing Zhou, Wenbin Jiang, Hai Jin, Xiangliang Zhang

</div>



<div class='paper-box-text' markdown="1">
![EMNLP 2024](https://img.shields.io/badge/EMNLP-2024-7740bd) **1+1>2: Can Large Language Models Serve as Cross-Lingual Knowledge Aggregators?**
[PDF](https://arxiv.org/abs/2402.14853)

Yue Huang, Chenrui Fan, Yuan Li, **Siyuan Wu**, Tianyi Zhou, Xiangliang Zhang, Lichao Sun
</div>


<div class='paper-box-text' markdown="1">

![EACL 2024](https://img.shields.io/badge/EACL-2024-7740bd) **NL2Formula: Generating Spreadsheet Formulas from Natural Language Queries**
[PDF](https://arxiv.org/abs/2406.14721)
Wei Zhao, Zhitao Hou, **Siyuan Wu**, Yan Gao, Haoyu Dong, Yao Wan, Hongyu Zhang, Yulei Sui, Haidong Zhang
</div>


<!-- # 🍀 Preprint -->



# 📖 Educations
*2021.09 - 2025.06 (expected), BEng., <img src='images/HUST.png' style='width: 1.2em;'> [Huazhong University of Science and Technology](https://english.hust.edu.cn/) 


<!-- # 💻 Internships
- *2023.04 - (now)*,  AI research intern, Huazhong University of Science and Technology, working under the guidance of Prof. [Yao Wan](http://wanyao.me/). -->