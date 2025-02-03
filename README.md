<!-- LTeX: language=zh-CN -->
# 浑元队芋圆杯项目
## 前言
## 内容
## 目前进度
chaoticvehicle文件夹是小车用的代码，platformio框架已经搭好
chaoticlaptop文件夹是上位机使用的代码，使用start.py启动整个过程。  
目前实装了：```start.py```一键运行从拍摄场地开始生成两条最短路径到```findtreasure.txt```（找宝藏）和```findfinish.txt```（从结束找终点），全程提示傻瓜操作。生成的路径对于每个格子的编号采取的是从0到80的顺序，转换成坐标也很容易。此外```start.py```留了一个调试窗口，可以选择现拍照片还是选取既有照片处理。


## to-do list
### 上位机部分
代码准确性有待测试。
此后上位机部分的操作最好和小车方面配合完成，有了能自个儿动的车才好继续根据情况写代码。  
## 开发环境
PlatformIO.
## 代码规范
```json
 "C_Cpp.clang_format_style": "{ BasedOnStyle: LLVM, BreakBeforeBraces: Linux, UseTab: Never, IndentWidth: 4, TabWidth: 4, AllowShortIfStatementsOnASingleLine: true, IndentCaseLabels: false, ColumnLimit: 0, AccessModifierOffset: -4, NamespaceIndentation: All, FixNamespaceComments: false }",
"C_Cpp.clang_format_fallbackStyle": "{ BasedOnStyle: LLVM, BreakBeforeBraces: Linux, UseTab: Never, IndentWidth: 4, TabWidth: 4, AllowShortIfStatementsOnASingleLine: true, IndentCaseLabels: false, ColumnLimit: 0, AccessModifierOffset: -4, NamespaceIndentation: All, FixNamespaceComments: false }",
```
