＃tft_zynpzy
云顶官方接口：https：/////lol.qq.com/tft/js/api.js
免责声明
一. 本源码/软件完全出于个人兴趣爱好，由本人在业余时间编写的

二. 利用本软件/源码所做出的而衍生的软件作品，和本人无关.

三. 本源码/软件绝对不针对任何一款游戏或者游戏开发商，如果有人利用本软件/源码运营游戏辅助，本人将保留追究其民事以及刑事责任的权利.

四. 因使用本软件/源码而引致的任何意外、疏忽、合约毁坏、诽谤、版权或知识产权侵犯及其所造成的任何损失，本人概不负责，亦概不承担任何民事或刑事法律责任。

五. 本软件的功能用python实现，但与python官方无任何关系.

六. 当你第一次开始使用本人所提供的任何软件/源码/资源的那一刻起就将被视为对本声明全部内容的认可。同时您必须认可上述免责条款，方可使用本源码及资源。如有任何异议，建议立刻删除本源码及资源并且停止使用.

七. 以上内容，本人保留最终解释权。
源码中用到的库都是可以pip命令进行安装下载的 pip如果不懂的请百度..补补基础

这个必须要搞明白
精力有限目前仅封装了1920*1080无边框模式的字库.所以请手动设置这个分辨率和无边框.
本源码的开发初衷就是自己用,然后学习pyqt5,和python,以及大漠的调用等.还有很多bug有能力的你,可以自己修复,或者等我有时间..


使用方法:

1.只要自动列表中有英雄,脚本会自动启动不需要人为启动任何开关,本脚本会智能识别天选牌,然后将不进行购买(以免买错天选羁绊,浪费钱),也会自动识别有没有购买成功,并且不会重复购买!
2.自动帮拿列表中，支持您非常熟悉的快捷键，多选和单选删除操作..按ctrl + a全选，还有其他windows用户都懂的快捷方式，然后按del键删除某个棋子。鼠标双击某个棋子，也可以单独的进行删除
3.有一些英雄没有字库所以不拿,我玩的比较少阵容,都是玩狼人,所以还没发现.发现了后面会修复!

源码教程:
1使用python脚本编辑器,比如pycham等,安装好需要的库之后,比如pyqt5,还有别的,你看报错就懂了.一个一个安装
2基本上都是,选择项目,然后选择文件夹,就确定就行了.就会加载.然后找到main.py进行运行,,报错后肯定是没安装xx库,看报错提示就行了.一个一个安装好

成品exe教程:
1.先解压整个rar包,然后找打main.exe 右键管理员方式运行即可(如果遇到了弹窗错误,一般就是大漠没注册成功,请注意你的目录是不是有垃圾符号..你懂得,然后关闭杀毒软件比较靠谱)
2.一开始,可以点击官方阵容,然后随便选一个自己喜欢的阵容,之后看屏幕右边,会有阵容详情,,上方会看到一个确认自动的大大的按钮,没错你不用怀疑它的用处,点击后,自动列表里就会出现阵容里面的英雄,至此只要遇到这些英雄棋子就会自动拿了
3.游戏方面,你需要注意的是你第一次进入游戏时,先点击游戏里面的设置按钮(小地图右上角)然后找到视频选项,,把分辨率跳出1920*1080 模式为无边框模式(不能是全屏或者窗口)
4以上步骤搞完了基本就行了.

源码中用到的库都是可以pip命令进行安装下载的 pip如果不懂的请百度.总会解决..编译方法  pyinstaller -Fw main.py


20201020更新说明:
1.修复了各种傻逼的bug
2.点击失效的情况已经完全修复
3.恢复后台点击,现在体验贼棒,,自己都佩服自己
4.羁绊界面优化,防止窗口过大,遮挡太多了.
5.新增智能判断天选英雄的功能(有时候自动列表中的某个棋子来了一个垃圾天选羁绊,,但是脚本也傻乎乎的买了,,这很讨厌,,因为卖掉是会亏钱的,这个功能就是解决这个问题,现在会自动跳过,把主动权交给用户)

20201022更新说明:
1.修复天选识别有时候不成功的情况!
20201024更新说明:
1.修复努努的帮拿
2.修复官方阵容的爬取

本次最新的原码下载地址:
https://www.lanzoui.com/idhqlhot02h