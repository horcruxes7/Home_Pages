---
title: "A Multiple Object Tracking Method for People Flow Statistical Monitoring based on FairMOT"
subtitle: '一种基于FairMOT的多目标跟踪人流量监测方法'
authors:
- admin
- Yong Du
author_notes:
- "1"
- "Corresponding Author"
date: "2021-06-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-04T00:00:00Z"
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]
# Publication name and optional abbreviated publication name.
publication: "China National Intellectual Property Administration (中国国家知识产权局)"
publication_short: "Patent, CNIPA"

abstract: "The invention discloses a FairMOT-based Multiple Object Tracking for People Flow Statistical Monitoring method, which relates to the field of People Flow Statistical using computer vision technique.<br>
Including the following steps: 1) pre-collect the surveillance area video through the high-definition camera, and read the Real-Time video upload-stream of the camera through Python-OpenCV modules; 2) then input the acquired real-time video stream to the Encoder-Decoder Network, extract the high-resolution feature map as the output feature map; 3) obtain the output feature map for Object Detection task and Re-ID task respectively, to perform multi-target tracking. <br>
The invention has real-time capability, with high accuracy, and high robustness. It can adapt to congestion, density and eliminate the restriction of single-channel access scenes. It not only solves the phenomenon that the identity switch causes the resulting error after the occlusion and other blurring phenomena appear, but also improves the recognition accuracy of dense scenes. The phenomenon of resulting error caused by identity switching improves the recognition accuracy of dense scenes, and the simple hardware installation reduces a lot of costs. Only the wireless camera and divide the Region of Interest (ROI) for users to observe the volume of people flow."

# Summary. An optional shortened abstract.
summary:

#tags:
#- Source Themes
#featured: false

links:
- name: Patent
  url: http://english.cnipa.gov.cn/
url_pdf: https://www.patenthub.cn/patent/CN112906590A.html?ds=cn&ds=cn&dm=mix&p=1&ps=10&s=score!&m=none&q=%E4%B8%9C%E5%8C%97%E5%86%9C%E4%B8%9A%E5%A4%A7%E5%AD%A6%20%E5%88%98%E5%AE%87%E6%98%95#/pdf
url_code: ''
url_project: ''
url_slides: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image right: Yuxin Liu'
  focal_point: ""
  preview_only: false
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
**Patent Authorization Number**: CN112906590A <br>
**Advisor**: [Prof. Yong Du](http://dqxx.neau.edu.cn/info/1089/2087.htm)<br>
**Summary**: This work was done independently by me under the guidance of Associate Professor Yong Du of NUAU AI Lab.<br>
It based on real surveillance video,instead of simple datasets, which flexibly collected video stream and pushed it to my code, the great thing about this work is that the Cloud Server interaction between the MOT algorithm and the monitoring software(.NET) developed is almost real-time, which can be used for passengers and students in complex scenes such as airports, stations, schools, etc. The social safety distance of people is calculated dynamically (To some extent avoid Covid-19), and I have designed a mobile app to use the LSTM algorithm to estimate the number of people in the future. These are all based on the area of interest.<br>

<img src= "flow.gif" width = "300" height = "200" alt="flow" align=center />
<br>

### 摘要
本发明公开了一种基于FairMOT的多目标跟踪人流量监测方法，涉及基于计算机视觉的人流量统计监测技术领域，包括以下步骤：预先通过摄像头采集区域内监控视频，并通过Python‑OpenCV读取摄像头的实时视频流；将获取的实时视频流输入图像到Encoder‑Decoder Network，提取高分辨率的特征映射，并作为输出特征图；将获取输出特征图分别进行目标检测任务和Re‑ID任务，并进行多目标跟踪。本发明具有实时性，高精确度，高鲁棒性的能够适应拥堵、密集并消除单通道出入场景限制的系统，不仅通过目标检测任务和Re‑ID任务，解决了经过遮挡等模糊现象出现后身份切换造成结果误差的现象，提高了密集场景的识别准确度，而且硬件安装简单降低大量成本，仅需无线摄像头安置划分感兴趣区域便于使用者观察人流量。
