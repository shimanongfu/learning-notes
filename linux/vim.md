### 1）普通模式（Normal Mode）：###############################

这是默认的模式，用于浏览和编辑文本。
文本操作：x（删除光标下的字符）、dd（删除当前行）、ggdG(删除所有行)、yy（复制当前行）、p（粘贴）、u（撤销上一步操作）。
翻页：Ctrl+f（向下翻页）、Ctrl+b（向上翻页）。
跳转：gg（跳到文件开头）、G（跳到文件结尾）0（跳转到行首）、$（跳转至行末）。
查找：/（向前查找）、?（向后查找）回车键开始查找，n 跳转到下一个。

#####


### 2）插入模式（Insert Mode）：###############################

在此模式下，可以输入文本。
进入插入模式：i（在光标前插入）、a（在光标后插入）、o（在当前行下插入新行并切换到插入模式）。
退出插入模式：Esc（退出插入模式，回到普通模式）。

######


### 3）可视模式（Visual Mode）：###############################

在此模式下，可以选择文本块进行操作。
进入可视模式：v（进入字符选择模式）、V（进入行选择模式）。
文本选择：在普通模式下使用光标移动来选择文本块。
操作：选择文本后，可以进行复制、删除等操作。

######

### 4）命令行模式（Command-Line Mode）：###############################

在此模式下，可以执行一些命令，如保存文件、退出 Vim、查找替换等。
进入命令行模式：在普通模式下按下冒号 :。
保存文件：:w。
退出 Vim：:q。
强制退出 Vim：:q!。
查找替换：:s/old/new/g（替换当前行中所有的 old 为 new）。

######
