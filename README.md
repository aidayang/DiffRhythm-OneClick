# DiffRhythm-OneClick
DiffRhythm歌曲创作软件免安装一键启动整合包

![](https://raw.githubusercontent.com/aidayang/DiffRhythm-OneClick/refs/heads/main/a.jpg)

DiffRhythm是首个基于扩散技术的开源音乐生成模型，能够创作完整的歌曲，包括AI谱曲，AI演唱。基于当前最新V1.2版本我制作了免安装一键启动整合包。

## DiffRhythm介绍
Di♪♪Rhythm：速度惊人、简单至极、具有潜在扩散的端到端全长歌曲生成

DiffRhythm（中文名：谛韵，Dì Yùn）是首个基于扩散技术的开源音乐生成模型，能够创作完整的歌曲。其名称由“Diff”（指其扩散架构）和“Rhythm”（强调其对音乐和歌曲创作的专注）组成。中文名“谛韵”与“DiffRhythm”谐音，“谛”（专注聆听）象征着听觉感知，“韵”（旋律魅力）则代表着音乐性。

更新说明：

2025.5.9 🔥 DiffRhythm-v1.2 正式发布！1.2 版本在很大程度上解决了重复和遗漏问题，显著提高了音频质量和编排，乐器更加丰富，并且能够通过对音乐结构和风格的深入了解进行歌曲编辑和延续。
## DiffRhythm一键启动整合包使用说明
由于是将歌词文本唱成歌曲，所以软件依赖于文字转语音合成软件espeak-ng，所以使用前先安装网盘内的espeak-ng.msi，双击安装，全程默认。

然后将网盘内的软件压缩包下载到本地电脑上并解压。然后双击【启动软件.exe】。

lrc歌词：首先上传lrc格式的歌词文件，lrc内容格式为前面是时间戳后面是歌词文本，不明白的可以随便找个lrc歌词文件打开看看，然后照着样子自己创作歌词。

输出目录就是生成的歌曲保存目录

风格描述：提供文本风格参考（如“爵士乐”或“快节奏摇滚”），通过文本提示控制生成歌曲的风格，可选但能显著影响输出效果。

参考音频：提供参考音频文件路径作为风格模板。从音频中提取风格特征（如节奏、音色），适用于模仿特定歌曲风格。

分块解码：处理长音频时减少内存占用，适合生成长歌曲（如285秒）时开启。

生成音频时长：设置生成音频长度，可选95到285秒，默认95秒。控制歌曲时长，用户按需求选择短版或长版。

模型ID:默认为最新模型DiffRhythm-1_2，使用其它模型的话软件会自动下载模型文件。

生成歌曲数量：一次性生成多少首歌曲

视频教程及效果演示：https://www.youtube.com/watch?v=ENji2Sd4D_Q

## 注意事项
英伟达显卡显存6G以上

支持英伟达50系列显卡

使用前请先将英伟达显卡驱动更新到最新版本

只支持windows10或11

软件运行路径中不要有非英文字符和空格，待使用文件素材同样要注意

## AI歌曲生成软件DiffRhythm V1.2整合包下载链接
https://pan.quark.cn/s/9b5a07574474

## 项目地址
https://github.com/ASLP-lab/DiffRhythm
