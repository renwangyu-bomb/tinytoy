# tinytoy：一些无聊的小玩意的封装
========================
原生js，无聊的时候把无聊的想法实现封装一下，持续更新。。。
1.正方体cube：
-------------------------
    调用window.tinytoy.tt_cube(cfg)，创建一个正方体。
    cfg:{
      stage, //舞台元素
      imgSrc, //img的src数组，大于或小于6个会做处理，空我不管。。。
      wh, //img的长宽
      perspective, //舞台视角，关系到3d的效果
    }
    鼠标点下去按住cube可以360旋转，没有绑在body上，还没有做去除drag的效果，不算完美，至少目前有这功能
###效果就是下面这样的：
  ![](https://github.com/renwangyu-bomb/tinytoy/blob/master/screenshots/cube.jpg)
  具体的可以见demo
 
###人懒，休息，休息一下
