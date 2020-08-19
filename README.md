[TensorFlow 2] Going Deeper with Convolutions | Simplified Version
=====

TensorFlow implementation of "Going Deeper with Convolutions"

## Related Repositories
<a href="https://github.com/YeongHyeon/XCeption-TF2">XCeption-TF2</a>  
## Concept
<div align="center">
  <img src="./figures/inception.png" width="400">  
  <p> The Inception module [1, 2]. In this repository, the concept of a simplified inception module is adopted for implementation.</p>
</div>

## Performance

|Indicator|Value|
|:---|:---:|
|Accuracy|0.99500|
|Precision|0.99495|
|Recall|0.99498|
|F1-Score|0.99497|

```
Confusion Matrix
[[ 976    0    0    0    0    1    2    1    0    0]
 [   1 1129    1    0    0    0    1    3    0    0]
 [   1    0 1030    0    0    0    0    0    1    0]
 [   0    0    1 1007    0    1    0    0    0    1]
 [   0    0    0    0  976    0    1    0    0    5]
 [   1    0    0    4    0  886    1    0    0    0]
 [   2    0    0    0    0    2  954    0    0    0]
 [   0    1    5    0    0    0    0 1021    0    1]
 [   1    0    2    0    0    1    0    0  969    1]
 [   0    0    0    0    5    1    0    1    0 1002]]
Class-0 | Precision: 0.99389, Recall: 0.99592, F1-Score: 0.99490
Class-1 | Precision: 0.99912, Recall: 0.99471, F1-Score: 0.99691
Class-2 | Precision: 0.99134, Recall: 0.99806, F1-Score: 0.99469
Class-3 | Precision: 0.99604, Recall: 0.99703, F1-Score: 0.99654
Class-4 | Precision: 0.99490, Recall: 0.99389, F1-Score: 0.99440
Class-5 | Precision: 0.99327, Recall: 0.99327, F1-Score: 0.99327
Class-6 | Precision: 0.99479, Recall: 0.99582, F1-Score: 0.99531
Class-7 | Precision: 0.99513, Recall: 0.99319, F1-Score: 0.99416
Class-8 | Precision: 0.99897, Recall: 0.99487, F1-Score: 0.99691
Class-9 | Precision: 0.99208, Recall: 0.99306, F1-Score: 0.99257

Total | Accuracy: 0.99500, Precision: 0.99495, Recall: 0.99498, F1-Score: 0.99497
```

## Requirements
* Python 3.7.6  
* Tensorflow 2.1.0  
* Numpy 1.18.1  
* Matplotlib 3.1.3  

## Reference
[1] Christian Szegedy et al. (2015). <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Szegedy_Going_Deeper_With_2015_CVPR_paper.html">Going Deeper With Convolutions</a> Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2015, pp. 1-9  
[2] François Chollet (2016). <a href="https://arxiv.org/abs/1610.02357">Xception: Deep Learning with Depthwise Separable Convolutions</a>. arXiv preprint arXiv:1610.02357.
