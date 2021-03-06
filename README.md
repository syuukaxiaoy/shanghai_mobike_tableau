
# 创建 Tableau 故事

## 概要

 利用摩拜提供的上海城区随机抽样百万条用户使用数据创建Tableau 故事。该数据包括，包含起点、目的地、租赁时间、还车时间、用户ID、车辆ID、交易编号。
 
 
第一版：https://public.tableau.com/profile/zhou.hua#!/vizhome/shanghaimobike0/12


最终版：https://public.tableau.com/profile/zhou.hua#!/vizhome/shanghaimobike15/shanghaimobike1?publish=yes

## 总结：
+ 上海市8月的日使用记录一路上升趋势。
+ 每辆单车被使用1次数为最多，每位用户的骑行次数4~7次居多，可以说大部分单车被合理利用。
+ 在一天当中，单车使用次数在早上8点和下午6点达到峰值，晚高峰持续时间较长，夜间骑车的人数明显多于白天。
+ 从工作日周末的平均时长要高于工作日。
+ 大部分的单车使用正常，安排合理，发现其中存在少数位置偏离市区，以及单次使用时长异常的数据。

## 设计：
+ 设置早上7-9时为早高峰，下午17-20时为晚出勤时段，其他时间为其他时段。
+ 分别统计了用户量，订单量，单车使用量的数据，并添加可视化。
+ 修改了图的配色
+ 添加标注，和互交模式
+ 计算异常订单占比

## 反馈：

>+ “用户量，订单量，单车使用量等数据统计数好像不符合，比如单日用户量和订单数可能不相等？”
>+ “如果添加注释可能会更容易看懂”
>+ “特异值订单的占比是多少？” 
>+ “特异值中比如距离过长的是否存在。。。”
>+ “我想知道这些特异值数据的更详细情况，比如路线？然后还有什么原因呢”

接受以上建议，通过查找资料，进行了部分修改。尝试了添加路线，计算距离但并没有成功，在设置路线id部分的内容没有理解，期待各位提出建议。

## 资源

+ https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_origin_destination.html


