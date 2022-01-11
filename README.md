# Deep embedding of concept ontology for hierarchical fashion recognition

## Figure
### Flowchart
The flowchart for augmented hierarchical deep learning(AHDL) algorithm by deep embedding of tree classifiers over the concept ontology, where the hierarchical features and classifiers of each tree node share a same set of CNN layers and they can be further used for fashion recommendation based on the recognized fine-grained fashion category.

![](https://github.com/t51645/Hierarchy-based-model-enhancement-method/blob/main/flowchart.png)

### Example
An example of the adopted concept ontology for fashion recognition, where i shows the level index from root to leaf nodes.

![](https://github.com/t51645/Hierarchy-based-model-enhancement-method/blob/main/example.png)


## Introduction
The natural concept ontology structure of clothes has enabled easy management of large quantities of fashion images for online retailers and it is meaningful to study how to automatically recognize fashion images for both commercial promotion and academic research.

In this project, a new hierarchical approach is developed for large-scale fashion recognition. It mainly contains two steps:
* We first embed concept ontology into deep convolutional neural network (CNN) by adopting multiple deep CNN branches to learn node-specific features and classifiers explicitly.

* Then, we introduce a hierarchical knowledge distillation method to further improve the performance of fashion recognition. 

Finally, we employ the proposed approach on the public DeepFashion dataset.

### Tips
If there is any copyright issue, please contact 592332380@qq.com.