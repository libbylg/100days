|形式|含义|
|--- |----|
| `${var}`|返回${var}的内容|
| `${#var}`|返回${var}的字符长度|
| `${var:offset}`|返回${var}从位置offset之后开始提取字符至结束|
| `${var:offset:length}`|返回${var}从offset之后，提取长度为length的字符|
| `${var#word}`|返回从${var}开头开始删除最短匹配的word子符串|
| `${var##word}`|返回从${var}开头开始删除最长匹配的word子符串|
| `${var%word}`|返回从${var}结尾开始删除最短匹配的word子符串|
| `${var%%word}`|返回从${var}结尾开始删除最长匹配的word子符串|
| `${var/oldstring/newstring}`|使用newstring替换第一个匹配的字符oldstring|
| `${var//oldstring/newstring}`|使用newstring替换所有匹配的字符oldstring
| `${var:-word}`|如果变量var的值为空或未赋值，则将word做为返回值，常用于防止变量为空或未定义而导致的异常|
| `${var:=word}`|如果变量var的值为空或未赋值，则将word赋值给var并返回其值。|
| `${var:?word}`|如果变量var的值为空或未赋值，则将word做为标准错误输出，否则则输出变量的值，常用于捕捉因变量未定义而导致的错误并退出程序|
| `${var:+word}`|如果变量var的值为空或未赋值，则什么都不做，否则word字符将替换变量的值|

