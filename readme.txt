project readme
1.自己写的代码基本上都做了注释，宏录制的代码注释较少；
2.Yield.Curve工作簿按要求完成，重复录入同一天的数据会跳出提醒，Yield Curve曲线图表也会在按下按钮之后显示；
3.Bond.Position工作簿Load Position按钮按要求完成；
4.考虑到先录入数据后计算画图的Calculate & Plot!按钮没有加入录入文件数据的功能，所以需要在录入数据后操作；
5.Position.BPV.Curve工作簿中的曲线在按下Calculate & Plot!按钮后生成，由于是宏录制生成，所以如果有给定数据以外的数据录入图表会存在问题；
6.Maturity数据我估计是给的数据少了一年，最后计算中，各种债券按以下方法计算：
	A债券：yield取1yr的yield数据，获得1次coupon和最后的coupon+principal
	B债券：yield取5yr的yield数据，获得7次coupon和最后的coupon+principal
	C债券：yield取10yr的yield数据，获得17次coupon和最后的coupon+principal
	D债券：yield取30yr的yield数据，获得57次coupon和最后的coupon+principal；
7.Position.PBV.Curve曲线的纵轴取的是BPV；
8.提交的xls文件中是功能实现的最终效果，如果要重新尝试可以把现有数据和图表都删了之后进行。