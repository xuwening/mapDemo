# gps地图示例

## 前言

最近工作中可能需要用到地图，就提前进行技术预言，花了两三天做了几个demo，基本能够覆盖大部分业务场景。

每个示例放在单独的文件夹中，这样可以独立运行。

注：示例中直接使用gps坐标进行绘制，因此在百度和高德地图中会有位置偏差，正式项目使用时，需要进行坐标转换。

```
百度地图坐标转换:BMap.Convertor  //比较扯的是每次转换最多10个坐标
高德地图坐标转换:AMap.convertFrom
```


## 全国数据大屏展示


![图片描述](./img/mapvDemo.png)

<video id="video" controls="" preload="none" poster="">
<source id="mp4" src="./img/mapvDemo.mp4" type="video/mp4">
</video>


[百度demo地址](./gps/baidu_map/mapvDemo)
[高德demo地址](./gps/gaode_map/mapvDemo)

## 车辆轨迹

![图片描述](./img/markerDemo.jpg)


[百度demo地址](./gps/baidu_map/markerDemo)
[高德demo地址](./gps/gaode_map/markerDemo)


## 车辆轨迹

![图片描述](./img/polylineDemo.jpg)


[百度demo地址](./gps/baidu_map/polylineDemo)
[高德demo地址](./gps/gaode_map/polylineDemo)



## 电子围栏

![图片描述](./img/electronicFence.jpg)


[百度demo地址](./gps/baidu_map/electronicFence)
[高德demo地址](./gps/gaode_map/electronicFence)


## 车辆轨迹播放

![图片描述](./img/roadbook.jpg)


[百度demo地址](./gps/baidu_map/roadbook)
[高德demo地址](./gps/gaode_map/roadbook)

## 富Marker-还款剩余金额

![图片描述](./img/richMarker.png)


[百度demo地址](./gps/baidu_map/richMarker)
[高德demo地址](./gps/gaode_map/richMarker)

## 车辆点聚合

![图片描述](./img/polymerization.png)


[百度demo地址](./gps/baidu_map/polymerization)
[高德demo地址](./gps/gaode_map/polymerization)






