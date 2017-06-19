# RadarScanView

#### layer + CAAnimation 实现雷达扫描的效果图,做的过程中主要遇到三个问题。  
	1. 用arc 画( )类似于这样的图时，一直画不好。通过layer的lineDashPattern设置虚线和实线，可以轻松解决。  
	2. layer.contens设置图片时，需要用__bridge id将c转成对象。  
	3. CAAimation.timeOffset 可以设置延时执行动画。group时begintime = 1，也可以实现延时效果，设置为其它值时，效果不是很好。
