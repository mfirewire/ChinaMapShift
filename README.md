ChinaMapShift
=============

Transformation algorithms between WGS-84, GCJ-02 and BD-09.

中国地区专用地图纠偏算法。

WGS-84：国际通用的坐标系统。GPS设备和芯片获取的坐标，Google 的卫星遥感图等均在此坐标系下；
GCJ-02：中国国家测绘局设计的坐标系统，高德地图（以及由此数据导出的各种地图，包括 Google 的道路图 API）在此坐标系下；
BD-09：百度地图专用的坐标系。

代码包含 WGS-->GCJ, GCJ-->WGS, GCJ-->BD, BD-->GCJ 四种转换的算法。

本算法以 C 语言呈现，可以直接应用于 iOS 系统。算法原理并不复杂，以数学三角运算为主。需要在其他平台下使用的，自行做语法上的简单改写即可。
