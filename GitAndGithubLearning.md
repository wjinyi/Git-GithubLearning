# Git & Github Learning Note
 ## 库文件管理
   * [Ignoring files and folders with the gitignore file](https://www.youtube.com/watch?v=wECCmRg8Qjc) - ignore的时候写的是相对路径。
 ## 临时笔记
   ![](https://github.com/wjinyi/Git-GithubLearning/blob/master/git%E4%B8%B4%E6%97%B6%E7%AC%94%E8%AE%B0-1.jpg)
 ## 跨系统协同工作
   * 编码问题
     + 当出现跨系统上传与下载时，可能会出现符号不识别的情况，提示error: unidentified file : "xxxxxxx"。
     + 首先通过 git diff 比较文件夹不同处，若无，排除文件冲突。
     + 接着可以通过直接删除出问题的文件或是ignore或是更改命名格式来解决无法同步的问题。
