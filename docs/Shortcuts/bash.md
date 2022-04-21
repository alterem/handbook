命令行工具bash快捷键
===


## 基础

`Ctrl + a` ：移到命令行首  
`Ctrl + e` ：移到命令行尾  
`Ctrl + f` ：按字符前移（右向）  
`Ctrl + b` ：按字符后移（左向）  
`Alt + f` ：按单词前移（右向）  
`Alt + b` ：按单词后移（左向）  
`Ctrl + xx`：在命令行首和光标之间移动  
`Ctrl + u` ：从光标处删除至命令行首  
`Ctrl + k` ：从光标处删除至命令行尾  
`Ctrl + w` ：从光标处删除至字首  
`Alt + d` ：从光标处删除至字尾  
`Ctrl + d` ：删除光标处的字符  
`Ctrl + h` ：删除光标前的字符  
`Ctrl + y` ：粘贴至光标后  
`Alt + c` ：从光标处更改为首字母大写的单词  
`Alt + u` ：从光标处更改为全部大写的单词  
`Alt + l` ：从光标处更改为全部小写的单词  
`Ctrl + t` ：交换光标处和之前的字符  
`Alt + t` ：交换光标处和之前的单词  
`Alt + Backspace`：与 `Ctrl + w` 相同  

## 重新执行命令
`Ctrl + r`：逆向搜索命令历史  
`Ctrl + g`：从历史搜索模式退出  
`Ctrl + p`：历史中的上一条命令  
`Ctrl + n`：历史中的下一条命令  
`Alt + .`：使用上一条命令的最后一个参数  

## 控制命令
`Ctrl + l`：清屏  
`Ctrl + o`：执行当前命令，并选择上一条命令  
`Ctrl + s`：阻止屏幕输出  
`Ctrl + q`：允许屏幕输出  
`Ctrl + c`：终止命令  
`Ctrl + z`：挂起命令  

## Bang (!) 命令

`!!`：执行上一条命令  
`!blah`：执行最近的以 blah 开头的命令，如 `!ls`  
`!blah:p`：仅打印输出，而不执行  
`!$`：上一条命令的最后一个参数，与 `Alt + .` 相同  
`!$:p`：打印输出 `!$` 的内容  
`!*`：上一条命令的所有参数  
`!*:p`：打印输出 `!*` 的内容  
`^blah`：删除上一条命令中的 `blah`  
`^blah^foo`：将上一条命令中的 `blah` 替换为 `foo`  
`^blah^foo^`：将上一条命令中所有的 `blah` 都替换为 `foo`  


## vi编辑器中快捷键

[iterm2](http://www.iterm2.cn/)  

> (注意下面的”前”都是指”左”或”上”，”后”是”右”或”下; `⌃` 表示 `ctrl` )


`⌃` Control  
注意下面的`前`都是指`左`或`上`，`后`是`右`或`下`  

`⌃ + r` 查找历史执行命令  
`⌃ + p` 前一条指令   
`⌃ + n` 后一条指令  
`⌃ + c` 终止已经运行的命令或者取消已经输入的命令  
`⌃ + o/⌃ + j/⌃ + m` 执行当前行输入的命令，跟 enter 类似  
`⌃ + l` 清屏，`clear` 命令  

`⌃ + a` 移动光标到行首  
`⌃ + e` 移动光标到行尾  

`⌃ + t` 交换光标前俩字符的位置  
`⌃ + h` 往后删除一字符  
`⌃ + d` 往前删除一字符  
`⌃ + b` 往后移动一个字符  
`⌃ + f` 往前移动一个字符  

`⌃ + w` 剪切前一个单词(空格间隔的字符串单元)  
`⌃ + u` 剪切到行首  
`⌃ + k` 剪切到行尾  
`⌃ + y` 粘贴剪切  

## 其它命令

`sudo chmod 755 -R node` 修改目录权限  
`sudo lsof -nP -iTCP -sTCP:LISTEN` 查看本地服务  
`ps -ef | grep websocket` 查看websocket进程  
`ps aux | grep mysql` 查看mysql进程  
`sudo kill 443` 杀掉进程  