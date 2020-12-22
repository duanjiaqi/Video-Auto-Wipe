# Video-Auto-Wipe
&emsp;&emsp;本人不定期的基于生成技术制作一些好玩有趣的算法模型，这次带来的作品是“视频擦除”方向的应用模型，它实现的功能是自动感知到视频中我们不想看见的部分（譬如图标、字幕等等）然后进行擦除。目前已开放出“体验版”模型供大家玩耍，希望能帮助到有需要的朋友。注意，<b>本人本着方便百姓生活、提升工作效率的初衷去制作技术，请您以合法合规的方式使用模型，本人对于您的使用造成的结果概不负责</b>。<br />
&emsp;&emsp;我后续会持续不断的探索和制作新的生成方向的应用类技术，基于生成模型可玩的点还有很多很多，此项目仅仅展示了其中的一个具象化例子。模型版权所属：[www.seeprettyface.com](www.seeprettyface.com) ，未获得授权请不要用作商业用途。关于算法的细节介绍可以参阅我的[研究笔记](http://www.seeprettyface.com/research_notes_page3.html)。<br/><br/><br/><br/>

# 效果预览
## 1. 图标擦除
&emsp;&emsp;图标擦除模型的功能是模型自动感知到视频中图标的位置然后进行擦除，感知图标的方法为在时域上静止不动的像素块被视作图标。<br/><br/>

### 1.1 测试1-电视剧的台标、剧名和角标擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试01-电视剧1.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_01.mp4)<br/><br/>

![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试02-电视剧2.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_01.mp4)<br/><br/>

![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试03-电视剧3.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_01.mp4)<br/><br/>



## 3.字幕擦除
&emsp;&emsp;字幕擦除模型的功能是模型自动感知到视频中字幕的位置然后进行擦除，感知字幕的方法为具有统一样式的文字区域被视作字幕。
