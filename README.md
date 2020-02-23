SimpleGobang程序简述
=======
[写在前面：我在csdn上的原创文章被脚本之家复制盗用用以投放广告盈利，请大家尊重原创，这里写上我的原创文章地址：https://blog.csdn.net/weixin_44899883/article/details/104379195]
本人目前是一名普通的在校大学生

这是我首次使用github，欢迎大家共同学习进步 : )  

## 这是啥？
这就是一个很简单的五子棋程序，你可以在和朋友一起用这个程序下五子棋。

说它简单的原因是这个程序目前还只能做一些比较基础的操作。比如下棋、判断胜负和复盘等...

你可以在Img文件夹中看到程序运行的截图

由于本人也是一个编程小白，所以代码对于C++编程新手来说也是十分友好的。希望能在github上能和大家一起进步，这也是我编写这个程序的最大初衷。
## 我为什么编写这个程序？
* 锻炼自己的编程能力。
* 测试自己设计的五子棋算法
* 检验五子棋的可对抗性。

在闲暇时，我常常会下五子棋，因为五子棋规则简单，并且有时也充满一定的挑战性。但随着我下五子棋的次数不断增多，我发现似乎我一直在使用一种
固定的策略来下五子棋。当然，对于五子棋新手来说，我常常能赢，但是当我面对实力相当的对手，往往会出现棋盘上的空格不多，但胜负依旧未分的情况。
这让我对五子棋的可对抗性产生了疑问和好奇。

关于可对抗性的一个大胆猜想是：在同等条件下，是否能证明棋盘上的棋子越多，出现胜局的概率越大。同等条件是指棋手双方水平不变，并且棋盘上的棋子不应该是简单的在同一条直线上叠加。

我想举一个简单例子来说明这个猜想：棋局开始时，棋盘上棋子数量较少，由于下棋的双方都是朝着自己胜利的目标下棋，如果将棋手的操作概括为：进攻（在同一条直线上累加棋子）或防守（在对手的同一条直线上累加棋子），那么随着棋局的进行，棋子数量不断增加，是否存在出现胜局的概率不断增大或者先增大后减小的情况，如果存在那么是否能够用数学表达式表达的问题。


## 使用这个程序？

你可以将代码拷贝至本地，该程序是用C++ MFC编写的，如果你用VS编写过MFC程序，那么你应该可以很轻松地运行代码。如有疑问，可发邮件至1069166224@qq.com

同时，如果你对这个程序的界面有任何改进意见，也欢迎联系我。
## 存在的问题
* 目前还没有实现程序自动下棋。
* 如果您在代码、运行等任何方面发现问题，也可发邮件给上面那个地址。
