# 山东科技大学-录课平台-辅助搜索  

学校上的课有录课挺好，复习啥的可以看看，但搜索做的太差了，只支持一个关键词，尤其是随着视频越来越多，一个关键词的搜索越来越不够用，找一个视频要找好久，做了个网页辅助搜索，顺便熟悉下js对dom的操作，放在 github-pages 方便使用。(css实在是不太会写，差不多这样吧，实用就好)  

实现原理：选择第一个输入的关键词，一次性请求全部内容，按每个输入框的关键词进行筛选后，显示在网页中。

### **注：请求的接口为 `http`，而 githubpage 为 `https`，需设置允许该网页的不安全内容才能运行，或下载 html 到本地，可直接运行**  

前往网页：[搜索页](https://mlyde.github.io/Search_tc2/search.html)  
