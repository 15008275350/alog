# alog
>一个简单的Linux 日志库适用于小型嵌入式，使用简单，只需要引用`#include "alog_printf.h"`
* 可以设置输出到指定路径下保存成文件
* 日志文件的大小和个数可设置
* 日志的保存等级可设置
* 可控制是否打印在终端
## 使用说明
>`#include "alog_printf.h"`  
>`alog_printf(level, outputEnable, ...);`  
>
>>level: 日志等级  
>>outputEnable: 打印使能
 
### 示例
>`alog_printf(ALOG_LVL_DEBUG, TURE, "this is a test \n");`
