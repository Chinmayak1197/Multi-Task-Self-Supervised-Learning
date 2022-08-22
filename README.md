**Boosting Semantic Segmentation with Multi-task Self-Supervised Learning for Image Segmentation Task** 

**Multi-Tasking:** Semantic Segmentation + Depth Estimation + Surface Normalization. Multi-tasking is used for summing the three losses with assigned weights to each specific task. 

**Weighting methods:** Nash-MTL and Uncertainty-Weighting methods. 

**Dataset:** NYU2D  

**Results:** 

**Task1: Sematic Segmentation**  

![](Aspose.Words.9f0d2f36-7722-4604-beb3-c77612de8ef6.001.png)

![](Aspose.Words.9f0d2f36-7722-4604-beb3-c77612de8ef6.002.png)

**Task2: Depth Estimation**  

![](Aspose.Words.9f0d2f36-7722-4604-beb3-c77612de8ef6.003.png)

**Task3: Surface Normalization**  

![](Aspose.Words.9f0d2f36-7722-4604-beb3-c77612de8ef6.004.png)


**Comparison Metric: Delta M**  

||Delta M  |
| :- | - |
|Nash – MTL  |-47.57 |
|Uncertainty Weighting (UW) |-32.67 |


**Visualization Results:** 

Cityscape dataset and Worcester Roads

![](Aspose.Words.9f0d2f36-7722-4604-beb3-c77612de8ef6.005.png)

![](Screencast_2022-08-17_21_15_53_AdobeExpress.gif) 

