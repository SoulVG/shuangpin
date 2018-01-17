# 六六双拼方案

本人曾经使用过一些双拼方案，但每次不用一段时间就记不得了那些韵母的分布，
还得从头拾起。原因很简单，就是绝大多数方案靠的是肌肉记忆，用进废退。
这可能也是双拼不普及的一个原因吧。

于是本人设计了一个极小记忆量的新方案，并认为不可能还有更小记忆量的了。
有了它，忘了就忘了吧，捡起来也就是分分钟的事。下面隆重推出：

![六六双拼方案](https://github.com/macroxue/shuangpin/blob/master/六六双拼方案.jpg)

本方案把键盘划分为六个规整的区域，每个区域最多六键，方案也因此得名。
每个区域内由一个根韵母根据简单而统一的规则派生出其它韵母。十分难得的是，
这个规则没有例外！

比如 a 区的根韵母是 a，右边是 根+i 得 ai，下边是 根+n 得 an，
右下是 根+ng 得 ang，右上是 根+o 得 ao。

再比如 ua 和 ia 共享一个 G 键，ua 是第一根韵母，ia 是第二根韵母。
右边是 根+i 得 uai 因为没有 iai，下边是 第一根+n 得 uan，
右下是 根+ng 得 uang 和 iang，右上是 根+o 得 iao 因为没有 uao，
上边是 第二根+n 得 ian。

共享键位在双拼方案里是不可避免的，因为韵母的数量比英文字母多。下面是
所有共享键位的韵母，其它方案里也有类似的共享。

 * ua 和 ia 共享，派生 ian 在上，uan 在下。
 * er 和 ie 共享。原则上 er 可以和任何一个不可单独成音的韵母共享，
   选择 ie 的目的是把 er 分配在 e 区。
 * ü 和 ui 共享，ue/üe 和 uai 共享， uo 和 o 共享， iong 和 ong 共享，
   都是相似和谐音。

双拼方案百花齐放，本方案独树一帜，最有规律，无需口诀助记。其设计的
唯一的目的是韵母分布的规律性，所以在击键舒适度上可能略逊色于某些方案。

# Linux 安装

 * 安装 fcitx
 * 拷贝 sp.dat 至 ~/.config/fcitx/pinyin 目录下
 * 在 fcitx 配置中选择自定义双拼
