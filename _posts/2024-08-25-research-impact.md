---
layout: post
title: The Rise of Computer Vision and Deep Learning’s Impact
date: 2024-08-25 11:46:00
featured: true
description: Understanding the impact of computer vision and deep learning research. 
tags: deep-learning computer-vision ai
categories: research-introduction
# thumbnail: assets/img/9.jpg
# images:
#   compare: false
#   slider: false
chart:
  chartjs: true
pretty_table: true
---


## The ups and downs of AI research

Artificial Intelligence (AI) has experienced multiple cycles of innovation and setbacks, often referred to as “waves” throughout its history. The journey began in the 1950s with the development of the [perceptron](https://en.wikipedia.org/wiki/Perceptron), initiating the exploration into neural networks. This early enthusiasm led to the first AI winter from 1974 to 1980, when exaggerated expectations led to a significant reduction in interest and funding.

Interest renewed in the 1980s with the development of [expert systems](https://en.wikipedia.org/wiki/Expert_system) designed to mimic the decision-making abilities of human experts. However, another downturn happened in the 1990s, as these systems fell short of broader applications, leading to the second AI winter.

The latest resurgence fuels by major advances in [computer vision](https://en.wikipedia.org/wiki/Computer_vision), [deep learning](https://en.wikipedia.org/wiki/Deep_learning), and a broader spectrum of technologies like big data. A pivotal moment occurred in 2012 when [AlexNet](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf), a deep learning model, won the ImageNet challenge, marking the beginning of the deep learning era. Unlike previous waves, this era is characterized by the practical integration of AI in daily life, significantly influencing various industries and enhancing how we interact with technology. 

## 2012 to now (2024)

When [Google Scholar Metrics](https://scholar.google.com/citations?view_op=top_venues) was first launched in [April 2012](https://scholar.googleblog.com/2012/04/google-scholar-metrics-for-publications.html), the [Conference on Computer Vision and Pattern Recognition (CVPR)](https://cvpr.thecvf.com/Conferences/2025) barely made the top 100 English publications list, ranking at 97. At that time, it was rare for engineering conferences and journals to break into top 100 list. Fast forward to 2024, CVPR has risen to the [No. 2](https://scholar.google.com/citations?view_op=top_venues) spot among all English publications across all desiplines, ranking just below Nature. This positions it above other prestigious publications such as the New England Journal of Medicine (No. 3), Science (No. 4), and The Lancet (No. 6), underscoring its substantial importance in the global research community. This milestone also represents a notable achievement for engineering research, illustrating the first time that an engineering publication has reached such a prominent ranking among all academic disciplines. To visually illustrate this shift over the past twelve years, the plot below traces CVPR’s ascent in ranking from its position in 2012, when Google Scholar Metrics were first introduced, to its current standing as of August 25, 2024. 

```chartjs
{
  "type": "line",
  "data": {
    "labels": [
      "2012",
      "2014",
      "2016",
      "2018",
      "2020",
      "2022",
      "2024"
    ],
    "datasets": [
      {
        "label": "CVPR rank in top 100 English publications from Google Scholar Metrics",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(75,192,192,0.4)",
        "borderColor": "rgba(75,192,192,1)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(75,192,192,1)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          97,
          65,
          55,
          35,
          10,
          4,
          2
        ],
        "spanGaps": false
      }
    ]
  },
  "options": {
    "scales": {
      "y": {
        "reverse": true,
        "min": 1,
        "max": 100,
        "ticks": {
          "stepSize": 5
        }
      }
    }
  }
}
```


CVPR’s meteoric rise reflects broader trends within the field. Similarly, other leading computer vision and AI conferences, such as NeurIPS, ICLR, and ICML, have also seen significant improvements in their standings among the top 100 English publications. Notably, the [International Conference on Computer Vision (ICCV)](https://openaccess.thecvf.com/ICCV2023?day=all) and the [European Conference on Computer Vision (ECCV)](https://eccv.ecva.net/Conferences/2024), which are held biennially and alternate each year, also rank highly despite their less frequent occurrences. The standings (ICCV 13th and ECCV 46th) are partly due to the H5-index [1] used by Google Scholar Metrics, which evaluates publications over a five-year period. 

Even though ICCV and ECCV contribute fewer volumes within any given five-year window, their influence remains nearly as significant as that of the annual conferences (CVPR, NeurIPS, ICLR, ICML, AAAI, etc), underscoring their high quality and impact in the field. An interesting perspective is to consider ICCV and ECCV as essentially splitting CVPR into two entities; collectively, their H5 indices (291 for ICCV and 206 for ECCV) even surpass that of CVPR (440), though a precise H5 index calculation would be necessary for an exact comparison. 


| Rank | Publication | h5-index |
| :-----------: | :------------ | :------------: |
| 2      | IEEE/CVF Conference on Computer Vision and Pattern Recognition      |       440 |
| 7       | Neural Information Processing Systems      |       337 |
| 10       | International Conference on Learning Representations      |       304 |
| 13       | IEEE/CVF International Conference on Computer Vision      |       291 |
| 17       | International Conference on Machine Learning      |       268 |
| 35       | AAAI Conference on Artificial Intelligence      |       220 |
| 36       | Meeting of the Association for Computational Linguistics (ACL)      |       215 |
| 46       | European Conference on Computer Vision      |       206 |
| 49       | IEEE Transactions on Pattern Analysis and Machine Intelligence      |       196 |
| 51       | Conference on Empirical Methods in Natural Language Processing (EMNLP)      |       193 |

<p></p>


## Moving forward

As computer vision and broader AI technologies increasingly intertwine with our daily lives, the robustness and generalizability of models to real-world scenarios become essential. Despite their impressive performance on curated benchmarks, many models struggle when deployed in practical, real-world settings, where results can often diverge from expectations. This gap highlights the critical need for research aimed at enhancing the robustness and generalization capabilities of AI systems.

A recent Business Insider report about Microsoft’s Copilot [2] highlights the challenges AI technologies face when transitioning from controlled test environments to real-world conditions. This underscores the importance of my research, which is dedicated to improving the adaptability and performance of models beyond controlled test cases.

If you’re interested in pushing the boundaries of computer vision, deep learning, and general AI research toward more robust and generalizable models, I encourage you to connect with me to explore potential collaborations.


[1] The h5-index is the h-index for articles published in the last five complete years. It measures the largest number h such that h articles published from 2019 to 2023 each have received at least h citations.

[2] [A CIO canceled a Microsoft AI deal. The reason should worry the entire tech industry.](https://www.businessinsider.com/pharma-cio-cancelled-microsoft-copilot-ai-tool-2024-7)