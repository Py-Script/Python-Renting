# 高德API + Python 解决租房问题
*使用 Python 脚本爬取某租房网站的房源信息，利用高德的 js API 在地图上标出房源地点，划出距离工作地点1小时内可到达的范围。在项目实现的过程中熟悉了 requests 、BeautifulSoup、csv 等库的简单使用。*

通过实验楼课程学习完成此项目
[链接](https://www.shiyanlou.com/courses/599)


## 环境
- VScode
- Windows/Linux
- Python 3.6


## 依赖
- requests
- BeautifulSoup
- csv
```
pip install requests bs4
```

## 运行
```
python -m http.server 3000
```
**打开浏览器 localhost:3000**

## 结果
![效果图](img/1.png)

## 思路
- 高德地图API
- 爬取58租房信息

通过爬取58租房信息,结合高德地图API,地图模拟得到地铁公交到租房直接的距离等


## 有兴趣的可以去实验楼学习