#win10 uwp 初始屏幕

很多情况我们程序在启动的时候需要加载数据，在加载数据的时候，还是显示开始的启动图片，看起来不好。本文主要说如何做一个启动界面类似段子之家的东西。

其实做这个很简单，我们需要在一开始就导航到启动页面。

我们需要去View新建一个页面，当然我把这个页面叫SplashPage，你可以使用你喜欢的名字。

修改导航，我是直接修改`App.xaml.cs`