---
layout: post
title: "Post-correction of OCR Errors Using PyEnchant Spelling Suggestions Selected Through a Modified Needleman-Wunsch Algorithm"
tag: 文献阅读
---

[  Christian Reul](https://dblp.uni-trier.de/pers/hd/r/Reul:Christian), [Uwe Springmann](https://dblp.uni-trier.de/pers/hd/s/Springmann:Uwe), [Christoph Wick](https://dblp.uni-trier.de/pers/hd/w/Wick:Christoph), [Frank Puppe](https://dblp.uni-trier.de/pers/hd/p/Puppe:Frank):
  Improving OCR Accuracy on Early Printed Books by Utilizing Cross Fold Training and Voting. [DAS 2018](https://dblp.uni-trier.de/db/conf/das/das2018.html#ReulSWP18): 423-428



使用经过修改的辅助算法选择的拼写建议对错误进行修正后

### 方法

- in this article, the efforts made by the vocalizer project development team to correct errors from texts generated by ocr tesseract are described. vocalizer consists of a device that captures images from books, converts them into plain texts with the aid of an ocr (optical character recognition) software. it also prepares the post-processing of the obtained text, and converts its textual content into voice. the whole process is performed autonomously. in the post-processing step, a modified needleman-wunsch algorithm was applied to select the suggestions made by the spellchecker pyenchant. the results obtained were reasonable, which encourages further research

  在本文中，描述了项目开发团队为纠正由ACCER生成的文本中的错误所做的努力。它由一种装置组成，它从书本中获取图像，借助光学字符识别软件将它们转换成纯文本。它还准备对获得的文本进行后处理，并将其文本内容转换为语音。整个过程被执行。在后处理步骤中，采用了一种改进的再匹配算法来选择所提出的建议。所得结果是合理的，有利于进一步的研究。

- 使用tesseract的输出结果，作为初步的识别结果

![ ](https://raw.githubusercontent.com/yaolinxia/img_resource/master/multi-input attention/微信截图_20190305170048.png)

#### 

### 实验

![ ](https://raw.githubusercontent.com/yaolinxia/img_resource/master/multi-input attention/微信截图_20190305165614.png)





### 结论





### 启发

- 提出了一种改进的再匹配算法
- 提出了一个spellchecker的方法
- 适用于英文，可能中文不是很适用



### 参考文献







