---
{"dg-publish":true,"permalink":"/完整知识体系/6_非编程内容/工具篇/Windows相关集合/win11的使用技巧/","dgPassFrontmatter":true}
---



# win11的使用技巧



## 1. win11软件添加到开机自启动中
2024/5/5 15:24


1. 按win+ R，输入`shell:startup`回车，打开启动文件夹
2. 应用的快捷方式复制到“启动”文件夹即可

我的电脑启动文件夹是
`C:\Users\JUN\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`

![assets/完整知识体系/6_非编程内容/工具篇/Windows相关集合/win11的使用技巧/IMG-20241203-171955337.png](/img/user/assets/%E5%AE%8C%E6%95%B4%E7%9F%A5%E8%AF%86%E4%BD%93%E7%B3%BB/6_%E9%9D%9E%E7%BC%96%E7%A8%8B%E5%86%85%E5%AE%B9/%E5%B7%A5%E5%85%B7%E7%AF%87/Windows%E7%9B%B8%E5%85%B3%E9%9B%86%E5%90%88/win11%E7%9A%84%E4%BD%BF%E7%94%A8%E6%8A%80%E5%B7%A7/IMG-20241203-171955337.png)

## 2. win的cmd技巧

### 2.1. seata多实例启动bat和相关的语法
```

```

## 3. win 11 自带输入法-自定义短语

### 3.1. 快速输入时间

2024-12-03 17:21:27

```
1. 中
2. 用户自定义短语
3. 添加

拼音：sj
短语：%yyyy%-%MM%-%dd% %HH%:%mm%:%ss%

注意：
最后一次操作是（添加或修改的）带变量的自定义短语才会生效。
否则，带变量的自定应短语，变量会固定，达不到效果。

变量固定后，重新设置短语：%yyyy%-%MM%-%dd% %HH%:%mm%:%ss%
保存即可。

```

![assets/完整知识体系/6_非编程内容/工具篇/Windows相关集合/win11的使用技巧/IMG-20241203-171955372.png](/img/user/assets/%E5%AE%8C%E6%95%B4%E7%9F%A5%E8%AF%86%E4%BD%93%E7%B3%BB/6_%E9%9D%9E%E7%BC%96%E7%A8%8B%E5%86%85%E5%AE%B9/%E5%B7%A5%E5%85%B7%E7%AF%87/Windows%E7%9B%B8%E5%85%B3%E9%9B%86%E5%90%88/win11%E7%9A%84%E4%BD%BF%E7%94%A8%E6%8A%80%E5%B7%A7/IMG-20241203-171955372.png)

### 3.2. 快速输入知识库路径

用于 [[完整知识体系/6_非编程内容/软件整理篇-New/everything#everthing\|everything]] 指定文件夹下的快速搜索

```
拼音：kb
短语：D:\BaiduSyncdisk\我的知识库\

拼音：kbr
短语：D:\BaiduSyncdisk\knowledge-reop\ regex:".*.*"

拼音：bdr
短语：D:\BaiduNetdiskDownload\ regex:".*.*"

拼音：wd (word)单词搜索
短语：D:\BaiduSyncdisk\CodeWord regex:".*.*"

拼音 td
短语：TODO

2025-05-15 18:23:00
添加
拼音：rs
D:\ regex:"^.*.*$"
```

## 4. win11常用的快捷键

- 应用窗口在两个屏幕间移动
	- win shift 左或右箭头


## 5. 拼音

`üe`
- 和jqxy组合，省略两点
- 和ln组合，不省略