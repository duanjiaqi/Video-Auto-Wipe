# Video-Auto-Wipe
&emsp;&emsp;本人不定期的基于生成技术制作一些好玩有趣的算法模型，这次带来的作品是“视频擦除”方向的应用模型，它实现的功能是自动感知到视频中我们不想看见的部分（譬如图标、字幕等等）然后进行擦除。目前已开放出“体验版”模型供大家玩耍，希望能帮助到有需要的朋友。注意，<b>本人本着方便百姓生活、提升工作效率的初衷去制作技术，请您以合法合规的方式使用模型，本人对于您的使用造成的结果概不负责</b>。<br />
&emsp;&emsp;我后续会持续不断的探索和制作新的生成方向的应用类技术，基于生成模型可玩的点还有很多很多，此项目仅仅展示了其中的一个具象化例子。模型版权所属：[www.seeprettyface.com](www.seeprettyface.com) ，未获得授权请不要用作商业用途。关于算法的细节介绍可以参阅我的[研究笔记](http://www.seeprettyface.com/research_notes_page3.html)。<br/><br/><br/><br/>

# 效果预览
## 1. 图标擦除
&emsp;&emsp;图标擦除模型的功能是模型自动感知到视频中图标的位置然后进行擦除，感知图标的方法为在时域上静止不动的像素块被视作图标。<br/><br/>

### 1.1 测试1-电视剧的台标、剧名和角标擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试01-电视剧1.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_01.mp4)<br/><br/>

### 1.2 测试2-足球赛的台标、状态栏擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试04-足球赛.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_02.mp4)<br/><br/>

### 1.3 测试3-综艺节目的台标、状态栏擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试06-综艺片段-台标角标遮挡.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_03.mp4)<br/><br/>

### 1.4 测试4-短视频MV的遮挡图标擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试07-音乐MV.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_04.mp4)<br/><br/>

### 1.5 测试5-自媒体视频的遮挡图标擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试08-自媒体视频1.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_05.mp4)<br/><br/>

### 1.6 测试6-新闻媒体的台标擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-logo/测试10-新闻媒体素材.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_06.mp4)<br/><br/>

## 2. 动态图标擦除
&emsp;&emsp;动态图标擦除模型的功能是模型自动感知到视频中动态图标的位置然后进行擦除，感知动态图标的方法为在时域上闪烁出现或动态移动的固定像素块被视作动态图标，这个在制作上有一定难度所以还没有对外开放。<br/><br/>
### 2.1 测试1-闪烁出现的特效文字擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-dynamic-logo/测试-动态字幕擦除_1.JPG)<br/>
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-dynamic-logo/测试-动态字幕擦除_2.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/delogo_06.mp4)<br/><br/>

## 3. 字幕擦除
&emsp;&emsp;字幕擦除模型的功能是模型自动感知到视频中字幕的位置然后进行擦除，感知字幕的方法为具有统一样式的文字区域被视作字幕。
### 3.1 测试1-电影字幕擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-text/测试03-电影片段2.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/detext_01.mp4)<br/><br/>

### 3.2 测试2-电视剧字幕擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-text/测试05-电视剧.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/detext_02.mp4)<br/><br/>

### 3.3 测试3-综艺节目字幕擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-text/测试06-综艺片段1.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/detext_03.mp4)<br/><br/>

### 3.4 测试4-综艺节目特殊字幕擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-text/测试08-综艺片段3.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/detext_04.mp4)<br/><br/>

### 3.5 测试5-网络视频字幕擦除
![Image text](https://github.com/a312863063/Video-Auto-Wipe/blob/main/pics/de-text/测试11-网络媒体素材3.JPG)<br/>
[查看视频](http://www.seeprettyface.com/mp4/video-inpainting/detext_05.mp4)<br/><br/>

