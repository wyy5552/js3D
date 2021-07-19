<!--
 * @Author: your name
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /js3D/readme.md
-->
    虽说做游戏有很多年了，却每天都被业务开发忙得晕头转向，对于底层实现，对于整个引擎提供的内容，在当前引擎里面有时候也有很多似是而非的时候。
    个人一直在做网页游戏，虽然从没有做过自己由衷喜欢的项目，但也希望能够在这方面有所建树。
    受限于引擎提供的“模板“，我经常不得不变成一个菜鸟，从引擎的文档去找我要的东西。而引擎底层怎么实现的，却经常一脸茫然。如果引擎不提供的，我就无法实现了么？
当然了，我做的东西，基本上引擎都提供全面了。并没有需要我再去创造什么。但，总感觉这些引擎在”欺骗“我。本来一些很简单的东西，却被他们包装成各种奇奇怪怪的方式。
比如，我从来没有关注过位图与纹理有什么区别；为什么文本总是我想要的效果；比如打包为什么这么费事；资源加载策略为什么需要长篇大论来讲；等等这些。
    那么，对于h5游戏引擎，我们需要有哪些东西呢？
    (参考egret，cocos，threejs)

1. 引擎底层库
    主要封装2d，3d相关的显示列表，以及他们之间的各种关系；
    物理；数学；着色器；
    2d： 文字，图片，矢量绘制；
    3d： 纹理，模型，摄像机，光照；

2. 加载器以及解析
    针对各种显示对象，2d or 3d，使用不同的加载策略与解析策略
    
3. 网路通讯
    针对http，websocket，再加一个协议格式protobuf

4. ui编辑器，场景编辑器

5. 资源管理工具
    合图，合包

6. 动画，模型
    2d动画，3d动画，缓动库

7. 粒子
    粒子系统，粒子编辑器

8. debug工具inspector

9. 声音

10. 工程控制
    发布，部署，缓存策略


后面，有时间就一步步实现一个这样的引擎。可能实现顺序会有所差别。

不喜欢当前国内的3大引擎
1. 高度封装
    自定义改动非常麻烦；
    把人当傻子看；
    
2. 自定义编译器
    无法自定义编译策略

3.  也想不出来别的了，可能是偏见；