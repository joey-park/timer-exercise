“番茄钟”介绍:

番茄钟，是根据一个瑞典人所写的番茄工作法理论进行开发的一款方便、实用的日程管理软件。
指的是把工作任务分解成半小时左右，集中精力工作25分钟后休息5分钟，如此视作种一个“番茄”，而“番茄工作法”的流程能使下一个30分钟更有动力。

使用说明

1)主页页面

a)主页页面的中央处有圆形倒计时钟，分布在其下的为“工作”与“休息”的两个button，点下任一个button即可触发响应的倒计时进行计时工作

b)在buttons上方有一个自动聚焦的input，在此处输入想要专注的任务名称，然后点击上方的button即可进行专属的专注工作 

c)最下方为tabBar，第一个对应的即为主页页面，第二个位记录界面，第三个为设置界面。选中图标会跳转到相应的界面同时图标会变成绿色

2)记录界面

会显示“时间段+任务名“，时刻提醒自己做了些什么，底部正中央有个“清除记录”的选项，点击后会清空所有记录

3)设置界面

a)工作时长和休息时长可调，最上方有连个slider，滑动即可进行调节 

b)两个switch:一个选择主页背景，另外一个选择铃声（还没有添加，正在完善）

c关于番茄时钟的说明

4)待增加的功能

a)统计界面，讲一天记录的时间按类别进行区分，并利用图表的形式进行表示 

b)处理交互效果，增加触发事件的动画特性 

c)美化界面，这个界面太简洁了，后续可能会增加自定义背景的功能，还会对当前的UI界面记性重构 

d)音乐播放功能，会多增加几首音乐并实现可选项

5)发现的bug

测试结果：无法显示已经完成的记录

logs.forEach is not a function;at "pages/logs/logs" page lifeCycleMethod onShow function
TypeError: logs.forEach is not a function
