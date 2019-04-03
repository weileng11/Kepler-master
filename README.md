# Kepler
这是我拿来展示一些新功能所搭建的项目

默认API-14

这个项目主要框架采用了FragmentTabHost作为底部导航

在该项目中，我自定义了不少view，可以给大家作为参考，有一些前期做的可能写得不是很规范。
引入Fragmention框架，实现侧滑结束Activity或者Fragment界面的效果。

![Image text](./Pics/gif/kpl1.gif?raw=true)
![Image text](./Pics/gif/kpl2.gif?raw=true)
![Image text](./Pics/gif/kpl3.gif?raw=true)


在第一个片段中
- [有一个切换日间/夜间主题的功能][1]
- 自定义banner显示图片
- 有一个自定义加载转圈的写法
- 有一个针对Rxjava的写法进行显示的写法
- 有一个针对6.0以上运行时权限的写法
- 自定义一个类似TabLayout的SlideTabView

以上是之前的内容，主界面采用CoordinatorLayout和DrawerLayout，
NavigationView等一系列[Material-Design实现抽屉式侧滑][2]，


- AppBarLayout+Toolbar+CollapsingToolbarLayout 实现Toolbar伸缩效果
- AppBarLayout+TabLayout+Toolbar 实现滑动隐藏显示Toolbar
- [FloatingActionButton的显示隐藏以及解决sdk25以上只隐藏不显示的问题][3]
- RecyclerView的线性流、网格流、瀑布流展示
- Palette颜色提取效果

因为不知道怎么在mac电脑上录制gif图片，所以没办法上传截图，后面补上

#### 联系方式：
- QQ：361561789
- email：voctex@163.com(邮箱很少登录)

---------------

[1]: http://blog.csdn.net/chen_xi_hao/article/details/74066757
[2]: http://blog.csdn.net/chen_xi_hao/article/details/73801136
[3]: http://blog.csdn.net/chen_xi_hao/article/details/74347023
