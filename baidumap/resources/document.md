# 百度地图使用说明
## 参考地址
[官方网站](https://lbsyun.baidu.com/index.php?title=jspopular3.0/guide/widget)
## 过程
1. 收集精度和纬度
2. 转换未bd09坐标
[地图转换说明](https://lbsyun.baidu.com/index.php?title=jspopular3.0/guide/coorinfo)
[地图转换示例](http://lbsyun.baidu.com/jsdemo.htm#a5_2)
3. 展示默认几个地点
4. 调用地点检索api
[例子](http://api.map.baidu.com/place/v2/suggestion?query=天安门&region=北京&city_limit=true&output=json&ak=tF55uGxM2SMkIHZWbhB7Ye0YT6Sb7YFU)
5. api的使用
[定位点](http://api.map.baidu.com/marker?location=40.047669,116.313082&title=我的位置&content=我的世界&output=html&src=webapp.baidu.openAPIdemo)
6. 标记多个点
[标记多个点]()

http://api.map.baidu.com/place/search?res=jsapi&query=北京&region=北京市&output=html
## 检索
### 本地检索示例
