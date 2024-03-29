# cart
基于fullpage.js全屏滚动插件实现购物网站宣传页面

##### 一、案例介绍

- 采用HTML5和CSS3制作
- 使用用几幅很大的图片或色块做背景，再添加一些简单的内容，实现全屏切换的效果
- 适用于制作各种宣传页、活动页

##### 二、知识点

- 使用动画分为js实现的动画（帧动画，使用定时器，每隔一段时间更改当前元素的状态）和css3显示的动画（补间动画，加过渡只需状态改变产出动画，多个节点来控制动画），css3动画性能会更好，并且在支持H5C3的浏览器尽可能的使用css3动画，比如移动端开发
- 2D转换有缩放scale、位移translate、旋转rotate、倾斜skew，关于动画速度有ease、linear、ease-in、ease-out、ease-in-out都是特殊的动画速度，都是由贝塞尔曲线，2D转换和3D转换的区别一是参数，二是在移动端使用3D转换可以优化性能(如果设备有3D加速引擎GPU可以提高性能,是2D转换是无法调用GPU)
- 背景图的百分比不是按照容器的大小去换算的，百分比的背景图定位基于容器的宽度-背景的宽度，计算公式：背景图的X定位 = （容器的宽度 - 背景的宽度） * 百分比

##### 三、实现方法：fullPage.js 插件

fullPage.js 是一个基于 jQuery 的插件，它能够很方便、很轻松的制作出全屏网站，主要功能有支持鼠标滚动、支持前进后退和键盘控制多个回调函数、支持手机平板触摸事件、支持 CSS3 动画、支持窗口缩放、窗口缩放时自动调整、可设置滚动宽度、背景颜色、滚动速度、循环选项、回调、文本对齐方式等等。兼容 jQuery 1.7+，兼容IE8+。

##### 四、效果图
效果图1：
![效果图1](https://github.com/HeMin0919/cart/blob/master/images/xg1.gif)

效果图2：
![效果图2](https://github.com/HeMin0919/cart/blob/master/images/xg2.gif)

效果图3：
![效果图3](https://github.com/HeMin0919/cart/blob/master/images/xg3.gif)

效果图4：
![效果图4](https://github.com/HeMin0919/cart/blob/master/images/xg4.gif)
