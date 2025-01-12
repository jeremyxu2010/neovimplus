## 插件相关

Leader Key: `,`

### fswitch

.h和.c/.cc/.cpp文件切换。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `gf`                | 切换文件并在当前窗口显示                  |

### vim-edit

方便的文本编辑工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `Ya`                | 复制行文本到字母a                         |
| `Da`                | 剪切行文本到字母a                         |
| `Ca`                | 改写行文本到字母a                         |
| `rr`                | 替换当前光标下的单词或v模式选中的文本     |
| `<leader>r`         | 单文件内全局替换                          |
| `rev`               | 翻转当前光标下的单词或使用V模式选择的文本 |

### LeaderF

强大的文件搜索工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader>f`         | 搜索当前目录下的文件                      |
| `<leader>t`         | 搜索当前文件的函数                        |

### ack.vim

快速的文件内容搜索工具。[帮助文档链接](https://beyondgrep.com/documentation/)

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader>F`         | 搜索当前目录下的文本                      |

### vim-easymotion

单词跳转工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader>w`         | 页面内单词跳转                            |
| `<leader><leader>w` | 页面内向后单词跳转                        |
| `<leader><leader>b` | 页面内向前单词跳转                        |
| `<leader><leader>j` | 页面内向后行跳转                          |
| `<leader><leader>k` | 页面内向前行跳转                          |

### incsearch.vim

文本搜索增强。可以把搜到的结果高亮显示。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `/`                 | 文件内搜索并高亮                          |
| `g/`                | 文件内搜索并高亮，但不移动光标            |

### nerdtree

文件树查看。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader>f`         | 打开/关闭文件树                           |
| `o`                 | 打开文件                                  |
| `m`                 | 打开文件操作菜单                          |

### vim-fugitive

Git集成插件，可以方便的处理git操作。

### vim-surround

括号高效处理工具，可以方便的处理各种配对符号。

符号转义：

| 符号                | 涵义                                      |
| -------             | -----                                     |
| `t`                 | 指html的tag对，例如`<html></html>`        |
| `iw`                | 一个单词                                  |

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `cs<c1><c2>`        | 把符号对c1替换为c2                        |
| `ds<c1>`            | 删除符号对c1                              |
| `ysiw<c1>`          | 在光标所在单词两侧加符号对c1              |
| `v模式下S<c1>`      | 在v模式选中的文本两侧加符号对c1           |

### nerdcommenter

代码注释工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `gcc`               | 注释代码                                  |
| `gcap`              | 注释段落                                  |
| `v模式下gc`         | 注释代码                                  |

### vim-repeat

扩展vim的repeat(`.`键)，使之可以重复vim-surround等插件的复杂操作。

### vim-cpp-enhanced-highlight

C++高亮工具。

### vim-airline & vim-airline-themes

vim状态栏美化。

### vim-devicons

图标美化插件，vim-airline和NerdTree等中都会用到。

### vim-slash

vim搜索优化(清掉高亮、自动居中)。

### gv.vim

Git commit查看工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader>g`         | 显示git仓库提交记录                       |
| `<leader>G`         | 显示当前文件提交记录                      |
| `<leader>gg`        | 显示当前文件在某个commit下的完整内容      |

### vim-textobj-user/indent/syntax/function/parameter

将不同对象视为整体，可以方便的进行选中、替换、删除操作。

符号转义：

| 符号                | 涵义                                      |
| -------             | -----                                     |
| `w`                 | 一个单词                                  |
| `f`                 | function，支持花括号包括的函数            |
| `i`                 | 相同缩放的内容                            |
| `,`                 | 函数参数                                  |

> 以下以function为例，其它对象同理

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `vif`               | 选中函数内容                              |
| `dif`               | 删除函数内容                              |
| `cif`               | 改写函数内容                              |
| `vaf`               | 选中函数内容（包括函数名 花括号）         |
| `daf`               | 删除函数内容（包括函数名 花括号）         |
| `caf`               | 改写函数内容（包括函数名 花括号）         |

### echodoc.vim

在代码补全时，显示函数签名。

### vim-smooth-scroll

滑动动画更平滑。

### clever-f.vim

快速字符跳转。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `fa`                | 正向查找字母a，然后再按f键查找下一个      |
| `Fa`                | 反向查找字母a，然后再按f键查找上一个      |

### indentpython.vim

Python代码缩进辅助。

### closetag.vim

自动完成html标签。

### vim-flake8

使用flake8完成python代码检察。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<F7>`              | 使用flake8检察                            |

### vim-buffer

Buffer操作工具。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<leader><tab>`     | 切换到下一个buffer                        |
| `<leader><S-tab>`   | 切换到上一个buffer                        |
| `<leader>x`         | 删除当前buffer                            |
| `<leader>X`         | 删除当前buffer外的所有buffer              |

### coc.nvim

强大的nvim代码智能感知插件。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<tab>`             | 触发补全动作                              |
| `<C-l>`             | 触发补全动作                              |
| `<cr>(回车)`        | 确认补全                                  |
| `[g`                | 跳转到上一处错误处                        |
| `]g`                | 跳转到下一处错误处                        |
| `<leader>d`         | 跳转到定义                                |
| `<leader>r`         | 显示所有引用                              |
| `K`                 | 显示文档                                  |
| `<leader>rn`        | 重命名当前单词(所有文件)                  |
| `<leader>a`         | 打开CodeAction菜单                        |
| `<leader>qf`        | 使用QuickFix                              |
| `:Format`           | Format代码                                |
| `:OR`               | 组织import                                |

### 杂项

> 未整理完，里面的快捷键可能是失效状态。

| 快捷键              | 说明                                      |
| -------             | -----                                     |
| `<F5>`              | 异步执行python代码或调试                  |
| `<leader>h`         | 打开vimplus帮助文档                       |
| `<leader>H`         | 打开当前光标所在单词的vim帮助文档         |
| `<leader><leader>y` | 复制当前选中到系统剪切板                  |
| `<leader><leader>p` | 将系统剪切板的内容粘贴                    |


## 插入模式

| 快捷键  | 说明                           |
| ------- | -----                          |
| `i`     | 在光标处进入插入模式           |
| `I`     | 在行首进入插入模式             |
| `a`     | 在光标后进入插入模式           |
| `A`     | 在行尾进入插入模式             |
| `o`     | 在下一行插入新行并进入插入模式 |
| `O`     | 在上一行插入新行并进入插入模式 |
| `gi`    | 进入到上一次插入模式的位置     |


## 缓存操作

| 快捷键          | 说明               |
| -------         | -----              |
| `:e <filename>` | 新建buffer打开文件 |
| `:bp`           | 切换到上一个buffer |
| `:bn`           | 切换到下一个buffer |
| `:bd`           | 删除当前buffer     |


## 窗口操作

| 快捷键            | 说明                   |
| -------           | -----                  |
| `:sp <filename>`  | 横向切分窗口并打开文件 |
| `:vsp <filename>` | 竖向切分窗口并打开文件 |
| `<c-w>h`          | 跳到左边的窗口         |
| `<c-w>j`          | 跳到下边的窗口         |
| `<c-w>k`          | 跳到上边的窗口         |
| `<c-w>l`          | 跳到右边的窗口         |
| `<c-w>c`          | 关闭当前窗口           |
| `<c-w>o`          | 关闭其他窗口           |
| `:only`           | 关闭其他窗口           |


## 光标移动

| 快捷键  | 说明                                     |
| ------- | -----                                    |
| `h`     | 上下左右移动                             |
| `j`     | 上下左右移动                             |
| `k`     | 上下左右移动                             |
| `l`     | 上下左右移动                             |
| `0`     | 光标移动到行首                           |
| `^`     | 跳到从行首开始第一个非空白字符           |
| `$`     | 光标移动到行尾                           |
| `<c-o>` | 跳到上一个位置                           |
| `<c-i>` | 跳到下一个位置                           |
| `<c-b>` | 上一页                                   |
| `<c-f>` | 下一页                                   |
| `<c-u>` | 上移半屏                                 |
| `<c-d>` | 下移半屏                                 |
| `H`     | 调到屏幕顶上                             |
| `M`     | 调到屏幕中间                             |
| `L`     | 调到屏幕下方                             |
| `:n`    | 跳到第n行                                |
| `w`     | 跳到下一个单词开头(标点或空格分隔的单词) |
| `W`     | 跳到下一个单词开头(空格分隔的单词)       |
| `e`     | 跳到下一个单词尾部(标点或空格分隔的单词) |
| `E`     | 跳到下一个单词尾部(空格分隔的单词)       |
| `b`     | 上一个单词头(标点或空格分隔的单词)       |
| `B`     | 上一个单词头(空格分隔的单词)             |
| `ge`    | 上一个单词尾                             |
| `%`     | 在配对符间移动, 可用于()、{}、[]         |
| `gg`    | 到文件首                                 |
| `G`     | 到文件尾                                 |
| `fx`    | 跳转到下一个为x的字符                    |
| `Fx`    | 跳转到上一个为x的字符                    |
| `tx`    | 跳转到下一个为x的字符前                  |
| `Tx`    | 跳转到上一个为x的字符前                  |
| `;`     | 跳到下一个搜索的结果                     |
| `[[`    | 跳转到函数开头                           |
| `]]`    | 跳转到函数结尾                           |


## 文本编辑

| 快捷键         | 说明                                                     |
| -------        | -----                                                    |
| `r`            | 替换当前字符                                             |
| `R`            | 进入替换模式，直至 ESC 离开                              |
| `s`            | 替换字符（删除光标处字符，并进入插入模式，前可接数量）   |
| `S`            | 替换行（删除当前行，并进入插入模式，前可接数量）         |
| `cc`           | 改写当前行（删除当前行并进入插入模式），同 S             |
| `cw`           | 改写光标开始处的当前单词                                 |
| `ciw`          | 改写光标所处的单词                                       |
| `caw`          | 改写光标所处的单词，并且包括前后空格（如果有的话）       |
| `ct,`          | 改写到逗号                                               |
| `c0`           | 改写到行首                                               |
| `c^`           | 改写到行首（第一个非零字符）                             |
| `c$`           | 改写到行末                                               |
| `C`            | 改写到行末（同 c$）                                      |
| `ci"`          | 改写双引号中的内容                                       |
| `ci'`          | 改写单引号中的内容                                       |
| `ci)`          | 改写小括号中的内容                                       |
| `ci]`          | 改写中括号中内容                                         |
| `ci}`          | 改写大括号中内容                                         |
| `cit`          | 改写 xml tag 中的内容                                    |
| `cis`          | 改写当前句子                                             |
| `ciB`          | 改写'{}'中的内容                                         |
| `c2w`          | 改写下两个单词                                           |
| `ct(`          | 改写到小括号前                                           |
| `x`            | 删除当前字符，前面可以接数字，3x代表删除三个字符         |
| `X`            | 向前删除字符                                             |
| `dd`           | 删除当前行                                               |
| `d0`           | 删除到行首                                               |
| `d^`           | 删除到行首（第一个非零字符）                             |
| `d$`           | 删除到行末                                               |
| `D`            | 删除到行末（同 d$）                                      |
| `dw`           | 删除当前单词                                             |
| `dt,`          | 删除到逗号                                               |
| `diw`          | 删除光标所处的单词                                       |
| `daw`          | 删除光标所处的单词，并包含前后空格（如果有的话）         |
| `di"`          | 删除双引号中的内容                                       |
| `di'`          | 删除单引号中的内容                                       |
| `di)`          | 删除小括号中的内容                                       |
| `di]`          | 删除中括号中内容                                         |
| `di}`          | 删除大括号中内容                                         |
| `diB`          | 删除'{}'中的内容                                         |
| `dit`          | 删除 xml tag 中的内容                                    |
| `dis`          | 删除当前句子                                             |
| `d2w`          | 删除下两个单词                                           |
| `dt(`          | 删除到小括号前                                           |
| `dgg`          | 删除到文件头部                                           |
| `dG`           | 删除到文件尾部                                           |
| `d}`           | 删除下一段                                               |
| `d{`           | 删除上一段                                               |
| `u`            | 撤销                                                     |
| `U`            | 撤销整行操作                                             |
| `CTRL-R`       | 撤销上一次 u 命令                                        |
| `J`            | 连接若干行                                               |
| `gJ`           | 连接若干行，删除空白字符                                 |
| `.`            | 重复上一次操作                                           |
| `~`            | 交换大小写                                               |
| `g~iw`         | 替换当前单词的大小写                                     |
| `gUiw`         | 将单词转成大写                                           |
| `guiw`         | 将当前单词转成小写                                       |
| `guu`          | 全行转为小写                                             |
| `gUU`          | 全行转为大写                                             |
| `gg=G`         | 缩进整个文件                                             |
| `=a{`          | 缩进光标所在代码块                                       |
| `=i{`          | 缩进光标所在代码块，不缩进"{"                            |
| `<<`           | 减少缩进                                                 |
| `>>`           | 增加缩进                                                 |
| `==`           | 自动缩进                                                 |
| `CTRL-A`       | 增加数字                                                 |
| `CTRL-X`       | 减少数字                                                 |
| `p`            | 粘贴到光标后                                             |
| `P`            | 粘贴到光标前                                             |
| `v`            | 开始标记                                                 |
| `y`            | 复制标记内容                                             |
| `V`            | 开始按行标记                                             |
| `CTRL-V`       | 开始列标记                                               |
| `y$`           | 复制当前位置到本行结束的内容                             |
| `yy`           | 复制当前行                                               |
| `Y`            | 复制当前行，同 yy                                        |
| `yt,`          | 复制到逗号                                               |
| `yiw`          | 复制当前单词                                             |
| `"+y`          | 复制当前选中到系统剪切板                                 |
| `3yy`          | 复制光标下三行内容                                       |
| `v0`           | 选中当前位置到行首                                       |
| `v$`           | 选中当前位置到行末                                       |
| `vt,`          | 选中到逗号                                               |
| `viw`          | 选中当前单词                                             |
| `vi)`          | 选中小括号内的东西                                       |
| `vi]`          | 选中中括号内的东西                                       |
| `viB`          | 选中'{}'中的内容                                         |
| `vis`          | 选中句子中的东西                                         |
| `gv`           | 重新选择上一次选中的文字                                 |
| `:set paste`   | 允许粘贴模式（避免粘贴时自动缩进影响格式）               |
| `:set nopaste` | 禁止粘贴模式                                             |
| `"?yy`         | 复制当前行到寄存器 ? ，问号代表 0-9 的寄存器名称         |
| `"?p`          | 将寄存器 ? 的内容粘贴到光标后                            |
| `"?P`          | 将寄存器 ? 的内容粘贴到光标前                            |
| `:registers`   | 显示所有寄存器内容                                       |
| `:[range]y`    | 复制范围，比如 :20,30y 是复制20到30行，:10y 是复制第十行 |
| `:[range]d`    | 删除范围，比如 :20,30d 是删除20到30行，:10d 是删除第十行 |
| `ddp`          | 交换两行内容：先删除当前行复制到寄存器，并粘贴           |


## 文件操作

| 快捷键               | 说明                                   |
| -------              | -----                                  |
| `:w`                 | 保存文件                               |
| `:w <filename>`      | 按名称保存文件                         |
| `ZZ`                 | 保存文件（如果有改动的话），并关闭窗口 |
| `:e <filename>`      | 打开文件并编辑                         |
| `:saveas <filename>` | 另存为文件                             |
| `:r <filename>`      | 读取文件并将内容插入到光标后           |
| `:r !dir`            | 将dir命令的输出捕获并插入到光标后      |
| `:close`             | 关闭文件                               |
| `:q`                 | 退出                                   |
| `:q!`                | 强制退出                               |
| `:wa`                | 保存所有文件                           |
| `:cd <path>`         | 切换Vim当前路径                        |
| `:new`               | 打开一个新的窗口编辑新文件             |
| `:enew`              | 在当前窗口创建新文件                   |
| `:vnew`              | 在左右切分的新窗口中编辑新文件         |
| `:tabnew`            | 在新的标签页中编辑新文件               |


## 使用外部程序

| 快捷键           | 说明                            |
| -------          | -----                           |
| `!`              | 告诉vim正在执行一个过滤操作     |
| `!5Gsort<Enter>` | 使用外部sort命令对1-5行文本排序 |
| `!!`             | 对当前行执行过滤命令            |
| `!!date<Enter>`  | 用"date"的输出代替当前行        |

## 宏录制

| 快捷键      | 说明                        |
| -------     | -----                       |
| `qa`        | 开始录制名字为a的宏         |
| `q`         | 结束录制宏                  |
| `@a`        | 播放名字为a的宏             |
| `100@a`     | 播放名字为a的宏100次        |
| `:normal@a` | 播放名字为a的宏直到自动结束 |


## 实用命令

| 快捷键               | 说明                                             |
| -------              | -----                                            |
| `/pattern`           | 从光标处向文件尾搜索 pattern                     |
| `?pattern`           | 从光标处向文件头搜索 pattern                     |
| `n`                  | 向同一方向执行上一次搜索                         |
| `N`                  | 向相反方向执行上一次搜索                         |
| `*`                  | 向前搜索光标下的单词                             |
| `#`                  | 向后搜索光标下的单词                             |
| `:s/p1/p2/g`         | 替换当前行的p1为p2                               |
| `:%s/p1/p2/g`        | 替换当前文件中的p1为p2                           |
| `:%s/<p1>/p2/g`      | 替换当前文件中的p1单词为p2                       |
| `:%s/p1/p2/gc`       | 替换当前文件中的p1为p2，并且每处询问你是否替换   |
| `:10,20s/p1/p2/g`    | 将第10到20行中所有p1替换为p2                     |
| `:%s/1\\2\/3/123/g`  | 将“1\2/3” 替换为 “123”（特殊字符使用反斜杠标注） |
| `:%s/\r//g`          | 删除 DOS 换行符 ^M                               |
| `:g/^\s*$/d`         | 删除空行                                         |
| `:g/test/d`          | 删除所有包含 test 的行                           |
| `:v/test/d`          | 删除所有不包含 test 的行                         |
| `:%s/^/test/`        | 在行首加入特定字符(也可以用宏录制来添加)         |
| `:%s/$/test/`        | 在行尾加入特定字符(也可以用宏录制来添加)         |
| `:sort`              | 排序                                             |
| `:g/^\(.\+\)$\n\1/d` | 去除重复行(先排序)                               |
| `:%s/^.\{10\}//`     | 删除每行前10个字符                               |
| `:%s/.\{10\}$//`     | 删除每行尾10个字符                               |


## 帮助

| 快捷键                 | 说明                         |
| -------                | -----                        |
| `h tutor`              | 入门文档                     |
| `h quickref`           | 快速帮助                     |
| `h index`              | 查询Vim所有键盘命令定义      |
| `h summary`            | 帮助你更好的使用内置帮助系统 |
| `h pattern.txt`        | 正则表达式帮助               |
| `h eval`               | 脚本编写帮助                 |
| `h function-list`      | 查看VimScript的函数列表      |
| `h windows.txt`        | 窗口使用帮助                 |
| `h tabpage.txt`        | 标签页使用帮助               |
| `h tips`               | 查看Vim内置的常用技巧文档    |
| `h quote`              | 寄存器                       |
| `h autocommand-events` | 所有可能事件                 |
| `h write-plugin`       | 编写插件                     |


## 其他

| 快捷键                | 说明                       |
| -------               | -----                      |
| `vim -u NONE -N`      | 开启vim时不加载vimrc文件   |
| `vimdiff file1 file2` | 显示文件差异               |
| `vim -R filename`     | 以只读方式打开（阅读模式） |
