项目起因: 平常喜欢使用Fira Code Retina作为Jetbrain系的编程字体,整体都很不错,唯独觉得里面的"l"弯曲的太厉害,给我一种失衡的感觉.Fira Code和Iosevka本身都支持风格集,可以自定义字体的细节,奈何IDE不支持,只能通过预编译为成品字体的方式来使用.

**Jetbrain系如何添加字体: 拷贝字体文件到 [每个IDE安装目录]\jbr\lib\fonts\\**

**Iosevka**

1.不要fork,右上角Use this template创建你自己的仓库.

2.前往 https://typeof.net/Iosevka/customizer 网站创建属于你的样式配置.

注意: Family Name 需要为 Iosevka .(或在Iosevka.yml修改命令)

3.保存网站Your Config中的toml内容到仓库中的private-build-plans.toml.(后续更改也可以import此toml)

4.前往仓库的Actions中手动触发Iosevka TTF/SuperTTC.
等待N分钟(取决于你的样式配置,一个TTF文件大约1-2分钟,全部拉满需要40+分钟)即可从结果链接中下载成品字体.

Tip:记得在网站预览下自己的样式,生成一次会消耗很多的Action额度,小修小改很亏甚至达到每月上限!

**Fira Code**

1.不要fork,右上角Use this template创建你自己的仓库.

2.前往 https://github.com/tonsky/FiraCode/wiki/How-to-enable-stylistic-sets 网站选择你的样式集.

3.将形如“cv10,zero,cv14”的样式集修改到Fira-Code.yml中的--feature后面.

4.前往仓库的Actions中手动触发Fira Code TTF,等待N分钟即可从结果链接中下载成品字体.
