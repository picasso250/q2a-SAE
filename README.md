Question2Answer on SAE
-------------------------

在SAE上不完美运行。而且增加了中文语言包。

1.5的在SAE的商店，但是版本低。

首先是改config中的db。

其次，是lock table在sae上没权限，全部注释掉。

再次ini_set没权限，会报错，到控制面板把报错关了就可以了。

zh的语言包，搜一下，就安装上了，现在你可以直接选择使用。

error_log() 无作用，改成sae storage的。（不改也可以的其实）

为了避免重复劳动，放在github上。

As of version 1.6.3, all development of [Question2Answer] will take place through GitHub.

The collaborative development process is being managed by [Scott Vivian].

For more information on contributing, please read the [CONTRIBUTING] page.

Thanks and enjoy!

Gideon


[Question2Answer]: http://www.question2answer.org/
[Scott Vivian]: http://www.question2answer.org/qa/user/Scott
[CONTRIBUTING]: https://github.com/q2a/question2answer/blob/master/CONTRIBUTING.md
