**js原生触屏位置操作插件--Sition** 

- 一款轻量级的移动触屏手势操作js插件,使用简单方便,支持多种判断操作
- https://uquhu.cn 一款利用该插件打造的移动端手势音乐播放器（有点炫酷）
- https://gitee.com/lovefc/fmusic 移动端手势音乐播放器项目地址
- 在线演示：https://uquhu.cn/sition

**如何使用：** 
- ` Sition(dom,action,function,debug) `


**参数：** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
| dom | 否  |string | 元素id名,为空代表整个body页面   |
| action  | 是  |string | 要执行的动作名称   |
| function | 是  |function | 执行后的回调函数   |
| debug | 否  | bool | 开启调试，true为开启   |

**action 动作参数说明：** 

|参数名|说明|
|---  | ---|  
| long | 长按操作 |
| clicked | 双击操作 |
| up | 向上滑动 |
| upLeft | 向上滑动-左边 |
| upRight | 向上滑动-右边 |
| down | 向下滑动 |
| downLeft | 向下滑动-左边 |
| downRight | 向下滑动-右边 |
| left | 向左滑动 |
| leftUp | 向左滑动-顶部 |
| leftDown | 向左滑动-底部 |
| right | 向右滑动 |
| rightUp | 向右滑动-顶部 |
| rightDown | 向右滑动-底部 |
| upCenter | 向上滑动-居中 |
| downCenter | 向下滑动-居中 |
| leftCenter | 向左滑动-居中 |
| rightCenter | 向右滑动-居中 |

**注意事项** 
 
- 要确保dom有高度和宽度，不然无法判断，默认读取的是body元素，body元素也要有高度和宽度

**前端调试**
- 可以使用谷歌浏览器自带的移动端模拟功能在电脑上调试

 ![](https://www.showdoc.cc/server/api/common/visitfile/sign/2a419bd9617cb07925d3867055df781a?showdoc=.jpg)

**作者备注**
- 如果发现问题，欢迎向我反馈，毕竟一个人测试有限，会有注意不到的地方。
- 作者QQ：1102952084
- 作者博客：lovefc.cn